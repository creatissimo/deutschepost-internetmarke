# # Authentication200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**access_token** | **string** | The access token / bearer token. (user_token is deprecated) | [optional]
**wallet_balance** | **int** | money balance in portokasse | [optional]
**info_message** | **string** | info message, if any | [optional]
**token_type** | **string** | Will always contain &#39;BearerToken&#39; | [optional]
**expires_in** | **int** | remaining token validity in seconds | [optional]
**issued_at** | **string** | Time when token was issued | [optional]
**external_customer_id** | **string** | Matches the user requesting the token, used internally | [optional]
**authenticated_user** | **string** | user requesting the token | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
