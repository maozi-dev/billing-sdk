# DtoCreatePaymentRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | **float32** |  | 
**Currency** | **string** |  | 
**CustomerId** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**DestinationId** | **string** |  | 
**DestinationType** | [**TypesPaymentDestinationType**](TypesPaymentDestinationType.md) |  | 
**IdempotencyKey** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to **map[string]string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**PaymentMethodId** | Pointer to **string** |  | [optional] 
**PaymentMethodType** | [**TypesPaymentMethodType**](TypesPaymentMethodType.md) |  | 
**ProcessPayment** | Pointer to **bool** |  | [optional] [default to true]
**RecordedAt** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 

## Methods

### NewDtoCreatePaymentRequest

`func NewDtoCreatePaymentRequest(amount float32, currency string, destinationId string, destinationType TypesPaymentDestinationType, paymentMethodType TypesPaymentMethodType, ) *DtoCreatePaymentRequest`

NewDtoCreatePaymentRequest instantiates a new DtoCreatePaymentRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtoCreatePaymentRequestWithDefaults

`func NewDtoCreatePaymentRequestWithDefaults() *DtoCreatePaymentRequest`

NewDtoCreatePaymentRequestWithDefaults instantiates a new DtoCreatePaymentRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmount

`func (o *DtoCreatePaymentRequest) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *DtoCreatePaymentRequest) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *DtoCreatePaymentRequest) SetAmount(v float32)`

SetAmount sets Amount field to given value.


### GetCurrency

`func (o *DtoCreatePaymentRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *DtoCreatePaymentRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *DtoCreatePaymentRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetCustomerId

`func (o *DtoCreatePaymentRequest) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *DtoCreatePaymentRequest) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *DtoCreatePaymentRequest) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *DtoCreatePaymentRequest) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetDescription

`func (o *DtoCreatePaymentRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *DtoCreatePaymentRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *DtoCreatePaymentRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *DtoCreatePaymentRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDestinationId

`func (o *DtoCreatePaymentRequest) GetDestinationId() string`

GetDestinationId returns the DestinationId field if non-nil, zero value otherwise.

### GetDestinationIdOk

`func (o *DtoCreatePaymentRequest) GetDestinationIdOk() (*string, bool)`

GetDestinationIdOk returns a tuple with the DestinationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationId

`func (o *DtoCreatePaymentRequest) SetDestinationId(v string)`

SetDestinationId sets DestinationId field to given value.


### GetDestinationType

`func (o *DtoCreatePaymentRequest) GetDestinationType() TypesPaymentDestinationType`

GetDestinationType returns the DestinationType field if non-nil, zero value otherwise.

### GetDestinationTypeOk

`func (o *DtoCreatePaymentRequest) GetDestinationTypeOk() (*TypesPaymentDestinationType, bool)`

GetDestinationTypeOk returns a tuple with the DestinationType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestinationType

`func (o *DtoCreatePaymentRequest) SetDestinationType(v TypesPaymentDestinationType)`

SetDestinationType sets DestinationType field to given value.


### GetIdempotencyKey

`func (o *DtoCreatePaymentRequest) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *DtoCreatePaymentRequest) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *DtoCreatePaymentRequest) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.

### HasIdempotencyKey

`func (o *DtoCreatePaymentRequest) HasIdempotencyKey() bool`

HasIdempotencyKey returns a boolean if a field has been set.

### GetMetadata

`func (o *DtoCreatePaymentRequest) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DtoCreatePaymentRequest) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DtoCreatePaymentRequest) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *DtoCreatePaymentRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetName

`func (o *DtoCreatePaymentRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DtoCreatePaymentRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DtoCreatePaymentRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *DtoCreatePaymentRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetPaymentMethodId

`func (o *DtoCreatePaymentRequest) GetPaymentMethodId() string`

GetPaymentMethodId returns the PaymentMethodId field if non-nil, zero value otherwise.

### GetPaymentMethodIdOk

`func (o *DtoCreatePaymentRequest) GetPaymentMethodIdOk() (*string, bool)`

GetPaymentMethodIdOk returns a tuple with the PaymentMethodId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentMethodId

`func (o *DtoCreatePaymentRequest) SetPaymentMethodId(v string)`

SetPaymentMethodId sets PaymentMethodId field to given value.

### HasPaymentMethodId

`func (o *DtoCreatePaymentRequest) HasPaymentMethodId() bool`

HasPaymentMethodId returns a boolean if a field has been set.

### GetPaymentMethodType

`func (o *DtoCreatePaymentRequest) GetPaymentMethodType() TypesPaymentMethodType`

GetPaymentMethodType returns the PaymentMethodType field if non-nil, zero value otherwise.

### GetPaymentMethodTypeOk

`func (o *DtoCreatePaymentRequest) GetPaymentMethodTypeOk() (*TypesPaymentMethodType, bool)`

GetPaymentMethodTypeOk returns a tuple with the PaymentMethodType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentMethodType

`func (o *DtoCreatePaymentRequest) SetPaymentMethodType(v TypesPaymentMethodType)`

SetPaymentMethodType sets PaymentMethodType field to given value.


### GetProcessPayment

`func (o *DtoCreatePaymentRequest) GetProcessPayment() bool`

GetProcessPayment returns the ProcessPayment field if non-nil, zero value otherwise.

### GetProcessPaymentOk

`func (o *DtoCreatePaymentRequest) GetProcessPaymentOk() (*bool, bool)`

GetProcessPaymentOk returns a tuple with the ProcessPayment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessPayment

`func (o *DtoCreatePaymentRequest) SetProcessPayment(v bool)`

SetProcessPayment sets ProcessPayment field to given value.

### HasProcessPayment

`func (o *DtoCreatePaymentRequest) HasProcessPayment() bool`

HasProcessPayment returns a boolean if a field has been set.

### GetRecordedAt

`func (o *DtoCreatePaymentRequest) GetRecordedAt() string`

GetRecordedAt returns the RecordedAt field if non-nil, zero value otherwise.

### GetRecordedAtOk

`func (o *DtoCreatePaymentRequest) GetRecordedAtOk() (*string, bool)`

GetRecordedAtOk returns a tuple with the RecordedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecordedAt

`func (o *DtoCreatePaymentRequest) SetRecordedAt(v string)`

SetRecordedAt sets RecordedAt field to given value.

### HasRecordedAt

`func (o *DtoCreatePaymentRequest) HasRecordedAt() bool`

HasRecordedAt returns a boolean if a field has been set.

### GetType

`func (o *DtoCreatePaymentRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *DtoCreatePaymentRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *DtoCreatePaymentRequest) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *DtoCreatePaymentRequest) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


