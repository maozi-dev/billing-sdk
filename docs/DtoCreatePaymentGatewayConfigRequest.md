# DtoCreatePaymentGatewayConfigRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Credential** | **map[string]string** |  | 
**DisplayName** | **string** |  | 
**EnabledScenes** | Pointer to **[]string** |  | [optional] 
**GatewayProvider** | **string** |  | 
**IsActive** | Pointer to **bool** |  | [optional] 
**NotifyUrl** | Pointer to **string** |  | [optional] 
**ReturnUrl** | Pointer to **string** |  | [optional] 

## Methods

### NewDtoCreatePaymentGatewayConfigRequest

`func NewDtoCreatePaymentGatewayConfigRequest(credential map[string]string, displayName string, gatewayProvider string, ) *DtoCreatePaymentGatewayConfigRequest`

NewDtoCreatePaymentGatewayConfigRequest instantiates a new DtoCreatePaymentGatewayConfigRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtoCreatePaymentGatewayConfigRequestWithDefaults

`func NewDtoCreatePaymentGatewayConfigRequestWithDefaults() *DtoCreatePaymentGatewayConfigRequest`

NewDtoCreatePaymentGatewayConfigRequestWithDefaults instantiates a new DtoCreatePaymentGatewayConfigRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCredential

`func (o *DtoCreatePaymentGatewayConfigRequest) GetCredential() map[string]string`

GetCredential returns the Credential field if non-nil, zero value otherwise.

### GetCredentialOk

`func (o *DtoCreatePaymentGatewayConfigRequest) GetCredentialOk() (*map[string]string, bool)`

GetCredentialOk returns a tuple with the Credential field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredential

`func (o *DtoCreatePaymentGatewayConfigRequest) SetCredential(v map[string]string)`

SetCredential sets Credential field to given value.


### GetDisplayName

`func (o *DtoCreatePaymentGatewayConfigRequest) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *DtoCreatePaymentGatewayConfigRequest) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *DtoCreatePaymentGatewayConfigRequest) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.


### GetEnabledScenes

`func (o *DtoCreatePaymentGatewayConfigRequest) GetEnabledScenes() []string`

GetEnabledScenes returns the EnabledScenes field if non-nil, zero value otherwise.

### GetEnabledScenesOk

`func (o *DtoCreatePaymentGatewayConfigRequest) GetEnabledScenesOk() (*[]string, bool)`

GetEnabledScenesOk returns a tuple with the EnabledScenes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabledScenes

`func (o *DtoCreatePaymentGatewayConfigRequest) SetEnabledScenes(v []string)`

SetEnabledScenes sets EnabledScenes field to given value.

### HasEnabledScenes

`func (o *DtoCreatePaymentGatewayConfigRequest) HasEnabledScenes() bool`

HasEnabledScenes returns a boolean if a field has been set.

### GetGatewayProvider

`func (o *DtoCreatePaymentGatewayConfigRequest) GetGatewayProvider() string`

GetGatewayProvider returns the GatewayProvider field if non-nil, zero value otherwise.

### GetGatewayProviderOk

`func (o *DtoCreatePaymentGatewayConfigRequest) GetGatewayProviderOk() (*string, bool)`

GetGatewayProviderOk returns a tuple with the GatewayProvider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGatewayProvider

`func (o *DtoCreatePaymentGatewayConfigRequest) SetGatewayProvider(v string)`

SetGatewayProvider sets GatewayProvider field to given value.


### GetIsActive

`func (o *DtoCreatePaymentGatewayConfigRequest) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *DtoCreatePaymentGatewayConfigRequest) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *DtoCreatePaymentGatewayConfigRequest) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *DtoCreatePaymentGatewayConfigRequest) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetNotifyUrl

`func (o *DtoCreatePaymentGatewayConfigRequest) GetNotifyUrl() string`

GetNotifyUrl returns the NotifyUrl field if non-nil, zero value otherwise.

### GetNotifyUrlOk

`func (o *DtoCreatePaymentGatewayConfigRequest) GetNotifyUrlOk() (*string, bool)`

GetNotifyUrlOk returns a tuple with the NotifyUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifyUrl

`func (o *DtoCreatePaymentGatewayConfigRequest) SetNotifyUrl(v string)`

SetNotifyUrl sets NotifyUrl field to given value.

### HasNotifyUrl

`func (o *DtoCreatePaymentGatewayConfigRequest) HasNotifyUrl() bool`

HasNotifyUrl returns a boolean if a field has been set.

### GetReturnUrl

`func (o *DtoCreatePaymentGatewayConfigRequest) GetReturnUrl() string`

GetReturnUrl returns the ReturnUrl field if non-nil, zero value otherwise.

### GetReturnUrlOk

`func (o *DtoCreatePaymentGatewayConfigRequest) GetReturnUrlOk() (*string, bool)`

GetReturnUrlOk returns a tuple with the ReturnUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReturnUrl

`func (o *DtoCreatePaymentGatewayConfigRequest) SetReturnUrl(v string)`

SetReturnUrl sets ReturnUrl field to given value.

### HasReturnUrl

`func (o *DtoCreatePaymentGatewayConfigRequest) HasReturnUrl() bool`

HasReturnUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


