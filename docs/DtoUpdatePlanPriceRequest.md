# DtoUpdatePlanPriceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | Pointer to **string** |  | [optional] 
**BillingModel** | [**TypesBillingModel**](TypesBillingModel.md) |  | 
**Description** | Pointer to **string** |  | [optional] 
**FilterValues** | Pointer to **map[string][]string** |  | [optional] 
**Id** | Pointer to **string** | The ID of the price to update (present if the price is being updated) | [optional] 
**LookupKey** | Pointer to **string** |  | [optional] 
**Metadata** | Pointer to **map[string]string** |  | [optional] 
**MeterId** | Pointer to **string** |  | [optional] 
**PaymentCadence** | [**TypesPaymentCadence**](TypesPaymentCadence.md) |  | 
**PlanId** | Pointer to **string** |  | [optional] 
**TierMode** | Pointer to [**TypesBillingTier**](TypesBillingTier.md) |  | [optional] 
**Tiers** | Pointer to [**[]DtoCreatePriceTier**](DtoCreatePriceTier.md) |  | [optional] 
**TransformQuantity** | Pointer to [**PriceTransformQuantity**](PriceTransformQuantity.md) |  | [optional] 
**TrialPeriod** | Pointer to **int32** |  | [optional] 
**Type** | [**TypesPriceType**](TypesPriceType.md) |  | 

## Methods

### NewDtoUpdatePlanPriceRequest

`func NewDtoUpdatePlanPriceRequest(billingModel TypesBillingModel, paymentCadence TypesPaymentCadence, type_ TypesPriceType, ) *DtoUpdatePlanPriceRequest`

NewDtoUpdatePlanPriceRequest instantiates a new DtoUpdatePlanPriceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtoUpdatePlanPriceRequestWithDefaults

`func NewDtoUpdatePlanPriceRequestWithDefaults() *DtoUpdatePlanPriceRequest`

NewDtoUpdatePlanPriceRequestWithDefaults instantiates a new DtoUpdatePlanPriceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmount

`func (o *DtoUpdatePlanPriceRequest) GetAmount() string`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *DtoUpdatePlanPriceRequest) GetAmountOk() (*string, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *DtoUpdatePlanPriceRequest) SetAmount(v string)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *DtoUpdatePlanPriceRequest) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetBillingModel

`func (o *DtoUpdatePlanPriceRequest) GetBillingModel() TypesBillingModel`

GetBillingModel returns the BillingModel field if non-nil, zero value otherwise.

### GetBillingModelOk

`func (o *DtoUpdatePlanPriceRequest) GetBillingModelOk() (*TypesBillingModel, bool)`

GetBillingModelOk returns a tuple with the BillingModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingModel

`func (o *DtoUpdatePlanPriceRequest) SetBillingModel(v TypesBillingModel)`

SetBillingModel sets BillingModel field to given value.


### GetDescription

`func (o *DtoUpdatePlanPriceRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *DtoUpdatePlanPriceRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *DtoUpdatePlanPriceRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *DtoUpdatePlanPriceRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetFilterValues

`func (o *DtoUpdatePlanPriceRequest) GetFilterValues() map[string][]string`

GetFilterValues returns the FilterValues field if non-nil, zero value otherwise.

### GetFilterValuesOk

`func (o *DtoUpdatePlanPriceRequest) GetFilterValuesOk() (*map[string][]string, bool)`

GetFilterValuesOk returns a tuple with the FilterValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterValues

`func (o *DtoUpdatePlanPriceRequest) SetFilterValues(v map[string][]string)`

SetFilterValues sets FilterValues field to given value.

### HasFilterValues

`func (o *DtoUpdatePlanPriceRequest) HasFilterValues() bool`

HasFilterValues returns a boolean if a field has been set.

### GetId

`func (o *DtoUpdatePlanPriceRequest) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DtoUpdatePlanPriceRequest) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DtoUpdatePlanPriceRequest) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *DtoUpdatePlanPriceRequest) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLookupKey

`func (o *DtoUpdatePlanPriceRequest) GetLookupKey() string`

GetLookupKey returns the LookupKey field if non-nil, zero value otherwise.

### GetLookupKeyOk

`func (o *DtoUpdatePlanPriceRequest) GetLookupKeyOk() (*string, bool)`

GetLookupKeyOk returns a tuple with the LookupKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLookupKey

`func (o *DtoUpdatePlanPriceRequest) SetLookupKey(v string)`

SetLookupKey sets LookupKey field to given value.

### HasLookupKey

`func (o *DtoUpdatePlanPriceRequest) HasLookupKey() bool`

HasLookupKey returns a boolean if a field has been set.

### GetMetadata

`func (o *DtoUpdatePlanPriceRequest) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DtoUpdatePlanPriceRequest) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DtoUpdatePlanPriceRequest) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *DtoUpdatePlanPriceRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetMeterId

`func (o *DtoUpdatePlanPriceRequest) GetMeterId() string`

GetMeterId returns the MeterId field if non-nil, zero value otherwise.

### GetMeterIdOk

`func (o *DtoUpdatePlanPriceRequest) GetMeterIdOk() (*string, bool)`

GetMeterIdOk returns a tuple with the MeterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeterId

`func (o *DtoUpdatePlanPriceRequest) SetMeterId(v string)`

SetMeterId sets MeterId field to given value.

### HasMeterId

`func (o *DtoUpdatePlanPriceRequest) HasMeterId() bool`

HasMeterId returns a boolean if a field has been set.

### GetPaymentCadence

`func (o *DtoUpdatePlanPriceRequest) GetPaymentCadence() TypesPaymentCadence`

GetPaymentCadence returns the PaymentCadence field if non-nil, zero value otherwise.

### GetPaymentCadenceOk

`func (o *DtoUpdatePlanPriceRequest) GetPaymentCadenceOk() (*TypesPaymentCadence, bool)`

GetPaymentCadenceOk returns a tuple with the PaymentCadence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentCadence

`func (o *DtoUpdatePlanPriceRequest) SetPaymentCadence(v TypesPaymentCadence)`

SetPaymentCadence sets PaymentCadence field to given value.


### GetPlanId

`func (o *DtoUpdatePlanPriceRequest) GetPlanId() string`

GetPlanId returns the PlanId field if non-nil, zero value otherwise.

### GetPlanIdOk

`func (o *DtoUpdatePlanPriceRequest) GetPlanIdOk() (*string, bool)`

GetPlanIdOk returns a tuple with the PlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanId

`func (o *DtoUpdatePlanPriceRequest) SetPlanId(v string)`

SetPlanId sets PlanId field to given value.

### HasPlanId

`func (o *DtoUpdatePlanPriceRequest) HasPlanId() bool`

HasPlanId returns a boolean if a field has been set.

### GetTierMode

`func (o *DtoUpdatePlanPriceRequest) GetTierMode() TypesBillingTier`

GetTierMode returns the TierMode field if non-nil, zero value otherwise.

### GetTierModeOk

`func (o *DtoUpdatePlanPriceRequest) GetTierModeOk() (*TypesBillingTier, bool)`

GetTierModeOk returns a tuple with the TierMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTierMode

`func (o *DtoUpdatePlanPriceRequest) SetTierMode(v TypesBillingTier)`

SetTierMode sets TierMode field to given value.

### HasTierMode

`func (o *DtoUpdatePlanPriceRequest) HasTierMode() bool`

HasTierMode returns a boolean if a field has been set.

### GetTiers

`func (o *DtoUpdatePlanPriceRequest) GetTiers() []DtoCreatePriceTier`

GetTiers returns the Tiers field if non-nil, zero value otherwise.

### GetTiersOk

`func (o *DtoUpdatePlanPriceRequest) GetTiersOk() (*[]DtoCreatePriceTier, bool)`

GetTiersOk returns a tuple with the Tiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTiers

`func (o *DtoUpdatePlanPriceRequest) SetTiers(v []DtoCreatePriceTier)`

SetTiers sets Tiers field to given value.

### HasTiers

`func (o *DtoUpdatePlanPriceRequest) HasTiers() bool`

HasTiers returns a boolean if a field has been set.

### GetTransformQuantity

`func (o *DtoUpdatePlanPriceRequest) GetTransformQuantity() PriceTransformQuantity`

GetTransformQuantity returns the TransformQuantity field if non-nil, zero value otherwise.

### GetTransformQuantityOk

`func (o *DtoUpdatePlanPriceRequest) GetTransformQuantityOk() (*PriceTransformQuantity, bool)`

GetTransformQuantityOk returns a tuple with the TransformQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransformQuantity

`func (o *DtoUpdatePlanPriceRequest) SetTransformQuantity(v PriceTransformQuantity)`

SetTransformQuantity sets TransformQuantity field to given value.

### HasTransformQuantity

`func (o *DtoUpdatePlanPriceRequest) HasTransformQuantity() bool`

HasTransformQuantity returns a boolean if a field has been set.

### GetTrialPeriod

`func (o *DtoUpdatePlanPriceRequest) GetTrialPeriod() int32`

GetTrialPeriod returns the TrialPeriod field if non-nil, zero value otherwise.

### GetTrialPeriodOk

`func (o *DtoUpdatePlanPriceRequest) GetTrialPeriodOk() (*int32, bool)`

GetTrialPeriodOk returns a tuple with the TrialPeriod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialPeriod

`func (o *DtoUpdatePlanPriceRequest) SetTrialPeriod(v int32)`

SetTrialPeriod sets TrialPeriod field to given value.

### HasTrialPeriod

`func (o *DtoUpdatePlanPriceRequest) HasTrialPeriod() bool`

HasTrialPeriod returns a boolean if a field has been set.

### GetType

`func (o *DtoUpdatePlanPriceRequest) GetType() TypesPriceType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *DtoUpdatePlanPriceRequest) GetTypeOk() (*TypesPriceType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *DtoUpdatePlanPriceRequest) SetType(v TypesPriceType)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


