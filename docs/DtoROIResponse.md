# DtoROIResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cost** | Pointer to **float32** | Cost and Revenue | [optional] 
**CostBreakdown** | Pointer to [**[]DtoCostBreakdownItem**](DtoCostBreakdownItem.md) | Cost breakdown by meter | [optional] 
**Markup** | Pointer to **float32** | Markup (Revenue - Cost / Cost) | [optional] 
**MarkupPercentage** | Pointer to **float32** |  | [optional] 
**NetMargin** | Pointer to **float32** | Net Margin (ROI) | [optional] 
**NetMarginPercentage** | Pointer to **float32** |  | [optional] 
**NetRevenue** | Pointer to **float32** | Net Revenue (Revenue - Cost) | [optional] 
**Revenue** | Pointer to **float32** |  | [optional] 

## Methods

### NewDtoROIResponse

`func NewDtoROIResponse() *DtoROIResponse`

NewDtoROIResponse instantiates a new DtoROIResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtoROIResponseWithDefaults

`func NewDtoROIResponseWithDefaults() *DtoROIResponse`

NewDtoROIResponseWithDefaults instantiates a new DtoROIResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCost

`func (o *DtoROIResponse) GetCost() float32`

GetCost returns the Cost field if non-nil, zero value otherwise.

### GetCostOk

`func (o *DtoROIResponse) GetCostOk() (*float32, bool)`

GetCostOk returns a tuple with the Cost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCost

`func (o *DtoROIResponse) SetCost(v float32)`

SetCost sets Cost field to given value.

### HasCost

`func (o *DtoROIResponse) HasCost() bool`

HasCost returns a boolean if a field has been set.

### GetCostBreakdown

`func (o *DtoROIResponse) GetCostBreakdown() []DtoCostBreakdownItem`

GetCostBreakdown returns the CostBreakdown field if non-nil, zero value otherwise.

### GetCostBreakdownOk

`func (o *DtoROIResponse) GetCostBreakdownOk() (*[]DtoCostBreakdownItem, bool)`

GetCostBreakdownOk returns a tuple with the CostBreakdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostBreakdown

`func (o *DtoROIResponse) SetCostBreakdown(v []DtoCostBreakdownItem)`

SetCostBreakdown sets CostBreakdown field to given value.

### HasCostBreakdown

`func (o *DtoROIResponse) HasCostBreakdown() bool`

HasCostBreakdown returns a boolean if a field has been set.

### GetMarkup

`func (o *DtoROIResponse) GetMarkup() float32`

GetMarkup returns the Markup field if non-nil, zero value otherwise.

### GetMarkupOk

`func (o *DtoROIResponse) GetMarkupOk() (*float32, bool)`

GetMarkupOk returns a tuple with the Markup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkup

`func (o *DtoROIResponse) SetMarkup(v float32)`

SetMarkup sets Markup field to given value.

### HasMarkup

`func (o *DtoROIResponse) HasMarkup() bool`

HasMarkup returns a boolean if a field has been set.

### GetMarkupPercentage

`func (o *DtoROIResponse) GetMarkupPercentage() float32`

GetMarkupPercentage returns the MarkupPercentage field if non-nil, zero value otherwise.

### GetMarkupPercentageOk

`func (o *DtoROIResponse) GetMarkupPercentageOk() (*float32, bool)`

GetMarkupPercentageOk returns a tuple with the MarkupPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkupPercentage

`func (o *DtoROIResponse) SetMarkupPercentage(v float32)`

SetMarkupPercentage sets MarkupPercentage field to given value.

### HasMarkupPercentage

`func (o *DtoROIResponse) HasMarkupPercentage() bool`

HasMarkupPercentage returns a boolean if a field has been set.

### GetNetMargin

`func (o *DtoROIResponse) GetNetMargin() float32`

GetNetMargin returns the NetMargin field if non-nil, zero value otherwise.

### GetNetMarginOk

`func (o *DtoROIResponse) GetNetMarginOk() (*float32, bool)`

GetNetMarginOk returns a tuple with the NetMargin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetMargin

`func (o *DtoROIResponse) SetNetMargin(v float32)`

SetNetMargin sets NetMargin field to given value.

### HasNetMargin

`func (o *DtoROIResponse) HasNetMargin() bool`

HasNetMargin returns a boolean if a field has been set.

### GetNetMarginPercentage

`func (o *DtoROIResponse) GetNetMarginPercentage() float32`

GetNetMarginPercentage returns the NetMarginPercentage field if non-nil, zero value otherwise.

### GetNetMarginPercentageOk

`func (o *DtoROIResponse) GetNetMarginPercentageOk() (*float32, bool)`

GetNetMarginPercentageOk returns a tuple with the NetMarginPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetMarginPercentage

`func (o *DtoROIResponse) SetNetMarginPercentage(v float32)`

SetNetMarginPercentage sets NetMarginPercentage field to given value.

### HasNetMarginPercentage

`func (o *DtoROIResponse) HasNetMarginPercentage() bool`

HasNetMarginPercentage returns a boolean if a field has been set.

### GetNetRevenue

`func (o *DtoROIResponse) GetNetRevenue() float32`

GetNetRevenue returns the NetRevenue field if non-nil, zero value otherwise.

### GetNetRevenueOk

`func (o *DtoROIResponse) GetNetRevenueOk() (*float32, bool)`

GetNetRevenueOk returns a tuple with the NetRevenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetRevenue

`func (o *DtoROIResponse) SetNetRevenue(v float32)`

SetNetRevenue sets NetRevenue field to given value.

### HasNetRevenue

`func (o *DtoROIResponse) HasNetRevenue() bool`

HasNetRevenue returns a boolean if a field has been set.

### GetRevenue

`func (o *DtoROIResponse) GetRevenue() float32`

GetRevenue returns the Revenue field if non-nil, zero value otherwise.

### GetRevenueOk

`func (o *DtoROIResponse) GetRevenueOk() (*float32, bool)`

GetRevenueOk returns a tuple with the Revenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevenue

`func (o *DtoROIResponse) SetRevenue(v float32)`

SetRevenue sets Revenue field to given value.

### HasRevenue

`func (o *DtoROIResponse) HasRevenue() bool`

HasRevenue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


