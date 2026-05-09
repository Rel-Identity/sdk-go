# FinderBatchJobRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Deadline** | Pointer to **time.Time** | Optional hard deadline for the job. Omit it to start as soon as capacity allows. If provided, the API returns 422 when the deadline is too tight even with immediate execution. | [optional] 
**CallbackUrl** | Pointer to **NullableString** |  | [optional] 
**Inputs** | [**[]FinderBatchJobRequestInputsInner**](FinderBatchJobRequestInputsInner.md) | One or more Finder-style inputs that will be processed asynchronously. | 

## Methods

### NewFinderBatchJobRequest

`func NewFinderBatchJobRequest(inputs []FinderBatchJobRequestInputsInner, ) *FinderBatchJobRequest`

NewFinderBatchJobRequest instantiates a new FinderBatchJobRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFinderBatchJobRequestWithDefaults

`func NewFinderBatchJobRequestWithDefaults() *FinderBatchJobRequest`

NewFinderBatchJobRequestWithDefaults instantiates a new FinderBatchJobRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeadline

`func (o *FinderBatchJobRequest) GetDeadline() time.Time`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *FinderBatchJobRequest) GetDeadlineOk() (*time.Time, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *FinderBatchJobRequest) SetDeadline(v time.Time)`

SetDeadline sets Deadline field to given value.

### HasDeadline

`func (o *FinderBatchJobRequest) HasDeadline() bool`

HasDeadline returns a boolean if a field has been set.

### GetCallbackUrl

`func (o *FinderBatchJobRequest) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *FinderBatchJobRequest) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *FinderBatchJobRequest) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *FinderBatchJobRequest) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### SetCallbackUrlNil

`func (o *FinderBatchJobRequest) SetCallbackUrlNil(b bool)`

 SetCallbackUrlNil sets the value for CallbackUrl to be an explicit nil

### UnsetCallbackUrl
`func (o *FinderBatchJobRequest) UnsetCallbackUrl()`

UnsetCallbackUrl ensures that no value is present for CallbackUrl, not even an explicit nil
### GetInputs

`func (o *FinderBatchJobRequest) GetInputs() []FinderBatchJobRequestInputsInner`

GetInputs returns the Inputs field if non-nil, zero value otherwise.

### GetInputsOk

`func (o *FinderBatchJobRequest) GetInputsOk() (*[]FinderBatchJobRequestInputsInner, bool)`

GetInputsOk returns a tuple with the Inputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputs

`func (o *FinderBatchJobRequest) SetInputs(v []FinderBatchJobRequestInputsInner)`

SetInputs sets Inputs field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


