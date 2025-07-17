# \AppBillingAPI

All URIs are relative to */v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BillingPost**](AppBillingAPI.md#BillingPost) | **Post** /billing | Create a new App Billing



## BillingPost

> DtoAppBillingResponse BillingPost(ctx).Billing(billing).Execute()

Create a new App Billing



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
	billing := *openapiclient.NewDtoCreateAppBillingRequest("EventName_example", "IdempotencyKey_example", map[string]interface{}{"key": interface{}(123)}, "Timestamp_example", "Type_example") // DtoCreateAppBillingRequest | Task details

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AppBillingAPI.BillingPost(context.Background()).Billing(billing).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AppBillingAPI.BillingPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BillingPost`: DtoAppBillingResponse
	fmt.Fprintf(os.Stdout, "Response from `AppBillingAPI.BillingPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBillingPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **billing** | [**DtoCreateAppBillingRequest**](DtoCreateAppBillingRequest.md) | Task details | 

### Return type

[**DtoAppBillingResponse**](DtoAppBillingResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

