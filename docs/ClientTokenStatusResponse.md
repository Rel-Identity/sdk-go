# ClientTokenStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Valid** | Pointer to **bool** | Whether the current bearer token is valid for this request. | [optional] 
**UserId** | **string** | User id associated with the bearer token. | 
**TokenType** | **string** | How the bearer token was issued. | 
**Scopes** | Pointer to **[]string** | Scopes currently attached to the bearer token. | [optional] 
**ExpiresAt** | Pointer to **NullableTime** |  | [optional] 
**ExpiresInSeconds** | Pointer to **NullableInt32** |  | [optional] 

## Methods

### NewClientTokenStatusResponse

`func NewClientTokenStatusResponse(userId string, tokenType string, ) *ClientTokenStatusResponse`

NewClientTokenStatusResponse instantiates a new ClientTokenStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientTokenStatusResponseWithDefaults

`func NewClientTokenStatusResponseWithDefaults() *ClientTokenStatusResponse`

NewClientTokenStatusResponseWithDefaults instantiates a new ClientTokenStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValid

`func (o *ClientTokenStatusResponse) GetValid() bool`

GetValid returns the Valid field if non-nil, zero value otherwise.

### GetValidOk

`func (o *ClientTokenStatusResponse) GetValidOk() (*bool, bool)`

GetValidOk returns a tuple with the Valid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValid

`func (o *ClientTokenStatusResponse) SetValid(v bool)`

SetValid sets Valid field to given value.

### HasValid

`func (o *ClientTokenStatusResponse) HasValid() bool`

HasValid returns a boolean if a field has been set.

### GetUserId

`func (o *ClientTokenStatusResponse) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *ClientTokenStatusResponse) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *ClientTokenStatusResponse) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetTokenType

`func (o *ClientTokenStatusResponse) GetTokenType() string`

GetTokenType returns the TokenType field if non-nil, zero value otherwise.

### GetTokenTypeOk

`func (o *ClientTokenStatusResponse) GetTokenTypeOk() (*string, bool)`

GetTokenTypeOk returns a tuple with the TokenType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenType

`func (o *ClientTokenStatusResponse) SetTokenType(v string)`

SetTokenType sets TokenType field to given value.


### GetScopes

`func (o *ClientTokenStatusResponse) GetScopes() []string`

GetScopes returns the Scopes field if non-nil, zero value otherwise.

### GetScopesOk

`func (o *ClientTokenStatusResponse) GetScopesOk() (*[]string, bool)`

GetScopesOk returns a tuple with the Scopes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopes

`func (o *ClientTokenStatusResponse) SetScopes(v []string)`

SetScopes sets Scopes field to given value.

### HasScopes

`func (o *ClientTokenStatusResponse) HasScopes() bool`

HasScopes returns a boolean if a field has been set.

### GetExpiresAt

`func (o *ClientTokenStatusResponse) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *ClientTokenStatusResponse) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *ClientTokenStatusResponse) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *ClientTokenStatusResponse) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *ClientTokenStatusResponse) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *ClientTokenStatusResponse) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetExpiresInSeconds

`func (o *ClientTokenStatusResponse) GetExpiresInSeconds() int32`

GetExpiresInSeconds returns the ExpiresInSeconds field if non-nil, zero value otherwise.

### GetExpiresInSecondsOk

`func (o *ClientTokenStatusResponse) GetExpiresInSecondsOk() (*int32, bool)`

GetExpiresInSecondsOk returns a tuple with the ExpiresInSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresInSeconds

`func (o *ClientTokenStatusResponse) SetExpiresInSeconds(v int32)`

SetExpiresInSeconds sets ExpiresInSeconds field to given value.

### HasExpiresInSeconds

`func (o *ClientTokenStatusResponse) HasExpiresInSeconds() bool`

HasExpiresInSeconds returns a boolean if a field has been set.

### SetExpiresInSecondsNil

`func (o *ClientTokenStatusResponse) SetExpiresInSecondsNil(b bool)`

 SetExpiresInSecondsNil sets the value for ExpiresInSeconds to be an explicit nil

### UnsetExpiresInSeconds
`func (o *ClientTokenStatusResponse) UnsetExpiresInSeconds()`

UnsetExpiresInSeconds ensures that no value is present for ExpiresInSeconds, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


