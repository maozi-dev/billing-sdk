# DtoCostBreakdownResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | Pointer to [**[]DtoCostBreakdownItem**](DtoCostBreakdownItem.md) | Items contains the breakdown by meter | [optional] 
**TotalCost** | Pointer to **float32** | TotalCost is the sum of all meter costs | [optional] 

## Methods

### NewDtoCostBreakdownResponse

`func NewDtoCostBreakdownResponse() *DtoCostBreakdownResponse`

NewDtoCostBreakdownResponse instantiates a new DtoCostBreakdownResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtoCostBreakdownResponseWithDefaults

`func NewDtoCostBreakdownResponseWithDefaults() *DtoCostBreakdownResponse`

NewDtoCostBreakdownResponseWithDefaults instantiates a new DtoCostBreakdownResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *DtoCostBreakdownResponse) GetItems() []DtoCostBreakdownItem`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *DtoCostBreakdownResponse) GetItemsOk() (*[]DtoCostBreakdownItem, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *DtoCostBreakdownResponse) SetItems(v []DtoCostBreakdownItem)`

SetItems sets Items field to given value.

### HasItems

`func (o *DtoCostBreakdownResponse) HasItems() bool`

HasItems returns a boolean if a field has been set.

### GetTotalCost

`func (o *DtoCostBreakdownResponse) GetTotalCost() float32`

GetTotalCost returns the TotalCost field if non-nil, zero value otherwise.

### GetTotalCostOk

`func (o *DtoCostBreakdownResponse) GetTotalCostOk() (*float32, bool)`

GetTotalCostOk returns a tuple with the TotalCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCost

`func (o *DtoCostBreakdownResponse) SetTotalCost(v float32)`

SetTotalCost sets TotalCost field to given value.

### HasTotalCost

`func (o *DtoCostBreakdownResponse) HasTotalCost() bool`

HasTotalCost returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


