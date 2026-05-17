# fio_sdk.UserApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**user_allusers_get**](UserApi.md#user_allusers_get) | **GET** /user/allusers | Retrieves all FIO users
[**user_post**](UserApi.md#user_post) | **POST** /user | Posts USER_DATA payload
[**user_resetalldata_post**](UserApi.md#user_resetalldata_post) | **POST** /user/resetalldata | Resets the current user&#x27;s data.
[**user_user_name_get**](UserApi.md#user_user_name_get) | **GET** /user/{UserName} | Retrieves userdata for specified UserName

# **user_allusers_get**
> list[str] user_allusers_get()

Retrieves all FIO users

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
api_instance = fio_sdk.UserApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves all FIO users
    api_response = api_instance.user_allusers_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling UserApi->user_allusers_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

**list[str]**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **user_post**
> user_post()

Posts USER_DATA payload

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
api_instance = fio_sdk.UserApi(fio_sdk.ApiClient(configuration))

try:
    # Posts USER_DATA payload
    api_instance.user_post()
except ApiException as e:
    print("Exception when calling UserApi->user_post: %s\n" % e)
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

# **user_resetalldata_post**
> user_resetalldata_post()

Resets the current user's data.

This will delete the following data for your User: 1) Company data 2) ProductionLine data 3) Ship data 4) Site data 5) Workforce data 6) User data 7) Warehouse data 8) Contract data  You should only use this if your data has been corrupted by excess hydration timeouts 

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
api_instance = fio_sdk.UserApi(fio_sdk.ApiClient(configuration))

try:
    # Resets the current user's data.
    api_instance.user_resetalldata_post()
except ApiException as e:
    print("Exception when calling UserApi->user_resetalldata_post: %s\n" % e)
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

# **user_user_name_get**
> user_user_name_get(user_name)

Retrieves userdata for specified UserName

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
api_instance = fio_sdk.UserApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve user data for

try:
    # Retrieves userdata for specified UserName
    api_instance.user_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling UserApi->user_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve user data for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

