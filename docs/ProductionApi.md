# fio_sdk.ProductionApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**production_planets_user_name_get**](ProductionApi.md#production_planets_user_name_get) | **GET** /production/planets/{UserName} | Retrieve all the planets where production lines are present for the provided UserName
[**production_post**](ProductionApi.md#production_post) | **POST** /production | Posts PRODUCTION_SITE_PRODUCTION_LINES payload
[**production_user_name_get**](ProductionApi.md#production_user_name_get) | **GET** /production/{UserName} | Retrieve all production lines for provided UserName
[**production_user_name_planet_get**](ProductionApi.md#production_user_name_planet_get) | **GET** /production/{UserName}/{Planet} | Retrieve production line for the given UserName on the specified Planet

# **production_planets_user_name_get**
> list[str] production_planets_user_name_get(user_name)

Retrieve all the planets where production lines are present for the provided UserName

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
api_instance = fio_sdk.ProductionApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve a planet list for

try:
    # Retrieve all the planets where production lines are present for the provided UserName
    api_response = api_instance.production_planets_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProductionApi->production_planets_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve a planet list for | 

### Return type

**list[str]**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **production_post**
> production_post()

Posts PRODUCTION_SITE_PRODUCTION_LINES payload

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
api_instance = fio_sdk.ProductionApi(fio_sdk.ApiClient(configuration))

try:
    # Posts PRODUCTION_SITE_PRODUCTION_LINES payload
    api_instance.production_post()
except ApiException as e:
    print("Exception when calling ProductionApi->production_post: %s\n" % e)
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

# **production_user_name_get**
> production_user_name_get(user_name)

Retrieve all production lines for provided UserName

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
api_instance = fio_sdk.ProductionApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve production lines for

try:
    # Retrieve all production lines for provided UserName
    api_instance.production_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling ProductionApi->production_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve production lines for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **production_user_name_planet_get**
> list[object] production_user_name_planet_get(user_name, planet)

Retrieve production line for the given UserName on the specified Planet

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
api_instance = fio_sdk.ProductionApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve a planet list for
planet = 'planet_example' # str | The planet.  It can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName 

try:
    # Retrieve production line for the given UserName on the specified Planet
    api_response = api_instance.production_user_name_planet_get(user_name, planet)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ProductionApi->production_user_name_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve a planet list for | 
 **planet** | **str**| The planet.  It can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName  | 

### Return type

**list[object]**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

