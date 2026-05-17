# fio_sdk.VersionApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**version_download_get**](VersionApi.md#version_download_get) | **GET** /version/download | Retrieves latest FIOUI setup executable
[**version_extension_download_get**](VersionApi.md#version_extension_download_get) | **GET** /version/extension/download | Redirects you to to the FIO Chrome Extension page
[**version_extension_script_get**](VersionApi.md#version_extension_script_get) | **GET** /version/extension/script | Retrieves the latest version of the FIO uploader script
[**version_latest_get**](VersionApi.md#version_latest_get) | **GET** /version/latest | Retrieves latest version number of the FIOUI
[**version_releasenotes_get**](VersionApi.md#version_releasenotes_get) | **GET** /version/releasenotes | Retrieves latest version release notes of the FIOUI as an rtf file

# **version_download_get**
> version_download_get()

Retrieves latest FIOUI setup executable

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.VersionApi()

try:
    # Retrieves latest FIOUI setup executable
    api_instance.version_download_get()
except ApiException as e:
    print("Exception when calling VersionApi->version_download_get: %s\n" % e)
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

# **version_extension_download_get**
> version_extension_download_get()

Redirects you to to the FIO Chrome Extension page

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.VersionApi()

try:
    # Redirects you to to the FIO Chrome Extension page
    api_instance.version_extension_download_get()
except ApiException as e:
    print("Exception when calling VersionApi->version_extension_download_get: %s\n" % e)
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

# **version_extension_script_get**
> version_extension_script_get()

Retrieves the latest version of the FIO uploader script

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.VersionApi()

try:
    # Retrieves the latest version of the FIO uploader script
    api_instance.version_extension_script_get()
except ApiException as e:
    print("Exception when calling VersionApi->version_extension_script_get: %s\n" % e)
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

# **version_latest_get**
> str version_latest_get()

Retrieves latest version number of the FIOUI

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.VersionApi()

try:
    # Retrieves latest version number of the FIOUI
    api_response = api_instance.version_latest_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling VersionApi->version_latest_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

**str**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **version_releasenotes_get**
> version_releasenotes_get()

Retrieves latest version release notes of the FIOUI as an rtf file

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.VersionApi()

try:
    # Retrieves latest version release notes of the FIOUI as an rtf file
    api_instance.version_releasenotes_get()
except ApiException as e:
    print("Exception when calling VersionApi->version_releasenotes_get: %s\n" % e)
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

