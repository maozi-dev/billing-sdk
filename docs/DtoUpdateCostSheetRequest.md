# DtoUpdateCostSheetRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | ID of the costsheet to update | 
**Status** | Pointer to **string** | Status updates the costsheet&#39;s status (optional) | [optional] 

## Methods

### NewDtoUpdateCostSheetRequest

`func NewDtoUpdateCostSheetRequest(id string, ) *DtoUpdateCostSheetRequest`

NewDtoUpdateCostSheetRequest instantiates a new DtoUpdateCostSheetRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtoUpdateCostSheetRequestWithDefaults

`func NewDtoUpdateCostSheetRequestWithDefaults() *DtoUpdateCostSheetRequest`

NewDtoUpdateCostSheetRequestWithDefaults instantiates a new DtoUpdateCostSheetRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DtoUpdateCostSheetRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DtoUpdateCostSheetRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DtoUpdateCostSheetRequest) SetId(v string)`

SetId sets Id field to given value.


### GetStatus

`func (o *DtoUpdateCostSheetRequest) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DtoUpdateCostSheetRequest) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DtoUpdateCostSheetRequest) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *DtoUpdateCostSheetRequest) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


