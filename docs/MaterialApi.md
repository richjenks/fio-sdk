# fio_sdk.MaterialApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**material_allmaterials_get**](MaterialApi.md#material_allmaterials_get) | **GET** /material/allmaterials | Retrieves all materials.  See FIORest source for payload definition
[**material_category_category_name_get**](MaterialApi.md#material_category_category_name_get) | **GET** /material/category/{CategoryName} | Retrieves all materials that belong to the provided CategoryName. See FIORest source for payload definition
[**material_material_ticker_get**](MaterialApi.md#material_material_ticker_get) | **GET** /material/{MaterialTicker} | Retrieves an individual material by Ticker.  See FIORest source for payload definition
[**material_post**](MaterialApi.md#material_post) | **POST** /material | Posts WORLD_MATERIAL_CATEGORIES payload

# **material_allmaterials_get**
> material_allmaterials_get()

Retrieves all materials.  See FIORest source for payload definition

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.MaterialApi()

try:
    # Retrieves all materials.  See FIORest source for payload definition
    api_instance.material_allmaterials_get()
except ApiException as e:
    print("Exception when calling MaterialApi->material_allmaterials_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **material_category_category_name_get**
> material_category_category_name_get(category_name)

Retrieves all materials that belong to the provided CategoryName. See FIORest source for payload definition

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.MaterialApi()
category_name = 'category_name_example' # str | The CategoryName to retrieve

try:
    # Retrieves all materials that belong to the provided CategoryName. See FIORest source for payload definition
    api_instance.material_category_category_name_get(category_name)
except ApiException as e:
    print("Exception when calling MaterialApi->material_category_category_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **category_name** | **str**| The CategoryName to retrieve | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **material_material_ticker_get**
> material_material_ticker_get(material_ticker)

Retrieves an individual material by Ticker.  See FIORest source for payload definition

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.MaterialApi()
material_ticker = 'material_ticker_example' # str | The Ticker of the material to retrieve

try:
    # Retrieves an individual material by Ticker.  See FIORest source for payload definition
    api_instance.material_material_ticker_get(material_ticker)
except ApiException as e:
    print("Exception when calling MaterialApi->material_material_ticker_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **material_ticker** | **str**| The Ticker of the material to retrieve | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **material_post**
> material_post()

Posts WORLD_MATERIAL_CATEGORIES payload

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
api_instance = fio_sdk.MaterialApi(fio_sdk.ApiClient(configuration))

try:
    # Posts WORLD_MATERIAL_CATEGORIES payload
    api_instance.material_post()
except ApiException as e:
    print("Exception when calling MaterialApi->material_post: %s\n" % e)
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

