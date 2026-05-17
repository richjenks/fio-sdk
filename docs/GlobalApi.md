# fio_sdk.GlobalApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**global_comexexchanges_get**](GlobalApi.md#global_comexexchanges_get) | **GET** /global/comexexchanges | Retrieves COMEX_EXCHANGE_LIST data
[**global_comexexchanges_post**](GlobalApi.md#global_comexexchanges_post) | **POST** /global/comexexchanges | Posts COMEX_EXCHANGE_LIST data
[**global_countries_get**](GlobalApi.md#global_countries_get) | **GET** /global/countries | Retrieves COUNTRY_REGISTRY_COUNTRIES data
[**global_countries_post**](GlobalApi.md#global_countries_post) | **POST** /global/countries | Posts COUNTRY_REGISTRY_COUNTRIES data
[**global_simulationdata_get**](GlobalApi.md#global_simulationdata_get) | **GET** /global/simulationdata | Retrieves SIMULATION_DATA data
[**global_simulationdata_post**](GlobalApi.md#global_simulationdata_post) | **POST** /global/simulationdata | Posts SIMULATION_DATA data
[**global_workforceneeds_get**](GlobalApi.md#global_workforceneeds_get) | **GET** /global/workforceneeds | Retrieves workforce needs

# **global_comexexchanges_get**
> global_comexexchanges_get()

Retrieves COMEX_EXCHANGE_LIST data

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.GlobalApi()

try:
    # Retrieves COMEX_EXCHANGE_LIST data
    api_instance.global_comexexchanges_get()
except ApiException as e:
    print("Exception when calling GlobalApi->global_comexexchanges_get: %s\n" % e)
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

# **global_comexexchanges_post**
> global_comexexchanges_post()

Posts COMEX_EXCHANGE_LIST data

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
api_instance = fio_sdk.GlobalApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COMEX_EXCHANGE_LIST data
    api_instance.global_comexexchanges_post()
except ApiException as e:
    print("Exception when calling GlobalApi->global_comexexchanges_post: %s\n" % e)
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

# **global_countries_get**
> global_countries_get()

Retrieves COUNTRY_REGISTRY_COUNTRIES data

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.GlobalApi()

try:
    # Retrieves COUNTRY_REGISTRY_COUNTRIES data
    api_instance.global_countries_get()
except ApiException as e:
    print("Exception when calling GlobalApi->global_countries_get: %s\n" % e)
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

# **global_countries_post**
> global_countries_post()

Posts COUNTRY_REGISTRY_COUNTRIES data

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
api_instance = fio_sdk.GlobalApi(fio_sdk.ApiClient(configuration))

try:
    # Posts COUNTRY_REGISTRY_COUNTRIES data
    api_instance.global_countries_post()
except ApiException as e:
    print("Exception when calling GlobalApi->global_countries_post: %s\n" % e)
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

# **global_simulationdata_get**
> global_simulationdata_get()

Retrieves SIMULATION_DATA data

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.GlobalApi()

try:
    # Retrieves SIMULATION_DATA data
    api_instance.global_simulationdata_get()
except ApiException as e:
    print("Exception when calling GlobalApi->global_simulationdata_get: %s\n" % e)
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

# **global_simulationdata_post**
> global_simulationdata_post()

Posts SIMULATION_DATA data

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
api_instance = fio_sdk.GlobalApi(fio_sdk.ApiClient(configuration))

try:
    # Posts SIMULATION_DATA data
    api_instance.global_simulationdata_post()
except ApiException as e:
    print("Exception when calling GlobalApi->global_simulationdata_post: %s\n" % e)
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

# **global_workforceneeds_get**
> global_workforceneeds_get()

Retrieves workforce needs

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.GlobalApi()

try:
    # Retrieves workforce needs
    api_instance.global_workforceneeds_get()
except ApiException as e:
    print("Exception when calling GlobalApi->global_workforceneeds_get: %s\n" % e)
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

