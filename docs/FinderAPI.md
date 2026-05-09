# \FinderAPI

All URIs are relative to *https://api.relentlessidentity.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**FinderAttempt**](FinderAPI.md#FinderAttempt) | **Post** /client/attempt | Find a work email



## FinderAttempt

> ClientFinderResponse FinderAttempt(ctx).FinderRequest(finderRequest).Execute()

Find a work email



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
	finderRequest := *openapiclient.NewFinderRequest("Jane Doe", "acme.com") // FinderRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FinderAPI.FinderAttempt(context.Background()).FinderRequest(finderRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FinderAPI.FinderAttempt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FinderAttempt`: ClientFinderResponse
	fmt.Fprintf(os.Stdout, "Response from `FinderAPI.FinderAttempt`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFinderAttemptRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **finderRequest** | [**FinderRequest**](FinderRequest.md) |  | 

### Return type

[**ClientFinderResponse**](ClientFinderResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

