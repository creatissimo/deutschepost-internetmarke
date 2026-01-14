# # AppShoppingCartPreviewPDFRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**type** | **string** | set AppShoppingCartPDFRequest if validate&#x3D;false, AppShoppingCartPreviewPDFRequest if validate&#x3D;true | [optional] [default to 'AppShoppingCartPreviewPDFRequest']
**product_code** | **int** | The product code for the selected product, e.g. standard letter, maxi letter etc. The product code must be greater than 0 and the product must be available in the third-party application. | [optional]
**image_id** | **int** | The ID of the motif. | [optional]
**voucher_layout** | **string** |  |
**page_format_id** | **int** | The ID of the print format. All available formats can be identified by request /app/catalog?types&#x3D;PAGE_FORMATS | [optional]
**dpi** | **string** |  | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
