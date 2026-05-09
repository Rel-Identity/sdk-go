# ClientRequestHistoryPageResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]ClientRequestHistoryItem**](ClientRequestHistoryItem.md) |  | 
**Total** | **int32** |  | 
**Page** | **int32** |  | 
**PageSize** | **int32** |  | 
**TotalPages** | **int32** |  | 

## Methods

### NewClientRequestHistoryPageResponse

`func NewClientRequestHistoryPageResponse(items []ClientRequestHistoryItem, total int32, page int32, pageSize int32, totalPages int32, ) *ClientRequestHistoryPageResponse`

NewClientRequestHistoryPageResponse instantiates a new ClientRequestHistoryPageResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientRequestHistoryPageResponseWithDefaults

`func NewClientRequestHistoryPageResponseWithDefaults() *ClientRequestHistoryPageResponse`

NewClientRequestHistoryPageResponseWithDefaults instantiates a new ClientRequestHistoryPageResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *ClientRequestHistoryPageResponse) GetItems() []ClientRequestHistoryItem`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *ClientRequestHistoryPageResponse) GetItemsOk() (*[]ClientRequestHistoryItem, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *ClientRequestHistoryPageResponse) SetItems(v []ClientRequestHistoryItem)`

SetItems sets Items field to given value.


### GetTotal

`func (o *ClientRequestHistoryPageResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ClientRequestHistoryPageResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ClientRequestHistoryPageResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetPage

`func (o *ClientRequestHistoryPageResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ClientRequestHistoryPageResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ClientRequestHistoryPageResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPageSize

`func (o *ClientRequestHistoryPageResponse) GetPageSize() int32`

GetPageSize returns the PageSize field if non-nil, zero value otherwise.

### GetPageSizeOk

`func (o *ClientRequestHistoryPageResponse) GetPageSizeOk() (*int32, bool)`

GetPageSizeOk returns a tuple with the PageSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageSize

`func (o *ClientRequestHistoryPageResponse) SetPageSize(v int32)`

SetPageSize sets PageSize field to given value.


### GetTotalPages

`func (o *ClientRequestHistoryPageResponse) GetTotalPages() int32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *ClientRequestHistoryPageResponse) GetTotalPagesOk() (*int32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *ClientRequestHistoryPageResponse) SetTotalPages(v int32)`

SetTotalPages sets TotalPages field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


