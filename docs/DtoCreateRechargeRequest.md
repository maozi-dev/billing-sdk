# DtoCreateRechargeRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | **float32** |  | 
**BonusAmount** | Pointer to **float32** |  | [optional] 
**ClientIp** | Pointer to **string** |  | [optional] 
**Currency** | Pointer to **string** |  | [optional] 
**Gateway** | **string** |  | 
**IdempotencyKey** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to **map[string]string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**PayerId** | Pointer to **string** |  | [optional] 
**Scene** | Pointer to **string** |  | [optional] 
**WalletId** | **string** |  | 

## Methods

### NewDtoCreateRechargeRequest

`func NewDtoCreateRechargeRequest(amount float32, gateway string, walletId string, ) *DtoCreateRechargeRequest`

NewDtoCreateRechargeRequest instantiates a new DtoCreateRechargeRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtoCreateRechargeRequestWithDefaults

`func NewDtoCreateRechargeRequestWithDefaults() *DtoCreateRechargeRequest`

NewDtoCreateRechargeRequestWithDefaults instantiates a new DtoCreateRechargeRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmount

`func (o *DtoCreateRechargeRequest) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *DtoCreateRechargeRequest) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *DtoCreateRechargeRequest) SetAmount(v float32)`

SetAmount sets Amount field to given value.


### GetBonusAmount

`func (o *DtoCreateRechargeRequest) GetBonusAmount() float32`

GetBonusAmount returns the BonusAmount field if non-nil, zero value otherwise.

### GetBonusAmountOk

`func (o *DtoCreateRechargeRequest) GetBonusAmountOk() (*float32, bool)`

GetBonusAmountOk returns a tuple with the BonusAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBonusAmount

`func (o *DtoCreateRechargeRequest) SetBonusAmount(v float32)`

SetBonusAmount sets BonusAmount field to given value.

### HasBonusAmount

`func (o *DtoCreateRechargeRequest) HasBonusAmount() bool`

HasBonusAmount returns a boolean if a field has been set.

### GetClientIp

`func (o *DtoCreateRechargeRequest) GetClientIp() string`

GetClientIp returns the ClientIp field if non-nil, zero value otherwise.

### GetClientIpOk

`func (o *DtoCreateRechargeRequest) GetClientIpOk() (*string, bool)`

GetClientIpOk returns a tuple with the ClientIp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClientIp

`func (o *DtoCreateRechargeRequest) SetClientIp(v string)`

SetClientIp sets ClientIp field to given value.

### HasClientIp

`func (o *DtoCreateRechargeRequest) HasClientIp() bool`

HasClientIp returns a boolean if a field has been set.

### GetCurrency

`func (o *DtoCreateRechargeRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *DtoCreateRechargeRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *DtoCreateRechargeRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *DtoCreateRechargeRequest) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetGateway

`func (o *DtoCreateRechargeRequest) GetGateway() string`

GetGateway returns the Gateway field if non-nil, zero value otherwise.

### GetGatewayOk

`func (o *DtoCreateRechargeRequest) GetGatewayOk() (*string, bool)`

GetGatewayOk returns a tuple with the Gateway field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGateway

`func (o *DtoCreateRechargeRequest) SetGateway(v string)`

SetGateway sets Gateway field to given value.


### GetIdempotencyKey

`func (o *DtoCreateRechargeRequest) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *DtoCreateRechargeRequest) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *DtoCreateRechargeRequest) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.

### HasIdempotencyKey

`func (o *DtoCreateRechargeRequest) HasIdempotencyKey() bool`

HasIdempotencyKey returns a boolean if a field has been set.

### GetMetadata

`func (o *DtoCreateRechargeRequest) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DtoCreateRechargeRequest) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DtoCreateRechargeRequest) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *DtoCreateRechargeRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetName

`func (o *DtoCreateRechargeRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DtoCreateRechargeRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DtoCreateRechargeRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *DtoCreateRechargeRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPayerId

`func (o *DtoCreateRechargeRequest) GetPayerId() string`

GetPayerId returns the PayerId field if non-nil, zero value otherwise.

### GetPayerIdOk

`func (o *DtoCreateRechargeRequest) GetPayerIdOk() (*string, bool)`

GetPayerIdOk returns a tuple with the PayerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayerId

`func (o *DtoCreateRechargeRequest) SetPayerId(v string)`

SetPayerId sets PayerId field to given value.

### HasPayerId

`func (o *DtoCreateRechargeRequest) HasPayerId() bool`

HasPayerId returns a boolean if a field has been set.

### GetScene

`func (o *DtoCreateRechargeRequest) GetScene() string`

GetScene returns the Scene field if non-nil, zero value otherwise.

### GetSceneOk

`func (o *DtoCreateRechargeRequest) GetSceneOk() (*string, bool)`

GetSceneOk returns a tuple with the Scene field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScene

`func (o *DtoCreateRechargeRequest) SetScene(v string)`

SetScene sets Scene field to given value.

### HasScene

`func (o *DtoCreateRechargeRequest) HasScene() bool`

HasScene returns a boolean if a field has been set.

### GetWalletId

`func (o *DtoCreateRechargeRequest) GetWalletId() string`

GetWalletId returns the WalletId field if non-nil, zero value otherwise.

### GetWalletIdOk

`func (o *DtoCreateRechargeRequest) GetWalletIdOk() (*string, bool)`

GetWalletIdOk returns a tuple with the WalletId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWalletId

`func (o *DtoCreateRechargeRequest) SetWalletId(v string)`

SetWalletId sets WalletId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


