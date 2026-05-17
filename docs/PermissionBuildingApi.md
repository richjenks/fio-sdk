# fio_sdk.PermissionBuildingApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**rain_userplanetbuildingreclaimables_user_name_get**](PermissionBuildingApi.md#rain_userplanetbuildingreclaimables_user_name_get) | **GET** /rain/userplanetbuildingreclaimables/{UserName} | Retrieves planet building reclaimables for the given UserName
[**rain_userplanetbuildings_user_name_get**](PermissionBuildingApi.md#rain_userplanetbuildings_user_name_get) | **GET** /rain/userplanetbuildings/{UserName} | Retrieves planet buildings for the given UserName
[**sites_planets_user_name_get**](PermissionBuildingApi.md#sites_planets_user_name_get) | **GET** /sites/planets/{UserName} | Retrieves list of planets user has site data for
[**sites_user_name_get**](PermissionBuildingApi.md#sites_user_name_get) | **GET** /sites/{UserName} | Retrieves site data
[**sites_user_name_planet_get**](PermissionBuildingApi.md#sites_user_name_planet_get) | **GET** /sites/{UserName}/{Planet} | Retrieves list of planets user has site data for
[**sites_warehouses_user_name_get**](PermissionBuildingApi.md#sites_warehouses_user_name_get) | **GET** /sites/warehouses/{UserName} | Retrieves all warehouse sites the user has

# **rain_userplanetbuildingreclaimables_user_name_get**
> list[RainPlanetBuildingReclaimable] rain_userplanetbuildingreclaimables_user_name_get(user_name)

Retrieves planet building reclaimables for the given UserName

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
api_instance = fio_sdk.PermissionBuildingApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet building reclaimables for the given UserName
    api_response = api_instance.rain_userplanetbuildingreclaimables_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling PermissionBuildingApi->rain_userplanetbuildingreclaimables_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve data for | 

### Return type

[**list[RainPlanetBuildingReclaimable]**](RainPlanetBuildingReclaimable.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rain_userplanetbuildings_user_name_get**
> list[RainPlanetBuilding] rain_userplanetbuildings_user_name_get(user_name)

Retrieves planet buildings for the given UserName

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
api_instance = fio_sdk.PermissionBuildingApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet buildings for the given UserName
    api_response = api_instance.rain_userplanetbuildings_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling PermissionBuildingApi->rain_userplanetbuildings_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve data for | 

### Return type

[**list[RainPlanetBuilding]**](RainPlanetBuilding.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sites_planets_user_name_get**
> list[str] sites_planets_user_name_get(user_name)

Retrieves list of planets user has site data for

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
api_instance = fio_sdk.PermissionBuildingApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve site data for

try:
    # Retrieves list of planets user has site data for
    api_response = api_instance.sites_planets_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling PermissionBuildingApi->sites_planets_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve site data for | 

### Return type

**list[str]**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sites_user_name_get**
> sites_user_name_get(user_name)

Retrieves site data

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
api_instance = fio_sdk.PermissionBuildingApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve site data for

try:
    # Retrieves site data
    api_instance.sites_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling PermissionBuildingApi->sites_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve site data for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sites_user_name_planet_get**
> sites_user_name_planet_get(user_name, planet)

Retrieves list of planets user has site data for

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
api_instance = fio_sdk.PermissionBuildingApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve site data for
planet = 'planet_example' # str | Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName 

try:
    # Retrieves list of planets user has site data for
    api_instance.sites_user_name_planet_get(user_name, planet)
except ApiException as e:
    print("Exception when calling PermissionBuildingApi->sites_user_name_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve site data for | 
 **planet** | **str**| Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName  | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sites_warehouses_user_name_get**
> sites_warehouses_user_name_get(user_name)

Retrieves all warehouse sites the user has

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
api_instance = fio_sdk.PermissionBuildingApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve site data for

try:
    # Retrieves all warehouse sites the user has
    api_instance.sites_warehouses_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling PermissionBuildingApi->sites_warehouses_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve site data for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

