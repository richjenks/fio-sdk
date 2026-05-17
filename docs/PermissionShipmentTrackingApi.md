# fio_sdk.PermissionShipmentTrackingApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**contract_shipments_get**](PermissionShipmentTrackingApi.md#contract_shipments_get) | **GET** /contract/shipments | Retrieves information on the location of your shipments

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
api_instance = fio_sdk.PermissionShipmentTrackingApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieves information on the location of your shipments
    api_instance.contract_shipments_get()
except ApiException as e:
    print("Exception when calling PermissionShipmentTrackingApi->contract_shipments_get: %s\n" % e)
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

