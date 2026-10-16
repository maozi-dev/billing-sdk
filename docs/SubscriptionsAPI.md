# \SubscriptionsAPI

All URIs are relative to */v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**SubscriptionsGet**](SubscriptionsAPI.md#SubscriptionsGet) | **Get** /subscriptions | List subscriptions
[**SubscriptionsIdCancelPost**](SubscriptionsAPI.md#SubscriptionsIdCancelPost) | **Post** /subscriptions/{id}/cancel | Cancel subscription
[**SubscriptionsIdGet**](SubscriptionsAPI.md#SubscriptionsIdGet) | **Get** /subscriptions/{id} | Get subscription
[**SubscriptionsPeriodUsagePost**](SubscriptionsAPI.md#SubscriptionsPeriodUsagePost) | **Post** /subscriptions/period/usage | Get usage by period
[**SubscriptionsPost**](SubscriptionsAPI.md#SubscriptionsPost) | **Post** /subscriptions | Create subscription
[**SubscriptionsUsagePost**](SubscriptionsAPI.md#SubscriptionsUsagePost) | **Post** /subscriptions/usage | Get usage by subscription



## SubscriptionsGet

> DtoListSubscriptionsResponse SubscriptionsGet(ctx).ActiveAt(activeAt).BillingCadence(billingCadence).BillingPeriod(billingPeriod).CustomerId(customerId).EndTime(endTime).Expand(expand).ExternalCustomerId(externalCustomerId).Limit(limit).Offset(offset).Order(order).PlanId(planId).Sort(sort).StartTime(startTime).Status(status).SubscriptionIds(subscriptionIds).SubscriptionStatus(subscriptionStatus).Execute()

List subscriptions



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/maozi-dev/billing-sdk/billing"
)

func main() {
	activeAt := "activeAt_example" // string | ActiveAt filters subscriptions that are active at the given time (optional)
	billingCadence := []string{"BillingCadence_example"} // []string | BillingCadence filters by billing cadence (optional)
	billingPeriod := []string{"BillingPeriod_example"} // []string | BillingPeriod filters by billing period (optional)
	customerId := "customerId_example" // string | CustomerID filters by customer ID (optional)
	endTime := "endTime_example" // string |  (optional)
	expand := "expand_example" // string |  (optional)
	externalCustomerId := "externalCustomerId_example" // string |  (optional)
	limit := int32(56) // int32 |  (optional)
	offset := int32(56) // int32 |  (optional)
	order := "order_example" // string |  (optional)
	planId := "planId_example" // string | PlanID filters by plan ID (optional)
	sort := "sort_example" // string |  (optional)
	startTime := "startTime_example" // string |  (optional)
	status := "status_example" // string |  (optional)
	subscriptionIds := []string{"Inner_example"} // []string |  (optional)
	subscriptionStatus := []string{"SubscriptionStatus_example"} // []string | SubscriptionStatus filters by subscription status (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionsAPI.SubscriptionsGet(context.Background()).ActiveAt(activeAt).BillingCadence(billingCadence).BillingPeriod(billingPeriod).CustomerId(customerId).EndTime(endTime).Expand(expand).ExternalCustomerId(externalCustomerId).Limit(limit).Offset(offset).Order(order).PlanId(planId).Sort(sort).StartTime(startTime).Status(status).SubscriptionIds(subscriptionIds).SubscriptionStatus(subscriptionStatus).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionsAPI.SubscriptionsGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubscriptionsGet`: DtoListSubscriptionsResponse
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionsAPI.SubscriptionsGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSubscriptionsGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **activeAt** | **string** | ActiveAt filters subscriptions that are active at the given time | 
 **billingCadence** | **[]string** | BillingCadence filters by billing cadence | 
 **billingPeriod** | **[]string** | BillingPeriod filters by billing period | 
 **customerId** | **string** | CustomerID filters by customer ID | 
 **endTime** | **string** |  | 
 **expand** | **string** |  | 
 **externalCustomerId** | **string** |  | 
 **limit** | **int32** |  | 
 **offset** | **int32** |  | 
 **order** | **string** |  | 
 **planId** | **string** | PlanID filters by plan ID | 
 **sort** | **string** |  | 
 **startTime** | **string** |  | 
 **status** | **string** |  | 
 **subscriptionIds** | **[]string** |  | 
 **subscriptionStatus** | **[]string** | SubscriptionStatus filters by subscription status | 

### Return type

[**DtoListSubscriptionsResponse**](DtoListSubscriptionsResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubscriptionsIdCancelPost

> map[string]interface{} SubscriptionsIdCancelPost(ctx, id).CancelAtPeriodEnd(cancelAtPeriodEnd).Execute()

Cancel subscription



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/maozi-dev/billing-sdk/billing"
)

func main() {
	id := "id_example" // string | Subscription ID
	cancelAtPeriodEnd := true // bool | Cancel at period end (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionsAPI.SubscriptionsIdCancelPost(context.Background(), id).CancelAtPeriodEnd(cancelAtPeriodEnd).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionsAPI.SubscriptionsIdCancelPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubscriptionsIdCancelPost`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionsAPI.SubscriptionsIdCancelPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Subscription ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiSubscriptionsIdCancelPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **cancelAtPeriodEnd** | **bool** | Cancel at period end | 

### Return type

**map[string]interface{}**

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubscriptionsIdGet

> DtoSubscriptionResponse SubscriptionsIdGet(ctx, id).Execute()

Get subscription



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/maozi-dev/billing-sdk/billing"
)

func main() {
	id := "id_example" // string | Subscription ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionsAPI.SubscriptionsIdGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionsAPI.SubscriptionsIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubscriptionsIdGet`: DtoSubscriptionResponse
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionsAPI.SubscriptionsIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Subscription ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiSubscriptionsIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DtoSubscriptionResponse**](DtoSubscriptionResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubscriptionsPeriodUsagePost

> []DtoPeriodUsageResponse SubscriptionsPeriodUsagePost(ctx).Request(request).Execute()

Get usage by period



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/maozi-dev/billing-sdk/billing"
)

func main() {
	request := *openapiclient.NewDtoGetUsageByPeriodRequest("123") // DtoGetUsageByPeriodRequest | Usage request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionsAPI.SubscriptionsPeriodUsagePost(context.Background()).Request(request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionsAPI.SubscriptionsPeriodUsagePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubscriptionsPeriodUsagePost`: []DtoPeriodUsageResponse
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionsAPI.SubscriptionsPeriodUsagePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSubscriptionsPeriodUsagePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**DtoGetUsageByPeriodRequest**](DtoGetUsageByPeriodRequest.md) | Usage request | 

### Return type

[**[]DtoPeriodUsageResponse**](DtoPeriodUsageResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubscriptionsPost

> DtoSubscriptionResponse SubscriptionsPost(ctx).Subscription(subscription).Execute()

Create subscription



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/maozi-dev/billing-sdk/billing"
)

func main() {
	subscription := *openapiclient.NewDtoCreateSubscriptionRequest(int32(123), "PlanId_example", "StartDate_example") // DtoCreateSubscriptionRequest | Subscription Request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionsAPI.SubscriptionsPost(context.Background()).Subscription(subscription).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionsAPI.SubscriptionsPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubscriptionsPost`: DtoSubscriptionResponse
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionsAPI.SubscriptionsPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSubscriptionsPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subscription** | [**DtoCreateSubscriptionRequest**](DtoCreateSubscriptionRequest.md) | Subscription Request | 

### Return type

[**DtoSubscriptionResponse**](DtoSubscriptionResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SubscriptionsUsagePost

> DtoGetUsageBySubscriptionResponse SubscriptionsUsagePost(ctx).Request(request).Execute()

Get usage by subscription



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/maozi-dev/billing-sdk/billing"
)

func main() {
	request := *openapiclient.NewDtoGetUsageBySubscriptionRequest("123") // DtoGetUsageBySubscriptionRequest | Usage request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SubscriptionsAPI.SubscriptionsUsagePost(context.Background()).Request(request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SubscriptionsAPI.SubscriptionsUsagePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SubscriptionsUsagePost`: DtoGetUsageBySubscriptionResponse
	fmt.Fprintf(os.Stdout, "Response from `SubscriptionsAPI.SubscriptionsUsagePost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSubscriptionsUsagePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**DtoGetUsageBySubscriptionRequest**](DtoGetUsageBySubscriptionRequest.md) | Usage request | 

### Return type

[**DtoGetUsageBySubscriptionResponse**](DtoGetUsageBySubscriptionResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

