# fio_sdk.ContractApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**contract_allcontracts_get**](ContractApi.md#contract_allcontracts_get) | **GET** /contract/allcontracts | Retrieves most recent 100 contracts for the current user
[**contract_allcontracts_user_name_get**](ContractApi.md#contract_allcontracts_user_name_get) | **GET** /contract/allcontracts/{UserName} | Retrieves most recent 100 contracts for the given UserName
[**contract_change_post**](ContractApi.md#contract_change_post) | **POST** /contract/change | Posts CONTRACTS_CONTRACT payload. See FIORest source for payload definition
[**contract_concerns_get**](ContractApi.md#contract_concerns_get) | **GET** /contract/concerns | Retrieves contracts which can be extended or are within 1 day of ending
[**contract_concerns_user_name_get**](ContractApi.md#contract_concerns_user_name_get) | **GET** /contract/concerns/{UserName} | Retrieves concerning contracts for the given UserName
[**contract_loans_get**](ContractApi.md#contract_loans_get) | **GET** /contract/loans | Retrieves loan contracts for the current user
[**contract_loans_user_name_get**](ContractApi.md#contract_loans_user_name_get) | **GET** /contract/loans/{UserName} | Retrieves loan contracts for the given UserName
[**contract_post**](ContractApi.md#contract_post) | **POST** /contract | Posts CONTRACTS_CONTRACTS payload. See FIORest source for payload definition
[**contract_shipments_get**](ContractApi.md#contract_shipments_get) | **GET** /contract/shipments | Retrieves information on the location of your shipments
[**contract_taco_get**](ContractApi.md#contract_taco_get) | **GET** /contract/taco | Retrieves taco statistics for EatTacos88

# **contract_allcontracts_get**
> contract_allcontracts_get()

Retrieves most recent 100 contracts for the current user

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
api_instance = fio_sdk.ContractApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves most recent 100 contracts for the current user
    api_instance.contract_allcontracts_get()
except ApiException as e:
    print("Exception when calling ContractApi->contract_allcontracts_get: %s\n" % e)
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
api_instance = fio_sdk.ContractApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to lookup

try:
    # Retrieves most recent 100 contracts for the given UserName
    api_instance.contract_allcontracts_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling ContractApi->contract_allcontracts_user_name_get: %s\n" % e)
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

# **contract_change_post**
> contract_change_post()

Posts CONTRACTS_CONTRACT payload. See FIORest source for payload definition

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
api_instance = fio_sdk.ContractApi(fio_sdk.ApiClient(configuration))

try:
    # Posts CONTRACTS_CONTRACT payload. See FIORest source for payload definition
    api_instance.contract_change_post()
except ApiException as e:
    print("Exception when calling ContractApi->contract_change_post: %s\n" % e)
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

# **contract_concerns_get**
> contract_concerns_get()

Retrieves contracts which can be extended or are within 1 day of ending

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
api_instance = fio_sdk.ContractApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves contracts which can be extended or are within 1 day of ending
    api_instance.contract_concerns_get()
except ApiException as e:
    print("Exception when calling ContractApi->contract_concerns_get: %s\n" % e)
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
api_instance = fio_sdk.ContractApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to lookup

try:
    # Retrieves concerning contracts for the given UserName
    api_instance.contract_concerns_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling ContractApi->contract_concerns_user_name_get: %s\n" % e)
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

# **contract_loans_get**
> contract_loans_get()

Retrieves loan contracts for the current user

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
api_instance = fio_sdk.ContractApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves loan contracts for the current user
    api_instance.contract_loans_get()
except ApiException as e:
    print("Exception when calling ContractApi->contract_loans_get: %s\n" % e)
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
api_instance = fio_sdk.ContractApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to lookup

try:
    # Retrieves loan contracts for the given UserName
    api_instance.contract_loans_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling ContractApi->contract_loans_user_name_get: %s\n" % e)
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

# **contract_post**
> contract_post()

Posts CONTRACTS_CONTRACTS payload. See FIORest source for payload definition

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
api_instance = fio_sdk.ContractApi(fio_sdk.ApiClient(configuration))

try:
    # Posts CONTRACTS_CONTRACTS payload. See FIORest source for payload definition
    api_instance.contract_post()
except ApiException as e:
    print("Exception when calling ContractApi->contract_post: %s\n" % e)
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

# **contract_shipments_get**
> contract_shipments_get()

Retrieves information on the location of your shipments

This will retrieve the location of your shipment, assuming that user is also present on FIO and has given you the 'ShipmentTracking' permission 

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
api_instance = fio_sdk.ContractApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves information on the location of your shipments
    api_instance.contract_shipments_get()
except ApiException as e:
    print("Exception when calling ContractApi->contract_shipments_get: %s\n" % e)
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
api_instance = fio_sdk.ContractApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves taco statistics for EatTacos88
    api_instance.contract_taco_get()
except ApiException as e:
    print("Exception when calling ContractApi->contract_taco_get: %s\n" % e)
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

