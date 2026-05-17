# fio_sdk.PermissionStorageApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**company_code_company_code_get**](PermissionStorageApi.md#company_code_company_code_get) | **GET** /company/code/{CompanyCode} | Retrieves company data by CompanyCode
[**company_name_company_name_get**](PermissionStorageApi.md#company_name_company_name_get) | **GET** /company/name/{CompanyName} | Retrieves company data by CompanyName
[**rain_userliquid_user_name_get**](PermissionStorageApi.md#rain_userliquid_user_name_get) | **GET** /rain/userliquid/{UserName} | Retrieves liquid asset data for the given UserName
[**rain_userplanets_user_name_get**](PermissionStorageApi.md#rain_userplanets_user_name_get) | **GET** /rain/userplanets/{UserName} | Retrieves planets for the given UserName
[**rain_userstorage_user_name_get**](PermissionStorageApi.md#rain_userstorage_user_name_get) | **GET** /rain/userstorage/{UserName} | Retrieves planet production workforces for the given UserName
[**storage_planets_user_name_get**](PermissionStorageApi.md#storage_planets_user_name_get) | **GET** /storage/planets/{UserName} | Retrieves list of Planets where storage data exists for UserName
[**storage_user_name_get**](PermissionStorageApi.md#storage_user_name_get) | **GET** /storage/{UserName} | Retrieves storage data
[**storage_user_name_storage_description_get**](PermissionStorageApi.md#storage_user_name_storage_description_get) | **GET** /storage/{UserName}/{StorageDescription} | Retrieves list of Planets where storage data exists for UserName
[**usersettings_burnrate_user_name_get**](PermissionStorageApi.md#usersettings_burnrate_user_name_get) | **GET** /usersettings/burnrate/{UserName} | Retrieves BurnRateSettings for the specified user
[**usersettings_burnrate_user_name_planet_natural_id_get**](PermissionStorageApi.md#usersettings_burnrate_user_name_planet_natural_id_get) | **GET** /usersettings/burnrate/{UserName}/{PlanetNaturalId} | Retrivies BurnRateSettings for the specified user on the specified planet

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
api_instance = fio_sdk.PermissionStorageApi(fio_sdk.ApiClient(configuration))
company_code = 'company_code_example' # str | The company code to lookup

try:
    # Retrieves company data by CompanyCode
    api_instance.company_code_company_code_get(company_code)
except ApiException as e:
    print("Exception when calling PermissionStorageApi->company_code_company_code_get: %s\n" % e)
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
api_instance = fio_sdk.PermissionStorageApi(fio_sdk.ApiClient(configuration))
company_name = 'company_name_example' # str | The company name to lookup

try:
    # Retrieves company data by CompanyName
    api_instance.company_name_company_name_get(company_name)
except ApiException as e:
    print("Exception when calling PermissionStorageApi->company_name_company_name_get: %s\n" % e)
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
api_instance = fio_sdk.PermissionStorageApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves liquid asset data for the given UserName
    api_response = api_instance.rain_userliquid_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling PermissionStorageApi->rain_userliquid_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.PermissionStorageApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planets for the given UserName
    api_response = api_instance.rain_userplanets_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling PermissionStorageApi->rain_userplanets_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.PermissionStorageApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet production workforces for the given UserName
    api_response = api_instance.rain_userstorage_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling PermissionStorageApi->rain_userstorage_user_name_get: %s\n" % e)
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

# **storage_planets_user_name_get**
> list[str] storage_planets_user_name_get(user_name)

Retrieves list of Planets where storage data exists for UserName

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
api_instance = fio_sdk.PermissionStorageApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve storage data for

try:
    # Retrieves list of Planets where storage data exists for UserName
    api_response = api_instance.storage_planets_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling PermissionStorageApi->storage_planets_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve storage data for | 

### Return type

**list[str]**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **storage_user_name_get**
> storage_user_name_get(user_name)

Retrieves storage data

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
api_instance = fio_sdk.PermissionStorageApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve storage data for

try:
    # Retrieves storage data
    api_instance.storage_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling PermissionStorageApi->storage_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve storage data for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **storage_user_name_storage_description_get**
> storage_user_name_storage_description_get(user_name, storage_description)

Retrieves list of Planets where storage data exists for UserName

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
api_instance = fio_sdk.PermissionStorageApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve storage data for
storage_description = 'storage_description_example' # str | Can be any of the following: 1) StorageId 2) PlanetId 3) PlanetNaturalId 4) PlanetName 

try:
    # Retrieves list of Planets where storage data exists for UserName
    api_instance.storage_user_name_storage_description_get(user_name, storage_description)
except ApiException as e:
    print("Exception when calling PermissionStorageApi->storage_user_name_storage_description_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve storage data for | 
 **storage_description** | **str**| Can be any of the following: 1) StorageId 2) PlanetId 3) PlanetNaturalId 4) PlanetName  | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **usersettings_burnrate_user_name_get**
> usersettings_burnrate_user_name_get(user_name)

Retrieves BurnRateSettings for the specified user

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
api_instance = fio_sdk.PermissionStorageApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to retrieve BurnRate settings for

try:
    # Retrieves BurnRateSettings for the specified user
    api_instance.usersettings_burnrate_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling PermissionStorageApi->usersettings_burnrate_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The UserName to retrieve BurnRate settings for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **usersettings_burnrate_user_name_planet_natural_id_get**
> usersettings_burnrate_user_name_planet_natural_id_get(user_name, planet_natural_id)

Retrivies BurnRateSettings for the specified user on the specified planet

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
api_instance = fio_sdk.PermissionStorageApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to retrieve BurnRate settings for
planet_natural_id = 'planet_natural_id_example' # str | The PlanetNaturalId

try:
    # Retrivies BurnRateSettings for the specified user on the specified planet
    api_instance.usersettings_burnrate_user_name_planet_natural_id_get(user_name, planet_natural_id)
except ApiException as e:
    print("Exception when calling PermissionStorageApi->usersettings_burnrate_user_name_planet_natural_id_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The UserName to retrieve BurnRate settings for | 
 **planet_natural_id** | **str**| The PlanetNaturalId | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

