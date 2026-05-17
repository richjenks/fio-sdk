# fio_sdk.CompanyApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**company_code_company_code_get**](CompanyApi.md#company_code_company_code_get) | **GET** /company/code/{CompanyCode} | Retrieves company data by CompanyCode
[**company_data_post**](CompanyApi.md#company_data_post) | **POST** /company/data | Posts COMPANY_DATA_DATA payload.  For payload, see FIORest source
[**company_name_company_name_get**](CompanyApi.md#company_name_company_name_get) | **GET** /company/name/{CompanyName} | Retrieves company data by CompanyName
[**company_post**](CompanyApi.md#company_post) | **POST** /company | Posts COMPANY_DATA payload.  For payload, see FIORest source

# **company_code_company_code_get**
> company_code_company_code_get(company_code)

Retrieves company data by CompanyCode

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
api_instance = fio_sdk.CompanyApi(fio_sdk.ApiClient(configuration))
company_code = 'company_code_example' # str | The company code to lookup

try:
    # Retrieves company data by CompanyCode
    api_instance.company_code_company_code_get(company_code)
except ApiException as e:
    print("Exception when calling CompanyApi->company_code_company_code_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **company_code** | **str**| The company code to lookup | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **company_data_post**
> company_data_post()

Posts COMPANY_DATA_DATA payload.  For payload, see FIORest source

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
api_instance = fio_sdk.CompanyApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COMPANY_DATA_DATA payload.  For payload, see FIORest source
    api_instance.company_data_post()
except ApiException as e:
    print("Exception when calling CompanyApi->company_data_post: %s\n" % e)
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

# **company_name_company_name_get**
> company_name_company_name_get(company_name)

Retrieves company data by CompanyName

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
api_instance = fio_sdk.CompanyApi(fio_sdk.ApiClient(configuration))
company_name = 'company_name_example' # str | The company name to lookup

try:
    # Retrieves company data by CompanyName
    api_instance.company_name_company_name_get(company_name)
except ApiException as e:
    print("Exception when calling CompanyApi->company_name_company_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **company_name** | **str**| The company name to lookup | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **company_post**
> company_post()

Posts COMPANY_DATA payload.  For payload, see FIORest source

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
api_instance = fio_sdk.CompanyApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COMPANY_DATA payload.  For payload, see FIORest source
    api_instance.company_post()
except ApiException as e:
    print("Exception when calling CompanyApi->company_post: %s\n" % e)
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

