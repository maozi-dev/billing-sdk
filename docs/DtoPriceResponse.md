# DtoPriceResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Amount** | Pointer to **float32** | Amount stored in main currency units (e.g., dollars, not cents) For USD: 12.50 means $12.50 | [optional] 
**BillingModel** | Pointer to [**TypesBillingModel**](TypesBillingModel.md) |  | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] 
**CreatedBy** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** | Description of the price | [optional] 
**EnvironmentId** | Pointer to **string** | EnvironmentID is the environment identifier for the price | [optional] 
**Id** | Pointer to **string** | ID uuid identifier for the price | [optional] 
**LookupKey** | Pointer to **string** | LookupKey used for looking up the price in the database | [optional] 
**Metadata** | Pointer to **map[string]string** |  | [optional] 
**Meter** | Pointer to [**DtoMeterResponse**](DtoMeterResponse.md) |  | [optional] 
**MeterId** | Pointer to **string** | MeterID is the id of the meter for usage based pricing | [optional] 
**PaymentCadence** | Pointer to [**TypesPaymentCadence**](TypesPaymentCadence.md) |  | [optional] 
**PlanId** | Pointer to **string** | PlanID is the id of the plan for plan based pricing | [optional] 
**Status** | Pointer to [**TypesStatus**](TypesStatus.md) |  | [optional] 
**TenantId** | Pointer to **string** |  | [optional] 
**TierMode** | Pointer to [**TypesBillingTier**](TypesBillingTier.md) |  | [optional] 
**Tiers** | Pointer to [**[]PricePriceTier**](PricePriceTier.md) |  | [optional] 
**TransformQuantity** | Pointer to [**PriceJSONBTransformQuantity**](PriceJSONBTransformQuantity.md) |  | [optional] 
**Type** | Pointer to [**TypesPriceType**](TypesPriceType.md) |  | [optional] 
**UpdatedAt** | Pointer to **string** |  | [optional] 
**UpdatedBy** | Pointer to **string** |  | [optional] 

## Methods

### NewDtoPriceResponse

`func NewDtoPriceResponse() *DtoPriceResponse`

NewDtoPriceResponse instantiates a new DtoPriceResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtoPriceResponseWithDefaults

`func NewDtoPriceResponseWithDefaults() *DtoPriceResponse`

NewDtoPriceResponseWithDefaults instantiates a new DtoPriceResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAmount

`func (o *DtoPriceResponse) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *DtoPriceResponse) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *DtoPriceResponse) SetAmount(v float32)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *DtoPriceResponse) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetBillingModel

`func (o *DtoPriceResponse) GetBillingModel() TypesBillingModel`

GetBillingModel returns the BillingModel field if non-nil, zero value otherwise.

### GetBillingModelOk

`func (o *DtoPriceResponse) GetBillingModelOk() (*TypesBillingModel, bool)`

GetBillingModelOk returns a tuple with the BillingModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingModel

`func (o *DtoPriceResponse) SetBillingModel(v TypesBillingModel)`

SetBillingModel sets BillingModel field to given value.

### HasBillingModel

`func (o *DtoPriceResponse) HasBillingModel() bool`

HasBillingModel returns a boolean if a field has been set.

### GetCreatedAt

`func (o *DtoPriceResponse) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DtoPriceResponse) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DtoPriceResponse) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *DtoPriceResponse) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetCreatedBy

`func (o *DtoPriceResponse) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *DtoPriceResponse) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *DtoPriceResponse) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *DtoPriceResponse) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetDescription

`func (o *DtoPriceResponse) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *DtoPriceResponse) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *DtoPriceResponse) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *DtoPriceResponse) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEnvironmentId

`func (o *DtoPriceResponse) GetEnvironmentId() string`

GetEnvironmentId returns the EnvironmentId field if non-nil, zero value otherwise.

### GetEnvironmentIdOk

`func (o *DtoPriceResponse) GetEnvironmentIdOk() (*string, bool)`

GetEnvironmentIdOk returns a tuple with the EnvironmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnvironmentId

`func (o *DtoPriceResponse) SetEnvironmentId(v string)`

SetEnvironmentId sets EnvironmentId field to given value.

### HasEnvironmentId

`func (o *DtoPriceResponse) HasEnvironmentId() bool`

HasEnvironmentId returns a boolean if a field has been set.

### GetId

`func (o *DtoPriceResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DtoPriceResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DtoPriceResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *DtoPriceResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLookupKey

`func (o *DtoPriceResponse) GetLookupKey() string`

GetLookupKey returns the LookupKey field if non-nil, zero value otherwise.

### GetLookupKeyOk

`func (o *DtoPriceResponse) GetLookupKeyOk() (*string, bool)`

GetLookupKeyOk returns a tuple with the LookupKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLookupKey

`func (o *DtoPriceResponse) SetLookupKey(v string)`

SetLookupKey sets LookupKey field to given value.

### HasLookupKey

`func (o *DtoPriceResponse) HasLookupKey() bool`

HasLookupKey returns a boolean if a field has been set.

### GetMetadata

`func (o *DtoPriceResponse) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DtoPriceResponse) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DtoPriceResponse) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *DtoPriceResponse) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetMeter

`func (o *DtoPriceResponse) GetMeter() DtoMeterResponse`

GetMeter returns the Meter field if non-nil, zero value otherwise.

### GetMeterOk

`func (o *DtoPriceResponse) GetMeterOk() (*DtoMeterResponse, bool)`

GetMeterOk returns a tuple with the Meter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeter

`func (o *DtoPriceResponse) SetMeter(v DtoMeterResponse)`

SetMeter sets Meter field to given value.

### HasMeter

`func (o *DtoPriceResponse) HasMeter() bool`

HasMeter returns a boolean if a field has been set.

### GetMeterId

`func (o *DtoPriceResponse) GetMeterId() string`

GetMeterId returns the MeterId field if non-nil, zero value otherwise.

### GetMeterIdOk

`func (o *DtoPriceResponse) GetMeterIdOk() (*string, bool)`

GetMeterIdOk returns a tuple with the MeterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeterId

`func (o *DtoPriceResponse) SetMeterId(v string)`

SetMeterId sets MeterId field to given value.

### HasMeterId

`func (o *DtoPriceResponse) HasMeterId() bool`

HasMeterId returns a boolean if a field has been set.

### GetPaymentCadence

`func (o *DtoPriceResponse) GetPaymentCadence() TypesPaymentCadence`

GetPaymentCadence returns the PaymentCadence field if non-nil, zero value otherwise.

### GetPaymentCadenceOk

`func (o *DtoPriceResponse) GetPaymentCadenceOk() (*TypesPaymentCadence, bool)`

GetPaymentCadenceOk returns a tuple with the PaymentCadence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentCadence

`func (o *DtoPriceResponse) SetPaymentCadence(v TypesPaymentCadence)`

SetPaymentCadence sets PaymentCadence field to given value.

### HasPaymentCadence

`func (o *DtoPriceResponse) HasPaymentCadence() bool`

HasPaymentCadence returns a boolean if a field has been set.

### GetPlanId

`func (o *DtoPriceResponse) GetPlanId() string`

GetPlanId returns the PlanId field if non-nil, zero value otherwise.

### GetPlanIdOk

`func (o *DtoPriceResponse) GetPlanIdOk() (*string, bool)`

GetPlanIdOk returns a tuple with the PlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanId

`func (o *DtoPriceResponse) SetPlanId(v string)`

SetPlanId sets PlanId field to given value.

### HasPlanId

`func (o *DtoPriceResponse) HasPlanId() bool`

HasPlanId returns a boolean if a field has been set.

### GetStatus

`func (o *DtoPriceResponse) GetStatus() TypesStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DtoPriceResponse) GetStatusOk() (*TypesStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DtoPriceResponse) SetStatus(v TypesStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *DtoPriceResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTenantId

`func (o *DtoPriceResponse) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *DtoPriceResponse) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *DtoPriceResponse) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *DtoPriceResponse) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### GetTierMode

`func (o *DtoPriceResponse) GetTierMode() TypesBillingTier`

GetTierMode returns the TierMode field if non-nil, zero value otherwise.

### GetTierModeOk

`func (o *DtoPriceResponse) GetTierModeOk() (*TypesBillingTier, bool)`

GetTierModeOk returns a tuple with the TierMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTierMode

`func (o *DtoPriceResponse) SetTierMode(v TypesBillingTier)`

SetTierMode sets TierMode field to given value.

### HasTierMode

`func (o *DtoPriceResponse) HasTierMode() bool`

HasTierMode returns a boolean if a field has been set.

### GetTiers

`func (o *DtoPriceResponse) GetTiers() []PricePriceTier`

GetTiers returns the Tiers field if non-nil, zero value otherwise.

### GetTiersOk

`func (o *DtoPriceResponse) GetTiersOk() (*[]PricePriceTier, bool)`

GetTiersOk returns a tuple with the Tiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTiers

`func (o *DtoPriceResponse) SetTiers(v []PricePriceTier)`

SetTiers sets Tiers field to given value.

### HasTiers

`func (o *DtoPriceResponse) HasTiers() bool`

HasTiers returns a boolean if a field has been set.

### GetTransformQuantity

`func (o *DtoPriceResponse) GetTransformQuantity() PriceJSONBTransformQuantity`

GetTransformQuantity returns the TransformQuantity field if non-nil, zero value otherwise.

### GetTransformQuantityOk

`func (o *DtoPriceResponse) GetTransformQuantityOk() (*PriceJSONBTransformQuantity, bool)`

GetTransformQuantityOk returns a tuple with the TransformQuantity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransformQuantity

`func (o *DtoPriceResponse) SetTransformQuantity(v PriceJSONBTransformQuantity)`

SetTransformQuantity sets TransformQuantity field to given value.

### HasTransformQuantity

`func (o *DtoPriceResponse) HasTransformQuantity() bool`

HasTransformQuantity returns a boolean if a field has been set.

### GetType

`func (o *DtoPriceResponse) GetType() TypesPriceType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *DtoPriceResponse) GetTypeOk() (*TypesPriceType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *DtoPriceResponse) SetType(v TypesPriceType)`

SetType sets Type field to given value.

### HasType

`func (o *DtoPriceResponse) HasType() bool`

HasType returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *DtoPriceResponse) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *DtoPriceResponse) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *DtoPriceResponse) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *DtoPriceResponse) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetUpdatedBy

`func (o *DtoPriceResponse) GetUpdatedBy() string`

GetUpdatedBy returns the UpdatedBy field if non-nil, zero value otherwise.

### GetUpdatedByOk

`func (o *DtoPriceResponse) GetUpdatedByOk() (*string, bool)`

GetUpdatedByOk returns a tuple with the UpdatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBy

`func (o *DtoPriceResponse) SetUpdatedBy(v string)`

SetUpdatedBy sets UpdatedBy field to given value.

### HasUpdatedBy

`func (o *DtoPriceResponse) HasUpdatedBy() bool`

HasUpdatedBy returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


