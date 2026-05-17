# fio_sdk.AdminApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**admin_allusers_get**](AdminApi.md#admin_allusers_get) | **GET** /admin/allusers | Retrieves a list of all usernames provided data from chat messages
[**admin_clearcxdata_post**](AdminApi.md#admin_clearcxdata_post) | **POST** /admin/clearcxdata | Clears all CX Data
[**admin_clearjumpcache_post**](AdminApi.md#admin_clearjumpcache_post) | **POST** /admin/clearjumpcache | Clears all JumpCache Data
[**admin_clearmatdata_post**](AdminApi.md#admin_clearmatdata_post) | **POST** /admin/clearmatdata | Clears all MAT Data
[**admin_create_post**](AdminApi.md#admin_create_post) | **POST** /admin/create | Creates an account
[**admin_disable_post**](AdminApi.md#admin_disable_post) | **POST** /admin/disable | Disables an account
[**admin_forceupdatesystemid_post**](AdminApi.md#admin_forceupdatesystemid_post) | **POST** /admin/forceupdatesystemid | Force update system ids (manual upgrade path)
[**admin_get**](AdminApi.md#admin_get) | **GET** /admin | Check if the user is an administrator
[**admin_requestdata_get**](AdminApi.md#admin_requestdata_get) | **GET** /admin/requestdata | Retrieves request data statistics for this run instance
[**admin_resetuserdata_user_name_post**](AdminApi.md#admin_resetuserdata_user_name_post) | **POST** /admin/resetuserdata/{UserName} | Resets the provided username&#x27;s userdata\&quot;
[**admin_user_name_get**](AdminApi.md#admin_user_name_get) | **GET** /admin/{UserName} | Checks if the UserName provided exists
[**admin_usercount_get**](AdminApi.md#admin_usercount_get) | **GET** /admin/usercount | Retrieves a count of all usernames provided data from chat messages

# **admin_allusers_get**
> list[str] admin_allusers_get()

Retrieves a list of all usernames provided data from chat messages

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
api_instance = fio_sdk.AdminApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves a list of all usernames provided data from chat messages
    api_response = api_instance.admin_allusers_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling AdminApi->admin_allusers_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

**list[str]**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **admin_clearcxdata_post**
> admin_clearcxdata_post()

Clears all CX Data

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
api_instance = fio_sdk.AdminApi(fio_sdk.ApiClient(configuration))

try:
    # Clears all CX Data
    api_instance.admin_clearcxdata_post()
except ApiException as e:
    print("Exception when calling AdminApi->admin_clearcxdata_post: %s\n" % e)
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

# **admin_clearjumpcache_post**
> admin_clearjumpcache_post()

Clears all JumpCache Data

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
api_instance = fio_sdk.AdminApi(fio_sdk.ApiClient(configuration))

try:
    # Clears all JumpCache Data
    api_instance.admin_clearjumpcache_post()
except ApiException as e:
    print("Exception when calling AdminApi->admin_clearjumpcache_post: %s\n" % e)
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

# **admin_clearmatdata_post**
> admin_clearmatdata_post()

Clears all MAT Data

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
api_instance = fio_sdk.AdminApi(fio_sdk.ApiClient(configuration))

try:
    # Clears all MAT Data
    api_instance.admin_clearmatdata_post()
except ApiException as e:
    print("Exception when calling AdminApi->admin_clearmatdata_post: %s\n" % e)
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

# **admin_create_post**
> admin_create_post(body)

Creates an account

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
api_instance = fio_sdk.AdminApi(fio_sdk.ApiClient(configuration))
body = fio_sdk.AdminCreate() # AdminCreate | New account information

try:
    # Creates an account
    api_instance.admin_create_post(body)
except ApiException as e:
    print("Exception when calling AdminApi->admin_create_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**AdminCreate**](AdminCreate.md)| New account information | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **admin_disable_post**
> admin_disable_post(body)

Disables an account

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
api_instance = fio_sdk.AdminApi(fio_sdk.ApiClient(configuration))
body = fio_sdk.AdminDisable() # AdminDisable | Payload to disable an account with reason

try:
    # Disables an account
    api_instance.admin_disable_post(body)
except ApiException as e:
    print("Exception when calling AdminApi->admin_disable_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**AdminDisable**](AdminDisable.md)| Payload to disable an account with reason | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **admin_forceupdatesystemid_post**
> admin_forceupdatesystemid_post()

Force update system ids (manual upgrade path)

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
api_instance = fio_sdk.AdminApi(fio_sdk.ApiClient(configuration))

try:
    # Force update system ids (manual upgrade path)
    api_instance.admin_forceupdatesystemid_post()
except ApiException as e:
    print("Exception when calling AdminApi->admin_forceupdatesystemid_post: %s\n" % e)
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

# **admin_get**
> admin_get()

Check if the user is an administrator

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
api_instance = fio_sdk.AdminApi(fio_sdk.ApiClient(configuration))

try:
    # Check if the user is an administrator
    api_instance.admin_get()
except ApiException as e:
    print("Exception when calling AdminApi->admin_get: %s\n" % e)
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

# **admin_requestdata_get**
> admin_requestdata_get()

Retrieves request data statistics for this run instance

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
api_instance = fio_sdk.AdminApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves request data statistics for this run instance
    api_instance.admin_requestdata_get()
except ApiException as e:
    print("Exception when calling AdminApi->admin_requestdata_get: %s\n" % e)
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

# **admin_resetuserdata_user_name_post**
> admin_resetuserdata_user_name_post(user_name)

Resets the provided username's userdata\"

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
api_instance = fio_sdk.AdminApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to reset

try:
    # Resets the provided username's userdata\"
    api_instance.admin_resetuserdata_user_name_post(user_name)
except ApiException as e:
    print("Exception when calling AdminApi->admin_resetuserdata_user_name_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The UserName to reset | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **admin_user_name_get**
> admin_user_name_get(user_name)

Checks if the UserName provided exists

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
api_instance = fio_sdk.AdminApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to check

try:
    # Checks if the UserName provided exists
    api_instance.admin_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling AdminApi->admin_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to check | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **admin_usercount_get**
> int admin_usercount_get()

Retrieves a count of all usernames provided data from chat messages

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
api_instance = fio_sdk.AdminApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves a count of all usernames provided data from chat messages
    api_response = api_instance.admin_usercount_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling AdminApi->admin_usercount_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

**int**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

