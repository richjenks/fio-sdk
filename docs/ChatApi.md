# fio_sdk.ChatApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**chat_data_post**](ChatApi.md#chat_data_post) | **POST** /chat/data | Posts the CHANNEL_DATA payload to the server.  For payload, see FIORest source
[**chat_display_channel_description_get**](ChatApi.md#chat_display_channel_description_get) | **GET** /chat/display/{ChannelDescription} | Retrieves the last 300 messages of the provided ChannelDescription
[**chat_display_pretty_channel_description_get**](ChatApi.md#chat_display_pretty_channel_description_get) | **GET** /chat/display/pretty/{ChannelDescription} | Retrieves the last 300 messages of the provided ChannelDescription in a &#x27;pretty&#x27; (textual) format
[**chat_list_get**](ChatApi.md#chat_list_get) | **GET** /chat/list | Retrieves a list of searchable channel names and their corresponding ChannelIds
[**chat_message_added_post**](ChatApi.md#chat_message_added_post) | **POST** /chat/message_added | Posts the CHANNEL_MESSAGE_ADDED payload to the server.  For payload, see FIORest source
[**chat_message_deleted_post**](ChatApi.md#chat_message_deleted_post) | **POST** /chat/message_deleted | Posts the CHANNEL_MESSAGE_DELETED payload to the server.  For payload, see FIORest source
[**chat_message_list_post**](ChatApi.md#chat_message_list_post) | **POST** /chat/message_list | Posts the CHANNEL_MESSAGE_LIST payload to the server.  For payload, see FIORest source

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
api_instance = fio_sdk.ChatApi(fio_sdk.ApiClient(configuration))

try:
    # Posts the CHANNEL_DATA payload to the server.  For payload, see FIORest source
    api_instance.chat_data_post()
except ApiException as e:
    print("Exception when calling ChatApi->chat_data_post: %s\n" % e)
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

# **chat_display_channel_description_get**
> chat_display_channel_description_get(channel_description)

Retrieves the last 300 messages of the provided ChannelDescription

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.ChatApi()
channel_description = 'channel_description_example' # str | The ChannelDescription.  Can be: 1) ChannelId 2) ChannelDisplayName 2) PlanetName 3) PlanetNaturalId 

try:
    # Retrieves the last 300 messages of the provided ChannelDescription
    api_instance.chat_display_channel_description_get(channel_description)
except ApiException as e:
    print("Exception when calling ChatApi->chat_display_channel_description_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **channel_description** | **str**| The ChannelDescription.  Can be: 1) ChannelId 2) ChannelDisplayName 2) PlanetName 3) PlanetNaturalId  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **chat_display_pretty_channel_description_get**
> chat_display_pretty_channel_description_get(channel_description)

Retrieves the last 300 messages of the provided ChannelDescription in a 'pretty' (textual) format

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.ChatApi()
channel_description = 'channel_description_example' # str | The ChannelDescription.  Can be: 1) ChannelId 2) ChannelDisplayName 2) PlanetName 3) PlanetNaturalId 

try:
    # Retrieves the last 300 messages of the provided ChannelDescription in a 'pretty' (textual) format
    api_instance.chat_display_pretty_channel_description_get(channel_description)
except ApiException as e:
    print("Exception when calling ChatApi->chat_display_pretty_channel_description_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **channel_description** | **str**| The ChannelDescription.  Can be: 1) ChannelId 2) ChannelDisplayName 2) PlanetName 3) PlanetNaturalId  | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **chat_list_get**
> list[ChatListItem] chat_list_get()

Retrieves a list of searchable channel names and their corresponding ChannelIds

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.ChatApi()

try:
    # Retrieves a list of searchable channel names and their corresponding ChannelIds
    api_response = api_instance.chat_list_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling ChatApi->chat_list_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[ChatListItem]**](ChatListItem.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

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
api_instance = fio_sdk.ChatApi(fio_sdk.ApiClient(configuration))

try:
    # Posts the CHANNEL_MESSAGE_ADDED payload to the server.  For payload, see FIORest source
    api_instance.chat_message_added_post()
except ApiException as e:
    print("Exception when calling ChatApi->chat_message_added_post: %s\n" % e)
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
api_instance = fio_sdk.ChatApi(fio_sdk.ApiClient(configuration))

try:
    # Posts the CHANNEL_MESSAGE_DELETED payload to the server.  For payload, see FIORest source
    api_instance.chat_message_deleted_post()
except ApiException as e:
    print("Exception when calling ChatApi->chat_message_deleted_post: %s\n" % e)
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
api_instance = fio_sdk.ChatApi(fio_sdk.ApiClient(configuration))

try:
    # Posts the CHANNEL_MESSAGE_LIST payload to the server.  For payload, see FIORest source
    api_instance.chat_message_list_post()
except ApiException as e:
    print("Exception when calling ChatApi->chat_message_list_post: %s\n" % e)
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

