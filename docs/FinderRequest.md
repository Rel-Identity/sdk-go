# FinderRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FullName** | **string** | The real person&#39;s full name. Include middle names or initials when known. | 
**EmailDomain** | **string** | The company&#39;s public website or mailbox domain. | 

## Methods

### NewFinderRequest

`func NewFinderRequest(fullName string, emailDomain string, ) *FinderRequest`

NewFinderRequest instantiates a new FinderRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFinderRequestWithDefaults

`func NewFinderRequestWithDefaults() *FinderRequest`

NewFinderRequestWithDefaults instantiates a new FinderRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFullName

`func (o *FinderRequest) GetFullName() string`

GetFullName returns the FullName field if non-nil, zero value otherwise.

### GetFullNameOk

`func (o *FinderRequest) GetFullNameOk() (*string, bool)`

GetFullNameOk returns a tuple with the FullName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFullName

`func (o *FinderRequest) SetFullName(v string)`

SetFullName sets FullName field to given value.


### GetEmailDomain

`func (o *FinderRequest) GetEmailDomain() string`

GetEmailDomain returns the EmailDomain field if non-nil, zero value otherwise.

### GetEmailDomainOk

`func (o *FinderRequest) GetEmailDomainOk() (*string, bool)`

GetEmailDomainOk returns a tuple with the EmailDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmailDomain

`func (o *FinderRequest) SetEmailDomain(v string)`

SetEmailDomain sets EmailDomain field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


