# DtoCreateSubscriptionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BillingCycle** | Pointer to [**TypesBillingCycle**](TypesBillingCycle.md) |  | [optional] 
**BillingPeriodCount** | **int32** | BillingCadence     types.BillingCadence &#x60;json:\&quot;billing_cadence\&quot; validate:\&quot;required\&quot;&#x60; BillingPeriod      types.BillingPeriod  &#x60;json:\&quot;billing_period\&quot; validate:\&quot;required\&quot;&#x60; | 
**CommitmentAmount** | Pointer to **float32** | Credit grants to be applied when subscription is created CreditGrants []CreateCreditGrantRequest &#x60;json:\&quot;credit_grants,omitempty\&quot;&#x60; CommitmentAmount is the minimum amount a customer commits to paying for a billing period | [optional] 
**CustomerId** | Pointer to **string** | customer_id is the flexprice customer id and it is prioritized over external_customer_id in case both are provided. | [optional] 
**EndDate** | Pointer to **string** |  | [optional] 
**ExternalCustomerId** | Pointer to **string** | external_customer_id is the customer id in your DB and must be same as what you provided as external_id while creating the customer in flexprice. | [optional] 
**LookupKey** | Pointer to **string** | Currency           string               &#x60;json:\&quot;currency\&quot; validate:\&quot;required,len&#x3D;3\&quot;&#x60; | [optional] 
**Metadata** | Pointer to **map[string]string** |  | [optional] 
**OverageFactor** | Pointer to **float32** | OverageFactor is a multiplier applied to usage beyond the commitment amount | [optional] 
**PlanId** | **string** |  | 
**StartDate** | **string** |  | 
**TrialEnd** | Pointer to **string** |  | [optional] 
**TrialStart** | Pointer to **string** |  | [optional] 

## Methods

### NewDtoCreateSubscriptionRequest

`func NewDtoCreateSubscriptionRequest(billingPeriodCount int32, planId string, startDate string, ) *DtoCreateSubscriptionRequest`

NewDtoCreateSubscriptionRequest instantiates a new DtoCreateSubscriptionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtoCreateSubscriptionRequestWithDefaults

`func NewDtoCreateSubscriptionRequestWithDefaults() *DtoCreateSubscriptionRequest`

NewDtoCreateSubscriptionRequestWithDefaults instantiates a new DtoCreateSubscriptionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBillingCycle

`func (o *DtoCreateSubscriptionRequest) GetBillingCycle() TypesBillingCycle`

GetBillingCycle returns the BillingCycle field if non-nil, zero value otherwise.

### GetBillingCycleOk

`func (o *DtoCreateSubscriptionRequest) GetBillingCycleOk() (*TypesBillingCycle, bool)`

GetBillingCycleOk returns a tuple with the BillingCycle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingCycle

`func (o *DtoCreateSubscriptionRequest) SetBillingCycle(v TypesBillingCycle)`

SetBillingCycle sets BillingCycle field to given value.

### HasBillingCycle

`func (o *DtoCreateSubscriptionRequest) HasBillingCycle() bool`

HasBillingCycle returns a boolean if a field has been set.

### GetBillingPeriodCount

`func (o *DtoCreateSubscriptionRequest) GetBillingPeriodCount() int32`

GetBillingPeriodCount returns the BillingPeriodCount field if non-nil, zero value otherwise.

### GetBillingPeriodCountOk

`func (o *DtoCreateSubscriptionRequest) GetBillingPeriodCountOk() (*int32, bool)`

GetBillingPeriodCountOk returns a tuple with the BillingPeriodCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingPeriodCount

`func (o *DtoCreateSubscriptionRequest) SetBillingPeriodCount(v int32)`

SetBillingPeriodCount sets BillingPeriodCount field to given value.


### GetCommitmentAmount

`func (o *DtoCreateSubscriptionRequest) GetCommitmentAmount() float32`

GetCommitmentAmount returns the CommitmentAmount field if non-nil, zero value otherwise.

### GetCommitmentAmountOk

`func (o *DtoCreateSubscriptionRequest) GetCommitmentAmountOk() (*float32, bool)`

GetCommitmentAmountOk returns a tuple with the CommitmentAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommitmentAmount

`func (o *DtoCreateSubscriptionRequest) SetCommitmentAmount(v float32)`

SetCommitmentAmount sets CommitmentAmount field to given value.

### HasCommitmentAmount

`func (o *DtoCreateSubscriptionRequest) HasCommitmentAmount() bool`

HasCommitmentAmount returns a boolean if a field has been set.

### GetCustomerId

`func (o *DtoCreateSubscriptionRequest) GetCustomerId() string`

GetCustomerId returns the CustomerId field if non-nil, zero value otherwise.

### GetCustomerIdOk

`func (o *DtoCreateSubscriptionRequest) GetCustomerIdOk() (*string, bool)`

GetCustomerIdOk returns a tuple with the CustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerId

`func (o *DtoCreateSubscriptionRequest) SetCustomerId(v string)`

SetCustomerId sets CustomerId field to given value.

### HasCustomerId

`func (o *DtoCreateSubscriptionRequest) HasCustomerId() bool`

HasCustomerId returns a boolean if a field has been set.

### GetEndDate

`func (o *DtoCreateSubscriptionRequest) GetEndDate() string`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *DtoCreateSubscriptionRequest) GetEndDateOk() (*string, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *DtoCreateSubscriptionRequest) SetEndDate(v string)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *DtoCreateSubscriptionRequest) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.

### GetExternalCustomerId

`func (o *DtoCreateSubscriptionRequest) GetExternalCustomerId() string`

GetExternalCustomerId returns the ExternalCustomerId field if non-nil, zero value otherwise.

### GetExternalCustomerIdOk

`func (o *DtoCreateSubscriptionRequest) GetExternalCustomerIdOk() (*string, bool)`

GetExternalCustomerIdOk returns a tuple with the ExternalCustomerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalCustomerId

`func (o *DtoCreateSubscriptionRequest) SetExternalCustomerId(v string)`

SetExternalCustomerId sets ExternalCustomerId field to given value.

### HasExternalCustomerId

`func (o *DtoCreateSubscriptionRequest) HasExternalCustomerId() bool`

HasExternalCustomerId returns a boolean if a field has been set.

### GetLookupKey

`func (o *DtoCreateSubscriptionRequest) GetLookupKey() string`

GetLookupKey returns the LookupKey field if non-nil, zero value otherwise.

### GetLookupKeyOk

`func (o *DtoCreateSubscriptionRequest) GetLookupKeyOk() (*string, bool)`

GetLookupKeyOk returns a tuple with the LookupKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLookupKey

`func (o *DtoCreateSubscriptionRequest) SetLookupKey(v string)`

SetLookupKey sets LookupKey field to given value.

### HasLookupKey

`func (o *DtoCreateSubscriptionRequest) HasLookupKey() bool`

HasLookupKey returns a boolean if a field has been set.

### GetMetadata

`func (o *DtoCreateSubscriptionRequest) GetMetadata() map[string]string`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *DtoCreateSubscriptionRequest) GetMetadataOk() (*map[string]string, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *DtoCreateSubscriptionRequest) SetMetadata(v map[string]string)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *DtoCreateSubscriptionRequest) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetOverageFactor

`func (o *DtoCreateSubscriptionRequest) GetOverageFactor() float32`

GetOverageFactor returns the OverageFactor field if non-nil, zero value otherwise.

### GetOverageFactorOk

`func (o *DtoCreateSubscriptionRequest) GetOverageFactorOk() (*float32, bool)`

GetOverageFactorOk returns a tuple with the OverageFactor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverageFactor

`func (o *DtoCreateSubscriptionRequest) SetOverageFactor(v float32)`

SetOverageFactor sets OverageFactor field to given value.

### HasOverageFactor

`func (o *DtoCreateSubscriptionRequest) HasOverageFactor() bool`

HasOverageFactor returns a boolean if a field has been set.

### GetPlanId

`func (o *DtoCreateSubscriptionRequest) GetPlanId() string`

GetPlanId returns the PlanId field if non-nil, zero value otherwise.

### GetPlanIdOk

`func (o *DtoCreateSubscriptionRequest) GetPlanIdOk() (*string, bool)`

GetPlanIdOk returns a tuple with the PlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanId

`func (o *DtoCreateSubscriptionRequest) SetPlanId(v string)`

SetPlanId sets PlanId field to given value.


### GetStartDate

`func (o *DtoCreateSubscriptionRequest) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *DtoCreateSubscriptionRequest) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *DtoCreateSubscriptionRequest) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.


### GetTrialEnd

`func (o *DtoCreateSubscriptionRequest) GetTrialEnd() string`

GetTrialEnd returns the TrialEnd field if non-nil, zero value otherwise.

### GetTrialEndOk

`func (o *DtoCreateSubscriptionRequest) GetTrialEndOk() (*string, bool)`

GetTrialEndOk returns a tuple with the TrialEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialEnd

`func (o *DtoCreateSubscriptionRequest) SetTrialEnd(v string)`

SetTrialEnd sets TrialEnd field to given value.

### HasTrialEnd

`func (o *DtoCreateSubscriptionRequest) HasTrialEnd() bool`

HasTrialEnd returns a boolean if a field has been set.

### GetTrialStart

`func (o *DtoCreateSubscriptionRequest) GetTrialStart() string`

GetTrialStart returns the TrialStart field if non-nil, zero value otherwise.

### GetTrialStartOk

`func (o *DtoCreateSubscriptionRequest) GetTrialStartOk() (*string, bool)`

GetTrialStartOk returns a tuple with the TrialStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialStart

`func (o *DtoCreateSubscriptionRequest) SetTrialStart(v string)`

SetTrialStart sets TrialStart field to given value.

### HasTrialStart

`func (o *DtoCreateSubscriptionRequest) HasTrialStart() bool`

HasTrialStart returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


