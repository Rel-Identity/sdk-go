# ClientBatchIdentityResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Results** | [**[]ClientIdentityResponse**](ClientIdentityResponse.md) | Per-email compact probe results in request order. | 
**Summary** | [**BatchSummary**](BatchSummary.md) |  | 

## Methods

### NewClientBatchIdentityResponse

`func NewClientBatchIdentityResponse(results []ClientIdentityResponse, summary BatchSummary, ) *ClientBatchIdentityResponse`

NewClientBatchIdentityResponse instantiates a new ClientBatchIdentityResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientBatchIdentityResponseWithDefaults

`func NewClientBatchIdentityResponseWithDefaults() *ClientBatchIdentityResponse`

NewClientBatchIdentityResponseWithDefaults instantiates a new ClientBatchIdentityResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResults

`func (o *ClientBatchIdentityResponse) GetResults() []ClientIdentityResponse`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *ClientBatchIdentityResponse) GetResultsOk() (*[]ClientIdentityResponse, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *ClientBatchIdentityResponse) SetResults(v []ClientIdentityResponse)`

SetResults sets Results field to given value.


### GetSummary

`func (o *ClientBatchIdentityResponse) GetSummary() BatchSummary`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *ClientBatchIdentityResponse) GetSummaryOk() (*BatchSummary, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *ClientBatchIdentityResponse) SetSummary(v BatchSummary)`

SetSummary sets Summary field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


