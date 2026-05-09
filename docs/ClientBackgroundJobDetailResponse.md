# ClientBackgroundJobDetailResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Job** | [**ClientBackgroundJobResponse**](ClientBackgroundJobResponse.md) |  | 
**Items** | [**[]ClientBackgroundJobItemResponse**](ClientBackgroundJobItemResponse.md) |  | 
**TotalItems** | **int32** |  | 
**Page** | **int32** |  | 
**PageSize** | **int32** |  | 
**TotalPages** | **int32** |  | 
**ResultsExpired** | Pointer to **bool** | Whether the stored item payload rows have already expired and been pruned. | [optional] 

## Methods

### NewClientBackgroundJobDetailResponse

`func NewClientBackgroundJobDetailResponse(job ClientBackgroundJobResponse, items []ClientBackgroundJobItemResponse, totalItems int32, page int32, pageSize int32, totalPages int32, ) *ClientBackgroundJobDetailResponse`

NewClientBackgroundJobDetailResponse instantiates a new ClientBackgroundJobDetailResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientBackgroundJobDetailResponseWithDefaults

`func NewClientBackgroundJobDetailResponseWithDefaults() *ClientBackgroundJobDetailResponse`

NewClientBackgroundJobDetailResponseWithDefaults instantiates a new ClientBackgroundJobDetailResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJob

`func (o *ClientBackgroundJobDetailResponse) GetJob() ClientBackgroundJobResponse`

GetJob returns the Job field if non-nil, zero value otherwise.

### GetJobOk

`func (o *ClientBackgroundJobDetailResponse) GetJobOk() (*ClientBackgroundJobResponse, bool)`

GetJobOk returns a tuple with the Job field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJob

`func (o *ClientBackgroundJobDetailResponse) SetJob(v ClientBackgroundJobResponse)`

SetJob sets Job field to given value.


### GetItems

`func (o *ClientBackgroundJobDetailResponse) GetItems() []ClientBackgroundJobItemResponse`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *ClientBackgroundJobDetailResponse) GetItemsOk() (*[]ClientBackgroundJobItemResponse, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *ClientBackgroundJobDetailResponse) SetItems(v []ClientBackgroundJobItemResponse)`

SetItems sets Items field to given value.


### GetTotalItems

`func (o *ClientBackgroundJobDetailResponse) GetTotalItems() int32`

GetTotalItems returns the TotalItems field if non-nil, zero value otherwise.

### GetTotalItemsOk

`func (o *ClientBackgroundJobDetailResponse) GetTotalItemsOk() (*int32, bool)`

GetTotalItemsOk returns a tuple with the TotalItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalItems

`func (o *ClientBackgroundJobDetailResponse) SetTotalItems(v int32)`

SetTotalItems sets TotalItems field to given value.


### GetPage

`func (o *ClientBackgroundJobDetailResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ClientBackgroundJobDetailResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ClientBackgroundJobDetailResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetPageSize

`func (o *ClientBackgroundJobDetailResponse) GetPageSize() int32`

GetPageSize returns the PageSize field if non-nil, zero value otherwise.

### GetPageSizeOk

`func (o *ClientBackgroundJobDetailResponse) GetPageSizeOk() (*int32, bool)`

GetPageSizeOk returns a tuple with the PageSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageSize

`func (o *ClientBackgroundJobDetailResponse) SetPageSize(v int32)`

SetPageSize sets PageSize field to given value.


### GetTotalPages

`func (o *ClientBackgroundJobDetailResponse) GetTotalPages() int32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *ClientBackgroundJobDetailResponse) GetTotalPagesOk() (*int32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *ClientBackgroundJobDetailResponse) SetTotalPages(v int32)`

SetTotalPages sets TotalPages field to given value.


### GetResultsExpired

`func (o *ClientBackgroundJobDetailResponse) GetResultsExpired() bool`

GetResultsExpired returns the ResultsExpired field if non-nil, zero value otherwise.

### GetResultsExpiredOk

`func (o *ClientBackgroundJobDetailResponse) GetResultsExpiredOk() (*bool, bool)`

GetResultsExpiredOk returns a tuple with the ResultsExpired field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResultsExpired

`func (o *ClientBackgroundJobDetailResponse) SetResultsExpired(v bool)`

SetResultsExpired sets ResultsExpired field to given value.

### HasResultsExpired

`func (o *ClientBackgroundJobDetailResponse) HasResultsExpired() bool`

HasResultsExpired returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


