# fio_sdk.CxosApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**cxos_added_post**](CxosApi.md#cxos_added_post) | **POST** /cxos/added | Posts COMEX_TRADER_ORDER_ADDED data payload
[**cxos_post**](CxosApi.md#cxos_post) | **POST** /cxos | Posts COMEX_TRADER_ORDERS data payload
[**cxos_removed_post**](CxosApi.md#cxos_removed_post) | **POST** /cxos/removed | Posts COMEX_TRADER_ORDER_REMOVED data payload
[**cxos_updated_post**](CxosApi.md#cxos_updated_post) | **POST** /cxos/updated | Posts COMEX_TRADER_ORDER_UPDATED data payload
[**cxos_user_name_get**](CxosApi.md#cxos_user_name_get) | **GET** /cxos/{UserName} | Retrieves CXOS data for provided username.  See FIORest source for payload definition

# **cxos_added_post**
> cxos_added_post()

Posts COMEX_TRADER_ORDER_ADDED data payload

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
api_instance = fio_sdk.CxosApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COMEX_TRADER_ORDER_ADDED data payload
    api_instance.cxos_added_post()
except ApiException as e:
    print("Exception when calling CxosApi->cxos_added_post: %s\n" % e)
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

# **cxos_post**
> cxos_post()

Posts COMEX_TRADER_ORDERS data payload

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
api_instance = fio_sdk.CxosApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COMEX_TRADER_ORDERS data payload
    api_instance.cxos_post()
except ApiException as e:
    print("Exception when calling CxosApi->cxos_post: %s\n" % e)
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

# **cxos_removed_post**
> cxos_removed_post()

Posts COMEX_TRADER_ORDER_REMOVED data payload

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
api_instance = fio_sdk.CxosApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COMEX_TRADER_ORDER_REMOVED data payload
    api_instance.cxos_removed_post()
except ApiException as e:
    print("Exception when calling CxosApi->cxos_removed_post: %s\n" % e)
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

# **cxos_updated_post**
> cxos_updated_post()

Posts COMEX_TRADER_ORDER_UPDATED data payload

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
api_instance = fio_sdk.CxosApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COMEX_TRADER_ORDER_UPDATED data payload
    api_instance.cxos_updated_post()
except ApiException as e:
    print("Exception when calling CxosApi->cxos_updated_post: %s\n" % e)
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

# **cxos_user_name_get**
> cxos_user_name_get(user_name)

Retrieves CXOS data for provided username.  See FIORest source for payload definition

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
api_instance = fio_sdk.CxosApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to lookup CXOS data for

try:
    # Retrieves CXOS data for provided username.  See FIORest source for payload definition
    api_instance.cxos_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling CxosApi->cxos_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to lookup CXOS data for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

