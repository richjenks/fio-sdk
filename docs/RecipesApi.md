# fio_sdk.RecipesApi

All URIs are relative to *https://rest.fnar.net/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**recipes_allrecipes_get**](RecipesApi.md#recipes_allrecipes_get) | **GET** /recipes/allrecipes | Retrieve all recipes
[**recipes_ticker_get**](RecipesApi.md#recipes_ticker_get) | **GET** /recipes/{Ticker} | Retrieves the recipes for a given ticker

# **recipes_allrecipes_get**
> list[RecipeMinimalRecipe] recipes_allrecipes_get()

Retrieve all recipes

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
api_instance = fio_sdk.RecipesApi(fio_sdk.ApiClient(configuration))

try:
    # Retrieve all recipes
    api_response = api_instance.recipes_allrecipes_get()
    pprint(api_response)
except ApiException as e:
    print("Exception when calling RecipesApi->recipes_allrecipes_get: %s\n" % e)
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**list[RecipeMinimalRecipe]**](RecipeMinimalRecipe.md)

### Authorization

[api_key](../README.md#api_key)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **recipes_ticker_get**
> recipes_ticker_get(ticker)

Retrieves the recipes for a given ticker

### Example
```python
from __future__ import print_function
import time
import fio_sdk
from fio_sdk.rest import ApiException
from pprint import pprint

# create an instance of the API class
api_instance = fio_sdk.RecipesApi()
ticker = 'ticker_example' # str | The ticker to retrieve recipe data for

try:
    # Retrieves the recipes for a given ticker
    api_instance.recipes_ticker_get(ticker)
except ApiException as e:
    print("Exception when calling RecipesApi->recipes_ticker_get: %s\n" % e)
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ticker** | **str**| The ticker to retrieve recipe data for | 

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

