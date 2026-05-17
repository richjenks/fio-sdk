# fio_sdk.RainApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**rain_buildingcosts_get**](RainApi.md#rain_buildingcosts_get) | **GET** /rain/buildingcosts | Retrieves all building cost data (normalized)
[**rain_buildingrecipes_get**](RainApi.md#rain_buildingrecipes_get) | **GET** /rain/buildingrecipes | Retrieves all building recipe data (normalized)
[**rain_buildings_get**](RainApi.md#rain_buildings_get) | **GET** /rain/buildings | Retrieves all building data
[**rain_buildingworkforces_get**](RainApi.md#rain_buildingworkforces_get) | **GET** /rain/buildingworkforces | Retrieves all building workforce data (normalized)
[**rain_materials_get**](RainApi.md#rain_materials_get) | **GET** /rain/materials | Retrieves all material data
[**rain_planetresources_get**](RainApi.md#rain_planetresources_get) | **GET** /rain/planetresources | Retrieves all planet resource data (normalized)
[**rain_prices_get**](RainApi.md#rain_prices_get) | **GET** /rain/prices | Retrieves all CX price data
[**rain_recipeinputs_get**](RainApi.md#rain_recipeinputs_get) | **GET** /rain/recipeinputs | Retrieves all recipe input data (normalized)
[**rain_recipeoutputs_get**](RainApi.md#rain_recipeoutputs_get) | **GET** /rain/recipeoutputs | Retrieves all recipe output data (normalized)
[**rain_userliquid_user_name_get**](RainApi.md#rain_userliquid_user_name_get) | **GET** /rain/userliquid/{UserName} | Retrieves liquid asset data for the given UserName
[**rain_userplanetbuildingreclaimables_user_name_get**](RainApi.md#rain_userplanetbuildingreclaimables_user_name_get) | **GET** /rain/userplanetbuildingreclaimables/{UserName} | Retrieves planet building reclaimables for the given UserName
[**rain_userplanetbuildings_user_name_get**](RainApi.md#rain_userplanetbuildings_user_name_get) | **GET** /rain/userplanetbuildings/{UserName} | Retrieves planet buildings for the given UserName
[**rain_userplanetproduction_user_name_get**](RainApi.md#rain_userplanetproduction_user_name_get) | **GET** /rain/userplanetproduction/{UserName} | Retrieves planet production for the given UserName
[**rain_userplanetproductioninput_user_name_get**](RainApi.md#rain_userplanetproductioninput_user_name_get) | **GET** /rain/userplanetproductioninput/{UserName} | Retrieves planet production inputs for the given UserName
[**rain_userplanetproductionoutput_user_name_get**](RainApi.md#rain_userplanetproductionoutput_user_name_get) | **GET** /rain/userplanetproductionoutput/{UserName} | Retrieves planet production outputs for the given UserName
[**rain_userplanets_user_name_get**](RainApi.md#rain_userplanets_user_name_get) | **GET** /rain/userplanets/{UserName} | Retrieves planets for the given UserName
[**rain_userplanetworkforce_user_name_get**](RainApi.md#rain_userplanetworkforce_user_name_get) | **GET** /rain/userplanetworkforce/{UserName} | Retrieves planet production workforces for the given UserName
[**rain_userstorage_user_name_get**](RainApi.md#rain_userstorage_user_name_get) | **GET** /rain/userstorage/{UserName} | Retrieves planet production workforces for the given UserName

# **rain_buildingcosts_get**
> list[RainBuildingCost] rain_buildingcosts_get()

Retrieves all building cost data (normalized)

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.RainApi()

try:
    # Retrieves all building cost data (normalized)
    api_response = api_instance.rain_buildingcosts_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_buildingcosts_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[RainBuildingCost]**](RainBuildingCost.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rain_buildingrecipes_get**
> list[RainBuildingRecipe] rain_buildingrecipes_get()

Retrieves all building recipe data (normalized)

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.RainApi()

try:
    # Retrieves all building recipe data (normalized)
    api_response = api_instance.rain_buildingrecipes_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_buildingrecipes_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[RainBuildingRecipe]**](RainBuildingRecipe.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rain_buildings_get**
> list[RainBuilding] rain_buildings_get()

Retrieves all building data

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.RainApi()

try:
    # Retrieves all building data
    api_response = api_instance.rain_buildings_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_buildings_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[RainBuilding]**](RainBuilding.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rain_buildingworkforces_get**
> list[RainBuildingWorkforce] rain_buildingworkforces_get()

Retrieves all building workforce data (normalized)

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.RainApi()

try:
    # Retrieves all building workforce data (normalized)
    api_response = api_instance.rain_buildingworkforces_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_buildingworkforces_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[RainBuildingWorkforce]**](RainBuildingWorkforce.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rain_materials_get**
> list[RainMaterial] rain_materials_get()

Retrieves all material data

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.RainApi()

try:
    # Retrieves all material data
    api_response = api_instance.rain_materials_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_materials_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[RainMaterial]**](RainMaterial.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rain_planetresources_get**
> list[RainPlanetResource] rain_planetresources_get()

Retrieves all planet resource data (normalized)

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.RainApi()

try:
    # Retrieves all planet resource data (normalized)
    api_response = api_instance.rain_planetresources_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_planetresources_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[RainPlanetResource]**](RainPlanetResource.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rain_prices_get**
> list[RainPrices] rain_prices_get()

Retrieves all CX price data

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.RainApi()

try:
    # Retrieves all CX price data
    api_response = api_instance.rain_prices_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_prices_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[RainPrices]**](RainPrices.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rain_recipeinputs_get**
> list[RainRecipeInput] rain_recipeinputs_get()

Retrieves all recipe input data (normalized)

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.RainApi()

try:
    # Retrieves all recipe input data (normalized)
    api_response = api_instance.rain_recipeinputs_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_recipeinputs_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[RainRecipeInput]**](RainRecipeInput.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rain_recipeoutputs_get**
> list[RainRecipeOutput] rain_recipeoutputs_get()

Retrieves all recipe output data (normalized)

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.RainApi()

try:
    # Retrieves all recipe output data (normalized)
    api_response = api_instance.rain_recipeoutputs_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_recipeoutputs_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[RainRecipeOutput]**](RainRecipeOutput.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rain_userliquid_user_name_get**
> list[RainLiquid] rain_userliquid_user_name_get(user_name)

Retrieves liquid asset data for the given UserName

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
api_instance = fio_sdk.RainApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves liquid asset data for the given UserName
    api_response = api_instance.rain_userliquid_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_userliquid_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve data for | 

### Return type

[**list[RainLiquid]**](RainLiquid.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

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
api_instance = fio_sdk.RainApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet building reclaimables for the given UserName
    api_response = api_instance.rain_userplanetbuildingreclaimables_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_userplanetbuildingreclaimables_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RainApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet buildings for the given UserName
    api_response = api_instance.rain_userplanetbuildings_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_userplanetbuildings_user_name_get: %s\n" % e)
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

# **rain_userplanetproduction_user_name_get**
> list[RainPlanetProduction] rain_userplanetproduction_user_name_get(user_name)

Retrieves planet production for the given UserName

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
api_instance = fio_sdk.RainApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet production for the given UserName
    api_response = api_instance.rain_userplanetproduction_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_userplanetproduction_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve data for | 

### Return type

[**list[RainPlanetProduction]**](RainPlanetProduction.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rain_userplanetproductioninput_user_name_get**
> list[RainPlanetProductionInput] rain_userplanetproductioninput_user_name_get(user_name)

Retrieves planet production inputs for the given UserName

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
api_instance = fio_sdk.RainApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet production inputs for the given UserName
    api_response = api_instance.rain_userplanetproductioninput_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_userplanetproductioninput_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve data for | 

### Return type

[**list[RainPlanetProductionInput]**](RainPlanetProductionInput.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rain_userplanetproductionoutput_user_name_get**
> list[RainPlanetProductionOutput] rain_userplanetproductionoutput_user_name_get(user_name)

Retrieves planet production outputs for the given UserName

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
api_instance = fio_sdk.RainApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet production outputs for the given UserName
    api_response = api_instance.rain_userplanetproductionoutput_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_userplanetproductionoutput_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve data for | 

### Return type

[**list[RainPlanetProductionOutput]**](RainPlanetProductionOutput.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rain_userplanets_user_name_get**
> list[RainUserPlanet] rain_userplanets_user_name_get(user_name)

Retrieves planets for the given UserName

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
api_instance = fio_sdk.RainApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planets for the given UserName
    api_response = api_instance.rain_userplanets_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_userplanets_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve data for | 

### Return type

[**list[RainUserPlanet]**](RainUserPlanet.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rain_userplanetworkforce_user_name_get**
> list[RainPlanetWorkforce] rain_userplanetworkforce_user_name_get(user_name)

Retrieves planet production workforces for the given UserName

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
api_instance = fio_sdk.RainApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet production workforces for the given UserName
    api_response = api_instance.rain_userplanetworkforce_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_userplanetworkforce_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve data for | 

### Return type

[**list[RainPlanetWorkforce]**](RainPlanetWorkforce.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rain_userstorage_user_name_get**
> list[RainStorage] rain_userstorage_user_name_get(user_name)

Retrieves planet production workforces for the given UserName

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
api_instance = fio_sdk.RainApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet production workforces for the given UserName
    api_response = api_instance.rain_userstorage_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RainApi->rain_userstorage_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve data for | 

### Return type

[**list[RainStorage]**](RainStorage.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

