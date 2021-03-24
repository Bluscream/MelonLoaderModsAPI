# MelonLoaderModsAPI.Api.DefaultApi

All URIs are relative to *https://ruby-core.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApiModsJsonGet**](DefaultApi.md#apimodsjsonget) | **GET** /api/mods.json | Gets list of available mods

<a name="apimodsjsonget"></a>
# **ApiModsJsonGet**
> List ApiModsJsonGet ()

Gets list of available mods

### Example
```csharp
using System;
using System.Diagnostics;
using MelonLoaderModsAPI.Api;
using MelonLoaderModsAPI.Client;
using MelonLoaderModsAPI.Model;

namespace Example
{
    public class ApiModsJsonGetExample
    {
        public void main()
        {
            var apiInstance = new DefaultApi();

            try
            {
                // Gets list of available mods
                List result = apiInstance.ApiModsJsonGet();
                Debug.WriteLine(result);
            }
            catch (Exception e)
            {
                Debug.Print("Exception when calling DefaultApi.ApiModsJsonGet: " + e.Message );
            }
        }
    }
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

**List**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)
