# BatchSummary

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | **int32** | Total number of requested items. | 
**Found** | **int32** | Items that resolved to a positive deliverable result. | 
**NotFound** | **int32** | Items that completed cleanly with a negative result. | 
**Errors** | **int32** | Items that ended with an operational verification error rather than a mailbox verdict. | 
**UniqueDomains** | **int32** | Distinct mailbox domains represented in the batch. | 

## Methods

### NewBatchSummary

`func NewBatchSummary(total int32, found int32, notFound int32, errors int32, uniqueDomains int32, ) *BatchSummary`

NewBatchSummary instantiates a new BatchSummary object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBatchSummaryWithDefaults

`func NewBatchSummaryWithDefaults() *BatchSummary`

NewBatchSummaryWithDefaults instantiates a new BatchSummary object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *BatchSummary) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *BatchSummary) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *BatchSummary) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetFound

`func (o *BatchSummary) GetFound() int32`

GetFound returns the Found field if non-nil, zero value otherwise.

### GetFoundOk

`func (o *BatchSummary) GetFoundOk() (*int32, bool)`

GetFoundOk returns a tuple with the Found field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFound

`func (o *BatchSummary) SetFound(v int32)`

SetFound sets Found field to given value.


### GetNotFound

`func (o *BatchSummary) GetNotFound() int32`

GetNotFound returns the NotFound field if non-nil, zero value otherwise.

### GetNotFoundOk

`func (o *BatchSummary) GetNotFoundOk() (*int32, bool)`

GetNotFoundOk returns a tuple with the NotFound field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotFound

`func (o *BatchSummary) SetNotFound(v int32)`

SetNotFound sets NotFound field to given value.


### GetErrors

`func (o *BatchSummary) GetErrors() int32`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *BatchSummary) GetErrorsOk() (*int32, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *BatchSummary) SetErrors(v int32)`

SetErrors sets Errors field to given value.


### GetUniqueDomains

`func (o *BatchSummary) GetUniqueDomains() int32`

GetUniqueDomains returns the UniqueDomains field if non-nil, zero value otherwise.

### GetUniqueDomainsOk

`func (o *BatchSummary) GetUniqueDomainsOk() (*int32, bool)`

GetUniqueDomainsOk returns a tuple with the UniqueDomains field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUniqueDomains

`func (o *BatchSummary) SetUniqueDomains(v int32)`

SetUniqueDomains sets UniqueDomains field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


