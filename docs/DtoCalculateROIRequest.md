# DtoCalculateROIRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MeterId** | Pointer to **string** | MeterID references the meter to track usage | [optional] 
**PeriodEnd** | Pointer to **string** |  | [optional] 
**PeriodStart** | Pointer to **string** | Optional time range. If not provided, uses entire subscription period | [optional] 
**PriceId** | Pointer to **string** | PriceID references the price configuration | [optional] 
**SubscriptionId** | **string** | SubscriptionID is required to get subscription details | 

## Methods

### NewDtoCalculateROIRequest

`func NewDtoCalculateROIRequest(subscriptionId string, ) *DtoCalculateROIRequest`

NewDtoCalculateROIRequest instantiates a new DtoCalculateROIRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtoCalculateROIRequestWithDefaults

`func NewDtoCalculateROIRequestWithDefaults() *DtoCalculateROIRequest`

NewDtoCalculateROIRequestWithDefaults instantiates a new DtoCalculateROIRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMeterId

`func (o *DtoCalculateROIRequest) GetMeterId() string`

GetMeterId returns the MeterId field if non-nil, zero value otherwise.

### GetMeterIdOk

`func (o *DtoCalculateROIRequest) GetMeterIdOk() (*string, bool)`

GetMeterIdOk returns a tuple with the MeterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeterId

`func (o *DtoCalculateROIRequest) SetMeterId(v string)`

SetMeterId sets MeterId field to given value.

### HasMeterId

`func (o *DtoCalculateROIRequest) HasMeterId() bool`

HasMeterId returns a boolean if a field has been set.

### GetPeriodEnd

`func (o *DtoCalculateROIRequest) GetPeriodEnd() string`

GetPeriodEnd returns the PeriodEnd field if non-nil, zero value otherwise.

### GetPeriodEndOk

`func (o *DtoCalculateROIRequest) GetPeriodEndOk() (*string, bool)`

GetPeriodEndOk returns a tuple with the PeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodEnd

`func (o *DtoCalculateROIRequest) SetPeriodEnd(v string)`

SetPeriodEnd sets PeriodEnd field to given value.

### HasPeriodEnd

`func (o *DtoCalculateROIRequest) HasPeriodEnd() bool`

HasPeriodEnd returns a boolean if a field has been set.

### GetPeriodStart

`func (o *DtoCalculateROIRequest) GetPeriodStart() string`

GetPeriodStart returns the PeriodStart field if non-nil, zero value otherwise.

### GetPeriodStartOk

`func (o *DtoCalculateROIRequest) GetPeriodStartOk() (*string, bool)`

GetPeriodStartOk returns a tuple with the PeriodStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodStart

`func (o *DtoCalculateROIRequest) SetPeriodStart(v string)`

SetPeriodStart sets PeriodStart field to given value.

### HasPeriodStart

`func (o *DtoCalculateROIRequest) HasPeriodStart() bool`

HasPeriodStart returns a boolean if a field has been set.

### GetPriceId

`func (o *DtoCalculateROIRequest) GetPriceId() string`

GetPriceId returns the PriceId field if non-nil, zero value otherwise.

### GetPriceIdOk

`func (o *DtoCalculateROIRequest) GetPriceIdOk() (*string, bool)`

GetPriceIdOk returns a tuple with the PriceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceId

`func (o *DtoCalculateROIRequest) SetPriceId(v string)`

SetPriceId sets PriceId field to given value.

### HasPriceId

`func (o *DtoCalculateROIRequest) HasPriceId() bool`

HasPriceId returns a boolean if a field has been set.

### GetSubscriptionId

`func (o *DtoCalculateROIRequest) GetSubscriptionId() string`

GetSubscriptionId returns the SubscriptionId field if non-nil, zero value otherwise.

### GetSubscriptionIdOk

`func (o *DtoCalculateROIRequest) GetSubscriptionIdOk() (*string, bool)`

GetSubscriptionIdOk returns a tuple with the SubscriptionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubscriptionId

`func (o *DtoCalculateROIRequest) SetSubscriptionId(v string)`

SetSubscriptionId sets SubscriptionId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


