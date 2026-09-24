# DtoRechargeResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | Pointer to **float32** |  | [optional] 
**BonusAmount** | Pointer to **float32** |  | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] 
**Currency** | Pointer to **string** |  | [optional] 
**Gateway** | Pointer to **string** |  | [optional] 
**GatewayOrderId** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to **map[string]string** |  | [optional] 
**PayPayload** | Pointer to **map[string]string** |  | [optional] 
**PayUrl** | Pointer to **string** |  | [optional] 
**RenderType** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **string** |  | [optional] 
**WalletId** | Pointer to **string** |  | [optional] 

## Methods

### NewDtoRechargeResponse

`func NewDtoRechargeResponse() *DtoRechargeResponse`

NewDtoRechargeResponse instantiates a new DtoRechargeResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtoRechargeResponseWithDefaults

`func NewDtoRechargeResponseWithDefaults() *DtoRechargeResponse`

NewDtoRechargeResponseWithDefaults instantiates a new DtoRechargeResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmount

`func (o *DtoRechargeResponse) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *DtoRechargeResponse) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *DtoRechargeResponse) SetAmount(v float32)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *DtoRechargeResponse) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetBonusAmount

`func (o *DtoRechargeResponse) GetBonusAmount() float32`

GetBonusAmount returns the BonusAmount field if non-nil, zero value otherwise.

### GetBonusAmountOk

`func (o *DtoRechargeResponse) GetBonusAmountOk() (*float32, bool)`

GetBonusAmountOk returns a tuple with the BonusAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBonusAmount

`func (o *DtoRechargeResponse) SetBonusAmount(v float32)`

SetBonusAmount sets BonusAmount field to given value.

### HasBonusAmount

`func (o *DtoRechargeResponse) HasBonusAmount() bool`

HasBonusAmount returns a boolean if a field has been set.

### GetCreatedAt

`func (o *DtoRechargeResponse) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DtoRechargeResponse) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DtoRechargeResponse) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *DtoRechargeResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetCurrency

`func (o *DtoRechargeResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *DtoRechargeResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *DtoRechargeResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *DtoRechargeResponse) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetGateway

`func (o *DtoRechargeResponse) GetGateway() string`

GetGateway returns the Gateway field if non-nil, zero value otherwise.

### GetGatewayOk

`func (o *DtoRechargeResponse) GetGatewayOk() (*string, bool)`

GetGatewayOk returns a tuple with the Gateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGateway

`func (o *DtoRechargeResponse) SetGateway(v string)`

SetGateway sets Gateway field to given value.

### HasGateway

`func (o *DtoRechargeResponse) HasGateway() bool`

HasGateway returns a boolean if a field has been set.

### GetGatewayOrderId

`func (o *DtoRechargeResponse) GetGatewayOrderId() string`

GetGatewayOrderId returns the GatewayOrderId field if non-nil, zero value otherwise.

### GetGatewayOrderIdOk

`func (o *DtoRechargeResponse) GetGatewayOrderIdOk() (*string, bool)`

GetGatewayOrderIdOk returns a tuple with the GatewayOrderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayOrderId

`func (o *DtoRechargeResponse) SetGatewayOrderId(v string)`

SetGatewayOrderId sets GatewayOrderId field to given value.

### HasGatewayOrderId

`func (o *DtoRechargeResponse) HasGatewayOrderId() bool`

HasGatewayOrderId returns a boolean if a field has been set.

### GetId

`func (o *DtoRechargeResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DtoRechargeResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DtoRechargeResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *DtoRechargeResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetMetadata

`func (o *DtoRechargeResponse) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DtoRechargeResponse) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DtoRechargeResponse) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *DtoRechargeResponse) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetPayPayload

`func (o *DtoRechargeResponse) GetPayPayload() map[string]string`

GetPayPayload returns the PayPayload field if non-nil, zero value otherwise.

### GetPayPayloadOk

`func (o *DtoRechargeResponse) GetPayPayloadOk() (*map[string]string, bool)`

GetPayPayloadOk returns a tuple with the PayPayload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayPayload

`func (o *DtoRechargeResponse) SetPayPayload(v map[string]string)`

SetPayPayload sets PayPayload field to given value.

### HasPayPayload

`func (o *DtoRechargeResponse) HasPayPayload() bool`

HasPayPayload returns a boolean if a field has been set.

### GetPayUrl

`func (o *DtoRechargeResponse) GetPayUrl() string`

GetPayUrl returns the PayUrl field if non-nil, zero value otherwise.

### GetPayUrlOk

`func (o *DtoRechargeResponse) GetPayUrlOk() (*string, bool)`

GetPayUrlOk returns a tuple with the PayUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayUrl

`func (o *DtoRechargeResponse) SetPayUrl(v string)`

SetPayUrl sets PayUrl field to given value.

### HasPayUrl

`func (o *DtoRechargeResponse) HasPayUrl() bool`

HasPayUrl returns a boolean if a field has been set.

### GetRenderType

`func (o *DtoRechargeResponse) GetRenderType() string`

GetRenderType returns the RenderType field if non-nil, zero value otherwise.

### GetRenderTypeOk

`func (o *DtoRechargeResponse) GetRenderTypeOk() (*string, bool)`

GetRenderTypeOk returns a tuple with the RenderType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRenderType

`func (o *DtoRechargeResponse) SetRenderType(v string)`

SetRenderType sets RenderType field to given value.

### HasRenderType

`func (o *DtoRechargeResponse) HasRenderType() bool`

HasRenderType returns a boolean if a field has been set.

### GetStatus

`func (o *DtoRechargeResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DtoRechargeResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DtoRechargeResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *DtoRechargeResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *DtoRechargeResponse) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DtoRechargeResponse) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DtoRechargeResponse) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *DtoRechargeResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetWalletId

`func (o *DtoRechargeResponse) GetWalletId() string`

GetWalletId returns the WalletId field if non-nil, zero value otherwise.

### GetWalletIdOk

`func (o *DtoRechargeResponse) GetWalletIdOk() (*string, bool)`

GetWalletIdOk returns a tuple with the WalletId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWalletId

`func (o *DtoRechargeResponse) SetWalletId(v string)`

SetWalletId sets WalletId field to given value.

### HasWalletId

`func (o *DtoRechargeResponse) HasWalletId() bool`

HasWalletId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


