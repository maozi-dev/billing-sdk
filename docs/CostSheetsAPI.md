# \CostSheetsAPI

All URIs are relative to */v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CostBreakdownSubscriptionIdGet**](CostSheetsAPI.md#CostBreakdownSubscriptionIdGet) | **Get** /cost/breakdown/{subscription_id} | Get cost breakdown
[**CostGet**](CostSheetsAPI.md#CostGet) | **Get** /cost | List cost sheets
[**CostIdDelete**](CostSheetsAPI.md#CostIdDelete) | **Delete** /cost/{id} | Delete a cost sheet
[**CostIdGet**](CostSheetsAPI.md#CostIdGet) | **Get** /cost/{id} | Get a cost sheet by ID
[**CostIdPut**](CostSheetsAPI.md#CostIdPut) | **Put** /cost/{id} | Update a cost sheet
[**CostPost**](CostSheetsAPI.md#CostPost) | **Post** /cost | Create a new cost sheet
[**CostRoiPost**](CostSheetsAPI.md#CostRoiPost) | **Post** /cost/roi | Calculate ROI for cost sheet



## CostBreakdownSubscriptionIdGet

> DtoCostBreakdownResponse CostBreakdownSubscriptionIdGet(ctx, subscriptionId).StartTime(startTime).EndTime(endTime).Execute()

Get cost breakdown



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
	subscriptionId := "subscriptionId_example" // string | Subscription ID
	startTime := "startTime_example" // string | Start time (RFC3339) (optional)
	endTime := "endTime_example" // string | End time (RFC3339) (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CostSheetsAPI.CostBreakdownSubscriptionIdGet(context.Background(), subscriptionId).StartTime(startTime).EndTime(endTime).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CostSheetsAPI.CostBreakdownSubscriptionIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CostBreakdownSubscriptionIdGet`: DtoCostBreakdownResponse
	fmt.Fprintf(os.Stdout, "Response from `CostSheetsAPI.CostBreakdownSubscriptionIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**subscriptionId** | **string** | Subscription ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCostBreakdownSubscriptionIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **startTime** | **string** | Start time (RFC3339) | 
 **endTime** | **string** | End time (RFC3339) | 

### Return type

[**DtoCostBreakdownResponse**](DtoCostBreakdownResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CostGet

> DtoListCostSheetsResponse CostGet(ctx).CostsheetIDs(costsheetIDs).EnvironmentID(environmentID).MeterIDs(meterIDs).PriceIDs(priceIDs).Status(status).TenantID(tenantID).Execute()

List cost sheets



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
	costsheetIDs := []string{"Inner_example"} // []string | CostsheetIDs allows filtering by specific costsheet IDs (optional)
	environmentID := "environmentID_example" // string | EnvironmentID filters by specific environment ID (optional)
	meterIDs := []string{"Inner_example"} // []string | MeterIDs filters by specific meter IDs (optional)
	priceIDs := []string{"Inner_example"} // []string | PriceIDs filters by specific price IDs (optional)
	status := "status_example" // string | Status filters by costsheet status (optional)
	tenantID := "tenantID_example" // string | TenantID filters by specific tenant ID (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CostSheetsAPI.CostGet(context.Background()).CostsheetIDs(costsheetIDs).EnvironmentID(environmentID).MeterIDs(meterIDs).PriceIDs(priceIDs).Status(status).TenantID(tenantID).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CostSheetsAPI.CostGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CostGet`: DtoListCostSheetsResponse
	fmt.Fprintf(os.Stdout, "Response from `CostSheetsAPI.CostGet`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCostGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **costsheetIDs** | **[]string** | CostsheetIDs allows filtering by specific costsheet IDs | 
 **environmentID** | **string** | EnvironmentID filters by specific environment ID | 
 **meterIDs** | **[]string** | MeterIDs filters by specific meter IDs | 
 **priceIDs** | **[]string** | PriceIDs filters by specific price IDs | 
 **status** | **string** | Status filters by costsheet status | 
 **tenantID** | **string** | TenantID filters by specific tenant ID | 

### Return type

[**DtoListCostSheetsResponse**](DtoListCostSheetsResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CostIdDelete

> CostIdDelete(ctx, id).Execute()

Delete a cost sheet



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
	id := "id_example" // string | Cost Sheet ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CostSheetsAPI.CostIdDelete(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CostSheetsAPI.CostIdDelete``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Cost Sheet ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCostIdDeleteRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

 (empty response body)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CostIdGet

> DtoCostSheetResponse CostIdGet(ctx, id).Execute()

Get a cost sheet by ID



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
	id := "id_example" // string | Cost Sheet ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CostSheetsAPI.CostIdGet(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CostSheetsAPI.CostIdGet``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CostIdGet`: DtoCostSheetResponse
	fmt.Fprintf(os.Stdout, "Response from `CostSheetsAPI.CostIdGet`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Cost Sheet ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCostIdGetRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**DtoCostSheetResponse**](DtoCostSheetResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CostIdPut

> DtoCostSheetResponse CostIdPut(ctx, id).Costsheet(costsheet).Execute()

Update a cost sheet



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
	id := "id_example" // string | Cost Sheet ID
	costsheet := *openapiclient.NewDtoUpdateCostSheetRequest("Id_example") // DtoUpdateCostSheetRequest | Cost sheet configuration

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CostSheetsAPI.CostIdPut(context.Background(), id).Costsheet(costsheet).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CostSheetsAPI.CostIdPut``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CostIdPut`: DtoCostSheetResponse
	fmt.Fprintf(os.Stdout, "Response from `CostSheetsAPI.CostIdPut`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** | Cost Sheet ID | 

### Other Parameters

Other parameters are passed through a pointer to a apiCostIdPutRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **costsheet** | [**DtoUpdateCostSheetRequest**](DtoUpdateCostSheetRequest.md) | Cost sheet configuration | 

### Return type

[**DtoCostSheetResponse**](DtoCostSheetResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CostPost

> DtoCostSheetResponse CostPost(ctx).Costsheet(costsheet).Execute()

Create a new cost sheet



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
	costsheet := *openapiclient.NewDtoCreateCostSheetRequest("MeterId_example", "PriceId_example") // DtoCreateCostSheetRequest | Cost sheet configuration

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CostSheetsAPI.CostPost(context.Background()).Costsheet(costsheet).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CostSheetsAPI.CostPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CostPost`: DtoCostSheetResponse
	fmt.Fprintf(os.Stdout, "Response from `CostSheetsAPI.CostPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCostPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **costsheet** | [**DtoCreateCostSheetRequest**](DtoCreateCostSheetRequest.md) | Cost sheet configuration | 

### Return type

[**DtoCostSheetResponse**](DtoCostSheetResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CostRoiPost

> DtoROIResponse CostRoiPost(ctx).Request(request).Execute()

Calculate ROI for cost sheet



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
	request := *openapiclient.NewDtoCalculateROIRequest("SubscriptionId_example") // DtoCalculateROIRequest | ROI calculation request

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CostSheetsAPI.CostRoiPost(context.Background()).Request(request).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CostSheetsAPI.CostRoiPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CostRoiPost`: DtoROIResponse
	fmt.Fprintf(os.Stdout, "Response from `CostSheetsAPI.CostRoiPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCostRoiPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **request** | [**DtoCalculateROIRequest**](DtoCalculateROIRequest.md) | ROI calculation request | 

### Return type

[**DtoROIResponse**](DtoROIResponse.md)

### Authorization

[ApiKeyAuth](../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

