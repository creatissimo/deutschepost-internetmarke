# # RetoureState

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**retoure_transaction_id** | **int** | The transaction number for the refund. | [optional]
**shop_retoure_id** | **string** | The id to be assigned by the shop for the refund. |
**total_count** | **int** | The number of stamps processed with this refund transaction. | [optional]
**count_still_open** | **int** | The number of stamps not yet processed. ZINS feedback has not arrived here yet. | [optional]
**retoure_price** | **int** | The total value of confirmed refunds. | [optional]
**creation_date** | **string** | The timestamp when the refund was created. |
**serialnumber** | **string** | The serial number of the Safebox (FrankierAccountId). |
**refunded_vouchers** | [**\DPInternetmarke\Client\Model\Voucher[]**](Voucher.md) | The list of created franking IDs. |
**not_refunded_vouchers** | [**\DPInternetmarke\Client\Model\Voucher[]**](Voucher.md) | The list of created franking IDs. |

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
