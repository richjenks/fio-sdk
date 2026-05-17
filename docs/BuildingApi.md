# fio_sdk.BuildingApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**building_allbuildings_get**](BuildingApi.md#building_allbuildings_get) | **GET** /building/allbuildings | Gets a list of all buildings (WorldReactorData).
[**building_building_ticker_get**](BuildingApi.md#building_building_ticker_get) | **GET** /building/{BuildingTicker} | Retrieve a payload describing the specified BuildingTicker
[**building_post**](BuildingApi.md#building_post) | **POST** /building | Posts building game data (WorldReactorData) to the server.  For payload, see FIORest source

# **building_allbuildings_get**
> building_allbuildings_get()

Gets a list of all buildings (WorldReactorData).

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.BuildingApi()

try:
    # Gets a list of all buildings (WorldReactorData).
    api_instance.building_allbuildings_get()
except ApiException as e:
    print("Exception when calling BuildingApi->building_allbuildings_get: %s\n" % e)
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

# **building_building_ticker_get**
> building_building_ticker_get(building_ticker)

Retrieve a payload describing the specified BuildingTicker

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.BuildingApi()
building_ticker = 'building_ticker_example' # str | The building ticker to retrieve

try:
    # Retrieve a payload describing the specified BuildingTicker
    api_instance.building_building_ticker_get(building_ticker)
except ApiException as e:
    print("Exception when calling BuildingApi->building_building_ticker_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **building_ticker** | **str**| The building ticker to retrieve | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **building_post**
> building_post()

Posts building game data (WorldReactorData) to the server.  For payload, see FIORest source

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
api_instance = fio_sdk.BuildingApi(fio_sdk.ApiClient(configuration))

try:
    # Posts building game data (WorldReactorData) to the server.  For payload, see FIORest source
    api_instance.building_post()
except ApiException as e:
    print("Exception when calling BuildingApi->building_post: %s\n" % e)
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

