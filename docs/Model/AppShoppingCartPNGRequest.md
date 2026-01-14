# # AppShoppingCartPNGRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**shop_order_id** | **string** | The order number in the shop. All characters are allowed except &lt; and &amp;. It is optional in case of query parameter directCheckout is true. In all other cases it is mandatory required. | [optional]
**total** | **int** | Total value of the shopping cart in euro cents. |
**create_manifest** | **bool** | The flag indicating whether a posting receipt should be created. | [optional]
**create_shipping_list** | **string** | Identifier of which type of shipping list is to be created: 0: No shipping list 1: Shipping list without addresses / delivery receipt only 2: Shipping list with addresses | [optional]
**dpi** | **string** |  | [optional]
**optimize_png** | **bool** | The flag to optimize the PNG (avoid redundant area height). | [optional]
**positions** | [**\DPInternetmarke\Client\Model\AppShoppingCartPosition[]**](AppShoppingCartPosition.md) | List of PNG order items. At least one item has to be specified. |
**type** | **string** |  |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
