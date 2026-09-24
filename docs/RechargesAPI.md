# \RechargesAPI

All URIs are relative to */v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PaymentGatewaysCallbackGatewayPost**](RechargesAPI.md#PaymentGatewaysCallbackGatewayPost) | **Post** /payment-gateways/callback/{gateway} | Payment gateway async callback
[**RechargesGet**](RechargesAPI.md#RechargesGet) | **Get** /recharges | List recharges
[**RechargesIdGet**](RechargesAPI.md#RechargesIdGet) | **Get** /recharges/{id} | Get a recharge
[**RechargesIdProcessPost**](RechargesAPI.md#RechargesIdProcessPost) | **Post** /recharges/{id}/process | Process a recharge
[**RechargesIdQueryPost**](RechargesAPI.md#RechargesIdQueryPost) | **Post** /recharges/{id}/query | Query and settle a recharge
[**RechargesPost**](RechargesAPI.md#RechargesPost) | **Post** /recharges | Create a wallet recharge



## PaymentGatewaysCallbackGatewayPost

> string PaymentGatewaysCallbackGatewayPost(ctx, gateway).Execute()

Payment gateway async callback



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
	gateway := "gateway_example" // string | Gateway type (e.g. xunhupay)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RechargesAPI.PaymentGatewaysCallbackGatewayPost(context.Background(), gateway).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RechargesAPI.PaymentGatewaysCallbackGatewayPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PaymentGatewaysCallbackGatewayPost`: string
	fmt.Fprintf(os.Stdout, "Response from `RechargesAPI.PaymentGatewaysCallbackGatewayPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**gateway** | **string** | Gateway type (e.g. xunhupay) | 

### Other Parameters

Other parameters are passed through a pointer to a apiPaymentGatewaysCallbackGatewayPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RechargesGet

> DtoListRechargesResponse RechargesGet(ctx).WalletId(walletId).PaymentStatus(paymentStatus).Gateway(gateway).Limit(limit).Offset(offset).Execute()

List recharges



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
	walletId := "walletId_example" // string | Filter by wallet ID (optional)
	paymentStatus := "paymentStatus_example" // string | Filter by recharge status (optional)
	gateway := "gateway_example" // string | Filter by gateway (optional)
	limit := int32(56) // int32 | Limit (optional)
	offset := int32(56) // int32 | Offset (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RechargesAPI.RechargesGet(context.Background()).WalletId(walletId).PaymentStatus(paymentStatus).Gateway(gateway).Limit(limit).Offset(offset).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RechargesAPI.RechargesGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RechargesGet`: DtoListRechargesResponse
	fmt.Fprintf(os.Stdout, "Response from `RechargesAPI.RechargesGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRechargesGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **walletId** | **string** | Filter by wallet ID | 
 **paymentStatus** | **string** | Filter by recharge status | 
 **gateway** | **string** | Filter by gateway | 
 **limit** | **int32** | Limit | 
 **offset** | **int32** | Offset | 

### Return type

[**DtoListRechargesResponse**](DtoListRechargesResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RechargesIdGet

> DtoRechargeResponse RechargesIdGet(ctx, id).Execute()

Get a recharge



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
	id := "id_example" // string | Recharge ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RechargesAPI.RechargesIdGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RechargesAPI.RechargesIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RechargesIdGet`: DtoRechargeResponse
	fmt.Fprintf(os.Stdout, "Response from `RechargesAPI.RechargesIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Recharge ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiRechargesIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DtoRechargeResponse**](DtoRechargeResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RechargesIdProcessPost

> DtoRechargeResponse RechargesIdProcessPost(ctx, id).Execute()

Process a recharge



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
	id := "id_example" // string | Recharge ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RechargesAPI.RechargesIdProcessPost(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RechargesAPI.RechargesIdProcessPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RechargesIdProcessPost`: DtoRechargeResponse
	fmt.Fprintf(os.Stdout, "Response from `RechargesAPI.RechargesIdProcessPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Recharge ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiRechargesIdProcessPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DtoRechargeResponse**](DtoRechargeResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RechargesIdQueryPost

> DtoRechargeResponse RechargesIdQueryPost(ctx, id).Execute()

Query and settle a recharge



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
	id := "id_example" // string | Recharge ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RechargesAPI.RechargesIdQueryPost(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RechargesAPI.RechargesIdQueryPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RechargesIdQueryPost`: DtoRechargeResponse
	fmt.Fprintf(os.Stdout, "Response from `RechargesAPI.RechargesIdQueryPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Recharge ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiRechargesIdQueryPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DtoRechargeResponse**](DtoRechargeResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RechargesPost

> DtoRechargeResponse RechargesPost(ctx).Recharge(recharge).Execute()

Create a wallet recharge



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
	recharge := *openapiclient.NewDtoCreateRechargeRequest("Amount_example", "Gateway_example", "WalletId_example") // DtoCreateRechargeRequest | Recharge request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RechargesAPI.RechargesPost(context.Background()).Recharge(recharge).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RechargesAPI.RechargesPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RechargesPost`: DtoRechargeResponse
	fmt.Fprintf(os.Stdout, "Response from `RechargesAPI.RechargesPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRechargesPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **recharge** | [**DtoCreateRechargeRequest**](DtoCreateRechargeRequest.md) | Recharge request | 

### Return type

[**DtoRechargeResponse**](DtoRechargeResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

