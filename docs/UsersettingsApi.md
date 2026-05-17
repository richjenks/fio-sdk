# fio_sdk.UsersettingsApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**usersettings_burnrate_addexclusion_post**](UsersettingsApi.md#usersettings_burnrate_addexclusion_post) | **POST** /usersettings/burnrate/addexclusion | Adds a BurnRateExclusion
[**usersettings_burnrate_deleteexclusion_post**](UsersettingsApi.md#usersettings_burnrate_deleteexclusion_post) | **POST** /usersettings/burnrate/deleteexclusion | Deletes a BurnRateExclusion
[**usersettings_burnrate_redthreshold_post**](UsersettingsApi.md#usersettings_burnrate_redthreshold_post) | **POST** /usersettings/burnrate/redthreshold | Currently unused.  Will be used in the future
[**usersettings_burnrate_user_name_get**](UsersettingsApi.md#usersettings_burnrate_user_name_get) | **GET** /usersettings/burnrate/{UserName} | Retrieves BurnRateSettings for the specified user
[**usersettings_burnrate_user_name_planet_natural_id_get**](UsersettingsApi.md#usersettings_burnrate_user_name_planet_natural_id_get) | **GET** /usersettings/burnrate/{UserName}/{PlanetNaturalId} | Retrivies BurnRateSettings for the specified user on the specified planet
[**usersettings_burnrate_yellowthreshold_post**](UsersettingsApi.md#usersettings_burnrate_yellowthreshold_post) | **POST** /usersettings/burnrate/yellowthreshold | Currently unused.  Will be used in the future
[**usersettings_general_get**](UsersettingsApi.md#usersettings_general_get) | **GET** /usersettings/general | Currently unused.  Will be used in the future
[**usersettings_general_post**](UsersettingsApi.md#usersettings_general_post) | **POST** /usersettings/general | Currently unused.  Will be used in the future
[**usersettings_general_user_name_get**](UsersettingsApi.md#usersettings_general_user_name_get) | **GET** /usersettings/general/{UserName} | Currently unused.  Will be used in the future

# **usersettings_burnrate_addexclusion_post**
> usersettings_burnrate_addexclusion_post(body)

Adds a BurnRateExclusion

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.UsersettingsApi()
body = fio_sdk.UserSettingsBurnRateExclusion() # UserSettingsBurnRateExclusion | A BurnRateExclusion

try:
    # Adds a BurnRateExclusion
    api_instance.usersettings_burnrate_addexclusion_post(body)
except ApiException as e:
    print("Exception when calling UsersettingsApi->usersettings_burnrate_addexclusion_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**UserSettingsBurnRateExclusion**](UserSettingsBurnRateExclusion.md)| A BurnRateExclusion | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **usersettings_burnrate_deleteexclusion_post**
> usersettings_burnrate_deleteexclusion_post(body)

Deletes a BurnRateExclusion

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.UsersettingsApi()
body = fio_sdk.UserSettingsBurnRateExclusion() # UserSettingsBurnRateExclusion | A BurnRateExclusion

try:
    # Deletes a BurnRateExclusion
    api_instance.usersettings_burnrate_deleteexclusion_post(body)
except ApiException as e:
    print("Exception when calling UsersettingsApi->usersettings_burnrate_deleteexclusion_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**UserSettingsBurnRateExclusion**](UserSettingsBurnRateExclusion.md)| A BurnRateExclusion | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **usersettings_burnrate_redthreshold_post**
> usersettings_burnrate_redthreshold_post()

Currently unused.  Will be used in the future

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
api_instance = fio_sdk.UsersettingsApi(fio_sdk.ApiClient(configuration))

try:
    # Currently unused.  Will be used in the future
    api_instance.usersettings_burnrate_redthreshold_post()
except ApiException as e:
    print("Exception when calling UsersettingsApi->usersettings_burnrate_redthreshold_post: %s\n" % e)
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
api_instance = fio_sdk.UsersettingsApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to retrieve BurnRate settings for

try:
    # Retrieves BurnRateSettings for the specified user
    api_instance.usersettings_burnrate_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling UsersettingsApi->usersettings_burnrate_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.UsersettingsApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to retrieve BurnRate settings for
planet_natural_id = 'planet_natural_id_example' # str | The PlanetNaturalId

try:
    # Retrivies BurnRateSettings for the specified user on the specified planet
    api_instance.usersettings_burnrate_user_name_planet_natural_id_get(user_name, planet_natural_id)
except ApiException as e:
    print("Exception when calling UsersettingsApi->usersettings_burnrate_user_name_planet_natural_id_get: %s\n" % e)
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

# **usersettings_burnrate_yellowthreshold_post**
> usersettings_burnrate_yellowthreshold_post()

Currently unused.  Will be used in the future

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
api_instance = fio_sdk.UsersettingsApi(fio_sdk.ApiClient(configuration))

try:
    # Currently unused.  Will be used in the future
    api_instance.usersettings_burnrate_yellowthreshold_post()
except ApiException as e:
    print("Exception when calling UsersettingsApi->usersettings_burnrate_yellowthreshold_post: %s\n" % e)
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

# **usersettings_general_get**
> usersettings_general_get()

Currently unused.  Will be used in the future

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
api_instance = fio_sdk.UsersettingsApi(fio_sdk.ApiClient(configuration))

try:
    # Currently unused.  Will be used in the future
    api_instance.usersettings_general_get()
except ApiException as e:
    print("Exception when calling UsersettingsApi->usersettings_general_get: %s\n" % e)
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

# **usersettings_general_post**
> usersettings_general_post()

Currently unused.  Will be used in the future

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
api_instance = fio_sdk.UsersettingsApi(fio_sdk.ApiClient(configuration))

try:
    # Currently unused.  Will be used in the future
    api_instance.usersettings_general_post()
except ApiException as e:
    print("Exception when calling UsersettingsApi->usersettings_general_post: %s\n" % e)
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

# **usersettings_general_user_name_get**
> usersettings_general_user_name_get(user_name)

Currently unused.  Will be used in the future

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
api_instance = fio_sdk.UsersettingsApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | 

try:
    # Currently unused.  Will be used in the future
    api_instance.usersettings_general_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling UsersettingsApi->usersettings_general_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**|  | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

