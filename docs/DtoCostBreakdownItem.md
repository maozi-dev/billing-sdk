# DtoCostBreakdownItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cost** | Pointer to **float32** | Cost is the calculated cost for this meter | [optional] 
**MeterId** | Pointer to **string** | MeterID identifies the usage meter | [optional] 
**MeterName** | Pointer to **string** | MeterName is the display name of the meter | [optional] 
**Usage** | Pointer to **float32** | Usage is the quantity consumed | [optional] 

## Methods

### NewDtoCostBreakdownItem

`func NewDtoCostBreakdownItem() *DtoCostBreakdownItem`

NewDtoCostBreakdownItem instantiates a new DtoCostBreakdownItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtoCostBreakdownItemWithDefaults

`func NewDtoCostBreakdownItemWithDefaults() *DtoCostBreakdownItem`

NewDtoCostBreakdownItemWithDefaults instantiates a new DtoCostBreakdownItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCost

`func (o *DtoCostBreakdownItem) GetCost() float32`

GetCost returns the Cost field if non-nil, zero value otherwise.

### GetCostOk

`func (o *DtoCostBreakdownItem) GetCostOk() (*float32, bool)`

GetCostOk returns a tuple with the Cost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCost

`func (o *DtoCostBreakdownItem) SetCost(v float32)`

SetCost sets Cost field to given value.

### HasCost

`func (o *DtoCostBreakdownItem) HasCost() bool`

HasCost returns a boolean if a field has been set.

### GetMeterId

`func (o *DtoCostBreakdownItem) GetMeterId() string`

GetMeterId returns the MeterId field if non-nil, zero value otherwise.

### GetMeterIdOk

`func (o *DtoCostBreakdownItem) GetMeterIdOk() (*string, bool)`

GetMeterIdOk returns a tuple with the MeterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeterId

`func (o *DtoCostBreakdownItem) SetMeterId(v string)`

SetMeterId sets MeterId field to given value.

### HasMeterId

`func (o *DtoCostBreakdownItem) HasMeterId() bool`

HasMeterId returns a boolean if a field has been set.

### GetMeterName

`func (o *DtoCostBreakdownItem) GetMeterName() string`

GetMeterName returns the MeterName field if non-nil, zero value otherwise.

### GetMeterNameOk

`func (o *DtoCostBreakdownItem) GetMeterNameOk() (*string, bool)`

GetMeterNameOk returns a tuple with the MeterName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeterName

`func (o *DtoCostBreakdownItem) SetMeterName(v string)`

SetMeterName sets MeterName field to given value.

### HasMeterName

`func (o *DtoCostBreakdownItem) HasMeterName() bool`

HasMeterName returns a boolean if a field has been set.

### GetUsage

`func (o *DtoCostBreakdownItem) GetUsage() float32`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *DtoCostBreakdownItem) GetUsageOk() (*float32, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *DtoCostBreakdownItem) SetUsage(v float32)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *DtoCostBreakdownItem) HasUsage() bool`

HasUsage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


