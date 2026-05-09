# ClientIdentityResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**State** | **string** | Final public deliverability verdict. | 
**Outcome** | Pointer to **string** | Operational outcome. &#x60;error&#x60; means the verification could not complete cleanly and should not be treated as a negative mailbox verdict. | [optional] 
**Address** | Pointer to **NullableString** |  | [optional] 
**IsAlias** | Pointer to **bool** | Whether the resolved address is an alias rather than a primary mailbox. | [optional] 
**Alias** | Pointer to [**ClientFinderResponseAlias**](ClientFinderResponseAlias.md) |  | [optional] 
**IsCatchall** | Pointer to **bool** | Whether the mailbox domain behaved like a catch-all during verification. | [optional] 
**IdentityProviders** | Pointer to [**[]IdentityProvider**](IdentityProvider.md) | Identity providers associated with the mailbox domain when available. | [optional] 
**MxHosts** | Pointer to **[]string** | Observed MX hosts for the mailbox domain. | [optional] 
**RequestId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewClientIdentityResponse

`func NewClientIdentityResponse(state string, ) *ClientIdentityResponse`

NewClientIdentityResponse instantiates a new ClientIdentityResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientIdentityResponseWithDefaults

`func NewClientIdentityResponseWithDefaults() *ClientIdentityResponse`

NewClientIdentityResponseWithDefaults instantiates a new ClientIdentityResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetState

`func (o *ClientIdentityResponse) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ClientIdentityResponse) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ClientIdentityResponse) SetState(v string)`

SetState sets State field to given value.


### GetOutcome

`func (o *ClientIdentityResponse) GetOutcome() string`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *ClientIdentityResponse) GetOutcomeOk() (*string, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *ClientIdentityResponse) SetOutcome(v string)`

SetOutcome sets Outcome field to given value.

### HasOutcome

`func (o *ClientIdentityResponse) HasOutcome() bool`

HasOutcome returns a boolean if a field has been set.

### GetAddress

`func (o *ClientIdentityResponse) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *ClientIdentityResponse) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *ClientIdentityResponse) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *ClientIdentityResponse) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *ClientIdentityResponse) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *ClientIdentityResponse) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetIsAlias

`func (o *ClientIdentityResponse) GetIsAlias() bool`

GetIsAlias returns the IsAlias field if non-nil, zero value otherwise.

### GetIsAliasOk

`func (o *ClientIdentityResponse) GetIsAliasOk() (*bool, bool)`

GetIsAliasOk returns a tuple with the IsAlias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAlias

`func (o *ClientIdentityResponse) SetIsAlias(v bool)`

SetIsAlias sets IsAlias field to given value.

### HasIsAlias

`func (o *ClientIdentityResponse) HasIsAlias() bool`

HasIsAlias returns a boolean if a field has been set.

### GetAlias

`func (o *ClientIdentityResponse) GetAlias() ClientFinderResponseAlias`

GetAlias returns the Alias field if non-nil, zero value otherwise.

### GetAliasOk

`func (o *ClientIdentityResponse) GetAliasOk() (*ClientFinderResponseAlias, bool)`

GetAliasOk returns a tuple with the Alias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlias

`func (o *ClientIdentityResponse) SetAlias(v ClientFinderResponseAlias)`

SetAlias sets Alias field to given value.

### HasAlias

`func (o *ClientIdentityResponse) HasAlias() bool`

HasAlias returns a boolean if a field has been set.

### GetIsCatchall

`func (o *ClientIdentityResponse) GetIsCatchall() bool`

GetIsCatchall returns the IsCatchall field if non-nil, zero value otherwise.

### GetIsCatchallOk

`func (o *ClientIdentityResponse) GetIsCatchallOk() (*bool, bool)`

GetIsCatchallOk returns a tuple with the IsCatchall field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCatchall

`func (o *ClientIdentityResponse) SetIsCatchall(v bool)`

SetIsCatchall sets IsCatchall field to given value.

### HasIsCatchall

`func (o *ClientIdentityResponse) HasIsCatchall() bool`

HasIsCatchall returns a boolean if a field has been set.

### GetIdentityProviders

`func (o *ClientIdentityResponse) GetIdentityProviders() []IdentityProvider`

GetIdentityProviders returns the IdentityProviders field if non-nil, zero value otherwise.

### GetIdentityProvidersOk

`func (o *ClientIdentityResponse) GetIdentityProvidersOk() (*[]IdentityProvider, bool)`

GetIdentityProvidersOk returns a tuple with the IdentityProviders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentityProviders

`func (o *ClientIdentityResponse) SetIdentityProviders(v []IdentityProvider)`

SetIdentityProviders sets IdentityProviders field to given value.

### HasIdentityProviders

`func (o *ClientIdentityResponse) HasIdentityProviders() bool`

HasIdentityProviders returns a boolean if a field has been set.

### GetMxHosts

`func (o *ClientIdentityResponse) GetMxHosts() []string`

GetMxHosts returns the MxHosts field if non-nil, zero value otherwise.

### GetMxHostsOk

`func (o *ClientIdentityResponse) GetMxHostsOk() (*[]string, bool)`

GetMxHostsOk returns a tuple with the MxHosts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMxHosts

`func (o *ClientIdentityResponse) SetMxHosts(v []string)`

SetMxHosts sets MxHosts field to given value.

### HasMxHosts

`func (o *ClientIdentityResponse) HasMxHosts() bool`

HasMxHosts returns a boolean if a field has been set.

### GetRequestId

`func (o *ClientIdentityResponse) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *ClientIdentityResponse) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *ClientIdentityResponse) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *ClientIdentityResponse) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.

### SetRequestIdNil

`func (o *ClientIdentityResponse) SetRequestIdNil(b bool)`

 SetRequestIdNil sets the value for RequestId to be an explicit nil

### UnsetRequestId
`func (o *ClientIdentityResponse) UnsetRequestId()`

UnsetRequestId ensures that no value is present for RequestId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


