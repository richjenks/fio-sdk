# fio_sdk.StorageApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**storage_change_post**](StorageApi.md#storage_change_post) | **POST** /storage/change | Posts STORAGE_CHANGE payload
[**storage_planets_user_name_get**](StorageApi.md#storage_planets_user_name_get) | **GET** /storage/planets/{UserName} | Retrieves list of Planets where storage data exists for UserName
[**storage_user_name_get**](StorageApi.md#storage_user_name_get) | **GET** /storage/{UserName} | Retrieves storage data
[**storage_user_name_storage_description_get**](StorageApi.md#storage_user_name_storage_description_get) | **GET** /storage/{UserName}/{StorageDescription} | Retrieves list of Planets where storage data exists for UserName

# **storage_change_post**
> storage_change_post()

Posts STORAGE_CHANGE payload

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
api_instance = fio_sdk.StorageApi(fio_sdk.ApiClient(configuration))

try:
    # Posts STORAGE_CHANGE payload
    api_instance.storage_change_post()
except ApiException as e:
    print("Exception when calling StorageApi->storage_change_post: %s\n" % e)
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

# **storage_planets_user_name_get**
> list[str] storage_planets_user_name_get(user_name)

Retrieves list of Planets where storage data exists for UserName

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
api_instance = fio_sdk.StorageApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve storage data for

try:
    # Retrieves list of Planets where storage data exists for UserName
    api_response = api_instance.storage_planets_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling StorageApi->storage_planets_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve storage data for | 

### Return type

**list[str]**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **storage_user_name_get**
> storage_user_name_get(user_name)

Retrieves storage data

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
api_instance = fio_sdk.StorageApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve storage data for

try:
    # Retrieves storage data
    api_instance.storage_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling StorageApi->storage_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve storage data for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **storage_user_name_storage_description_get**
> storage_user_name_storage_description_get(user_name, storage_description)

Retrieves list of Planets where storage data exists for UserName

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
api_instance = fio_sdk.StorageApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve storage data for
storage_description = 'storage_description_example' # str | Can be any of the following: 1) StorageId 2) PlanetId 3) PlanetNaturalId 4) PlanetName 

try:
    # Retrieves list of Planets where storage data exists for UserName
    api_instance.storage_user_name_storage_description_get(user_name, storage_description)
except ApiException as e:
    print("Exception when calling StorageApi->storage_user_name_storage_description_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve storage data for | 
 **storage_description** | **str**| Can be any of the following: 1) StorageId 2) PlanetId 3) PlanetNaturalId 4) PlanetName  | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

