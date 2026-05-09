# ClientBackgroundJobResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**JobType** | **string** |  | 
**Status** | **string** | Current high-level job lifecycle state. | 
**DeadlineAt** | **time.Time** |  | 
**EstimatedRuntimeSeconds** | **int32** |  | 
**ScheduledStartAt** | **time.Time** |  | 
**CallbackUrl** | Pointer to **NullableString** |  | [optional] 
**CallbackStatus** | **string** |  | 
**CallbackAttempts** | **int32** |  | 
**CallbackLastError** | Pointer to **NullableString** |  | [optional] 
**RequestedCount** | **int32** | Total number of submitted items for the job. | 
**CompletedCount** | **int32** |  | 
**SuccessCount** | **int32** |  | 
**NotFoundCount** | **int32** |  | 
**ErrorCount** | **int32** |  | 
**ReservedAmountMicros** | **int32** |  | 
**ActualAmountMicros** | **int32** |  | 
**ProgressPercent** | Pointer to **float32** | Approximate percent complete based on completed item count. | [optional] 
**Summary** | Pointer to **map[string]interface{}** | Aggregated counts and provider stats for the job. | [optional] 
**Metadata** | Pointer to **map[string]interface{}** |  | [optional] 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**HistoryExpiresAt** | Pointer to **NullableTime** |  | [optional] 
**ResultsPrunedAt** | Pointer to **NullableTime** |  | [optional] 
**ArtifactAvailable** | Pointer to **bool** |  | [optional] [default to false]
**ArtifactJsonUrl** | Pointer to **NullableString** |  | [optional] 
**ArtifactSizeBytes** | Pointer to **NullableInt32** |  | [optional] 
**ArtifactUploadedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewClientBackgroundJobResponse

`func NewClientBackgroundJobResponse(id string, jobType string, status string, deadlineAt time.Time, estimatedRuntimeSeconds int32, scheduledStartAt time.Time, callbackStatus string, callbackAttempts int32, requestedCount int32, completedCount int32, successCount int32, notFoundCount int32, errorCount int32, reservedAmountMicros int32, actualAmountMicros int32, createdAt time.Time, updatedAt time.Time, ) *ClientBackgroundJobResponse`

NewClientBackgroundJobResponse instantiates a new ClientBackgroundJobResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientBackgroundJobResponseWithDefaults

`func NewClientBackgroundJobResponseWithDefaults() *ClientBackgroundJobResponse`

NewClientBackgroundJobResponseWithDefaults instantiates a new ClientBackgroundJobResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ClientBackgroundJobResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ClientBackgroundJobResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ClientBackgroundJobResponse) SetId(v string)`

SetId sets Id field to given value.


### GetJobType

`func (o *ClientBackgroundJobResponse) GetJobType() string`

GetJobType returns the JobType field if non-nil, zero value otherwise.

### GetJobTypeOk

`func (o *ClientBackgroundJobResponse) GetJobTypeOk() (*string, bool)`

GetJobTypeOk returns a tuple with the JobType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobType

`func (o *ClientBackgroundJobResponse) SetJobType(v string)`

SetJobType sets JobType field to given value.


### GetStatus

`func (o *ClientBackgroundJobResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ClientBackgroundJobResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ClientBackgroundJobResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetDeadlineAt

`func (o *ClientBackgroundJobResponse) GetDeadlineAt() time.Time`

GetDeadlineAt returns the DeadlineAt field if non-nil, zero value otherwise.

### GetDeadlineAtOk

`func (o *ClientBackgroundJobResponse) GetDeadlineAtOk() (*time.Time, bool)`

GetDeadlineAtOk returns a tuple with the DeadlineAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadlineAt

`func (o *ClientBackgroundJobResponse) SetDeadlineAt(v time.Time)`

SetDeadlineAt sets DeadlineAt field to given value.


### GetEstimatedRuntimeSeconds

`func (o *ClientBackgroundJobResponse) GetEstimatedRuntimeSeconds() int32`

GetEstimatedRuntimeSeconds returns the EstimatedRuntimeSeconds field if non-nil, zero value otherwise.

### GetEstimatedRuntimeSecondsOk

`func (o *ClientBackgroundJobResponse) GetEstimatedRuntimeSecondsOk() (*int32, bool)`

GetEstimatedRuntimeSecondsOk returns a tuple with the EstimatedRuntimeSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedRuntimeSeconds

`func (o *ClientBackgroundJobResponse) SetEstimatedRuntimeSeconds(v int32)`

SetEstimatedRuntimeSeconds sets EstimatedRuntimeSeconds field to given value.


### GetScheduledStartAt

`func (o *ClientBackgroundJobResponse) GetScheduledStartAt() time.Time`

GetScheduledStartAt returns the ScheduledStartAt field if non-nil, zero value otherwise.

### GetScheduledStartAtOk

`func (o *ClientBackgroundJobResponse) GetScheduledStartAtOk() (*time.Time, bool)`

GetScheduledStartAtOk returns a tuple with the ScheduledStartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledStartAt

`func (o *ClientBackgroundJobResponse) SetScheduledStartAt(v time.Time)`

SetScheduledStartAt sets ScheduledStartAt field to given value.


### GetCallbackUrl

`func (o *ClientBackgroundJobResponse) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *ClientBackgroundJobResponse) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *ClientBackgroundJobResponse) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *ClientBackgroundJobResponse) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### SetCallbackUrlNil

`func (o *ClientBackgroundJobResponse) SetCallbackUrlNil(b bool)`

 SetCallbackUrlNil sets the value for CallbackUrl to be an explicit nil

### UnsetCallbackUrl
`func (o *ClientBackgroundJobResponse) UnsetCallbackUrl()`

UnsetCallbackUrl ensures that no value is present for CallbackUrl, not even an explicit nil
### GetCallbackStatus

`func (o *ClientBackgroundJobResponse) GetCallbackStatus() string`

GetCallbackStatus returns the CallbackStatus field if non-nil, zero value otherwise.

### GetCallbackStatusOk

`func (o *ClientBackgroundJobResponse) GetCallbackStatusOk() (*string, bool)`

GetCallbackStatusOk returns a tuple with the CallbackStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackStatus

`func (o *ClientBackgroundJobResponse) SetCallbackStatus(v string)`

SetCallbackStatus sets CallbackStatus field to given value.


### GetCallbackAttempts

`func (o *ClientBackgroundJobResponse) GetCallbackAttempts() int32`

GetCallbackAttempts returns the CallbackAttempts field if non-nil, zero value otherwise.

### GetCallbackAttemptsOk

`func (o *ClientBackgroundJobResponse) GetCallbackAttemptsOk() (*int32, bool)`

GetCallbackAttemptsOk returns a tuple with the CallbackAttempts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackAttempts

`func (o *ClientBackgroundJobResponse) SetCallbackAttempts(v int32)`

SetCallbackAttempts sets CallbackAttempts field to given value.


### GetCallbackLastError

`func (o *ClientBackgroundJobResponse) GetCallbackLastError() string`

GetCallbackLastError returns the CallbackLastError field if non-nil, zero value otherwise.

### GetCallbackLastErrorOk

`func (o *ClientBackgroundJobResponse) GetCallbackLastErrorOk() (*string, bool)`

GetCallbackLastErrorOk returns a tuple with the CallbackLastError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackLastError

`func (o *ClientBackgroundJobResponse) SetCallbackLastError(v string)`

SetCallbackLastError sets CallbackLastError field to given value.

### HasCallbackLastError

`func (o *ClientBackgroundJobResponse) HasCallbackLastError() bool`

HasCallbackLastError returns a boolean if a field has been set.

### SetCallbackLastErrorNil

`func (o *ClientBackgroundJobResponse) SetCallbackLastErrorNil(b bool)`

 SetCallbackLastErrorNil sets the value for CallbackLastError to be an explicit nil

### UnsetCallbackLastError
`func (o *ClientBackgroundJobResponse) UnsetCallbackLastError()`

UnsetCallbackLastError ensures that no value is present for CallbackLastError, not even an explicit nil
### GetRequestedCount

`func (o *ClientBackgroundJobResponse) GetRequestedCount() int32`

GetRequestedCount returns the RequestedCount field if non-nil, zero value otherwise.

### GetRequestedCountOk

`func (o *ClientBackgroundJobResponse) GetRequestedCountOk() (*int32, bool)`

GetRequestedCountOk returns a tuple with the RequestedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestedCount

`func (o *ClientBackgroundJobResponse) SetRequestedCount(v int32)`

SetRequestedCount sets RequestedCount field to given value.


### GetCompletedCount

`func (o *ClientBackgroundJobResponse) GetCompletedCount() int32`

GetCompletedCount returns the CompletedCount field if non-nil, zero value otherwise.

### GetCompletedCountOk

`func (o *ClientBackgroundJobResponse) GetCompletedCountOk() (*int32, bool)`

GetCompletedCountOk returns a tuple with the CompletedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedCount

`func (o *ClientBackgroundJobResponse) SetCompletedCount(v int32)`

SetCompletedCount sets CompletedCount field to given value.


### GetSuccessCount

`func (o *ClientBackgroundJobResponse) GetSuccessCount() int32`

GetSuccessCount returns the SuccessCount field if non-nil, zero value otherwise.

### GetSuccessCountOk

`func (o *ClientBackgroundJobResponse) GetSuccessCountOk() (*int32, bool)`

GetSuccessCountOk returns a tuple with the SuccessCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccessCount

`func (o *ClientBackgroundJobResponse) SetSuccessCount(v int32)`

SetSuccessCount sets SuccessCount field to given value.


### GetNotFoundCount

`func (o *ClientBackgroundJobResponse) GetNotFoundCount() int32`

GetNotFoundCount returns the NotFoundCount field if non-nil, zero value otherwise.

### GetNotFoundCountOk

`func (o *ClientBackgroundJobResponse) GetNotFoundCountOk() (*int32, bool)`

GetNotFoundCountOk returns a tuple with the NotFoundCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotFoundCount

`func (o *ClientBackgroundJobResponse) SetNotFoundCount(v int32)`

SetNotFoundCount sets NotFoundCount field to given value.


### GetErrorCount

`func (o *ClientBackgroundJobResponse) GetErrorCount() int32`

GetErrorCount returns the ErrorCount field if non-nil, zero value otherwise.

### GetErrorCountOk

`func (o *ClientBackgroundJobResponse) GetErrorCountOk() (*int32, bool)`

GetErrorCountOk returns a tuple with the ErrorCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorCount

`func (o *ClientBackgroundJobResponse) SetErrorCount(v int32)`

SetErrorCount sets ErrorCount field to given value.


### GetReservedAmountMicros

`func (o *ClientBackgroundJobResponse) GetReservedAmountMicros() int32`

GetReservedAmountMicros returns the ReservedAmountMicros field if non-nil, zero value otherwise.

### GetReservedAmountMicrosOk

`func (o *ClientBackgroundJobResponse) GetReservedAmountMicrosOk() (*int32, bool)`

GetReservedAmountMicrosOk returns a tuple with the ReservedAmountMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReservedAmountMicros

`func (o *ClientBackgroundJobResponse) SetReservedAmountMicros(v int32)`

SetReservedAmountMicros sets ReservedAmountMicros field to given value.


### GetActualAmountMicros

`func (o *ClientBackgroundJobResponse) GetActualAmountMicros() int32`

GetActualAmountMicros returns the ActualAmountMicros field if non-nil, zero value otherwise.

### GetActualAmountMicrosOk

`func (o *ClientBackgroundJobResponse) GetActualAmountMicrosOk() (*int32, bool)`

GetActualAmountMicrosOk returns a tuple with the ActualAmountMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActualAmountMicros

`func (o *ClientBackgroundJobResponse) SetActualAmountMicros(v int32)`

SetActualAmountMicros sets ActualAmountMicros field to given value.


### GetProgressPercent

`func (o *ClientBackgroundJobResponse) GetProgressPercent() float32`

GetProgressPercent returns the ProgressPercent field if non-nil, zero value otherwise.

### GetProgressPercentOk

`func (o *ClientBackgroundJobResponse) GetProgressPercentOk() (*float32, bool)`

GetProgressPercentOk returns a tuple with the ProgressPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgressPercent

`func (o *ClientBackgroundJobResponse) SetProgressPercent(v float32)`

SetProgressPercent sets ProgressPercent field to given value.

### HasProgressPercent

`func (o *ClientBackgroundJobResponse) HasProgressPercent() bool`

HasProgressPercent returns a boolean if a field has been set.

### GetSummary

`func (o *ClientBackgroundJobResponse) GetSummary() map[string]interface{}`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *ClientBackgroundJobResponse) GetSummaryOk() (*map[string]interface{}, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *ClientBackgroundJobResponse) SetSummary(v map[string]interface{})`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *ClientBackgroundJobResponse) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### GetMetadata

`func (o *ClientBackgroundJobResponse) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ClientBackgroundJobResponse) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ClientBackgroundJobResponse) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ClientBackgroundJobResponse) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetStartedAt

`func (o *ClientBackgroundJobResponse) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *ClientBackgroundJobResponse) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *ClientBackgroundJobResponse) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *ClientBackgroundJobResponse) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *ClientBackgroundJobResponse) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *ClientBackgroundJobResponse) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *ClientBackgroundJobResponse) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *ClientBackgroundJobResponse) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *ClientBackgroundJobResponse) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *ClientBackgroundJobResponse) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *ClientBackgroundJobResponse) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *ClientBackgroundJobResponse) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetHistoryExpiresAt

`func (o *ClientBackgroundJobResponse) GetHistoryExpiresAt() time.Time`

GetHistoryExpiresAt returns the HistoryExpiresAt field if non-nil, zero value otherwise.

### GetHistoryExpiresAtOk

`func (o *ClientBackgroundJobResponse) GetHistoryExpiresAtOk() (*time.Time, bool)`

GetHistoryExpiresAtOk returns a tuple with the HistoryExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistoryExpiresAt

`func (o *ClientBackgroundJobResponse) SetHistoryExpiresAt(v time.Time)`

SetHistoryExpiresAt sets HistoryExpiresAt field to given value.

### HasHistoryExpiresAt

`func (o *ClientBackgroundJobResponse) HasHistoryExpiresAt() bool`

HasHistoryExpiresAt returns a boolean if a field has been set.

### SetHistoryExpiresAtNil

`func (o *ClientBackgroundJobResponse) SetHistoryExpiresAtNil(b bool)`

 SetHistoryExpiresAtNil sets the value for HistoryExpiresAt to be an explicit nil

### UnsetHistoryExpiresAt
`func (o *ClientBackgroundJobResponse) UnsetHistoryExpiresAt()`

UnsetHistoryExpiresAt ensures that no value is present for HistoryExpiresAt, not even an explicit nil
### GetResultsPrunedAt

`func (o *ClientBackgroundJobResponse) GetResultsPrunedAt() time.Time`

GetResultsPrunedAt returns the ResultsPrunedAt field if non-nil, zero value otherwise.

### GetResultsPrunedAtOk

`func (o *ClientBackgroundJobResponse) GetResultsPrunedAtOk() (*time.Time, bool)`

GetResultsPrunedAtOk returns a tuple with the ResultsPrunedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultsPrunedAt

`func (o *ClientBackgroundJobResponse) SetResultsPrunedAt(v time.Time)`

SetResultsPrunedAt sets ResultsPrunedAt field to given value.

### HasResultsPrunedAt

`func (o *ClientBackgroundJobResponse) HasResultsPrunedAt() bool`

HasResultsPrunedAt returns a boolean if a field has been set.

### SetResultsPrunedAtNil

`func (o *ClientBackgroundJobResponse) SetResultsPrunedAtNil(b bool)`

 SetResultsPrunedAtNil sets the value for ResultsPrunedAt to be an explicit nil

### UnsetResultsPrunedAt
`func (o *ClientBackgroundJobResponse) UnsetResultsPrunedAt()`

UnsetResultsPrunedAt ensures that no value is present for ResultsPrunedAt, not even an explicit nil
### GetArtifactAvailable

`func (o *ClientBackgroundJobResponse) GetArtifactAvailable() bool`

GetArtifactAvailable returns the ArtifactAvailable field if non-nil, zero value otherwise.

### GetArtifactAvailableOk

`func (o *ClientBackgroundJobResponse) GetArtifactAvailableOk() (*bool, bool)`

GetArtifactAvailableOk returns a tuple with the ArtifactAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtifactAvailable

`func (o *ClientBackgroundJobResponse) SetArtifactAvailable(v bool)`

SetArtifactAvailable sets ArtifactAvailable field to given value.

### HasArtifactAvailable

`func (o *ClientBackgroundJobResponse) HasArtifactAvailable() bool`

HasArtifactAvailable returns a boolean if a field has been set.

### GetArtifactJsonUrl

`func (o *ClientBackgroundJobResponse) GetArtifactJsonUrl() string`

GetArtifactJsonUrl returns the ArtifactJsonUrl field if non-nil, zero value otherwise.

### GetArtifactJsonUrlOk

`func (o *ClientBackgroundJobResponse) GetArtifactJsonUrlOk() (*string, bool)`

GetArtifactJsonUrlOk returns a tuple with the ArtifactJsonUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtifactJsonUrl

`func (o *ClientBackgroundJobResponse) SetArtifactJsonUrl(v string)`

SetArtifactJsonUrl sets ArtifactJsonUrl field to given value.

### HasArtifactJsonUrl

`func (o *ClientBackgroundJobResponse) HasArtifactJsonUrl() bool`

HasArtifactJsonUrl returns a boolean if a field has been set.

### SetArtifactJsonUrlNil

`func (o *ClientBackgroundJobResponse) SetArtifactJsonUrlNil(b bool)`

 SetArtifactJsonUrlNil sets the value for ArtifactJsonUrl to be an explicit nil

### UnsetArtifactJsonUrl
`func (o *ClientBackgroundJobResponse) UnsetArtifactJsonUrl()`

UnsetArtifactJsonUrl ensures that no value is present for ArtifactJsonUrl, not even an explicit nil
### GetArtifactSizeBytes

`func (o *ClientBackgroundJobResponse) GetArtifactSizeBytes() int32`

GetArtifactSizeBytes returns the ArtifactSizeBytes field if non-nil, zero value otherwise.

### GetArtifactSizeBytesOk

`func (o *ClientBackgroundJobResponse) GetArtifactSizeBytesOk() (*int32, bool)`

GetArtifactSizeBytesOk returns a tuple with the ArtifactSizeBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtifactSizeBytes

`func (o *ClientBackgroundJobResponse) SetArtifactSizeBytes(v int32)`

SetArtifactSizeBytes sets ArtifactSizeBytes field to given value.

### HasArtifactSizeBytes

`func (o *ClientBackgroundJobResponse) HasArtifactSizeBytes() bool`

HasArtifactSizeBytes returns a boolean if a field has been set.

### SetArtifactSizeBytesNil

`func (o *ClientBackgroundJobResponse) SetArtifactSizeBytesNil(b bool)`

 SetArtifactSizeBytesNil sets the value for ArtifactSizeBytes to be an explicit nil

### UnsetArtifactSizeBytes
`func (o *ClientBackgroundJobResponse) UnsetArtifactSizeBytes()`

UnsetArtifactSizeBytes ensures that no value is present for ArtifactSizeBytes, not even an explicit nil
### GetArtifactUploadedAt

`func (o *ClientBackgroundJobResponse) GetArtifactUploadedAt() time.Time`

GetArtifactUploadedAt returns the ArtifactUploadedAt field if non-nil, zero value otherwise.

### GetArtifactUploadedAtOk

`func (o *ClientBackgroundJobResponse) GetArtifactUploadedAtOk() (*time.Time, bool)`

GetArtifactUploadedAtOk returns a tuple with the ArtifactUploadedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArtifactUploadedAt

`func (o *ClientBackgroundJobResponse) SetArtifactUploadedAt(v time.Time)`

SetArtifactUploadedAt sets ArtifactUploadedAt field to given value.

### HasArtifactUploadedAt

`func (o *ClientBackgroundJobResponse) HasArtifactUploadedAt() bool`

HasArtifactUploadedAt returns a boolean if a field has been set.

### SetArtifactUploadedAtNil

`func (o *ClientBackgroundJobResponse) SetArtifactUploadedAtNil(b bool)`

 SetArtifactUploadedAtNil sets the value for ArtifactUploadedAt to be an explicit nil

### UnsetArtifactUploadedAt
`func (o *ClientBackgroundJobResponse) UnsetArtifactUploadedAt()`

UnsetArtifactUploadedAt ensures that no value is present for ArtifactUploadedAt, not even an explicit nil
### GetCreatedAt

`func (o *ClientBackgroundJobResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ClientBackgroundJobResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ClientBackgroundJobResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ClientBackgroundJobResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ClientBackgroundJobResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ClientBackgroundJobResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


