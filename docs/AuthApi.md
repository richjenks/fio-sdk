# fio_sdk.AuthApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**auth_addpermission_post**](AuthApi.md#auth_addpermission_post) | **POST** /auth/addpermission | Add a permission allowance
[**auth_changepassword_post**](AuthApi.md#auth_changepassword_post) | **POST** /auth/changepassword | Changes the user&#x27;s password
[**auth_createapikey_post**](AuthApi.md#auth_createapikey_post) | **POST** /auth/createapikey | Creates an API key
[**auth_creategroup_post**](AuthApi.md#auth_creategroup_post) | **POST** /auth/creategroup | Creates a group or modifies an existing group if GroupId is specified
[**auth_deletegroup_group_id_post**](AuthApi.md#auth_deletegroup_group_id_post) | **POST** /auth/deletegroup/{GroupId} | Deletes a group you own by id
[**auth_deletepermission_user_name_post**](AuthApi.md#auth_deletepermission_user_name_post) | **POST** /auth/deletepermission/{UserName} | Delete a permission allowance
[**auth_get**](AuthApi.md#auth_get) | **GET** /auth | Determines if the user is authenticated
[**auth_group_group_id_get**](AuthApi.md#auth_group_group_id_get) | **GET** /auth/group/{GroupId} | Retrieves group by GroupId
[**auth_groups_get**](AuthApi.md#auth_groups_get) | **GET** /auth/groups | Retrieves all groups owned by the current user
[**auth_listapikeys_post**](AuthApi.md#auth_listapikeys_post) | **POST** /auth/listapikeys | Lists all API keys
[**auth_login_post**](AuthApi.md#auth_login_post) | **POST** /auth/login | Login to FIO
[**auth_permissions_get**](AuthApi.md#auth_permissions_get) | **GET** /auth/permissions | Retrieves all permission allowances
[**auth_refreshauthtoken_post**](AuthApi.md#auth_refreshauthtoken_post) | **POST** /auth/refreshauthtoken | Refreshes the user&#x27;s auth token
[**auth_revokeapikey_post**](AuthApi.md#auth_revokeapikey_post) | **POST** /auth/revokeapikey | Revokes an API key
[**auth_visibility_get**](AuthApi.md#auth_visibility_get) | **GET** /auth/visibility | Retrieves all allowances given to the user
[**auth_visibility_permission_type_get**](AuthApi.md#auth_visibility_permission_type_get) | **GET** /auth/visibility/{PermissionType} | Retrieves all users where we have the permissionType specified given to us

# **auth_addpermission_post**
> auth_addpermission_post(body)

Add a permission allowance

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
api_instance = fio_sdk.AuthApi(fio_sdk.ApiClient(configuration))
body = fio_sdk.AuthPermissionAllowance() # AuthPermissionAllowance | A payload of a user and the permissions you grant them

try:
    # Add a permission allowance
    api_instance.auth_addpermission_post(body)
except ApiException as e:
    print("Exception when calling AuthApi->auth_addpermission_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**AuthPermissionAllowance**](AuthPermissionAllowance.md)| A payload of a user and the permissions you grant them | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **auth_changepassword_post**
> auth_changepassword_post(body)

Changes the user's password

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
api_instance = fio_sdk.AuthApi(fio_sdk.ApiClient(configuration))
body = fio_sdk.AuthChangePassword() # AuthChangePassword | Old and new password

try:
    # Changes the user's password
    api_instance.auth_changepassword_post(body)
except ApiException as e:
    print("Exception when calling AuthApi->auth_changepassword_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**AuthChangePassword**](AuthChangePassword.md)| Old and new password | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **auth_createapikey_post**
> auth_createapikey_post(body)

Creates an API key

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
api_instance = fio_sdk.AuthApi(fio_sdk.ApiClient(configuration))
body = fio_sdk.AuthCreateApiKey() # AuthCreateApiKey | The payload required for creating an API key.

try:
    # Creates an API key
    api_instance.auth_createapikey_post(body)
except ApiException as e:
    print("Exception when calling AuthApi->auth_createapikey_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**AuthCreateApiKey**](AuthCreateApiKey.md)| The payload required for creating an API key. | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **auth_creategroup_post**
> AuthCreateGroupResponse auth_creategroup_post(body)

Creates a group or modifies an existing group if GroupId is specified

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
api_instance = fio_sdk.AuthApi(fio_sdk.ApiClient(configuration))
body = fio_sdk.AuthCreateGroupPayload() # AuthCreateGroupPayload | A group description

try:
    # Creates a group or modifies an existing group if GroupId is specified
    api_response = api_instance.auth_creategroup_post(body)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling AuthApi->auth_creategroup_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**AuthCreateGroupPayload**](AuthCreateGroupPayload.md)| A group description | 

### Return type

[**AuthCreateGroupResponse**](AuthCreateGroupResponse.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **auth_deletegroup_group_id_post**
> auth_deletegroup_group_id_post(group_id)

Deletes a group you own by id

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
api_instance = fio_sdk.AuthApi(fio_sdk.ApiClient(configuration))
group_id = 56 # int | The Group's Id

try:
    # Deletes a group you own by id
    api_instance.auth_deletegroup_group_id_post(group_id)
except ApiException as e:
    print("Exception when calling AuthApi->auth_deletegroup_group_id_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **group_id** | **int**| The Group&#x27;s Id | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **auth_deletepermission_user_name_post**
> auth_deletepermission_user_name_post(user_name)

Delete a permission allowance

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
api_instance = fio_sdk.AuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName for which to delete the permission allowance

try:
    # Delete a permission allowance
    api_instance.auth_deletepermission_user_name_post(user_name)
except ApiException as e:
    print("Exception when calling AuthApi->auth_deletepermission_user_name_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The UserName for which to delete the permission allowance | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **auth_get**
> auth_get()

Determines if the user is authenticated

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
api_instance = fio_sdk.AuthApi(fio_sdk.ApiClient(configuration))

try:
    # Determines if the user is authenticated
    api_instance.auth_get()
except ApiException as e:
    print("Exception when calling AuthApi->auth_get: %s\n" % e)
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

# **auth_group_group_id_get**
> auth_group_group_id_get(group_id)

Retrieves group by GroupId

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.AuthApi()
group_id = 56 # int | The group's Id

try:
    # Retrieves group by GroupId
    api_instance.auth_group_group_id_get(group_id)
except ApiException as e:
    print("Exception when calling AuthApi->auth_group_group_id_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **group_id** | **int**| The group&#x27;s Id | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **auth_groups_get**
> auth_groups_get()

Retrieves all groups owned by the current user

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
api_instance = fio_sdk.AuthApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves all groups owned by the current user
    api_instance.auth_groups_get()
except ApiException as e:
    print("Exception when calling AuthApi->auth_groups_get: %s\n" % e)
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

# **auth_listapikeys_post**
> auth_listapikeys_post(body)

Lists all API keys

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
api_instance = fio_sdk.AuthApi(fio_sdk.ApiClient(configuration))
body = fio_sdk.AuthLoginAndPassword() # AuthLoginAndPassword | The payload required for retrieving all API keys.

try:
    # Lists all API keys
    api_instance.auth_listapikeys_post(body)
except ApiException as e:
    print("Exception when calling AuthApi->auth_listapikeys_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**AuthLoginAndPassword**](AuthLoginAndPassword.md)| The payload required for retrieving all API keys. | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **auth_login_post**
> AuthLoginResponse auth_login_post(body)

Login to FIO

Authenticates against FIO. Any requests that require auth must have the response AuthToken as a HTTP header: `Authorization`:`<AUTH_TOKEN_HASH>` 

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.AuthApi()
body = fio_sdk.AuthLoginAndPassword() # AuthLoginAndPassword | Login and password for user

try:
    # Login to FIO
    api_response = api_instance.auth_login_post(body)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling AuthApi->auth_login_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**AuthLoginAndPassword**](AuthLoginAndPassword.md)| Login and password for user | 

### Return type

[**AuthLoginResponse**](AuthLoginResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **auth_permissions_get**
> list[AuthPermissionAllowance] auth_permissions_get()

Retrieves all permission allowances

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
api_instance = fio_sdk.AuthApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves all permission allowances
    api_response = api_instance.auth_permissions_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling AuthApi->auth_permissions_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[AuthPermissionAllowance]**](AuthPermissionAllowance.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **auth_refreshauthtoken_post**
> auth_refreshauthtoken_post()

Refreshes the user's auth token

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
api_instance = fio_sdk.AuthApi(fio_sdk.ApiClient(configuration))

try:
    # Refreshes the user's auth token
    api_instance.auth_refreshauthtoken_post()
except ApiException as e:
    print("Exception when calling AuthApi->auth_refreshauthtoken_post: %s\n" % e)
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

# **auth_revokeapikey_post**
> auth_revokeapikey_post(body)

Revokes an API key

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
api_instance = fio_sdk.AuthApi(fio_sdk.ApiClient(configuration))
body = fio_sdk.AuthRevokeApiKey() # AuthRevokeApiKey | The payload required for revoking an API key.

try:
    # Revokes an API key
    api_instance.auth_revokeapikey_post(body)
except ApiException as e:
    print("Exception when calling AuthApi->auth_revokeapikey_post: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**AuthRevokeApiKey**](AuthRevokeApiKey.md)| The payload required for revoking an API key. | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: */*
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **auth_visibility_get**
> list[AuthPermissionAllowance] auth_visibility_get()

Retrieves all allowances given to the user

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
api_instance = fio_sdk.AuthApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves all allowances given to the user
    api_response = api_instance.auth_visibility_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling AuthApi->auth_visibility_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[AuthPermissionAllowance]**](AuthPermissionAllowance.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **auth_visibility_permission_type_get**
> list[str] auth_visibility_permission_type_get(permission_type)

Retrieves all users where we have the permissionType specified given to us

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
api_instance = fio_sdk.AuthApi(fio_sdk.ApiClient(configuration))
permission_type = 'permission_type_example' # str | The PermissionType

try:
    # Retrieves all users where we have the permissionType specified given to us
    api_response = api_instance.auth_visibility_permission_type_get(permission_type)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling AuthApi->auth_visibility_permission_type_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **permission_type** | **str**| The PermissionType | 

### Return type

**list[str]**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

