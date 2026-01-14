# DPInternetmarke\Client\ApiVersionResourceApi

The REST Api version resource (Healthcheck).

All URIs are relative to https://api-eu.dhl.com/post/de/shipping/im/v1, except if the operation defines another base path.

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
| [**apiVersion()**](ApiVersionResourceApi.md#apiVersion) | **GET** / | Get information about this REST Api version. |


## `apiVersion()`

```php
apiVersion(): \DPInternetmarke\Client\Model\ApiVersion200Response
```

Get information about this REST Api version.

The call can be used to obtain the current version of the API and to confirm that the API is operational. Note that this call does not require authentication, it can also be called via browser.

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');



$apiInstance = new DPInternetmarke\Client\Api\ApiVersionResourceApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);

try {
    $result = $apiInstance->apiVersion();
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling ApiVersionResourceApi->apiVersion: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

This endpoint does not need any parameter.

### Return type

[**\DPInternetmarke\Client\Model\ApiVersion200Response**](../Model/ApiVersion200Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)
