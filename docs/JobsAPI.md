# \JobsAPI

All URIs are relative to *https://api.relentlessidentity.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetJob**](JobsAPI.md#GetJob) | **Get** /client/jobs/{job_id} | Get background job
[**GetJobInputsText**](JobsAPI.md#GetJobInputsText) | **Get** /client/jobs/{job_id}/inputs.txt | Download job inputs
[**GetJobResultsJson**](JobsAPI.md#GetJobResultsJson) | **Get** /client/jobs/{job_id}/results.json | Download job results as JSON
[**GetJobResultsText**](JobsAPI.md#GetJobResultsText) | **Get** /client/jobs/{job_id}/results.txt | Download job results as text
[**ListJobs**](JobsAPI.md#ListJobs) | **Get** /client/jobs | List background jobs
[**ScheduleFinderBatch**](JobsAPI.md#ScheduleFinderBatch) | **Post** /client/jobs/finder | Schedule a finder batch
[**ScheduleProbeBatch**](JobsAPI.md#ScheduleProbeBatch) | **Post** /client/jobs/probe-batch | Schedule a probe batch



## GetJob

> ClientBackgroundJobDetailResponse GetJob(ctx, jobId).Page(page).PageSize(pageSize).Execute()

Get background job



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
	jobId := "jobId_example" // string | 
	page := int32(56) // int32 |  (optional) (default to 1)
	pageSize := int32(56) // int32 |  (optional) (default to 50)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobsAPI.GetJob(context.Background(), jobId).Page(page).PageSize(pageSize).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.GetJob``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetJob`: ClientBackgroundJobDetailResponse
	fmt.Fprintf(os.Stdout, "Response from `JobsAPI.GetJob`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetJobRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** |  | [default to 1]
 **pageSize** | **int32** |  | [default to 50]

### Return type

[**ClientBackgroundJobDetailResponse**](ClientBackgroundJobDetailResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetJobInputsText

> string GetJobInputsText(ctx, jobId).IfNoneMatch(ifNoneMatch).IfModifiedSince(ifModifiedSince).Execute()

Download job inputs



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
	jobId := "jobId_example" // string | 
	ifNoneMatch := "ifNoneMatch_example" // string |  (optional)
	ifModifiedSince := "ifModifiedSince_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobsAPI.GetJobInputsText(context.Background(), jobId).IfNoneMatch(ifNoneMatch).IfModifiedSince(ifModifiedSince).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.GetJobInputsText``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetJobInputsText`: string
	fmt.Fprintf(os.Stdout, "Response from `JobsAPI.GetJobInputsText`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetJobInputsTextRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ifNoneMatch** | **string** |  | 
 **ifModifiedSince** | **string** |  | 

### Return type

**string**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetJobResultsJson

> interface{} GetJobResultsJson(ctx, jobId).IfNoneMatch(ifNoneMatch).IfModifiedSince(ifModifiedSince).Execute()

Download job results as JSON



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
	jobId := "jobId_example" // string | 
	ifNoneMatch := "ifNoneMatch_example" // string |  (optional)
	ifModifiedSince := "ifModifiedSince_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobsAPI.GetJobResultsJson(context.Background(), jobId).IfNoneMatch(ifNoneMatch).IfModifiedSince(ifModifiedSince).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.GetJobResultsJson``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetJobResultsJson`: interface{}
	fmt.Fprintf(os.Stdout, "Response from `JobsAPI.GetJobResultsJson`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetJobResultsJsonRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ifNoneMatch** | **string** |  | 
 **ifModifiedSince** | **string** |  | 

### Return type

**interface{}**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetJobResultsText

> string GetJobResultsText(ctx, jobId).IfNoneMatch(ifNoneMatch).IfModifiedSince(ifModifiedSince).Execute()

Download job results as text



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
	jobId := "jobId_example" // string | 
	ifNoneMatch := "ifNoneMatch_example" // string |  (optional)
	ifModifiedSince := "ifModifiedSince_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobsAPI.GetJobResultsText(context.Background(), jobId).IfNoneMatch(ifNoneMatch).IfModifiedSince(ifModifiedSince).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.GetJobResultsText``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetJobResultsText`: string
	fmt.Fprintf(os.Stdout, "Response from `JobsAPI.GetJobResultsText`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**jobId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetJobResultsTextRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **ifNoneMatch** | **string** |  | 
 **ifModifiedSince** | **string** |  | 

### Return type

**string**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListJobs

> ClientBackgroundJobPageResponse ListJobs(ctx).Page(page).PageSize(pageSize).JobType(jobType).Status(status).Execute()

List background jobs



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
	page := int32(56) // int32 |  (optional) (default to 1)
	pageSize := int32(56) // int32 |  (optional) (default to 25)
	jobType := "jobType_example" // string |  (optional)
	status := "status_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobsAPI.ListJobs(context.Background()).Page(page).PageSize(pageSize).JobType(jobType).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.ListJobs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListJobs`: ClientBackgroundJobPageResponse
	fmt.Fprintf(os.Stdout, "Response from `JobsAPI.ListJobs`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListJobsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **page** | **int32** |  | [default to 1]
 **pageSize** | **int32** |  | [default to 25]
 **jobType** | **string** |  | 
 **status** | **string** |  | 

### Return type

[**ClientBackgroundJobPageResponse**](ClientBackgroundJobPageResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ScheduleFinderBatch

> ClientBackgroundJobResponse ScheduleFinderBatch(ctx).FinderBatchJobRequest(finderBatchJobRequest).Execute()

Schedule a finder batch



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
	finderBatchJobRequest := *openapiclient.NewFinderBatchJobRequest([]openapiclient.FinderBatchJobRequestInputsInner{*openapiclient.NewFinderBatchJobRequestInputsInner("Jane Doe", "acme.com")}) // FinderBatchJobRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobsAPI.ScheduleFinderBatch(context.Background()).FinderBatchJobRequest(finderBatchJobRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.ScheduleFinderBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ScheduleFinderBatch`: ClientBackgroundJobResponse
	fmt.Fprintf(os.Stdout, "Response from `JobsAPI.ScheduleFinderBatch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiScheduleFinderBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **finderBatchJobRequest** | [**FinderBatchJobRequest**](FinderBatchJobRequest.md) |  | 

### Return type

[**ClientBackgroundJobResponse**](ClientBackgroundJobResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ScheduleProbeBatch

> ClientBackgroundJobResponse ScheduleProbeBatch(ctx).ProbeBatchJobBackgroundRequest(probeBatchJobBackgroundRequest).Execute()

Schedule a probe batch



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
	probeBatchJobBackgroundRequest := *openapiclient.NewProbeBatchJobBackgroundRequest([]string{"Emails_example"}) // ProbeBatchJobBackgroundRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobsAPI.ScheduleProbeBatch(context.Background()).ProbeBatchJobBackgroundRequest(probeBatchJobBackgroundRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.ScheduleProbeBatch``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ScheduleProbeBatch`: ClientBackgroundJobResponse
	fmt.Fprintf(os.Stdout, "Response from `JobsAPI.ScheduleProbeBatch`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiScheduleProbeBatchRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **probeBatchJobBackgroundRequest** | [**ProbeBatchJobBackgroundRequest**](ProbeBatchJobBackgroundRequest.md) |  | 

### Return type

[**ClientBackgroundJobResponse**](ClientBackgroundJobResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

