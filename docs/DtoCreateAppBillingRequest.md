# DtoCreateAppBillingRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | Pointer to **float32** |  | [optional] 
**CustomerId** | Pointer to **string** |  | [optional] 
**EventName** | **string** | 需要统计的事件 | 
**IdempotencyKey** | **string** |  | 
**Metadata** | Pointer to **map[string]string** |  | [optional] 
**Properties** | **map[string]interface{}** |  | 
**ReferenceId** | Pointer to **string** |  | [optional] 
**ReferenceType** | Pointer to [**TypesBillingTxReferenceType**](TypesBillingTxReferenceType.md) |  | [optional] 
**Timestamp** | **string** |  | 
**Type** | **string** |  | 

## Methods

### NewDtoCreateAppBillingRequest

`func NewDtoCreateAppBillingRequest(eventName string, idempotencyKey string, properties map[string]interface{}, timestamp string, type_ string, ) *DtoCreateAppBillingRequest`

NewDtoCreateAppBillingRequest instantiates a new DtoCreateAppBillingRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtoCreateAppBillingRequestWithDefaults

`func NewDtoCreateAppBillingRequestWithDefaults() *DtoCreateAppBillingRequest`

NewDtoCreateAppBillingRequestWithDefaults instantiates a new DtoCreateAppBillingRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmount

`func (o *DtoCreateAppBillingRequest) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *DtoCreateAppBillingRequest) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *DtoCreateAppBillingRequest) SetAmount(v float32)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *DtoCreateAppBillingRequest) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetCustomerId

`func (o *DtoCreateAppBillingRequest) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *DtoCreateAppBillingRequest) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *DtoCreateAppBillingRequest) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *DtoCreateAppBillingRequest) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetEventName

`func (o *DtoCreateAppBillingRequest) GetEventName() string`

GetEventName returns the EventName field if non-nil, zero value otherwise.

### GetEventNameOk

`func (o *DtoCreateAppBillingRequest) GetEventNameOk() (*string, bool)`

GetEventNameOk returns a tuple with the EventName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEventName

`func (o *DtoCreateAppBillingRequest) SetEventName(v string)`

SetEventName sets EventName field to given value.


### GetIdempotencyKey

`func (o *DtoCreateAppBillingRequest) GetIdempotencyKey() string`

GetIdempotencyKey returns the IdempotencyKey field if non-nil, zero value otherwise.

### GetIdempotencyKeyOk

`func (o *DtoCreateAppBillingRequest) GetIdempotencyKeyOk() (*string, bool)`

GetIdempotencyKeyOk returns a tuple with the IdempotencyKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdempotencyKey

`func (o *DtoCreateAppBillingRequest) SetIdempotencyKey(v string)`

SetIdempotencyKey sets IdempotencyKey field to given value.


### GetMetadata

`func (o *DtoCreateAppBillingRequest) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DtoCreateAppBillingRequest) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DtoCreateAppBillingRequest) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *DtoCreateAppBillingRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetProperties

`func (o *DtoCreateAppBillingRequest) GetProperties() map[string]interface{}`

GetProperties returns the Properties field if non-nil, zero value otherwise.

### GetPropertiesOk

`func (o *DtoCreateAppBillingRequest) GetPropertiesOk() (*map[string]interface{}, bool)`

GetPropertiesOk returns a tuple with the Properties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperties

`func (o *DtoCreateAppBillingRequest) SetProperties(v map[string]interface{})`

SetProperties sets Properties field to given value.


### GetReferenceId

`func (o *DtoCreateAppBillingRequest) GetReferenceId() string`

GetReferenceId returns the ReferenceId field if non-nil, zero value otherwise.

### GetReferenceIdOk

`func (o *DtoCreateAppBillingRequest) GetReferenceIdOk() (*string, bool)`

GetReferenceIdOk returns a tuple with the ReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceId

`func (o *DtoCreateAppBillingRequest) SetReferenceId(v string)`

SetReferenceId sets ReferenceId field to given value.

### HasReferenceId

`func (o *DtoCreateAppBillingRequest) HasReferenceId() bool`

HasReferenceId returns a boolean if a field has been set.

### GetReferenceType

`func (o *DtoCreateAppBillingRequest) GetReferenceType() TypesBillingTxReferenceType`

GetReferenceType returns the ReferenceType field if non-nil, zero value otherwise.

### GetReferenceTypeOk

`func (o *DtoCreateAppBillingRequest) GetReferenceTypeOk() (*TypesBillingTxReferenceType, bool)`

GetReferenceTypeOk returns a tuple with the ReferenceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceType

`func (o *DtoCreateAppBillingRequest) SetReferenceType(v TypesBillingTxReferenceType)`

SetReferenceType sets ReferenceType field to given value.

### HasReferenceType

`func (o *DtoCreateAppBillingRequest) HasReferenceType() bool`

HasReferenceType returns a boolean if a field has been set.

### GetTimestamp

`func (o *DtoCreateAppBillingRequest) GetTimestamp() string`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *DtoCreateAppBillingRequest) GetTimestampOk() (*string, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *DtoCreateAppBillingRequest) SetTimestamp(v string)`

SetTimestamp sets Timestamp field to given value.


### GetType

`func (o *DtoCreateAppBillingRequest) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *DtoCreateAppBillingRequest) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *DtoCreateAppBillingRequest) SetType(v string)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


