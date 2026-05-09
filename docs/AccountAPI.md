# \AccountAPI

All URIs are relative to *https://api.relentlessidentity.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetRequestHistory**](AccountAPI.md#GetRequestHistory) | **Get** /client/history | Get paginated request history
[**GetTokenStatus**](AccountAPI.md#GetTokenStatus) | **Get** /client/token | Inspect the current bearer token
[**GetUsage**](AccountAPI.md#GetUsage) | **Get** /client/usage | Get current usage and limits



## GetRequestHistory

> ClientRequestHistoryPageResponse GetRequestHistory(ctx).Page(page).PageSize(pageSize).RequestType(requestType).State(state).Execute()

Get paginated request history



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "go.relentlessidentity.com/sdk"
)

func main() {
	page := int32(56) // int32 | Page number starting at 1. (optional) (default to 1)
	pageSize := int32(56) // int32 | Number of history rows per page. Maximum 25. (optional) (default to 25)
	requestType := "requestType_example" // string | Optional request-type filter. (optional)
	state := "state_example" // string | Optional deliverability-state filter. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountAPI.GetRequestHistory(context.Background()).Page(page).PageSize(pageSize).RequestType(requestType).State(state).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountAPI.GetRequestHistory``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRequestHistory`: ClientRequestHistoryPageResponse
	fmt.Fprintf(os.Stdout, "Response from `AccountAPI.GetRequestHistory`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetRequestHistoryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** | Page number starting at 1. | [default to 1]
 **pageSize** | **int32** | Number of history rows per page. Maximum 25. | [default to 25]
 **requestType** | **string** | Optional request-type filter. | 
 **state** | **string** | Optional deliverability-state filter. | 

### Return type

[**ClientRequestHistoryPageResponse**](ClientRequestHistoryPageResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetTokenStatus

> ClientTokenStatusResponse GetTokenStatus(ctx).Execute()

Inspect the current bearer token



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "go.relentlessidentity.com/sdk"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountAPI.GetTokenStatus(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountAPI.GetTokenStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetTokenStatus`: ClientTokenStatusResponse
	fmt.Fprintf(os.Stdout, "Response from `AccountAPI.GetTokenStatus`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetTokenStatusRequest struct via the builder pattern


### Return type

[**ClientTokenStatusResponse**](ClientTokenStatusResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUsage

> ClientUsageResponse GetUsage(ctx).Execute()

Get current usage and limits



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "go.relentlessidentity.com/sdk"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountAPI.GetUsage(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountAPI.GetUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUsage`: ClientUsageResponse
	fmt.Fprintf(os.Stdout, "Response from `AccountAPI.GetUsage`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetUsageRequest struct via the builder pattern


### Return type

[**ClientUsageResponse**](ClientUsageResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

