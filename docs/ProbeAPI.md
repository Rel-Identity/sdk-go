# \ProbeAPI

All URIs are relative to *https://api.relentlessidentity.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ProbeBatch**](ProbeAPI.md#ProbeBatch) | **Post** /client/probe/batch | Verify many email addresses
[**ProbeEmail**](ProbeAPI.md#ProbeEmail) | **Post** /client/probe | Verify an email address



## ProbeBatch

> ClientBatchIdentityResponse ProbeBatch(ctx).ProbeBatchRequest(probeBatchRequest).Execute()

Verify many email addresses



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
	probeBatchRequest := *openapiclient.NewProbeBatchRequest([]string{"Emails_example"}) // ProbeBatchRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProbeAPI.ProbeBatch(context.Background()).ProbeBatchRequest(probeBatchRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProbeAPI.ProbeBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProbeBatch`: ClientBatchIdentityResponse
	fmt.Fprintf(os.Stdout, "Response from `ProbeAPI.ProbeBatch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProbeBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **probeBatchRequest** | [**ProbeBatchRequest**](ProbeBatchRequest.md) |  | 

### Return type

[**ClientBatchIdentityResponse**](ClientBatchIdentityResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ProbeEmail

> ClientIdentityResponse ProbeEmail(ctx).ProbeRequest(probeRequest).Execute()

Verify an email address



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
	probeRequest := *openapiclient.NewProbeRequest("jane.doe@acme.com") // ProbeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProbeAPI.ProbeEmail(context.Background()).ProbeRequest(probeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProbeAPI.ProbeEmail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ProbeEmail`: ClientIdentityResponse
	fmt.Fprintf(os.Stdout, "Response from `ProbeAPI.ProbeEmail`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiProbeEmailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **probeRequest** | [**ProbeRequest**](ProbeRequest.md) |  | 

### Return type

[**ClientIdentityResponse**](ClientIdentityResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

