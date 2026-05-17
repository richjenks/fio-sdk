# fio_sdk.CsvApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**csv_bids_get**](CsvApi.md#csv_bids_get) | **GET** /csv/bids | Price bid information
[**csv_buildingcosts_get**](CsvApi.md#csv_buildingcosts_get) | **GET** /csv/buildingcosts | Building cost information
[**csv_buildingrecipes_get**](CsvApi.md#csv_buildingrecipes_get) | **GET** /csv/buildingrecipes | Building recipe information
[**csv_buildings_get**](CsvApi.md#csv_buildings_get) | **GET** /csv/buildings | Building information
[**csv_buildingworkforces_get**](CsvApi.md#csv_buildingworkforces_get) | **GET** /csv/buildingworkforces | Building workforce information
[**csv_burnrate_get**](CsvApi.md#csv_burnrate_get) | **GET** /csv/burnrate | A specified user&#x27;s burnrate
[**csv_cxos_get**](CsvApi.md#csv_cxos_get) | **GET** /csv/cxos | A specified user&#x27;s CXOS trades
[**csv_cxpc_ticker_get**](CsvApi.md#csv_cxpc_ticker_get) | **GET** /csv/cxpc/{Ticker} | CXPC data for a given ticker
[**csv_infrastructure_allinfos_get**](CsvApi.md#csv_infrastructure_allinfos_get) | **GET** /csv/infrastructure/allinfos | All infrastructure infos
[**csv_infrastructure_allreports_get**](CsvApi.md#csv_infrastructure_allreports_get) | **GET** /csv/infrastructure/allreports | All infrastructure reports
[**csv_infrastructure_infos_planet_get**](CsvApi.md#csv_infrastructure_infos_planet_get) | **GET** /csv/infrastructure/infos/{Planet} | Infrastructure infos for a given planet
[**csv_infrastructure_report_planet_get**](CsvApi.md#csv_infrastructure_report_planet_get) | **GET** /csv/infrastructure/report/{Planet} | Infrastructure report for a given planet
[**csv_inventory_get**](CsvApi.md#csv_inventory_get) | **GET** /csv/inventory | A specified user&#x27;s inventory
[**csv_localmarket_buy_planet_get**](CsvApi.md#csv_localmarket_buy_planet_get) | **GET** /csv/localmarket/buy/{Planet} | All buy ads on a given planet&#x27;s LM
[**csv_localmarket_sell_planet_get**](CsvApi.md#csv_localmarket_sell_planet_get) | **GET** /csv/localmarket/sell/{Planet} | All sell ads on a given planet&#x27;s LM
[**csv_localmarket_ship_planet_get**](CsvApi.md#csv_localmarket_ship_planet_get) | **GET** /csv/localmarket/ship/{Planet} | All shipping ads on a given planet&#x27;s LM
[**csv_materials_get**](CsvApi.md#csv_materials_get) | **GET** /csv/materials | Material information
[**csv_orders_get**](CsvApi.md#csv_orders_get) | **GET** /csv/orders | Price order information
[**csv_planetdetail_get**](CsvApi.md#csv_planetdetail_get) | **GET** /csv/planetdetail | Detailed planet information
[**csv_planetproductionfees_get**](CsvApi.md#csv_planetproductionfees_get) | **GET** /csv/planetproductionfees | Planet production fee information
[**csv_planetresources_get**](CsvApi.md#csv_planetresources_get) | **GET** /csv/planetresources | Planet resource information
[**csv_planets_get**](CsvApi.md#csv_planets_get) | **GET** /csv/planets | Planet information
[**csv_prices_condensed_get**](CsvApi.md#csv_prices_condensed_get) | **GET** /csv/prices/condensed | Price information (condensed horizontally)
[**csv_prices_get**](CsvApi.md#csv_prices_get) | **GET** /csv/prices | Full price information
[**csv_recipeinputs_get**](CsvApi.md#csv_recipeinputs_get) | **GET** /csv/recipeinputs | Recipe input information
[**csv_recipeoutputs_get**](CsvApi.md#csv_recipeoutputs_get) | **GET** /csv/recipeoutputs | Recipe output information
[**csv_sites_get**](CsvApi.md#csv_sites_get) | **GET** /csv/sites | A specified user&#x27;s sites
[**csv_systemlinks_get**](CsvApi.md#csv_systemlinks_get) | **GET** /csv/systemlinks | System links
[**csv_systemplanets_get**](CsvApi.md#csv_systemplanets_get) | **GET** /csv/systemplanets | System planet information
[**csv_systems_get**](CsvApi.md#csv_systems_get) | **GET** /csv/systems | System information
[**csv_workforce_get**](CsvApi.md#csv_workforce_get) | **GET** /csv/workforce | A specified user&#x27;s workforce information

# **csv_bids_get**
> csv_bids_get()

Price bid information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # Price bid information
    api_instance.csv_bids_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_bids_get: %s\n" % e)
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

# **csv_buildingcosts_get**
> csv_buildingcosts_get()

Building cost information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # Building cost information
    api_instance.csv_buildingcosts_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_buildingcosts_get: %s\n" % e)
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

# **csv_buildingrecipes_get**
> csv_buildingrecipes_get()

Building recipe information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # Building recipe information
    api_instance.csv_buildingrecipes_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_buildingrecipes_get: %s\n" % e)
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

# **csv_buildings_get**
> csv_buildings_get()

Building information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # Building information
    api_instance.csv_buildings_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_buildings_get: %s\n" % e)
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

# **csv_buildingworkforces_get**
> csv_buildingworkforces_get()

Building workforce information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # Building workforce information
    api_instance.csv_buildingworkforces_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_buildingworkforces_get: %s\n" % e)
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

# **csv_burnrate_get**
> csv_burnrate_get(apikey, username)

A specified user's burnrate

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()
apikey = 'apikey_example' # str | An API key with read permissions for the given user
username = 'username_example' # str | The username to retrieve information for

try:
    # A specified user's burnrate
    api_instance.csv_burnrate_get(apikey, username)
except ApiException as e:
    print("Exception when calling CsvApi->csv_burnrate_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **apikey** | **str**| An API key with read permissions for the given user | 
 **username** | **str**| The username to retrieve information for | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **csv_cxos_get**
> csv_cxos_get(apikey, username)

A specified user's CXOS trades

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()
apikey = 'apikey_example' # str | An API key with read permissions for the given user
username = 'username_example' # str | The username to retrieve information for

try:
    # A specified user's CXOS trades
    api_instance.csv_cxos_get(apikey, username)
except ApiException as e:
    print("Exception when calling CsvApi->csv_cxos_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **apikey** | **str**| An API key with read permissions for the given user | 
 **username** | **str**| The username to retrieve information for | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **csv_cxpc_ticker_get**
> csv_cxpc_ticker_get(ticker)

CXPC data for a given ticker

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()
ticker = 'ticker_example' # str | The Ticker to lookup

try:
    # CXPC data for a given ticker
    api_instance.csv_cxpc_ticker_get(ticker)
except ApiException as e:
    print("Exception when calling CsvApi->csv_cxpc_ticker_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ticker** | **str**| The Ticker to lookup | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **csv_infrastructure_allinfos_get**
> csv_infrastructure_allinfos_get()

All infrastructure infos

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # All infrastructure infos
    api_instance.csv_infrastructure_allinfos_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_infrastructure_allinfos_get: %s\n" % e)
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

# **csv_infrastructure_allreports_get**
> csv_infrastructure_allreports_get()

All infrastructure reports

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # All infrastructure reports
    api_instance.csv_infrastructure_allreports_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_infrastructure_allreports_get: %s\n" % e)
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

# **csv_infrastructure_infos_planet_get**
> csv_infrastructure_infos_planet_get(planet)

Infrastructure infos for a given planet

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()
planet = 'planet_example' # str | The Planet to lookup

try:
    # Infrastructure infos for a given planet
    api_instance.csv_infrastructure_infos_planet_get(planet)
except ApiException as e:
    print("Exception when calling CsvApi->csv_infrastructure_infos_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **planet** | **str**| The Planet to lookup | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **csv_infrastructure_report_planet_get**
> csv_infrastructure_report_planet_get(planet)

Infrastructure report for a given planet

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()
planet = 'planet_example' # str | The Planet to lookup

try:
    # Infrastructure report for a given planet
    api_instance.csv_infrastructure_report_planet_get(planet)
except ApiException as e:
    print("Exception when calling CsvApi->csv_infrastructure_report_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **planet** | **str**| The Planet to lookup | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **csv_inventory_get**
> csv_inventory_get(apikey, username)

A specified user's inventory

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()
apikey = 'apikey_example' # str | An API key with read permissions for the given user
username = 'username_example' # str | The username to retrieve information for

try:
    # A specified user's inventory
    api_instance.csv_inventory_get(apikey, username)
except ApiException as e:
    print("Exception when calling CsvApi->csv_inventory_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **apikey** | **str**| An API key with read permissions for the given user | 
 **username** | **str**| The username to retrieve information for | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **csv_localmarket_buy_planet_get**
> csv_localmarket_buy_planet_get(planet)

All buy ads on a given planet's LM

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()
planet = 'planet_example' # str | The Planet to lookup

try:
    # All buy ads on a given planet's LM
    api_instance.csv_localmarket_buy_planet_get(planet)
except ApiException as e:
    print("Exception when calling CsvApi->csv_localmarket_buy_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **planet** | **str**| The Planet to lookup | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **csv_localmarket_sell_planet_get**
> csv_localmarket_sell_planet_get(planet)

All sell ads on a given planet's LM

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()
planet = 'planet_example' # str | The Planet to lookup

try:
    # All sell ads on a given planet's LM
    api_instance.csv_localmarket_sell_planet_get(planet)
except ApiException as e:
    print("Exception when calling CsvApi->csv_localmarket_sell_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **planet** | **str**| The Planet to lookup | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **csv_localmarket_ship_planet_get**
> csv_localmarket_ship_planet_get(planet)

All shipping ads on a given planet's LM

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()
planet = 'planet_example' # str | The Planet to lookup

try:
    # All shipping ads on a given planet's LM
    api_instance.csv_localmarket_ship_planet_get(planet)
except ApiException as e:
    print("Exception when calling CsvApi->csv_localmarket_ship_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **planet** | **str**| The Planet to lookup | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **csv_materials_get**
> csv_materials_get()

Material information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # Material information
    api_instance.csv_materials_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_materials_get: %s\n" % e)
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

# **csv_orders_get**
> csv_orders_get()

Price order information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # Price order information
    api_instance.csv_orders_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_orders_get: %s\n" % e)
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

# **csv_planetdetail_get**
> csv_planetdetail_get()

Detailed planet information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # Detailed planet information
    api_instance.csv_planetdetail_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_planetdetail_get: %s\n" % e)
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

# **csv_planetproductionfees_get**
> csv_planetproductionfees_get()

Planet production fee information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # Planet production fee information
    api_instance.csv_planetproductionfees_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_planetproductionfees_get: %s\n" % e)
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

# **csv_planetresources_get**
> csv_planetresources_get()

Planet resource information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # Planet resource information
    api_instance.csv_planetresources_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_planetresources_get: %s\n" % e)
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

# **csv_planets_get**
> csv_planets_get()

Planet information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # Planet information
    api_instance.csv_planets_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_planets_get: %s\n" % e)
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

# **csv_prices_condensed_get**
> csv_prices_condensed_get()

Price information (condensed horizontally)

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # Price information (condensed horizontally)
    api_instance.csv_prices_condensed_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_prices_condensed_get: %s\n" % e)
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

# **csv_prices_get**
> csv_prices_get()

Full price information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # Full price information
    api_instance.csv_prices_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_prices_get: %s\n" % e)
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

# **csv_recipeinputs_get**
> csv_recipeinputs_get()

Recipe input information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # Recipe input information
    api_instance.csv_recipeinputs_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_recipeinputs_get: %s\n" % e)
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

# **csv_recipeoutputs_get**
> csv_recipeoutputs_get()

Recipe output information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # Recipe output information
    api_instance.csv_recipeoutputs_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_recipeoutputs_get: %s\n" % e)
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

# **csv_sites_get**
> csv_sites_get(apikey, username)

A specified user's sites

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()
apikey = 'apikey_example' # str | An API key with read permissions for the given user
username = 'username_example' # str | The username to retrieve information for

try:
    # A specified user's sites
    api_instance.csv_sites_get(apikey, username)
except ApiException as e:
    print("Exception when calling CsvApi->csv_sites_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **apikey** | **str**| An API key with read permissions for the given user | 
 **username** | **str**| The username to retrieve information for | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **csv_systemlinks_get**
> csv_systemlinks_get()

System links

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # System links
    api_instance.csv_systemlinks_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_systemlinks_get: %s\n" % e)
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

# **csv_systemplanets_get**
> csv_systemplanets_get()

System planet information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # System planet information
    api_instance.csv_systemplanets_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_systemplanets_get: %s\n" % e)
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

# **csv_systems_get**
> csv_systems_get()

System information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()

try:
    # System information
    api_instance.csv_systems_get()
except ApiException as e:
    print("Exception when calling CsvApi->csv_systems_get: %s\n" % e)
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

# **csv_workforce_get**
> csv_workforce_get(apikey, username)

A specified user's workforce information

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.CsvApi()
apikey = 'apikey_example' # str | An API key with read permissions for the given user
username = 'username_example' # str | The username to retrieve information for

try:
    # A specified user's workforce information
    api_instance.csv_workforce_get(apikey, username)
except ApiException as e:
    print("Exception when calling CsvApi->csv_workforce_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **apikey** | **str**| An API key with read permissions for the given user | 
 **username** | **str**| The username to retrieve information for | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

