# fio_sdk.RequiresAuthApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**auth_addpermission_post**](RequiresAuthApi.md#auth_addpermission_post) | **POST** /auth/addpermission | Add a permission allowance
[**auth_changepassword_post**](RequiresAuthApi.md#auth_changepassword_post) | **POST** /auth/changepassword | Changes the user&#x27;s password
[**auth_createapikey_post**](RequiresAuthApi.md#auth_createapikey_post) | **POST** /auth/createapikey | Creates an API key
[**auth_creategroup_post**](RequiresAuthApi.md#auth_creategroup_post) | **POST** /auth/creategroup | Creates a group or modifies an existing group if GroupId is specified
[**auth_deletegroup_group_id_post**](RequiresAuthApi.md#auth_deletegroup_group_id_post) | **POST** /auth/deletegroup/{GroupId} | Deletes a group you own by id
[**auth_deletepermission_user_name_post**](RequiresAuthApi.md#auth_deletepermission_user_name_post) | **POST** /auth/deletepermission/{UserName} | Delete a permission allowance
[**auth_get**](RequiresAuthApi.md#auth_get) | **GET** /auth | Determines if the user is authenticated
[**auth_groups_get**](RequiresAuthApi.md#auth_groups_get) | **GET** /auth/groups | Retrieves all groups owned by the current user
[**auth_listapikeys_post**](RequiresAuthApi.md#auth_listapikeys_post) | **POST** /auth/listapikeys | Lists all API keys
[**auth_permissions_get**](RequiresAuthApi.md#auth_permissions_get) | **GET** /auth/permissions | Retrieves all permission allowances
[**auth_refreshauthtoken_post**](RequiresAuthApi.md#auth_refreshauthtoken_post) | **POST** /auth/refreshauthtoken | Refreshes the user&#x27;s auth token
[**auth_revokeapikey_post**](RequiresAuthApi.md#auth_revokeapikey_post) | **POST** /auth/revokeapikey | Revokes an API key
[**auth_visibility_get**](RequiresAuthApi.md#auth_visibility_get) | **GET** /auth/visibility | Retrieves all allowances given to the user
[**auth_visibility_permission_type_get**](RequiresAuthApi.md#auth_visibility_permission_type_get) | **GET** /auth/visibility/{PermissionType} | Retrieves all users where we have the permissionType specified given to us
[**building_post**](RequiresAuthApi.md#building_post) | **POST** /building | Posts building game data (WorldReactorData) to the server.  For payload, see FIORest source
[**chat_data_post**](RequiresAuthApi.md#chat_data_post) | **POST** /chat/data | Posts the CHANNEL_DATA payload to the server.  For payload, see FIORest source
[**chat_message_added_post**](RequiresAuthApi.md#chat_message_added_post) | **POST** /chat/message_added | Posts the CHANNEL_MESSAGE_ADDED payload to the server.  For payload, see FIORest source
[**chat_message_deleted_post**](RequiresAuthApi.md#chat_message_deleted_post) | **POST** /chat/message_deleted | Posts the CHANNEL_MESSAGE_DELETED payload to the server.  For payload, see FIORest source
[**chat_message_list_post**](RequiresAuthApi.md#chat_message_list_post) | **POST** /chat/message_list | Posts the CHANNEL_MESSAGE_LIST payload to the server.  For payload, see FIORest source
[**company_code_company_code_get**](RequiresAuthApi.md#company_code_company_code_get) | **GET** /company/code/{CompanyCode} | Retrieves company data by CompanyCode
[**company_data_post**](RequiresAuthApi.md#company_data_post) | **POST** /company/data | Posts COMPANY_DATA_DATA payload.  For payload, see FIORest source
[**company_name_company_name_get**](RequiresAuthApi.md#company_name_company_name_get) | **GET** /company/name/{CompanyName} | Retrieves company data by CompanyName
[**company_post**](RequiresAuthApi.md#company_post) | **POST** /company | Posts COMPANY_DATA payload.  For payload, see FIORest source
[**contract_allcontracts_get**](RequiresAuthApi.md#contract_allcontracts_get) | **GET** /contract/allcontracts | Retrieves most recent 100 contracts for the current user
[**contract_allcontracts_user_name_get**](RequiresAuthApi.md#contract_allcontracts_user_name_get) | **GET** /contract/allcontracts/{UserName} | Retrieves most recent 100 contracts for the given UserName
[**contract_change_post**](RequiresAuthApi.md#contract_change_post) | **POST** /contract/change | Posts CONTRACTS_CONTRACT payload. See FIORest source for payload definition
[**contract_concerns_get**](RequiresAuthApi.md#contract_concerns_get) | **GET** /contract/concerns | Retrieves contracts which can be extended or are within 1 day of ending
[**contract_concerns_user_name_get**](RequiresAuthApi.md#contract_concerns_user_name_get) | **GET** /contract/concerns/{UserName} | Retrieves concerning contracts for the given UserName
[**contract_loans_get**](RequiresAuthApi.md#contract_loans_get) | **GET** /contract/loans | Retrieves loan contracts for the current user
[**contract_loans_user_name_get**](RequiresAuthApi.md#contract_loans_user_name_get) | **GET** /contract/loans/{UserName} | Retrieves loan contracts for the given UserName
[**contract_post**](RequiresAuthApi.md#contract_post) | **POST** /contract | Posts CONTRACTS_CONTRACTS payload. See FIORest source for payload definition
[**contract_shipments_get**](RequiresAuthApi.md#contract_shipments_get) | **GET** /contract/shipments | Retrieves information on the location of your shipments
[**contract_taco_get**](RequiresAuthApi.md#contract_taco_get) | **GET** /contract/taco | Retrieves taco statistics for EatTacos88
[**cxos_added_post**](RequiresAuthApi.md#cxos_added_post) | **POST** /cxos/added | Posts COMEX_TRADER_ORDER_ADDED data payload
[**cxos_post**](RequiresAuthApi.md#cxos_post) | **POST** /cxos | Posts COMEX_TRADER_ORDERS data payload
[**cxos_removed_post**](RequiresAuthApi.md#cxos_removed_post) | **POST** /cxos/removed | Posts COMEX_TRADER_ORDER_REMOVED data payload
[**cxos_updated_post**](RequiresAuthApi.md#cxos_updated_post) | **POST** /cxos/updated | Posts COMEX_TRADER_ORDER_UPDATED data payload
[**cxos_user_name_get**](RequiresAuthApi.md#cxos_user_name_get) | **GET** /cxos/{UserName} | Retrieves CXOS data for provided username.  See FIORest source for payload definition
[**exchange_post**](RequiresAuthApi.md#exchange_post) | **POST** /exchange | Posts COMEX_BROKER_DATA data payload
[**infrastructure_post**](RequiresAuthApi.md#infrastructure_post) | **POST** /infrastructure | Posts INFRASTRUCTURE_DATA_DATA data payload
[**infrastructure_project_post**](RequiresAuthApi.md#infrastructure_project_post) | **POST** /infrastructure/project | Posts INFRASTRUCTURE_PROJECTS_DATA data payload
[**localmarket_post**](RequiresAuthApi.md#localmarket_post) | **POST** /localmarket | Posts LOCAL_MARKET_DATA_DATA data payload
[**material_allmaterials_get**](RequiresAuthApi.md#material_allmaterials_get) | **GET** /material/allmaterials | Retrieves all materials.  See FIORest source for payload definition
[**material_post**](RequiresAuthApi.md#material_post) | **POST** /material | Posts WORLD_MATERIAL_CATEGORIES payload
[**planet_cogc_post**](RequiresAuthApi.md#planet_cogc_post) | **POST** /planet/cogc | Posts PLANET_COGC_DATA payload
[**planet_post**](RequiresAuthApi.md#planet_post) | **POST** /planet | Posts PLANET_DATA_DATA payload
[**planet_sites_post**](RequiresAuthApi.md#planet_sites_post) | **POST** /planet/sites | Posts PLANET_SITES payload
[**production_planets_user_name_get**](RequiresAuthApi.md#production_planets_user_name_get) | **GET** /production/planets/{UserName} | Retrieve all the planets where production lines are present for the provided UserName
[**production_post**](RequiresAuthApi.md#production_post) | **POST** /production | Posts PRODUCTION_SITE_PRODUCTION_LINES payload
[**production_user_name_get**](RequiresAuthApi.md#production_user_name_get) | **GET** /production/{UserName} | Retrieve all production lines for provided UserName
[**production_user_name_planet_get**](RequiresAuthApi.md#production_user_name_planet_get) | **GET** /production/{UserName}/{Planet} | Retrieve production line for the given UserName on the specified Planet
[**rain_userliquid_user_name_get**](RequiresAuthApi.md#rain_userliquid_user_name_get) | **GET** /rain/userliquid/{UserName} | Retrieves liquid asset data for the given UserName
[**rain_userplanetbuildingreclaimables_user_name_get**](RequiresAuthApi.md#rain_userplanetbuildingreclaimables_user_name_get) | **GET** /rain/userplanetbuildingreclaimables/{UserName} | Retrieves planet building reclaimables for the given UserName
[**rain_userplanetbuildings_user_name_get**](RequiresAuthApi.md#rain_userplanetbuildings_user_name_get) | **GET** /rain/userplanetbuildings/{UserName} | Retrieves planet buildings for the given UserName
[**rain_userplanetproduction_user_name_get**](RequiresAuthApi.md#rain_userplanetproduction_user_name_get) | **GET** /rain/userplanetproduction/{UserName} | Retrieves planet production for the given UserName
[**rain_userplanetproductioninput_user_name_get**](RequiresAuthApi.md#rain_userplanetproductioninput_user_name_get) | **GET** /rain/userplanetproductioninput/{UserName} | Retrieves planet production inputs for the given UserName
[**rain_userplanetproductionoutput_user_name_get**](RequiresAuthApi.md#rain_userplanetproductionoutput_user_name_get) | **GET** /rain/userplanetproductionoutput/{UserName} | Retrieves planet production outputs for the given UserName
[**rain_userplanets_user_name_get**](RequiresAuthApi.md#rain_userplanets_user_name_get) | **GET** /rain/userplanets/{UserName} | Retrieves planets for the given UserName
[**rain_userplanetworkforce_user_name_get**](RequiresAuthApi.md#rain_userplanetworkforce_user_name_get) | **GET** /rain/userplanetworkforce/{UserName} | Retrieves planet production workforces for the given UserName
[**rain_userstorage_user_name_get**](RequiresAuthApi.md#rain_userstorage_user_name_get) | **GET** /rain/userstorage/{UserName} | Retrieves planet production workforces for the given UserName
[**ship_flights_post**](RequiresAuthApi.md#ship_flights_post) | **POST** /ship/flights | Posts SHIP_FLIGHT_FLIGHTS payload
[**ship_flights_user_name_get**](RequiresAuthApi.md#ship_flights_user_name_get) | **GET** /ship/flights/{UserName} | Retrieves ship flight data
[**ship_ships_fuel_user_name_get**](RequiresAuthApi.md#ship_ships_fuel_user_name_get) | **GET** /ship/ships/fuel/{UserName} | Retrieves ship fuel store data
[**ship_ships_post**](RequiresAuthApi.md#ship_ships_post) | **POST** /ship/ships | Posts SHIP_SHIPS payload
[**ship_ships_user_name_get**](RequiresAuthApi.md#ship_ships_user_name_get) | **GET** /ship/ships/{UserName} | Retrieves ship data
[**sites_planets_user_name_get**](RequiresAuthApi.md#sites_planets_user_name_get) | **GET** /sites/planets/{UserName} | Retrieves list of planets user has site data for
[**sites_post**](RequiresAuthApi.md#sites_post) | **POST** /sites | Posts SITE_SITES payload
[**sites_user_name_get**](RequiresAuthApi.md#sites_user_name_get) | **GET** /sites/{UserName} | Retrieves site data
[**sites_user_name_planet_get**](RequiresAuthApi.md#sites_user_name_planet_get) | **GET** /sites/{UserName}/{Planet} | Retrieves list of planets user has site data for
[**sites_warehouses_post**](RequiresAuthApi.md#sites_warehouses_post) | **POST** /sites/warehouses | Posts STORAGE_WAREHOUSES payload
[**sites_warehouses_user_name_get**](RequiresAuthApi.md#sites_warehouses_user_name_get) | **GET** /sites/warehouses/{UserName} | Retrieves all warehouse sites the user has
[**storage_change_post**](RequiresAuthApi.md#storage_change_post) | **POST** /storage/change | Posts STORAGE_CHANGE payload
[**storage_planets_user_name_get**](RequiresAuthApi.md#storage_planets_user_name_get) | **GET** /storage/planets/{UserName} | Retrieves list of Planets where storage data exists for UserName
[**storage_post**](RequiresAuthApi.md#storage_post) | **POST** /storage | Posts STORAGE_STORAGES payload
[**storage_user_name_get**](RequiresAuthApi.md#storage_user_name_get) | **GET** /storage/{UserName} | Retrieves storage data
[**storage_user_name_storage_description_get**](RequiresAuthApi.md#storage_user_name_storage_description_get) | **GET** /storage/{UserName}/{StorageDescription} | Retrieves list of Planets where storage data exists for UserName
[**systemstars_star_post**](RequiresAuthApi.md#systemstars_star_post) | **POST** /systemstars/star | Posts SYSTEM_STAR data
[**user_allusers_get**](RequiresAuthApi.md#user_allusers_get) | **GET** /user/allusers | Retrieves all FIO users
[**user_post**](RequiresAuthApi.md#user_post) | **POST** /user | Posts USER_DATA payload
[**user_resetalldata_post**](RequiresAuthApi.md#user_resetalldata_post) | **POST** /user/resetalldata | Resets the current user&#x27;s data.
[**user_user_name_get**](RequiresAuthApi.md#user_user_name_get) | **GET** /user/{UserName} | Retrieves userdata for specified UserName
[**usersettings_burnrate_addexclusion_post**](RequiresAuthApi.md#usersettings_burnrate_addexclusion_post) | **POST** /usersettings/burnrate/addexclusion | Adds a BurnRateExclusion
[**usersettings_burnrate_deleteexclusion_post**](RequiresAuthApi.md#usersettings_burnrate_deleteexclusion_post) | **POST** /usersettings/burnrate/deleteexclusion | Deletes a BurnRateExclusion
[**usersettings_burnrate_redthreshold_post**](RequiresAuthApi.md#usersettings_burnrate_redthreshold_post) | **POST** /usersettings/burnrate/redthreshold | Currently unused.  Will be used in the future
[**usersettings_burnrate_user_name_get**](RequiresAuthApi.md#usersettings_burnrate_user_name_get) | **GET** /usersettings/burnrate/{UserName} | Retrieves BurnRateSettings for the specified user
[**usersettings_burnrate_user_name_planet_natural_id_get**](RequiresAuthApi.md#usersettings_burnrate_user_name_planet_natural_id_get) | **GET** /usersettings/burnrate/{UserName}/{PlanetNaturalId} | Retrivies BurnRateSettings for the specified user on the specified planet
[**usersettings_burnrate_yellowthreshold_post**](RequiresAuthApi.md#usersettings_burnrate_yellowthreshold_post) | **POST** /usersettings/burnrate/yellowthreshold | Currently unused.  Will be used in the future
[**usersettings_general_get**](RequiresAuthApi.md#usersettings_general_get) | **GET** /usersettings/general | Currently unused.  Will be used in the future
[**usersettings_general_post**](RequiresAuthApi.md#usersettings_general_post) | **POST** /usersettings/general | Currently unused.  Will be used in the future
[**usersettings_general_user_name_get**](RequiresAuthApi.md#usersettings_general_user_name_get) | **GET** /usersettings/general/{UserName} | Currently unused.  Will be used in the future
[**workforce_planets_user_name_get**](RequiresAuthApi.md#workforce_planets_user_name_get) | **GET** /workforce/planets/{UserName} | Retrieves list of planets where the specified user has Workforce data
[**workforce_post**](RequiresAuthApi.md#workforce_post) | **POST** /workforce | Posts WORKFORCE_WORKFORCES payload
[**workforce_user_name_get**](RequiresAuthApi.md#workforce_user_name_get) | **GET** /workforce/{UserName} | Retrieves workforce data for the specified user
[**workforce_user_name_planet_get**](RequiresAuthApi.md#workforce_user_name_planet_get) | **GET** /workforce/{UserName}/{Planet} | Retrieves workforce data for the specified usernaem and planet

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
body = fio_sdk.AuthPermissionAllowance() # AuthPermissionAllowance | A payload of a user and the permissions you grant them

try:
    # Add a permission allowance
    api_instance.auth_addpermission_post(body)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->auth_addpermission_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
body = fio_sdk.AuthChangePassword() # AuthChangePassword | Old and new password

try:
    # Changes the user's password
    api_instance.auth_changepassword_post(body)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->auth_changepassword_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
body = fio_sdk.AuthCreateApiKey() # AuthCreateApiKey | The payload required for creating an API key.

try:
    # Creates an API key
    api_instance.auth_createapikey_post(body)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->auth_createapikey_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
body = fio_sdk.AuthCreateGroupPayload() # AuthCreateGroupPayload | A group description

try:
    # Creates a group or modifies an existing group if GroupId is specified
    api_response = api_instance.auth_creategroup_post(body)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->auth_creategroup_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
group_id = 56 # int | The Group's Id

try:
    # Deletes a group you own by id
    api_instance.auth_deletegroup_group_id_post(group_id)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->auth_deletegroup_group_id_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName for which to delete the permission allowance

try:
    # Delete a permission allowance
    api_instance.auth_deletepermission_user_name_post(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->auth_deletepermission_user_name_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Determines if the user is authenticated
    api_instance.auth_get()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->auth_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves all groups owned by the current user
    api_instance.auth_groups_get()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->auth_groups_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
body = fio_sdk.AuthLoginAndPassword() # AuthLoginAndPassword | The payload required for retrieving all API keys.

try:
    # Lists all API keys
    api_instance.auth_listapikeys_post(body)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->auth_listapikeys_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves all permission allowances
    api_response = api_instance.auth_permissions_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->auth_permissions_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Refreshes the user's auth token
    api_instance.auth_refreshauthtoken_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->auth_refreshauthtoken_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
body = fio_sdk.AuthRevokeApiKey() # AuthRevokeApiKey | The payload required for revoking an API key.

try:
    # Revokes an API key
    api_instance.auth_revokeapikey_post(body)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->auth_revokeapikey_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves all allowances given to the user
    api_response = api_instance.auth_visibility_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->auth_visibility_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
permission_type = 'permission_type_example' # str | The PermissionType

try:
    # Retrieves all users where we have the permissionType specified given to us
    api_response = api_instance.auth_visibility_permission_type_get(permission_type)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->auth_visibility_permission_type_get: %s\n" % e)
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

# **building_post**
> building_post()

Posts building game data (WorldReactorData) to the server.  For payload, see FIORest source

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts building game data (WorldReactorData) to the server.  For payload, see FIORest source
    api_instance.building_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->building_post: %s\n" % e)
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

# **chat_data_post**
> chat_data_post()

Posts the CHANNEL_DATA payload to the server.  For payload, see FIORest source

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts the CHANNEL_DATA payload to the server.  For payload, see FIORest source
    api_instance.chat_data_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->chat_data_post: %s\n" % e)
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

# **chat_message_added_post**
> chat_message_added_post()

Posts the CHANNEL_MESSAGE_ADDED payload to the server.  For payload, see FIORest source

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts the CHANNEL_MESSAGE_ADDED payload to the server.  For payload, see FIORest source
    api_instance.chat_message_added_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->chat_message_added_post: %s\n" % e)
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

# **chat_message_deleted_post**
> chat_message_deleted_post()

Posts the CHANNEL_MESSAGE_DELETED payload to the server.  For payload, see FIORest source

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts the CHANNEL_MESSAGE_DELETED payload to the server.  For payload, see FIORest source
    api_instance.chat_message_deleted_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->chat_message_deleted_post: %s\n" % e)
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

# **chat_message_list_post**
> chat_message_list_post()

Posts the CHANNEL_MESSAGE_LIST payload to the server.  For payload, see FIORest source

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts the CHANNEL_MESSAGE_LIST payload to the server.  For payload, see FIORest source
    api_instance.chat_message_list_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->chat_message_list_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
company_code = 'company_code_example' # str | The company code to lookup

try:
    # Retrieves company data by CompanyCode
    api_instance.company_code_company_code_get(company_code)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->company_code_company_code_get: %s\n" % e)
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

# **company_data_post**
> company_data_post()

Posts COMPANY_DATA_DATA payload.  For payload, see FIORest source

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COMPANY_DATA_DATA payload.  For payload, see FIORest source
    api_instance.company_data_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->company_data_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
company_name = 'company_name_example' # str | The company name to lookup

try:
    # Retrieves company data by CompanyName
    api_instance.company_name_company_name_get(company_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->company_name_company_name_get: %s\n" % e)
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

# **company_post**
> company_post()

Posts COMPANY_DATA payload.  For payload, see FIORest source

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COMPANY_DATA payload.  For payload, see FIORest source
    api_instance.company_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->company_post: %s\n" % e)
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

# **contract_allcontracts_get**
> contract_allcontracts_get()

Retrieves most recent 100 contracts for the current user

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves most recent 100 contracts for the current user
    api_instance.contract_allcontracts_get()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->contract_allcontracts_get: %s\n" % e)
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

# **contract_allcontracts_user_name_get**
> contract_allcontracts_user_name_get(user_name)

Retrieves most recent 100 contracts for the given UserName

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to lookup

try:
    # Retrieves most recent 100 contracts for the given UserName
    api_instance.contract_allcontracts_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->contract_allcontracts_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The UserName to lookup | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **contract_change_post**
> contract_change_post()

Posts CONTRACTS_CONTRACT payload. See FIORest source for payload definition

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts CONTRACTS_CONTRACT payload. See FIORest source for payload definition
    api_instance.contract_change_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->contract_change_post: %s\n" % e)
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

# **contract_concerns_get**
> contract_concerns_get()

Retrieves contracts which can be extended or are within 1 day of ending

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves contracts which can be extended or are within 1 day of ending
    api_instance.contract_concerns_get()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->contract_concerns_get: %s\n" % e)
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

# **contract_concerns_user_name_get**
> contract_concerns_user_name_get(user_name)

Retrieves concerning contracts for the given UserName

Concerning contracts are defined as contracts which: 1) Can be extended 2) Are within 1 day of ending 

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to lookup

try:
    # Retrieves concerning contracts for the given UserName
    api_instance.contract_concerns_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->contract_concerns_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The UserName to lookup | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **contract_loans_get**
> contract_loans_get()

Retrieves loan contracts for the current user

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves loan contracts for the current user
    api_instance.contract_loans_get()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->contract_loans_get: %s\n" % e)
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

# **contract_loans_user_name_get**
> contract_loans_user_name_get(user_name)

Retrieves loan contracts for the given UserName

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to lookup

try:
    # Retrieves loan contracts for the given UserName
    api_instance.contract_loans_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->contract_loans_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The UserName to lookup | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **contract_post**
> contract_post()

Posts CONTRACTS_CONTRACTS payload. See FIORest source for payload definition

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts CONTRACTS_CONTRACTS payload. See FIORest source for payload definition
    api_instance.contract_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->contract_post: %s\n" % e)
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

# **contract_shipments_get**
> contract_shipments_get()

Retrieves information on the location of your shipments

This will retrieve the location of your shipment, assuming that user is also present on FIO and has given you the 'ShipmentTracking' permission 

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves information on the location of your shipments
    api_instance.contract_shipments_get()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->contract_shipments_get: %s\n" % e)
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

# **contract_taco_get**
> contract_taco_get()

Retrieves taco statistics for EatTacos88

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves taco statistics for EatTacos88
    api_instance.contract_taco_get()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->contract_taco_get: %s\n" % e)
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

# **cxos_added_post**
> cxos_added_post()

Posts COMEX_TRADER_ORDER_ADDED data payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COMEX_TRADER_ORDER_ADDED data payload
    api_instance.cxos_added_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->cxos_added_post: %s\n" % e)
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

# **cxos_post**
> cxos_post()

Posts COMEX_TRADER_ORDERS data payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COMEX_TRADER_ORDERS data payload
    api_instance.cxos_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->cxos_post: %s\n" % e)
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

# **cxos_removed_post**
> cxos_removed_post()

Posts COMEX_TRADER_ORDER_REMOVED data payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COMEX_TRADER_ORDER_REMOVED data payload
    api_instance.cxos_removed_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->cxos_removed_post: %s\n" % e)
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

# **cxos_updated_post**
> cxos_updated_post()

Posts COMEX_TRADER_ORDER_UPDATED data payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COMEX_TRADER_ORDER_UPDATED data payload
    api_instance.cxos_updated_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->cxos_updated_post: %s\n" % e)
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

# **cxos_user_name_get**
> cxos_user_name_get(user_name)

Retrieves CXOS data for provided username.  See FIORest source for payload definition

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to lookup CXOS data for

try:
    # Retrieves CXOS data for provided username.  See FIORest source for payload definition
    api_instance.cxos_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->cxos_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to lookup CXOS data for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COMEX_BROKER_DATA data payload
    api_instance.exchange_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->exchange_post: %s\n" % e)
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

# **infrastructure_post**
> infrastructure_post()

Posts INFRASTRUCTURE_DATA_DATA data payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts INFRASTRUCTURE_DATA_DATA data payload
    api_instance.infrastructure_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->infrastructure_post: %s\n" % e)
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

# **infrastructure_project_post**
> infrastructure_project_post()

Posts INFRASTRUCTURE_PROJECTS_DATA data payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts INFRASTRUCTURE_PROJECTS_DATA data payload
    api_instance.infrastructure_project_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->infrastructure_project_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts LOCAL_MARKET_DATA_DATA data payload
    api_instance.localmarket_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->localmarket_post: %s\n" % e)
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

# **material_allmaterials_get**
> material_allmaterials_get()

Retrieves all materials.  See FIORest source for payload definition

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.RequiresAuthApi()

try:
    # Retrieves all materials.  See FIORest source for payload definition
    api_instance.material_allmaterials_get()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->material_allmaterials_get: %s\n" % e)
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

# **material_post**
> material_post()

Posts WORLD_MATERIAL_CATEGORIES payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts WORLD_MATERIAL_CATEGORIES payload
    api_instance.material_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->material_post: %s\n" % e)
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

# **planet_cogc_post**
> planet_cogc_post()

Posts PLANET_COGC_DATA payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts PLANET_COGC_DATA payload
    api_instance.planet_cogc_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->planet_cogc_post: %s\n" % e)
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

# **planet_post**
> planet_post()

Posts PLANET_DATA_DATA payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts PLANET_DATA_DATA payload
    api_instance.planet_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->planet_post: %s\n" % e)
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

# **planet_sites_post**
> planet_sites_post()

Posts PLANET_SITES payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts PLANET_SITES payload
    api_instance.planet_sites_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->planet_sites_post: %s\n" % e)
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

# **production_planets_user_name_get**
> list[str] production_planets_user_name_get(user_name)

Retrieve all the planets where production lines are present for the provided UserName

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve a planet list for

try:
    # Retrieve all the planets where production lines are present for the provided UserName
    api_response = api_instance.production_planets_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->production_planets_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve a planet list for | 

### Return type

**list[str]**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **production_post**
> production_post()

Posts PRODUCTION_SITE_PRODUCTION_LINES payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts PRODUCTION_SITE_PRODUCTION_LINES payload
    api_instance.production_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->production_post: %s\n" % e)
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

# **production_user_name_get**
> production_user_name_get(user_name)

Retrieve all production lines for provided UserName

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve production lines for

try:
    # Retrieve all production lines for provided UserName
    api_instance.production_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->production_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve production lines for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **production_user_name_planet_get**
> list[object] production_user_name_planet_get(user_name, planet)

Retrieve production line for the given UserName on the specified Planet

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve a planet list for
planet = 'planet_example' # str | The planet.  It can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName 

try:
    # Retrieve production line for the given UserName on the specified Planet
    api_response = api_instance.production_user_name_planet_get(user_name, planet)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->production_user_name_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve a planet list for | 
 **planet** | **str**| The planet.  It can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName  | 

### Return type

**list[object]**

### Authorization

[api_key](../README.md#api_key)

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves liquid asset data for the given UserName
    api_response = api_instance.rain_userliquid_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->rain_userliquid_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet building reclaimables for the given UserName
    api_response = api_instance.rain_userplanetbuildingreclaimables_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->rain_userplanetbuildingreclaimables_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet buildings for the given UserName
    api_response = api_instance.rain_userplanetbuildings_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->rain_userplanetbuildings_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet production for the given UserName
    api_response = api_instance.rain_userplanetproduction_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->rain_userplanetproduction_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet production inputs for the given UserName
    api_response = api_instance.rain_userplanetproductioninput_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->rain_userplanetproductioninput_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet production outputs for the given UserName
    api_response = api_instance.rain_userplanetproductionoutput_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->rain_userplanetproductionoutput_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planets for the given UserName
    api_response = api_instance.rain_userplanets_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->rain_userplanets_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet production workforces for the given UserName
    api_response = api_instance.rain_userplanetworkforce_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->rain_userplanetworkforce_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve data for

try:
    # Retrieves planet production workforces for the given UserName
    api_response = api_instance.rain_userstorage_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->rain_userstorage_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts SHIP_FLIGHT_FLIGHTS payload
    api_instance.ship_flights_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->ship_flights_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve flight data for

try:
    # Retrieves ship flight data
    api_instance.ship_flights_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->ship_flights_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to ship stl/ftl store models for

try:
    # Retrieves ship fuel store data
    api_instance.ship_ships_fuel_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->ship_ships_fuel_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts SHIP_SHIPS payload
    api_instance.ship_ships_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->ship_ships_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve ship data for

try:
    # Retrieves ship data
    api_instance.ship_ships_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->ship_ships_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve site data for

try:
    # Retrieves list of planets user has site data for
    api_response = api_instance.sites_planets_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->sites_planets_user_name_get: %s\n" % e)
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

# **sites_post**
> sites_post()

Posts SITE_SITES payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts SITE_SITES payload
    api_instance.sites_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->sites_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve site data for

try:
    # Retrieves site data
    api_instance.sites_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->sites_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve site data for
planet = 'planet_example' # str | Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName 

try:
    # Retrieves list of planets user has site data for
    api_instance.sites_user_name_planet_get(user_name, planet)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->sites_user_name_planet_get: %s\n" % e)
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

# **sites_warehouses_post**
> sites_warehouses_post()

Posts STORAGE_WAREHOUSES payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts STORAGE_WAREHOUSES payload
    api_instance.sites_warehouses_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->sites_warehouses_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve site data for

try:
    # Retrieves all warehouse sites the user has
    api_instance.sites_warehouses_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->sites_warehouses_user_name_get: %s\n" % e)
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

# **storage_change_post**
> storage_change_post()

Posts STORAGE_CHANGE payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts STORAGE_CHANGE payload
    api_instance.storage_change_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->storage_change_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve storage data for

try:
    # Retrieves list of Planets where storage data exists for UserName
    api_response = api_instance.storage_planets_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->storage_planets_user_name_get: %s\n" % e)
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

# **storage_post**
> storage_post()

Posts STORAGE_STORAGES payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts STORAGE_STORAGES payload
    api_instance.storage_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->storage_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve storage data for

try:
    # Retrieves storage data
    api_instance.storage_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->storage_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve storage data for
storage_description = 'storage_description_example' # str | Can be any of the following: 1) StorageId 2) PlanetId 3) PlanetNaturalId 4) PlanetName 

try:
    # Retrieves list of Planets where storage data exists for UserName
    api_instance.storage_user_name_storage_description_get(user_name, storage_description)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->storage_user_name_storage_description_get: %s\n" % e)
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

# **systemstars_star_post**
> systemstars_star_post()

Posts SYSTEM_STAR data

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts SYSTEM_STAR data
    api_instance.systemstars_star_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->systemstars_star_post: %s\n" % e)
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

# **user_allusers_get**
> list[str] user_allusers_get()

Retrieves all FIO users

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves all FIO users
    api_response = api_instance.user_allusers_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->user_allusers_get: %s\n" % e)
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

# **user_post**
> user_post()

Posts USER_DATA payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts USER_DATA payload
    api_instance.user_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->user_post: %s\n" % e)
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

# **user_resetalldata_post**
> user_resetalldata_post()

Resets the current user's data.

This will delete the following data for your User: 1) Company data 2) ProductionLine data 3) Ship data 4) Site data 5) Workforce data 6) User data 7) Warehouse data 8) Contract data  You should only use this if your data has been corrupted by excess hydration timeouts 

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Resets the current user's data.
    api_instance.user_resetalldata_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->user_resetalldata_post: %s\n" % e)
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

# **user_user_name_get**
> user_user_name_get(user_name)

Retrieves userdata for specified UserName

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve user data for

try:
    # Retrieves userdata for specified UserName
    api_instance.user_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->user_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve user data for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

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
api_instance = fio_sdk.RequiresAuthApi()
body = fio_sdk.UserSettingsBurnRateExclusion() # UserSettingsBurnRateExclusion | A BurnRateExclusion

try:
    # Adds a BurnRateExclusion
    api_instance.usersettings_burnrate_addexclusion_post(body)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->usersettings_burnrate_addexclusion_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi()
body = fio_sdk.UserSettingsBurnRateExclusion() # UserSettingsBurnRateExclusion | A BurnRateExclusion

try:
    # Deletes a BurnRateExclusion
    api_instance.usersettings_burnrate_deleteexclusion_post(body)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->usersettings_burnrate_deleteexclusion_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Currently unused.  Will be used in the future
    api_instance.usersettings_burnrate_redthreshold_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->usersettings_burnrate_redthreshold_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to retrieve BurnRate settings for

try:
    # Retrieves BurnRateSettings for the specified user
    api_instance.usersettings_burnrate_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->usersettings_burnrate_user_name_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The UserName to retrieve BurnRate settings for
planet_natural_id = 'planet_natural_id_example' # str | The PlanetNaturalId

try:
    # Retrivies BurnRateSettings for the specified user on the specified planet
    api_instance.usersettings_burnrate_user_name_planet_natural_id_get(user_name, planet_natural_id)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->usersettings_burnrate_user_name_planet_natural_id_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Currently unused.  Will be used in the future
    api_instance.usersettings_burnrate_yellowthreshold_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->usersettings_burnrate_yellowthreshold_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Currently unused.  Will be used in the future
    api_instance.usersettings_general_get()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->usersettings_general_get: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Currently unused.  Will be used in the future
    api_instance.usersettings_general_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->usersettings_general_post: %s\n" % e)
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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | 

try:
    # Currently unused.  Will be used in the future
    api_instance.usersettings_general_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->usersettings_general_user_name_get: %s\n" % e)
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

# **workforce_planets_user_name_get**
> list[str] workforce_planets_user_name_get(user_name)

Retrieves list of planets where the specified user has Workforce data

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve workforce data for

try:
    # Retrieves list of planets where the specified user has Workforce data
    api_response = api_instance.workforce_planets_user_name_get(user_name)
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->workforce_planets_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve workforce data for | 

### Return type

**list[str]**

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **workforce_post**
> workforce_post()

Posts WORKFORCE_WORKFORCES payload

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))

try:
    # Posts WORKFORCE_WORKFORCES payload
    api_instance.workforce_post()
except ApiException as e:
    print("Exception when calling RequiresAuthApi->workforce_post: %s\n" % e)
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

# **workforce_user_name_get**
> workforce_user_name_get(user_name)

Retrieves workforce data for the specified user

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve workforce data for

try:
    # Retrieves workforce data for the specified user
    api_instance.workforce_user_name_get(user_name)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->workforce_user_name_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve workforce data for | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **workforce_user_name_planet_get**
> workforce_user_name_planet_get(user_name, planet)

Retrieves workforce data for the specified usernaem and planet

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
api_instance = fio_sdk.RequiresAuthApi(fio_sdk.ApiClient(configuration))
user_name = 'user_name_example' # str | The username to retrieve workforce data for
planet = 'planet_example' # str | Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName 

try:
    # Retrieves workforce data for the specified usernaem and planet
    api_instance.workforce_user_name_planet_get(user_name, planet)
except ApiException as e:
    print("Exception when calling RequiresAuthApi->workforce_user_name_planet_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **user_name** | **str**| The username to retrieve workforce data for | 
 **planet** | **str**| Can be any of the following: 1) PlanetId 2) PlanetNaturalId 3) PlanetName  | 

### Return type

void (empty response body)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

