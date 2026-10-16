# \PaymentGatewaysAPI

All URIs are relative to */v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PaymentGatewaysGet**](PaymentGatewaysAPI.md#PaymentGatewaysGet) | **Get** /payment-gateways | List payment gateway configurations
[**PaymentGatewaysIdDelete**](PaymentGatewaysAPI.md#PaymentGatewaysIdDelete) | **Delete** /payment-gateways/{id} | Delete a payment gateway configuration
[**PaymentGatewaysIdGet**](PaymentGatewaysAPI.md#PaymentGatewaysIdGet) | **Get** /payment-gateways/{id} | Get a payment gateway configuration
[**PaymentGatewaysIdPut**](PaymentGatewaysAPI.md#PaymentGatewaysIdPut) | **Put** /payment-gateways/{id} | Update a payment gateway configuration
[**PaymentGatewaysIdTestPost**](PaymentGatewaysAPI.md#PaymentGatewaysIdTestPost) | **Post** /payment-gateways/{id}/test | Test a payment gateway configuration
[**PaymentGatewaysPost**](PaymentGatewaysAPI.md#PaymentGatewaysPost) | **Post** /payment-gateways | Create a payment gateway configuration



## PaymentGatewaysGet

> DtoListPaymentGatewayConfigsResponse PaymentGatewaysGet(ctx).Execute()

List payment gateway configurations



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PaymentGatewaysAPI.PaymentGatewaysGet(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PaymentGatewaysAPI.PaymentGatewaysGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PaymentGatewaysGet`: DtoListPaymentGatewayConfigsResponse
	fmt.Fprintf(os.Stdout, "Response from `PaymentGatewaysAPI.PaymentGatewaysGet`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiPaymentGatewaysGetRequest struct via the builder pattern


### Return type

[**DtoListPaymentGatewayConfigsResponse**](DtoListPaymentGatewayConfigsResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PaymentGatewaysIdDelete

> map[string]interface{} PaymentGatewaysIdDelete(ctx, id).Execute()

Delete a payment gateway configuration



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
	id := "id_example" // string | Gateway configuration ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PaymentGatewaysAPI.PaymentGatewaysIdDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PaymentGatewaysAPI.PaymentGatewaysIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PaymentGatewaysIdDelete`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `PaymentGatewaysAPI.PaymentGatewaysIdDelete`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Gateway configuration ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiPaymentGatewaysIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


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


## PaymentGatewaysIdGet

> DtoPaymentGatewayConfigResponse PaymentGatewaysIdGet(ctx, id).Execute()

Get a payment gateway configuration



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
	id := "id_example" // string | Gateway configuration ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PaymentGatewaysAPI.PaymentGatewaysIdGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PaymentGatewaysAPI.PaymentGatewaysIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PaymentGatewaysIdGet`: DtoPaymentGatewayConfigResponse
	fmt.Fprintf(os.Stdout, "Response from `PaymentGatewaysAPI.PaymentGatewaysIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Gateway configuration ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiPaymentGatewaysIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DtoPaymentGatewayConfigResponse**](DtoPaymentGatewayConfigResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PaymentGatewaysIdPut

> DtoPaymentGatewayConfigResponse PaymentGatewaysIdPut(ctx, id).Config(config).Execute()

Update a payment gateway configuration



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
	id := "id_example" // string | Gateway configuration ID
	config := *openapiclient.NewDtoUpdatePaymentGatewayConfigRequest() // DtoUpdatePaymentGatewayConfigRequest | Gateway configuration

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PaymentGatewaysAPI.PaymentGatewaysIdPut(context.Background(), id).Config(config).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PaymentGatewaysAPI.PaymentGatewaysIdPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PaymentGatewaysIdPut`: DtoPaymentGatewayConfigResponse
	fmt.Fprintf(os.Stdout, "Response from `PaymentGatewaysAPI.PaymentGatewaysIdPut`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Gateway configuration ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiPaymentGatewaysIdPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **config** | [**DtoUpdatePaymentGatewayConfigRequest**](DtoUpdatePaymentGatewayConfigRequest.md) | Gateway configuration | 

### Return type

[**DtoPaymentGatewayConfigResponse**](DtoPaymentGatewayConfigResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PaymentGatewaysIdTestPost

> DtoPaymentGatewayConfigResponse PaymentGatewaysIdTestPost(ctx, id).Execute()

Test a payment gateway configuration



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
	id := "id_example" // string | Gateway configuration ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PaymentGatewaysAPI.PaymentGatewaysIdTestPost(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PaymentGatewaysAPI.PaymentGatewaysIdTestPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PaymentGatewaysIdTestPost`: DtoPaymentGatewayConfigResponse
	fmt.Fprintf(os.Stdout, "Response from `PaymentGatewaysAPI.PaymentGatewaysIdTestPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Gateway configuration ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiPaymentGatewaysIdTestPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DtoPaymentGatewayConfigResponse**](DtoPaymentGatewayConfigResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PaymentGatewaysPost

> DtoPaymentGatewayConfigResponse PaymentGatewaysPost(ctx).Config(config).Execute()

Create a payment gateway configuration



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
	config := *openapiclient.NewDtoCreatePaymentGatewayConfigRequest(map[string]string{"key": "Inner_example"}, "DisplayName_example", "GatewayProvider_example") // DtoCreatePaymentGatewayConfigRequest | Gateway configuration

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PaymentGatewaysAPI.PaymentGatewaysPost(context.Background()).Config(config).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PaymentGatewaysAPI.PaymentGatewaysPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PaymentGatewaysPost`: DtoPaymentGatewayConfigResponse
	fmt.Fprintf(os.Stdout, "Response from `PaymentGatewaysAPI.PaymentGatewaysPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPaymentGatewaysPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **config** | [**DtoCreatePaymentGatewayConfigRequest**](DtoCreatePaymentGatewayConfigRequest.md) | Gateway configuration | 

### Return type

[**DtoPaymentGatewayConfigResponse**](DtoPaymentGatewayConfigResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

