# DtoPaymentGatewayConfigResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | Pointer to **string** |  | [optional] 
**DisplayName** | Pointer to **string** |  | [optional] 
**EnabledScenes** | Pointer to **[]string** |  | [optional] 
**GatewayProvider** | Pointer to **string** |  | [optional] 
**Id** | Pointer to **string** |  | [optional] 
**IsActive** | Pointer to **bool** |  | [optional] 
**LastTestedAt** | Pointer to **string** |  | [optional] 
**NotifyUrl** | Pointer to **string** |  | [optional] 
**PublicConfig** | Pointer to **map[string]string** |  | [optional] 
**ReturnUrl** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **string** |  | [optional] 

## Methods

### NewDtoPaymentGatewayConfigResponse

`func NewDtoPaymentGatewayConfigResponse() *DtoPaymentGatewayConfigResponse`

NewDtoPaymentGatewayConfigResponse instantiates a new DtoPaymentGatewayConfigResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtoPaymentGatewayConfigResponseWithDefaults

`func NewDtoPaymentGatewayConfigResponseWithDefaults() *DtoPaymentGatewayConfigResponse`

NewDtoPaymentGatewayConfigResponseWithDefaults instantiates a new DtoPaymentGatewayConfigResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *DtoPaymentGatewayConfigResponse) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DtoPaymentGatewayConfigResponse) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DtoPaymentGatewayConfigResponse) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *DtoPaymentGatewayConfigResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetDisplayName

`func (o *DtoPaymentGatewayConfigResponse) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *DtoPaymentGatewayConfigResponse) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *DtoPaymentGatewayConfigResponse) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.

### HasDisplayName

`func (o *DtoPaymentGatewayConfigResponse) HasDisplayName() bool`

HasDisplayName returns a boolean if a field has been set.

### GetEnabledScenes

`func (o *DtoPaymentGatewayConfigResponse) GetEnabledScenes() []string`

GetEnabledScenes returns the EnabledScenes field if non-nil, zero value otherwise.

### GetEnabledScenesOk

`func (o *DtoPaymentGatewayConfigResponse) GetEnabledScenesOk() (*[]string, bool)`

GetEnabledScenesOk returns a tuple with the EnabledScenes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabledScenes

`func (o *DtoPaymentGatewayConfigResponse) SetEnabledScenes(v []string)`

SetEnabledScenes sets EnabledScenes field to given value.

### HasEnabledScenes

`func (o *DtoPaymentGatewayConfigResponse) HasEnabledScenes() bool`

HasEnabledScenes returns a boolean if a field has been set.

### GetGatewayProvider

`func (o *DtoPaymentGatewayConfigResponse) GetGatewayProvider() string`

GetGatewayProvider returns the GatewayProvider field if non-nil, zero value otherwise.

### GetGatewayProviderOk

`func (o *DtoPaymentGatewayConfigResponse) GetGatewayProviderOk() (*string, bool)`

GetGatewayProviderOk returns a tuple with the GatewayProvider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayProvider

`func (o *DtoPaymentGatewayConfigResponse) SetGatewayProvider(v string)`

SetGatewayProvider sets GatewayProvider field to given value.

### HasGatewayProvider

`func (o *DtoPaymentGatewayConfigResponse) HasGatewayProvider() bool`

HasGatewayProvider returns a boolean if a field has been set.

### GetId

`func (o *DtoPaymentGatewayConfigResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DtoPaymentGatewayConfigResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DtoPaymentGatewayConfigResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *DtoPaymentGatewayConfigResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIsActive

`func (o *DtoPaymentGatewayConfigResponse) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *DtoPaymentGatewayConfigResponse) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *DtoPaymentGatewayConfigResponse) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *DtoPaymentGatewayConfigResponse) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetLastTestedAt

`func (o *DtoPaymentGatewayConfigResponse) GetLastTestedAt() string`

GetLastTestedAt returns the LastTestedAt field if non-nil, zero value otherwise.

### GetLastTestedAtOk

`func (o *DtoPaymentGatewayConfigResponse) GetLastTestedAtOk() (*string, bool)`

GetLastTestedAtOk returns a tuple with the LastTestedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastTestedAt

`func (o *DtoPaymentGatewayConfigResponse) SetLastTestedAt(v string)`

SetLastTestedAt sets LastTestedAt field to given value.

### HasLastTestedAt

`func (o *DtoPaymentGatewayConfigResponse) HasLastTestedAt() bool`

HasLastTestedAt returns a boolean if a field has been set.

### GetNotifyUrl

`func (o *DtoPaymentGatewayConfigResponse) GetNotifyUrl() string`

GetNotifyUrl returns the NotifyUrl field if non-nil, zero value otherwise.

### GetNotifyUrlOk

`func (o *DtoPaymentGatewayConfigResponse) GetNotifyUrlOk() (*string, bool)`

GetNotifyUrlOk returns a tuple with the NotifyUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyUrl

`func (o *DtoPaymentGatewayConfigResponse) SetNotifyUrl(v string)`

SetNotifyUrl sets NotifyUrl field to given value.

### HasNotifyUrl

`func (o *DtoPaymentGatewayConfigResponse) HasNotifyUrl() bool`

HasNotifyUrl returns a boolean if a field has been set.

### GetPublicConfig

`func (o *DtoPaymentGatewayConfigResponse) GetPublicConfig() map[string]string`

GetPublicConfig returns the PublicConfig field if non-nil, zero value otherwise.

### GetPublicConfigOk

`func (o *DtoPaymentGatewayConfigResponse) GetPublicConfigOk() (*map[string]string, bool)`

GetPublicConfigOk returns a tuple with the PublicConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublicConfig

`func (o *DtoPaymentGatewayConfigResponse) SetPublicConfig(v map[string]string)`

SetPublicConfig sets PublicConfig field to given value.

### HasPublicConfig

`func (o *DtoPaymentGatewayConfigResponse) HasPublicConfig() bool`

HasPublicConfig returns a boolean if a field has been set.

### GetReturnUrl

`func (o *DtoPaymentGatewayConfigResponse) GetReturnUrl() string`

GetReturnUrl returns the ReturnUrl field if non-nil, zero value otherwise.

### GetReturnUrlOk

`func (o *DtoPaymentGatewayConfigResponse) GetReturnUrlOk() (*string, bool)`

GetReturnUrlOk returns a tuple with the ReturnUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnUrl

`func (o *DtoPaymentGatewayConfigResponse) SetReturnUrl(v string)`

SetReturnUrl sets ReturnUrl field to given value.

### HasReturnUrl

`func (o *DtoPaymentGatewayConfigResponse) HasReturnUrl() bool`

HasReturnUrl returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *DtoPaymentGatewayConfigResponse) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DtoPaymentGatewayConfigResponse) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DtoPaymentGatewayConfigResponse) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *DtoPaymentGatewayConfigResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


