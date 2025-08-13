# DtoCreateCostSheetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MeterId** | **string** | MeterID references the meter to track usage | 
**PriceId** | **string** | PriceID references the price configuration | 

## Methods

### NewDtoCreateCostSheetRequest

`func NewDtoCreateCostSheetRequest(meterId string, priceId string, ) *DtoCreateCostSheetRequest`

NewDtoCreateCostSheetRequest instantiates a new DtoCreateCostSheetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtoCreateCostSheetRequestWithDefaults

`func NewDtoCreateCostSheetRequestWithDefaults() *DtoCreateCostSheetRequest`

NewDtoCreateCostSheetRequestWithDefaults instantiates a new DtoCreateCostSheetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMeterId

`func (o *DtoCreateCostSheetRequest) GetMeterId() string`

GetMeterId returns the MeterId field if non-nil, zero value otherwise.

### GetMeterIdOk

`func (o *DtoCreateCostSheetRequest) GetMeterIdOk() (*string, bool)`

GetMeterIdOk returns a tuple with the MeterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeterId

`func (o *DtoCreateCostSheetRequest) SetMeterId(v string)`

SetMeterId sets MeterId field to given value.


### GetPriceId

`func (o *DtoCreateCostSheetRequest) GetPriceId() string`

GetPriceId returns the PriceId field if non-nil, zero value otherwise.

### GetPriceIdOk

`func (o *DtoCreateCostSheetRequest) GetPriceIdOk() (*string, bool)`

GetPriceIdOk returns a tuple with the PriceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPriceId

`func (o *DtoCreateCostSheetRequest) SetPriceId(v string)`

SetPriceId sets PriceId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


