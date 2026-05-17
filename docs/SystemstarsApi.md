# fio_sdk.SystemstarsApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**systemstars_get**](SystemstarsApi.md#systemstars_get) | **GET** /systemstars | Retrieves system star data
[**systemstars_jumpcount_source_destination_get**](SystemstarsApi.md#systemstars_jumpcount_source_destination_get) | **GET** /systemstars/jumpcount/{Source}/{Destination} | Retrieves jump count from source to destination specified
[**systemstars_jumproute_source_destination_get**](SystemstarsApi.md#systemstars_jumproute_source_destination_get) | **GET** /systemstars/jumproute/{Source}/{Destination} | Retrieves jump route from source to destination specified
[**systemstars_post**](SystemstarsApi.md#systemstars_post) | **POST** /systemstars | Posts SYSTEM_STARS_DATA payload
[**systemstars_star_post**](SystemstarsApi.md#systemstars_star_post) | **POST** /systemstars/star | Posts SYSTEM_STAR data
[**systemstars_star_star_get**](SystemstarsApi.md#systemstars_star_star_get) | **GET** /systemstars/star/{Star} | Retrieves SYSTEM_STAR data provided a Star definition
[**systemstars_worldsectors_get**](SystemstarsApi.md#systemstars_worldsectors_get) | **GET** /systemstars/worldsectors | Retrieves world sector data
[**systemstars_worldsectors_post**](SystemstarsApi.md#systemstars_worldsectors_post) | **POST** /systemstars/worldsectors | Posts WORLD_SECTORS payload

# **systemstars_get**
> systemstars_get()

Retrieves system star data

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
api_instance = fio_sdk.SystemstarsApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves system star data
    api_instance.systemstars_get()
except ApiException as e:
    print("Exception when calling SystemstarsApi->systemstars_get: %s\n" % e)
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

# **systemstars_jumpcount_source_destination_get**
> int systemstars_jumpcount_source_destination_get(source, destination)

Retrieves jump count from source to destination specified

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
api_instance = fio_sdk.SystemstarsApi(fio_sdk.ApiClient(configuration))
source = 'source_example' # str | Can be any of the following: 1) SystemId (XK-745) 2) PlanetId 3) PlanetNaturalId 4) PlanetName 
destination = 'destination_example' # str | Can be any of the following: 1) SystemId (XK-745) 2) PlanetId 3) PlanetNaturalId 4) PlanetName 

try:
    # Retrieves jump count from source to destination specified
    api_response = api_instance.systemstars_jumpcount_source_destination_get(source, destination)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling SystemstarsApi->systemstars_jumpcount_source_destination_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **source** | **str**| Can be any of the following: 1) SystemId (XK-745) 2) PlanetId 3) PlanetNaturalId 4) PlanetName  | 
 **destination** | **str**| Can be any of the following: 1) SystemId (XK-745) 2) PlanetId 3) PlanetNaturalId 4) PlanetName  | 

### Return type

**int**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **systemstars_jumproute_source_destination_get**
> list[SystemStarsJumpRoute] systemstars_jumproute_source_destination_get(source, destination)

Retrieves jump route from source to destination specified

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
api_instance = fio_sdk.SystemstarsApi(fio_sdk.ApiClient(configuration))
source = 'source_example' # str | Can be any of the following: 1) SystemId (XK-745) 2) PlanetId 3) PlanetNaturalId 4) PlanetName 
destination = 'destination_example' # str | Can be any of the following: 1) SystemId (XK-745) 2) PlanetId 3) PlanetNaturalId 4) PlanetName 

try:
    # Retrieves jump route from source to destination specified
    api_response = api_instance.systemstars_jumproute_source_destination_get(source, destination)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling SystemstarsApi->systemstars_jumproute_source_destination_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **source** | **str**| Can be any of the following: 1) SystemId (XK-745) 2) PlanetId 3) PlanetNaturalId 4) PlanetName  | 
 **destination** | **str**| Can be any of the following: 1) SystemId (XK-745) 2) PlanetId 3) PlanetNaturalId 4) PlanetName  | 

### Return type

[**list[SystemStarsJumpRoute]**](SystemStarsJumpRoute.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **systemstars_post**
> systemstars_post()

Posts SYSTEM_STARS_DATA payload

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
api_instance = fio_sdk.SystemstarsApi(fio_sdk.ApiClient(configuration))

try:
    # Posts SYSTEM_STARS_DATA payload
    api_instance.systemstars_post()
except ApiException as e:
    print("Exception when calling SystemstarsApi->systemstars_post: %s\n" % e)
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

# **systemstars_star_post**
> systemstars_star_post()

Posts SYSTEM_STAR data

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
api_instance = fio_sdk.SystemstarsApi(fio_sdk.ApiClient(configuration))

try:
    # Posts SYSTEM_STAR data
    api_instance.systemstars_star_post()
except ApiException as e:
    print("Exception when calling SystemstarsApi->systemstars_star_post: %s\n" % e)
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

# **systemstars_star_star_get**
> systemstars_star_star_get(star)

Retrieves SYSTEM_STAR data provided a Star definition

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.SystemstarsApi()
star = 'star_example' # str | Can be any of the following: 1) SystemId (hash) 2) SystemName (Benten) 3) SystemNaturalId (XK-745) 

try:
    # Retrieves SYSTEM_STAR data provided a Star definition
    api_instance.systemstars_star_star_get(star)
except ApiException as e:
    print("Exception when calling SystemstarsApi->systemstars_star_star_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **star** | **str**| Can be any of the following: 1) SystemId (hash) 2) SystemName (Benten) 3) SystemNaturalId (XK-745)  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **systemstars_worldsectors_get**
> systemstars_worldsectors_get()

Retrieves world sector data

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
api_instance = fio_sdk.SystemstarsApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves world sector data
    api_instance.systemstars_worldsectors_get()
except ApiException as e:
    print("Exception when calling SystemstarsApi->systemstars_worldsectors_get: %s\n" % e)
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

# **systemstars_worldsectors_post**
> systemstars_worldsectors_post()

Posts WORLD_SECTORS payload

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
api_instance = fio_sdk.SystemstarsApi(fio_sdk.ApiClient(configuration))

try:
    # Posts WORLD_SECTORS payload
    api_instance.systemstars_worldsectors_post()
except ApiException as e:
    print("Exception when calling SystemstarsApi->systemstars_worldsectors_post: %s\n" % e)
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

