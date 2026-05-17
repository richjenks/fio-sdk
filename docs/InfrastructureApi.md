# fio_sdk.InfrastructureApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**infrastructure_planet_or_infrastructure_id_get**](InfrastructureApi.md#infrastructure_planet_or_infrastructure_id_get) | **GET** /infrastructure/{PlanetOrInfrastructureId} | Retrieves infrastucture payload for the given PlanetOrInfrastructureId
[**infrastructure_post**](InfrastructureApi.md#infrastructure_post) | **POST** /infrastructure | Posts INFRASTRUCTURE_DATA_DATA data payload
[**infrastructure_project_post**](InfrastructureApi.md#infrastructure_project_post) | **POST** /infrastructure/project | Posts INFRASTRUCTURE_PROJECTS_DATA data payload

# **infrastructure_planet_or_infrastructure_id_get**
> infrastructure_planet_or_infrastructure_id_get(planet_or_infrastructure_id)

Retrieves infrastucture payload for the given PlanetOrInfrastructureId

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.InfrastructureApi()
planet_or_infrastructure_id = 'planet_or_infrastructure_id_example' # str | The planet or infrastucture id.  Can be any of the following: 1) PopulationId/InfrastructureId 2) PlanetId 3) PlanetNaturalId 4) PlanetName 

try:
    # Retrieves infrastucture payload for the given PlanetOrInfrastructureId
    api_instance.infrastructure_planet_or_infrastructure_id_get(planet_or_infrastructure_id)
except ApiException as e:
    print("Exception when calling InfrastructureApi->infrastructure_planet_or_infrastructure_id_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **planet_or_infrastructure_id** | **str**| The planet or infrastucture id.  Can be any of the following: 1) PopulationId/InfrastructureId 2) PlanetId 3) PlanetNaturalId 4) PlanetName  | 

### Return type

void (empty response body)

### Authorization

No authorization required

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
api_instance = fio_sdk.InfrastructureApi(fio_sdk.ApiClient(configuration))

try:
    # Posts INFRASTRUCTURE_DATA_DATA data payload
    api_instance.infrastructure_post()
except ApiException as e:
    print("Exception when calling InfrastructureApi->infrastructure_post: %s\n" % e)
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
api_instance = fio_sdk.InfrastructureApi(fio_sdk.ApiClient(configuration))

try:
    # Posts INFRASTRUCTURE_PROJECTS_DATA data payload
    api_instance.infrastructure_project_post()
except ApiException as e:
    print("Exception when calling InfrastructureApi->infrastructure_project_post: %s\n" % e)
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

