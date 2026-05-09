# IdentityProvider

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Provider** | Pointer to **string** |  | [optional] 
**Hostname** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewIdentityProvider

`func NewIdentityProvider() *IdentityProvider`

NewIdentityProvider instantiates a new IdentityProvider object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIdentityProviderWithDefaults

`func NewIdentityProviderWithDefaults() *IdentityProvider`

NewIdentityProviderWithDefaults instantiates a new IdentityProvider object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProvider

`func (o *IdentityProvider) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *IdentityProvider) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *IdentityProvider) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *IdentityProvider) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetHostname

`func (o *IdentityProvider) GetHostname() string`

GetHostname returns the Hostname field if non-nil, zero value otherwise.

### GetHostnameOk

`func (o *IdentityProvider) GetHostnameOk() (*string, bool)`

GetHostnameOk returns a tuple with the Hostname field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostname

`func (o *IdentityProvider) SetHostname(v string)`

SetHostname sets Hostname field to given value.

### HasHostname

`func (o *IdentityProvider) HasHostname() bool`

HasHostname returns a boolean if a field has been set.

### SetHostnameNil

`func (o *IdentityProvider) SetHostnameNil(b bool)`

 SetHostnameNil sets the value for Hostname to be an explicit nil

### UnsetHostname
`func (o *IdentityProvider) UnsetHostname()`

UnsetHostname ensures that no value is present for Hostname, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


