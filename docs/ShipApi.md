# fio_sdk.ShipApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ship_flights_post**](ShipApi.md#ship_flights_post) | **POST** /ship/flights | Posts SHIP_FLIGHT_FLIGHTS payload
[**ship_flights_user_name_get**](ShipApi.md#ship_flights_user_name_get) | **GET** /ship/flights/{UserName} | Retrieves ship flight data
[**ship_ships_fuel_user_name_get**](ShipApi.md#ship_ships_fuel_user_name_get) | **GET** /ship/ships/fuel/{UserName} | Retrieves ship fuel store data
[**ship_ships_post**](ShipApi.md#ship_ships_post) | **POST** /ship/ships | Posts SHIP_SHIPS payload
[**ship_ships_user_name_get**](ShipApi.md#ship_ships_user_name_get) | **GET** /ship/ships/{UserName} | Retrieves ship data

# **ship_flights_post**
> ship_flights_post()

Posts SHIP_FLIGHT_FLIGHTS payload

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
api_instance = fio_sdk.ShipApi(fio_sdk.ApiClient(configuration))

try:
    # Posts SHIP_FLIGHT_FLIGHTS payload
    api_instance.ship_flights_post()
except ApiException as e:
    print("Exception when calling ShipApi->ship_flights_post: %s\n" % e)
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

# **ship_flights_user_name_get**
> ship_flights_user_name_get(user_name)

Retrieves ship flight data

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
api_instance = fio_sdk.ShipApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve flight data for

try:
    # Retrieves ship flight data
    api_instance.ship_flights_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling ShipApi->ship_flights_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve flight data for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ship_ships_fuel_user_name_get**
> ship_ships_fuel_user_name_get(user_name)

Retrieves ship fuel store data

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
api_instance = fio_sdk.ShipApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to ship stl/ftl store models for

try:
    # Retrieves ship fuel store data
    api_instance.ship_ships_fuel_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling ShipApi->ship_ships_fuel_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to ship stl/ftl store models for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **ship_ships_post**
> ship_ships_post()

Posts SHIP_SHIPS payload

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
api_instance = fio_sdk.ShipApi(fio_sdk.ApiClient(configuration))

try:
    # Posts SHIP_SHIPS payload
    api_instance.ship_ships_post()
except ApiException as e:
    print("Exception when calling ShipApi->ship_ships_post: %s\n" % e)
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

# **ship_ships_user_name_get**
> ship_ships_user_name_get(user_name)

Retrieves ship data

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
api_instance = fio_sdk.ShipApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve ship data for

try:
    # Retrieves ship data
    api_instance.ship_ships_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling ShipApi->ship_ships_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve ship data for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

