# fio_sdk.ExchangeApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**exchange_all_get**](ExchangeApi.md#exchange_all_get) | **GET** /exchange/all | Retrieves summarized information of all exchange data
[**exchange_cxpc_exchange_ticker_get**](ExchangeApi.md#exchange_cxpc_exchange_ticker_get) | **GET** /exchange/cxpc/{ExchangeTicker} | Retrieves exchange price chart data for the given ticker
[**exchange_cxpc_exchange_ticker_time_stamp_get**](ExchangeApi.md#exchange_cxpc_exchange_ticker_time_stamp_get) | **GET** /exchange/cxpc/{ExchangeTicker}/{TimeStamp} | Retrieves exchange price chart data for the given ticker
[**exchange_exchange_ticker_get**](ExchangeApi.md#exchange_exchange_ticker_get) | **GET** /exchange/{ExchangeTicker} | Retrieves Exchange data for the provided ExchangeTicker
[**exchange_full_get**](ExchangeApi.md#exchange_full_get) | **GET** /exchange/full | Retrieves all the exchange data, including order info
[**exchange_orders_company_code_exchange_code_get**](ExchangeApi.md#exchange_orders_company_code_exchange_code_get) | **GET** /exchange/orders/{CompanyCode}/{ExchangeCode} | Retrieves a provided company code&#x27;s orders on all exchanges
[**exchange_orders_company_code_get**](ExchangeApi.md#exchange_orders_company_code_get) | **GET** /exchange/orders/{CompanyCode} | Retrieves a provided company code&#x27;s orders on all exchanges
[**exchange_post**](ExchangeApi.md#exchange_post) | **POST** /exchange | Posts COMEX_BROKER_DATA data payload
[**exchange_station_get**](ExchangeApi.md#exchange_station_get) | **GET** /exchange/station | Retrieves all exchange station data

# **exchange_all_get**
> exchange_all_get()

Retrieves summarized information of all exchange data

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.ExchangeApi()

try:
    # Retrieves summarized information of all exchange data
    api_instance.exchange_all_get()
except ApiException as e:
    print("Exception when calling ExchangeApi->exchange_all_get: %s\n" % e)
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

# **exchange_cxpc_exchange_ticker_get**
> exchange_cxpc_exchange_ticker_get(exchange_ticker)

Retrieves exchange price chart data for the given ticker

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.ExchangeApi()
exchange_ticker = 'exchange_ticker_example' # str | Format: 'Material.ExchangeCode'

try:
    # Retrieves exchange price chart data for the given ticker
    api_instance.exchange_cxpc_exchange_ticker_get(exchange_ticker)
except ApiException as e:
    print("Exception when calling ExchangeApi->exchange_cxpc_exchange_ticker_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **exchange_ticker** | **str**| Format: &#x27;Material.ExchangeCode&#x27; | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **exchange_cxpc_exchange_ticker_time_stamp_get**
> exchange_cxpc_exchange_ticker_time_stamp_get(exchange_ticker, time_stamp)

Retrieves exchange price chart data for the given ticker

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.ExchangeApi()
exchange_ticker = 'exchange_ticker_example' # str | Format: 'Material.ExchangeCode'
time_stamp = 56 # int | Format: 'Milliseconds since epoch, UTC'

try:
    # Retrieves exchange price chart data for the given ticker
    api_instance.exchange_cxpc_exchange_ticker_time_stamp_get(exchange_ticker, time_stamp)
except ApiException as e:
    print("Exception when calling ExchangeApi->exchange_cxpc_exchange_ticker_time_stamp_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **exchange_ticker** | **str**| Format: &#x27;Material.ExchangeCode&#x27; | 
 **time_stamp** | **int**| Format: &#x27;Milliseconds since epoch, UTC&#x27; | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **exchange_exchange_ticker_get**
> exchange_exchange_ticker_get(exchange_ticker)

Retrieves Exchange data for the provided ExchangeTicker

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.ExchangeApi()
exchange_ticker = 'exchange_ticker_example' # str | Format: 'Material.ExchangeCode'

try:
    # Retrieves Exchange data for the provided ExchangeTicker
    api_instance.exchange_exchange_ticker_get(exchange_ticker)
except ApiException as e:
    print("Exception when calling ExchangeApi->exchange_exchange_ticker_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **exchange_ticker** | **str**| Format: &#x27;Material.ExchangeCode&#x27; | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **exchange_full_get**
> exchange_full_get()

Retrieves all the exchange data, including order info

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.ExchangeApi()

try:
    # Retrieves all the exchange data, including order info
    api_instance.exchange_full_get()
except ApiException as e:
    print("Exception when calling ExchangeApi->exchange_full_get: %s\n" % e)
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

# **exchange_orders_company_code_exchange_code_get**
> exchange_orders_company_code_exchange_code_get(company_code, exchange_code)

Retrieves a provided company code's orders on all exchanges

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.ExchangeApi()
company_code = 'company_code_example' # str | The 1 to 4 character company code
exchange_code = 'exchange_code_example' # str | The 3 character exchange code

try:
    # Retrieves a provided company code's orders on all exchanges
    api_instance.exchange_orders_company_code_exchange_code_get(company_code, exchange_code)
except ApiException as e:
    print("Exception when calling ExchangeApi->exchange_orders_company_code_exchange_code_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **company_code** | **str**| The 1 to 4 character company code | 
 **exchange_code** | **str**| The 3 character exchange code | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **exchange_orders_company_code_get**
> exchange_orders_company_code_get(company_code)

Retrieves a provided company code's orders on all exchanges

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.ExchangeApi()
company_code = 'company_code_example' # str | The 1 to 4 character company code

try:
    # Retrieves a provided company code's orders on all exchanges
    api_instance.exchange_orders_company_code_get(company_code)
except ApiException as e:
    print("Exception when calling ExchangeApi->exchange_orders_company_code_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **company_code** | **str**| The 1 to 4 character company code | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **exchange_post**
> exchange_post()

Posts COMEX_BROKER_DATA data payload

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
api_instance = fio_sdk.ExchangeApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COMEX_BROKER_DATA data payload
    api_instance.exchange_post()
except ApiException as e:
    print("Exception when calling ExchangeApi->exchange_post: %s\n" % e)
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

# **exchange_station_get**
> exchange_station_get()

Retrieves all exchange station data

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.ExchangeApi()

try:
    # Retrieves all exchange station data
    api_instance.exchange_station_get()
except ApiException as e:
    print("Exception when calling ExchangeApi->exchange_station_get: %s\n" % e)
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

