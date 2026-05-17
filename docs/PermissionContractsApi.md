# fio_sdk.PermissionContractsApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**contract_allcontracts_user_name_get**](PermissionContractsApi.md#contract_allcontracts_user_name_get) | **GET** /contract/allcontracts/{UserName} | Retrieves most recent 100 contracts for the given UserName
[**contract_concerns_user_name_get**](PermissionContractsApi.md#contract_concerns_user_name_get) | **GET** /contract/concerns/{UserName} | Retrieves concerning contracts for the given UserName
[**contract_loans_user_name_get**](PermissionContractsApi.md#contract_loans_user_name_get) | **GET** /contract/loans/{UserName} | Retrieves loan contracts for the given UserName
[**contract_taco_get**](PermissionContractsApi.md#contract_taco_get) | **GET** /contract/taco | Retrieves taco statistics for EatTacos88
[**cxos_user_name_get**](PermissionContractsApi.md#cxos_user_name_get) | **GET** /cxos/{UserName} | Retrieves CXOS data for provided username.  See FIORest source for payload definition

# **contract_allcontracts_user_name_get**
> contract_allcontracts_user_name_get(user_name)

Retrieves most recent 100 contracts for the given UserName

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
api_instance = fio_sdk.PermissionContractsApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to lookup

try:
    # Retrieves most recent 100 contracts for the given UserName
    api_instance.contract_allcontracts_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling PermissionContractsApi->contract_allcontracts_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The UserName to lookup | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **contract_concerns_user_name_get**
> contract_concerns_user_name_get(user_name)

Retrieves concerning contracts for the given UserName

Concerning contracts are defined as contracts which: 1) Can be extended 2) Are within 1 day of ending 

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
api_instance = fio_sdk.PermissionContractsApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to lookup

try:
    # Retrieves concerning contracts for the given UserName
    api_instance.contract_concerns_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling PermissionContractsApi->contract_concerns_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The UserName to lookup | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **contract_loans_user_name_get**
> contract_loans_user_name_get(user_name)

Retrieves loan contracts for the given UserName

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
api_instance = fio_sdk.PermissionContractsApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to lookup

try:
    # Retrieves loan contracts for the given UserName
    api_instance.contract_loans_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling PermissionContractsApi->contract_loans_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The UserName to lookup | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **contract_taco_get**
> contract_taco_get()

Retrieves taco statistics for EatTacos88

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
api_instance = fio_sdk.PermissionContractsApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves taco statistics for EatTacos88
    api_instance.contract_taco_get()
except ApiException as e:
    print("Exception when calling PermissionContractsApi->contract_taco_get: %s\n" % e)
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
api_instance = fio_sdk.PermissionContractsApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to lookup CXOS data for

try:
    # Retrieves CXOS data for provided username.  See FIORest source for payload definition
    api_instance.cxos_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling PermissionContractsApi->cxos_user_name_get: %s\n" % e)
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

