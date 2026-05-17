# fio_sdk.WorkforceApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**workforce_planets_user_name_get**](WorkforceApi.md#workforce_planets_user_name_get) | **GET** /workforce/planets/{UserName} | Retrieves list of planets where the specified user has Workforce data
[**workforce_post**](WorkforceApi.md#workforce_post) | **POST** /workforce | Posts WORKFORCE_WORKFORCES payload
[**workforce_user_name_get**](WorkforceApi.md#workforce_user_name_get) | **GET** /workforce/{UserName} | Retrieves workforce data for the specified user
[**workforce_user_name_planet_get**](WorkforceApi.md#workforce_user_name_planet_get) | **GET** /workforce/{UserName}/{Planet} | Retrieves workforce data for the specified usernaem and planet

# **workforce_planets_user_name_get**
> list[str] workforce_planets_user_name_get(user_name)

Retrieves list of planets where the specified user has Workforce data

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
api_instance = fio_sdk.WorkforceApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve workforce data for

try:
    # Retrieves list of planets where the specified user has Workforce data
    api_response = api_instance.workforce_planets_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling WorkforceApi->workforce_planets_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve workforce data for | 

### Return type

**list[str]**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **workforce_post**
> workforce_post()

Posts WORKFORCE_WORKFORCES payload

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
api_instance = fio_sdk.WorkforceApi(fio_sdk.ApiClient(configuration))

try:
    # Posts WORKFORCE_WORKFORCES payload
    api_instance.workforce_post()
except ApiException as e:
    print("Exception when calling WorkforceApi->workforce_post: %s\n" % e)
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

# **workforce_user_name_get**
> workforce_user_name_get(user_name)

Retrieves workforce data for the specified user

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
api_instance = fio_sdk.WorkforceApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve workforce data for

try:
    # Retrieves workforce data for the specified user
    api_instance.workforce_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling WorkforceApi->workforce_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve workforce data for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **workforce_user_name_planet_get**
> workforce_user_name_planet_get(user_name, planet)

Retrieves workforce data for the specified usernaem and planet

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
api_instance = fio_sdk.WorkforceApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve workforce data for
planet = 'planet_example' # str | Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName 

try:
    # Retrieves workforce data for the specified usernaem and planet
    api_instance.workforce_user_name_planet_get(user_name, planet)
except ApiException as e:
    print("Exception when calling WorkforceApi->workforce_user_name_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve workforce data for | 
 **planet** | **str**| Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName  | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

