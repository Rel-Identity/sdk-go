# ClientBackgroundJobItemResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**ItemIndex** | **int32** |  | 
**Status** | **string** |  | 
**RequestType** | **string** |  | 
**Input** | **map[string]interface{}** | Original submitted input for this item. | 
**Result** | Pointer to **map[string]interface{}** |  | [optional] 
**ResultState** | Pointer to **NullableString** |  | [optional] 
**ResultOutcome** | Pointer to **NullableString** |  | [optional] 
**ResolvedAddress** | Pointer to **NullableString** |  | [optional] 
**Provider** | Pointer to **NullableString** |  | [optional] 
**ChargeMicros** | Pointer to **int32** |  | [optional] [default to 0]
**ErrorMessage** | Pointer to **NullableString** |  | [optional] 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**CompletedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**UpdatedAt** | **time.Time** |  | 

## Methods

### NewClientBackgroundJobItemResponse

`func NewClientBackgroundJobItemResponse(id string, itemIndex int32, status string, requestType string, input map[string]interface{}, createdAt time.Time, updatedAt time.Time, ) *ClientBackgroundJobItemResponse`

NewClientBackgroundJobItemResponse instantiates a new ClientBackgroundJobItemResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientBackgroundJobItemResponseWithDefaults

`func NewClientBackgroundJobItemResponseWithDefaults() *ClientBackgroundJobItemResponse`

NewClientBackgroundJobItemResponseWithDefaults instantiates a new ClientBackgroundJobItemResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ClientBackgroundJobItemResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ClientBackgroundJobItemResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ClientBackgroundJobItemResponse) SetId(v string)`

SetId sets Id field to given value.


### GetItemIndex

`func (o *ClientBackgroundJobItemResponse) GetItemIndex() int32`

GetItemIndex returns the ItemIndex field if non-nil, zero value otherwise.

### GetItemIndexOk

`func (o *ClientBackgroundJobItemResponse) GetItemIndexOk() (*int32, bool)`

GetItemIndexOk returns a tuple with the ItemIndex field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemIndex

`func (o *ClientBackgroundJobItemResponse) SetItemIndex(v int32)`

SetItemIndex sets ItemIndex field to given value.


### GetStatus

`func (o *ClientBackgroundJobItemResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ClientBackgroundJobItemResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ClientBackgroundJobItemResponse) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetRequestType

`func (o *ClientBackgroundJobItemResponse) GetRequestType() string`

GetRequestType returns the RequestType field if non-nil, zero value otherwise.

### GetRequestTypeOk

`func (o *ClientBackgroundJobItemResponse) GetRequestTypeOk() (*string, bool)`

GetRequestTypeOk returns a tuple with the RequestType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestType

`func (o *ClientBackgroundJobItemResponse) SetRequestType(v string)`

SetRequestType sets RequestType field to given value.


### GetInput

`func (o *ClientBackgroundJobItemResponse) GetInput() map[string]interface{}`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *ClientBackgroundJobItemResponse) GetInputOk() (*map[string]interface{}, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *ClientBackgroundJobItemResponse) SetInput(v map[string]interface{})`

SetInput sets Input field to given value.


### GetResult

`func (o *ClientBackgroundJobItemResponse) GetResult() map[string]interface{}`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *ClientBackgroundJobItemResponse) GetResultOk() (*map[string]interface{}, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *ClientBackgroundJobItemResponse) SetResult(v map[string]interface{})`

SetResult sets Result field to given value.

### HasResult

`func (o *ClientBackgroundJobItemResponse) HasResult() bool`

HasResult returns a boolean if a field has been set.

### SetResultNil

`func (o *ClientBackgroundJobItemResponse) SetResultNil(b bool)`

 SetResultNil sets the value for Result to be an explicit nil

### UnsetResult
`func (o *ClientBackgroundJobItemResponse) UnsetResult()`

UnsetResult ensures that no value is present for Result, not even an explicit nil
### GetResultState

`func (o *ClientBackgroundJobItemResponse) GetResultState() string`

GetResultState returns the ResultState field if non-nil, zero value otherwise.

### GetResultStateOk

`func (o *ClientBackgroundJobItemResponse) GetResultStateOk() (*string, bool)`

GetResultStateOk returns a tuple with the ResultState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultState

`func (o *ClientBackgroundJobItemResponse) SetResultState(v string)`

SetResultState sets ResultState field to given value.

### HasResultState

`func (o *ClientBackgroundJobItemResponse) HasResultState() bool`

HasResultState returns a boolean if a field has been set.

### SetResultStateNil

`func (o *ClientBackgroundJobItemResponse) SetResultStateNil(b bool)`

 SetResultStateNil sets the value for ResultState to be an explicit nil

### UnsetResultState
`func (o *ClientBackgroundJobItemResponse) UnsetResultState()`

UnsetResultState ensures that no value is present for ResultState, not even an explicit nil
### GetResultOutcome

`func (o *ClientBackgroundJobItemResponse) GetResultOutcome() string`

GetResultOutcome returns the ResultOutcome field if non-nil, zero value otherwise.

### GetResultOutcomeOk

`func (o *ClientBackgroundJobItemResponse) GetResultOutcomeOk() (*string, bool)`

GetResultOutcomeOk returns a tuple with the ResultOutcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultOutcome

`func (o *ClientBackgroundJobItemResponse) SetResultOutcome(v string)`

SetResultOutcome sets ResultOutcome field to given value.

### HasResultOutcome

`func (o *ClientBackgroundJobItemResponse) HasResultOutcome() bool`

HasResultOutcome returns a boolean if a field has been set.

### SetResultOutcomeNil

`func (o *ClientBackgroundJobItemResponse) SetResultOutcomeNil(b bool)`

 SetResultOutcomeNil sets the value for ResultOutcome to be an explicit nil

### UnsetResultOutcome
`func (o *ClientBackgroundJobItemResponse) UnsetResultOutcome()`

UnsetResultOutcome ensures that no value is present for ResultOutcome, not even an explicit nil
### GetResolvedAddress

`func (o *ClientBackgroundJobItemResponse) GetResolvedAddress() string`

GetResolvedAddress returns the ResolvedAddress field if non-nil, zero value otherwise.

### GetResolvedAddressOk

`func (o *ClientBackgroundJobItemResponse) GetResolvedAddressOk() (*string, bool)`

GetResolvedAddressOk returns a tuple with the ResolvedAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAddress

`func (o *ClientBackgroundJobItemResponse) SetResolvedAddress(v string)`

SetResolvedAddress sets ResolvedAddress field to given value.

### HasResolvedAddress

`func (o *ClientBackgroundJobItemResponse) HasResolvedAddress() bool`

HasResolvedAddress returns a boolean if a field has been set.

### SetResolvedAddressNil

`func (o *ClientBackgroundJobItemResponse) SetResolvedAddressNil(b bool)`

 SetResolvedAddressNil sets the value for ResolvedAddress to be an explicit nil

### UnsetResolvedAddress
`func (o *ClientBackgroundJobItemResponse) UnsetResolvedAddress()`

UnsetResolvedAddress ensures that no value is present for ResolvedAddress, not even an explicit nil
### GetProvider

`func (o *ClientBackgroundJobItemResponse) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ClientBackgroundJobItemResponse) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ClientBackgroundJobItemResponse) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *ClientBackgroundJobItemResponse) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *ClientBackgroundJobItemResponse) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *ClientBackgroundJobItemResponse) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetChargeMicros

`func (o *ClientBackgroundJobItemResponse) GetChargeMicros() int32`

GetChargeMicros returns the ChargeMicros field if non-nil, zero value otherwise.

### GetChargeMicrosOk

`func (o *ClientBackgroundJobItemResponse) GetChargeMicrosOk() (*int32, bool)`

GetChargeMicrosOk returns a tuple with the ChargeMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChargeMicros

`func (o *ClientBackgroundJobItemResponse) SetChargeMicros(v int32)`

SetChargeMicros sets ChargeMicros field to given value.

### HasChargeMicros

`func (o *ClientBackgroundJobItemResponse) HasChargeMicros() bool`

HasChargeMicros returns a boolean if a field has been set.

### GetErrorMessage

`func (o *ClientBackgroundJobItemResponse) GetErrorMessage() string`

GetErrorMessage returns the ErrorMessage field if non-nil, zero value otherwise.

### GetErrorMessageOk

`func (o *ClientBackgroundJobItemResponse) GetErrorMessageOk() (*string, bool)`

GetErrorMessageOk returns a tuple with the ErrorMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorMessage

`func (o *ClientBackgroundJobItemResponse) SetErrorMessage(v string)`

SetErrorMessage sets ErrorMessage field to given value.

### HasErrorMessage

`func (o *ClientBackgroundJobItemResponse) HasErrorMessage() bool`

HasErrorMessage returns a boolean if a field has been set.

### SetErrorMessageNil

`func (o *ClientBackgroundJobItemResponse) SetErrorMessageNil(b bool)`

 SetErrorMessageNil sets the value for ErrorMessage to be an explicit nil

### UnsetErrorMessage
`func (o *ClientBackgroundJobItemResponse) UnsetErrorMessage()`

UnsetErrorMessage ensures that no value is present for ErrorMessage, not even an explicit nil
### GetStartedAt

`func (o *ClientBackgroundJobItemResponse) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *ClientBackgroundJobItemResponse) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *ClientBackgroundJobItemResponse) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *ClientBackgroundJobItemResponse) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *ClientBackgroundJobItemResponse) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *ClientBackgroundJobItemResponse) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetCompletedAt

`func (o *ClientBackgroundJobItemResponse) GetCompletedAt() time.Time`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *ClientBackgroundJobItemResponse) GetCompletedAtOk() (*time.Time, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *ClientBackgroundJobItemResponse) SetCompletedAt(v time.Time)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *ClientBackgroundJobItemResponse) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### SetCompletedAtNil

`func (o *ClientBackgroundJobItemResponse) SetCompletedAtNil(b bool)`

 SetCompletedAtNil sets the value for CompletedAt to be an explicit nil

### UnsetCompletedAt
`func (o *ClientBackgroundJobItemResponse) UnsetCompletedAt()`

UnsetCompletedAt ensures that no value is present for CompletedAt, not even an explicit nil
### GetCreatedAt

`func (o *ClientBackgroundJobItemResponse) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ClientBackgroundJobItemResponse) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ClientBackgroundJobItemResponse) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ClientBackgroundJobItemResponse) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ClientBackgroundJobItemResponse) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ClientBackgroundJobItemResponse) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


