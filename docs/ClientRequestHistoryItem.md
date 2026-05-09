# ClientRequestHistoryItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**RequestType** | **string** |  | 
**InputName** | Pointer to **NullableString** |  | [optional] 
**InputDomain** | Pointer to **NullableString** |  | [optional] 
**InputEmail** | Pointer to **NullableString** |  | [optional] 
**InputLabel** | **string** | Compact human-readable identifier for the original request input. | 
**State** | **string** |  | 
**Outcome** | **string** |  | 
**ResolvedAddress** | Pointer to **NullableString** |  | [optional] 
**DurationMs** | Pointer to **NullableInt32** |  | [optional] 
**Provider** | Pointer to **NullableString** |  | [optional] 
**IdentityProviders** | Pointer to **[]map[string]interface{}** |  | [optional] 
**MxHosts** | Pointer to **[]string** |  | [optional] 
**Metadata** | Pointer to **map[string]interface{}** | Small transport and outcome metadata associated with the request. | [optional] 
**IsAlias** | Pointer to **bool** |  | [optional] [default to false]
**IsCatchall** | Pointer to **bool** |  | [optional] [default to false]
**RequestId** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewClientRequestHistoryItem

`func NewClientRequestHistoryItem(id string, requestType string, inputLabel string, state string, outcome string, createdAt time.Time, ) *ClientRequestHistoryItem`

NewClientRequestHistoryItem instantiates a new ClientRequestHistoryItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientRequestHistoryItemWithDefaults

`func NewClientRequestHistoryItemWithDefaults() *ClientRequestHistoryItem`

NewClientRequestHistoryItemWithDefaults instantiates a new ClientRequestHistoryItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ClientRequestHistoryItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ClientRequestHistoryItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ClientRequestHistoryItem) SetId(v string)`

SetId sets Id field to given value.


### GetRequestType

`func (o *ClientRequestHistoryItem) GetRequestType() string`

GetRequestType returns the RequestType field if non-nil, zero value otherwise.

### GetRequestTypeOk

`func (o *ClientRequestHistoryItem) GetRequestTypeOk() (*string, bool)`

GetRequestTypeOk returns a tuple with the RequestType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestType

`func (o *ClientRequestHistoryItem) SetRequestType(v string)`

SetRequestType sets RequestType field to given value.


### GetInputName

`func (o *ClientRequestHistoryItem) GetInputName() string`

GetInputName returns the InputName field if non-nil, zero value otherwise.

### GetInputNameOk

`func (o *ClientRequestHistoryItem) GetInputNameOk() (*string, bool)`

GetInputNameOk returns a tuple with the InputName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputName

`func (o *ClientRequestHistoryItem) SetInputName(v string)`

SetInputName sets InputName field to given value.

### HasInputName

`func (o *ClientRequestHistoryItem) HasInputName() bool`

HasInputName returns a boolean if a field has been set.

### SetInputNameNil

`func (o *ClientRequestHistoryItem) SetInputNameNil(b bool)`

 SetInputNameNil sets the value for InputName to be an explicit nil

### UnsetInputName
`func (o *ClientRequestHistoryItem) UnsetInputName()`

UnsetInputName ensures that no value is present for InputName, not even an explicit nil
### GetInputDomain

`func (o *ClientRequestHistoryItem) GetInputDomain() string`

GetInputDomain returns the InputDomain field if non-nil, zero value otherwise.

### GetInputDomainOk

`func (o *ClientRequestHistoryItem) GetInputDomainOk() (*string, bool)`

GetInputDomainOk returns a tuple with the InputDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputDomain

`func (o *ClientRequestHistoryItem) SetInputDomain(v string)`

SetInputDomain sets InputDomain field to given value.

### HasInputDomain

`func (o *ClientRequestHistoryItem) HasInputDomain() bool`

HasInputDomain returns a boolean if a field has been set.

### SetInputDomainNil

`func (o *ClientRequestHistoryItem) SetInputDomainNil(b bool)`

 SetInputDomainNil sets the value for InputDomain to be an explicit nil

### UnsetInputDomain
`func (o *ClientRequestHistoryItem) UnsetInputDomain()`

UnsetInputDomain ensures that no value is present for InputDomain, not even an explicit nil
### GetInputEmail

`func (o *ClientRequestHistoryItem) GetInputEmail() string`

GetInputEmail returns the InputEmail field if non-nil, zero value otherwise.

### GetInputEmailOk

`func (o *ClientRequestHistoryItem) GetInputEmailOk() (*string, bool)`

GetInputEmailOk returns a tuple with the InputEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputEmail

`func (o *ClientRequestHistoryItem) SetInputEmail(v string)`

SetInputEmail sets InputEmail field to given value.

### HasInputEmail

`func (o *ClientRequestHistoryItem) HasInputEmail() bool`

HasInputEmail returns a boolean if a field has been set.

### SetInputEmailNil

`func (o *ClientRequestHistoryItem) SetInputEmailNil(b bool)`

 SetInputEmailNil sets the value for InputEmail to be an explicit nil

### UnsetInputEmail
`func (o *ClientRequestHistoryItem) UnsetInputEmail()`

UnsetInputEmail ensures that no value is present for InputEmail, not even an explicit nil
### GetInputLabel

`func (o *ClientRequestHistoryItem) GetInputLabel() string`

GetInputLabel returns the InputLabel field if non-nil, zero value otherwise.

### GetInputLabelOk

`func (o *ClientRequestHistoryItem) GetInputLabelOk() (*string, bool)`

GetInputLabelOk returns a tuple with the InputLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputLabel

`func (o *ClientRequestHistoryItem) SetInputLabel(v string)`

SetInputLabel sets InputLabel field to given value.


### GetState

`func (o *ClientRequestHistoryItem) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ClientRequestHistoryItem) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ClientRequestHistoryItem) SetState(v string)`

SetState sets State field to given value.


### GetOutcome

`func (o *ClientRequestHistoryItem) GetOutcome() string`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *ClientRequestHistoryItem) GetOutcomeOk() (*string, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *ClientRequestHistoryItem) SetOutcome(v string)`

SetOutcome sets Outcome field to given value.


### GetResolvedAddress

`func (o *ClientRequestHistoryItem) GetResolvedAddress() string`

GetResolvedAddress returns the ResolvedAddress field if non-nil, zero value otherwise.

### GetResolvedAddressOk

`func (o *ClientRequestHistoryItem) GetResolvedAddressOk() (*string, bool)`

GetResolvedAddressOk returns a tuple with the ResolvedAddress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolvedAddress

`func (o *ClientRequestHistoryItem) SetResolvedAddress(v string)`

SetResolvedAddress sets ResolvedAddress field to given value.

### HasResolvedAddress

`func (o *ClientRequestHistoryItem) HasResolvedAddress() bool`

HasResolvedAddress returns a boolean if a field has been set.

### SetResolvedAddressNil

`func (o *ClientRequestHistoryItem) SetResolvedAddressNil(b bool)`

 SetResolvedAddressNil sets the value for ResolvedAddress to be an explicit nil

### UnsetResolvedAddress
`func (o *ClientRequestHistoryItem) UnsetResolvedAddress()`

UnsetResolvedAddress ensures that no value is present for ResolvedAddress, not even an explicit nil
### GetDurationMs

`func (o *ClientRequestHistoryItem) GetDurationMs() int32`

GetDurationMs returns the DurationMs field if non-nil, zero value otherwise.

### GetDurationMsOk

`func (o *ClientRequestHistoryItem) GetDurationMsOk() (*int32, bool)`

GetDurationMsOk returns a tuple with the DurationMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationMs

`func (o *ClientRequestHistoryItem) SetDurationMs(v int32)`

SetDurationMs sets DurationMs field to given value.

### HasDurationMs

`func (o *ClientRequestHistoryItem) HasDurationMs() bool`

HasDurationMs returns a boolean if a field has been set.

### SetDurationMsNil

`func (o *ClientRequestHistoryItem) SetDurationMsNil(b bool)`

 SetDurationMsNil sets the value for DurationMs to be an explicit nil

### UnsetDurationMs
`func (o *ClientRequestHistoryItem) UnsetDurationMs()`

UnsetDurationMs ensures that no value is present for DurationMs, not even an explicit nil
### GetProvider

`func (o *ClientRequestHistoryItem) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ClientRequestHistoryItem) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ClientRequestHistoryItem) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *ClientRequestHistoryItem) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *ClientRequestHistoryItem) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *ClientRequestHistoryItem) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetIdentityProviders

`func (o *ClientRequestHistoryItem) GetIdentityProviders() []map[string]interface{}`

GetIdentityProviders returns the IdentityProviders field if non-nil, zero value otherwise.

### GetIdentityProvidersOk

`func (o *ClientRequestHistoryItem) GetIdentityProvidersOk() (*[]map[string]interface{}, bool)`

GetIdentityProvidersOk returns a tuple with the IdentityProviders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentityProviders

`func (o *ClientRequestHistoryItem) SetIdentityProviders(v []map[string]interface{})`

SetIdentityProviders sets IdentityProviders field to given value.

### HasIdentityProviders

`func (o *ClientRequestHistoryItem) HasIdentityProviders() bool`

HasIdentityProviders returns a boolean if a field has been set.

### GetMxHosts

`func (o *ClientRequestHistoryItem) GetMxHosts() []string`

GetMxHosts returns the MxHosts field if non-nil, zero value otherwise.

### GetMxHostsOk

`func (o *ClientRequestHistoryItem) GetMxHostsOk() (*[]string, bool)`

GetMxHostsOk returns a tuple with the MxHosts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMxHosts

`func (o *ClientRequestHistoryItem) SetMxHosts(v []string)`

SetMxHosts sets MxHosts field to given value.

### HasMxHosts

`func (o *ClientRequestHistoryItem) HasMxHosts() bool`

HasMxHosts returns a boolean if a field has been set.

### GetMetadata

`func (o *ClientRequestHistoryItem) GetMetadata() map[string]interface{}`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *ClientRequestHistoryItem) GetMetadataOk() (*map[string]interface{}, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *ClientRequestHistoryItem) SetMetadata(v map[string]interface{})`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *ClientRequestHistoryItem) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.

### GetIsAlias

`func (o *ClientRequestHistoryItem) GetIsAlias() bool`

GetIsAlias returns the IsAlias field if non-nil, zero value otherwise.

### GetIsAliasOk

`func (o *ClientRequestHistoryItem) GetIsAliasOk() (*bool, bool)`

GetIsAliasOk returns a tuple with the IsAlias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAlias

`func (o *ClientRequestHistoryItem) SetIsAlias(v bool)`

SetIsAlias sets IsAlias field to given value.

### HasIsAlias

`func (o *ClientRequestHistoryItem) HasIsAlias() bool`

HasIsAlias returns a boolean if a field has been set.

### GetIsCatchall

`func (o *ClientRequestHistoryItem) GetIsCatchall() bool`

GetIsCatchall returns the IsCatchall field if non-nil, zero value otherwise.

### GetIsCatchallOk

`func (o *ClientRequestHistoryItem) GetIsCatchallOk() (*bool, bool)`

GetIsCatchallOk returns a tuple with the IsCatchall field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsCatchall

`func (o *ClientRequestHistoryItem) SetIsCatchall(v bool)`

SetIsCatchall sets IsCatchall field to given value.

### HasIsCatchall

`func (o *ClientRequestHistoryItem) HasIsCatchall() bool`

HasIsCatchall returns a boolean if a field has been set.

### GetRequestId

`func (o *ClientRequestHistoryItem) GetRequestId() string`

GetRequestId returns the RequestId field if non-nil, zero value otherwise.

### GetRequestIdOk

`func (o *ClientRequestHistoryItem) GetRequestIdOk() (*string, bool)`

GetRequestIdOk returns a tuple with the RequestId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequestId

`func (o *ClientRequestHistoryItem) SetRequestId(v string)`

SetRequestId sets RequestId field to given value.

### HasRequestId

`func (o *ClientRequestHistoryItem) HasRequestId() bool`

HasRequestId returns a boolean if a field has been set.

### SetRequestIdNil

`func (o *ClientRequestHistoryItem) SetRequestIdNil(b bool)`

 SetRequestIdNil sets the value for RequestId to be an explicit nil

### UnsetRequestId
`func (o *ClientRequestHistoryItem) UnsetRequestId()`

UnsetRequestId ensures that no value is present for RequestId, not even an explicit nil
### GetCreatedAt

`func (o *ClientRequestHistoryItem) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ClientRequestHistoryItem) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ClientRequestHistoryItem) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


