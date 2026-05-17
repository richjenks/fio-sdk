# fio_sdk.PlanetApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**planet_allplanets_full_get**](PlanetApi.md#planet_allplanets_full_get) | **GET** /planet/allplanets/full | Retrieves all planet data for all planets
[**planet_allplanets_get**](PlanetApi.md#planet_allplanets_get) | **GET** /planet/allplanets | Retrieves a list of all planets (minimal payload)
[**planet_cogc_post**](PlanetApi.md#planet_cogc_post) | **POST** /planet/cogc | Posts PLANET_COGC_DATA payload
[**planet_planet_get**](PlanetApi.md#planet_planet_get) | **GET** /planet/{Planet} | Retrieves planet payload.  See FIORest for payload definition
[**planet_post**](PlanetApi.md#planet_post) | **POST** /planet | Posts PLANET_DATA_DATA payload
[**planet_search_post**](PlanetApi.md#planet_search_post) | **POST** /planet/search | Searches for a planet given the parameters in the payload
[**planet_sites_planet_get**](PlanetApi.md#planet_sites_planet_get) | **GET** /planet/sites/{Planet} | Retrieves the planet sites payload.  See FIORest for payload definition
[**planet_sites_post**](PlanetApi.md#planet_sites_post) | **POST** /planet/sites | Posts PLANET_SITES payload
[**planet_sitescount_planet_get**](PlanetApi.md#planet_sitescount_planet_get) | **GET** /planet/sitescount/{Planet} | Retrieves the number of planet sites for the provided Planet

# **planet_allplanets_full_get**
> planet_allplanets_full_get()

Retrieves all planet data for all planets

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.PlanetApi()

try:
    # Retrieves all planet data for all planets
    api_instance.planet_allplanets_full_get()
except ApiException as e:
    print("Exception when calling PlanetApi->planet_allplanets_full_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **planet_allplanets_get**
> list[PlanetListItem] planet_allplanets_get()

Retrieves a list of all planets (minimal payload)

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.PlanetApi()

try:
    # Retrieves a list of all planets (minimal payload)
    api_response = api_instance.planet_allplanets_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling PlanetApi->planet_allplanets_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[PlanetListItem]**](PlanetListItem.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **planet_cogc_post**
> planet_cogc_post()

Posts PLANET_COGC_DATA payload

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# Configure API key authorization: api_key
configuration = fio_sdk.Configuration()
configuration.api_key['Authorization'] = 'YOUR_API_KEY'
# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['Authorization'] = 'Bearer'

# create an instance of the API class
api_instance = fio_sdk.PlanetApi(fio_sdk.ApiClient(configuration))

try:
    # Posts PLANET_COGC_DATA payload
    api_instance.planet_cogc_post()
except ApiException as e:
    print("Exception when calling PlanetApi->planet_cogc_post: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **planet_planet_get**
> planet_planet_get(planet)

Retrieves planet payload.  See FIORest for payload definition

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.PlanetApi()
planet = 'planet_example' # str | Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName 

try:
    # Retrieves planet payload.  See FIORest for payload definition
    api_instance.planet_planet_get(planet)
except ApiException as e:
    print("Exception when calling PlanetApi->planet_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **planet** | **str**| Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **planet_post**
> planet_post()

Posts PLANET_DATA_DATA payload

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# Configure API key authorization: api_key
configuration = fio_sdk.Configuration()
configuration.api_key['Authorization'] = 'YOUR_API_KEY'
# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['Authorization'] = 'Bearer'

# create an instance of the API class
api_instance = fio_sdk.PlanetApi(fio_sdk.ApiClient(configuration))

try:
    # Posts PLANET_DATA_DATA payload
    api_instance.planet_post()
except ApiException as e:
    print("Exception when calling PlanetApi->planet_post: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **planet_search_post**
> planet_search_post(body)

Searches for a planet given the parameters in the payload

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# Configure API key authorization: api_key
configuration = fio_sdk.Configuration()
configuration.api_key['Authorization'] = 'YOUR_API_KEY'
# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['Authorization'] = 'Bearer'

# create an instance of the API class
api_instance = fio_sdk.PlanetApi(fio_sdk.ApiClient(configuration))
body = fio_sdk.PlanetSearchRequest() # PlanetSearchRequest | The search parameters. Limitations: 1) Only the first 4 entries in the Materials array will be considered 2) Workforce populations (JobData) will not be present if not authenticated 3) DistanceResults will not be present if not authenticated 4) Only the first 3 entries in the DistanceChecks array will be considered 

try:
    # Searches for a planet given the parameters in the payload
    api_instance.planet_search_post(body)
except ApiException as e:
    print("Exception when calling PlanetApi->planet_search_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**PlanetSearchRequest**](PlanetSearchRequest.md)| The search parameters. Limitations: 1) Only the first 4 entries in the Materials array will be considered 2) Workforce populations (JobData) will not be present if not authenticated 3) DistanceResults will not be present if not authenticated 4) Only the first 3 entries in the DistanceChecks array will be considered  | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **planet_sites_planet_get**
> planet_sites_planet_get(planet)

Retrieves the planet sites payload.  See FIORest for payload definition

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.PlanetApi()
planet = 'planet_example' # str | Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName 

try:
    # Retrieves the planet sites payload.  See FIORest for payload definition
    api_instance.planet_sites_planet_get(planet)
except ApiException as e:
    print("Exception when calling PlanetApi->planet_sites_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **planet** | **str**| Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **planet_sites_post**
> planet_sites_post()

Posts PLANET_SITES payload

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# Configure API key authorization: api_key
configuration = fio_sdk.Configuration()
configuration.api_key['Authorization'] = 'YOUR_API_KEY'
# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
# configuration.api_key_prefix['Authorization'] = 'Bearer'

# create an instance of the API class
api_instance = fio_sdk.PlanetApi(fio_sdk.ApiClient(configuration))

try:
    # Posts PLANET_SITES payload
    api_instance.planet_sites_post()
except ApiException as e:
    print("Exception when calling PlanetApi->planet_sites_post: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **planet_sitescount_planet_get**
> planet_sitescount_planet_get(planet)

Retrieves the number of planet sites for the provided Planet

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.PlanetApi()
planet = 'planet_example' # str | Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName 

try:
    # Retrieves the number of planet sites for the provided Planet
    api_instance.planet_sitescount_planet_get(planet)
except ApiException as e:
    print("Exception when calling PlanetApi->planet_sitescount_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **planet** | **str**| Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

