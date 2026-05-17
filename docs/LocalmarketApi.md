# fio_sdk.LocalmarketApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**localmarket_company_company_get**](LocalmarketApi.md#localmarket_company_company_get) | **GET** /localmarket/company/{Company} | Retrieves all ads found by specified Company
[**localmarket_local_market_id_get**](LocalmarketApi.md#localmarket_local_market_id_get) | **GET** /localmarket/{LocalMarketId} | Retrieves LocalMarket data for the provided LocalMarketId
[**localmarket_planet_planet_get**](LocalmarketApi.md#localmarket_planet_planet_get) | **GET** /localmarket/planet/{Planet} | Retrieves LocalMarket data for provided Planet
[**localmarket_planet_planet_type_get**](LocalmarketApi.md#localmarket_planet_planet_type_get) | **GET** /localmarket/planet/{Planet}/{Type} | Retrieves LocalMarket data for provided Planet and specified type
[**localmarket_post**](LocalmarketApi.md#localmarket_post) | **POST** /localmarket | Posts LOCAL_MARKET_DATA_DATA data payload
[**localmarket_search_post**](LocalmarketApi.md#localmarket_search_post) | **POST** /localmarket/search | Searches all local markets for a given material
[**localmarket_shipping_destination_destination_planet_get**](LocalmarketApi.md#localmarket_shipping_destination_destination_planet_get) | **GET** /localmarket/shipping/destination/{DestinationPlanet} | Retrieves shipping LocalMarket data for the provided Planet where the drop-off location is DestinationPlanet
[**localmarket_shipping_source_source_planet_get**](LocalmarketApi.md#localmarket_shipping_source_source_planet_get) | **GET** /localmarket/shipping/source/{SourcePlanet} | Retrieves shipping LocalMarket data for the provided Planet where the pick-up location is SourcePlanet

# **localmarket_company_company_get**
> localmarket_company_company_get(company)

Retrieves all ads found by specified Company

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.LocalmarketApi()
company = 'company_example' # str | Can be any of the following: 1) CompanyId 2) CompanyId 3) CompanyName 

try:
    # Retrieves all ads found by specified Company
    api_instance.localmarket_company_company_get(company)
except ApiException as e:
    print("Exception when calling LocalmarketApi->localmarket_company_company_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **company** | **str**| Can be any of the following: 1) CompanyId 2) CompanyId 3) CompanyName  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **localmarket_local_market_id_get**
> localmarket_local_market_id_get(local_market_id)

Retrieves LocalMarket data for the provided LocalMarketId

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.LocalmarketApi()
local_market_id = 'local_market_id_example' # str | The MarketId (see payload in FIORest)

try:
    # Retrieves LocalMarket data for the provided LocalMarketId
    api_instance.localmarket_local_market_id_get(local_market_id)
except ApiException as e:
    print("Exception when calling LocalmarketApi->localmarket_local_market_id_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **local_market_id** | **str**| The MarketId (see payload in FIORest) | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **localmarket_planet_planet_get**
> localmarket_planet_planet_get(planet)

Retrieves LocalMarket data for provided Planet

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.LocalmarketApi()
planet = 'planet_example' # str | Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName 

try:
    # Retrieves LocalMarket data for provided Planet
    api_instance.localmarket_planet_planet_get(planet)
except ApiException as e:
    print("Exception when calling LocalmarketApi->localmarket_planet_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **planet** | **str**| Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **localmarket_planet_planet_type_get**
> localmarket_planet_planet_type_get(planet, type)

Retrieves LocalMarket data for provided Planet and specified type

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.LocalmarketApi()
planet = 'planet_example' # str | Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName 
type = 'type_example' # str | Can be any of the following: 1) BUY | BUYS | BUYING 2) SELL | SELLS | SELLING 3) SHIP | SHIPPING 

try:
    # Retrieves LocalMarket data for provided Planet and specified type
    api_instance.localmarket_planet_planet_type_get(planet, type)
except ApiException as e:
    print("Exception when calling LocalmarketApi->localmarket_planet_planet_type_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **planet** | **str**| Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName  | 
 **type** | **str**| Can be any of the following: 1) BUY | BUYS | BUYING 2) SELL | SELLS | SELLING 3) SHIP | SHIPPING  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **localmarket_post**
> localmarket_post()

Posts LOCAL_MARKET_DATA_DATA data payload

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
api_instance = fio_sdk.LocalmarketApi(fio_sdk.ApiClient(configuration))

try:
    # Posts LOCAL_MARKET_DATA_DATA data payload
    api_instance.localmarket_post()
except ApiException as e:
    print("Exception when calling LocalmarketApi->localmarket_post: %s\n" % e)
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

# **localmarket_search_post**
> localmarket_search_post(body)

Searches all local markets for a given material

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.LocalmarketApi()
body = fio_sdk.LocalMarketSearch() # LocalMarketSearch | The search paremeters

try:
    # Searches all local markets for a given material
    api_instance.localmarket_search_post(body)
except ApiException as e:
    print("Exception when calling LocalmarketApi->localmarket_search_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**LocalMarketSearch**](LocalMarketSearch.md)| The search paremeters | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **localmarket_shipping_destination_destination_planet_get**
> localmarket_shipping_destination_destination_planet_get(destination_planet)

Retrieves shipping LocalMarket data for the provided Planet where the drop-off location is DestinationPlanet

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.LocalmarketApi()
destination_planet = 'destination_planet_example' # str | Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName 

try:
    # Retrieves shipping LocalMarket data for the provided Planet where the drop-off location is DestinationPlanet
    api_instance.localmarket_shipping_destination_destination_planet_get(destination_planet)
except ApiException as e:
    print("Exception when calling LocalmarketApi->localmarket_shipping_destination_destination_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **destination_planet** | **str**| Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **localmarket_shipping_source_source_planet_get**
> localmarket_shipping_source_source_planet_get(source_planet)

Retrieves shipping LocalMarket data for the provided Planet where the pick-up location is SourcePlanet

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.LocalmarketApi()
source_planet = 'source_planet_example' # str | Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName 

try:
    # Retrieves shipping LocalMarket data for the provided Planet where the pick-up location is SourcePlanet
    api_instance.localmarket_shipping_source_source_planet_get(source_planet)
except ApiException as e:
    print("Exception when calling LocalmarketApi->localmarket_shipping_source_source_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **source_planet** | **str**| Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

