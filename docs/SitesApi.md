# fio_sdk.SitesApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**sites_planets_user_name_get**](SitesApi.md#sites_planets_user_name_get) | **GET** /sites/planets/{UserName} | Retrieves list of planets user has site data for
[**sites_post**](SitesApi.md#sites_post) | **POST** /sites | Posts SITE_SITES payload
[**sites_user_name_get**](SitesApi.md#sites_user_name_get) | **GET** /sites/{UserName} | Retrieves site data
[**sites_user_name_planet_get**](SitesApi.md#sites_user_name_planet_get) | **GET** /sites/{UserName}/{Planet} | Retrieves list of planets user has site data for
[**sites_warehouses_post**](SitesApi.md#sites_warehouses_post) | **POST** /sites/warehouses | Posts STORAGE_WAREHOUSES payload
[**sites_warehouses_user_name_get**](SitesApi.md#sites_warehouses_user_name_get) | **GET** /sites/warehouses/{UserName} | Retrieves all warehouse sites the user has
[**storage_post**](SitesApi.md#storage_post) | **POST** /storage | Posts STORAGE_STORAGES payload

# **sites_planets_user_name_get**
> list[str] sites_planets_user_name_get(user_name)

Retrieves list of planets user has site data for

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
api_instance = fio_sdk.SitesApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve site data for

try:
    # Retrieves list of planets user has site data for
    api_response = api_instance.sites_planets_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling SitesApi->sites_planets_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve site data for | 

### Return type

**list[str]**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sites_post**
> sites_post()

Posts SITE_SITES payload

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
api_instance = fio_sdk.SitesApi(fio_sdk.ApiClient(configuration))

try:
    # Posts SITE_SITES payload
    api_instance.sites_post()
except ApiException as e:
    print("Exception when calling SitesApi->sites_post: %s\n" % e)
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

# **sites_user_name_get**
> sites_user_name_get(user_name)

Retrieves site data

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
api_instance = fio_sdk.SitesApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve site data for

try:
    # Retrieves site data
    api_instance.sites_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling SitesApi->sites_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve site data for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sites_user_name_planet_get**
> sites_user_name_planet_get(user_name, planet)

Retrieves list of planets user has site data for

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
api_instance = fio_sdk.SitesApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve site data for
planet = 'planet_example' # str | Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName 

try:
    # Retrieves list of planets user has site data for
    api_instance.sites_user_name_planet_get(user_name, planet)
except ApiException as e:
    print("Exception when calling SitesApi->sites_user_name_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve site data for | 
 **planet** | **str**| Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName  | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sites_warehouses_post**
> sites_warehouses_post()

Posts STORAGE_WAREHOUSES payload

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
api_instance = fio_sdk.SitesApi(fio_sdk.ApiClient(configuration))

try:
    # Posts STORAGE_WAREHOUSES payload
    api_instance.sites_warehouses_post()
except ApiException as e:
    print("Exception when calling SitesApi->sites_warehouses_post: %s\n" % e)
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

# **sites_warehouses_user_name_get**
> sites_warehouses_user_name_get(user_name)

Retrieves all warehouse sites the user has

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
api_instance = fio_sdk.SitesApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve site data for

try:
    # Retrieves all warehouse sites the user has
    api_instance.sites_warehouses_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling SitesApi->sites_warehouses_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve site data for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **storage_post**
> storage_post()

Posts STORAGE_STORAGES payload

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
api_instance = fio_sdk.SitesApi(fio_sdk.ApiClient(configuration))

try:
    # Posts STORAGE_STORAGES payload
    api_instance.storage_post()
except ApiException as e:
    print("Exception when calling SitesApi->storage_post: %s\n" % e)
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

