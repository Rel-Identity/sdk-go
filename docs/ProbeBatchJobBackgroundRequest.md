# ProbeBatchJobBackgroundRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Deadline** | Pointer to **time.Time** | Optional hard deadline for the job. Omit it to start as soon as capacity allows. If provided, the API returns 422 when the deadline is too tight even with immediate execution. | [optional] 
**CallbackUrl** | Pointer to **NullableString** |  | [optional] 
**Emails** | **[]string** | One or more exact mailbox addresses to verify asynchronously. | 

## Methods

### NewProbeBatchJobBackgroundRequest

`func NewProbeBatchJobBackgroundRequest(emails []string, ) *ProbeBatchJobBackgroundRequest`

NewProbeBatchJobBackgroundRequest instantiates a new ProbeBatchJobBackgroundRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewProbeBatchJobBackgroundRequestWithDefaults

`func NewProbeBatchJobBackgroundRequestWithDefaults() *ProbeBatchJobBackgroundRequest`

NewProbeBatchJobBackgroundRequestWithDefaults instantiates a new ProbeBatchJobBackgroundRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeadline

`func (o *ProbeBatchJobBackgroundRequest) GetDeadline() time.Time`

GetDeadline returns the Deadline field if non-nil, zero value otherwise.

### GetDeadlineOk

`func (o *ProbeBatchJobBackgroundRequest) GetDeadlineOk() (*time.Time, bool)`

GetDeadlineOk returns a tuple with the Deadline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadline

`func (o *ProbeBatchJobBackgroundRequest) SetDeadline(v time.Time)`

SetDeadline sets Deadline field to given value.

### HasDeadline

`func (o *ProbeBatchJobBackgroundRequest) HasDeadline() bool`

HasDeadline returns a boolean if a field has been set.

### GetCallbackUrl

`func (o *ProbeBatchJobBackgroundRequest) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *ProbeBatchJobBackgroundRequest) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *ProbeBatchJobBackgroundRequest) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *ProbeBatchJobBackgroundRequest) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### SetCallbackUrlNil

`func (o *ProbeBatchJobBackgroundRequest) SetCallbackUrlNil(b bool)`

 SetCallbackUrlNil sets the value for CallbackUrl to be an explicit nil

### UnsetCallbackUrl
`func (o *ProbeBatchJobBackgroundRequest) UnsetCallbackUrl()`

UnsetCallbackUrl ensures that no value is present for CallbackUrl, not even an explicit nil
### GetEmails

`func (o *ProbeBatchJobBackgroundRequest) GetEmails() []string`

GetEmails returns the Emails field if non-nil, zero value otherwise.

### GetEmailsOk

`func (o *ProbeBatchJobBackgroundRequest) GetEmailsOk() (*[]string, bool)`

GetEmailsOk returns a tuple with the Emails field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmails

`func (o *ProbeBatchJobBackgroundRequest) SetEmails(v []string)`

SetEmails sets Emails field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


