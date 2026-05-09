# ClientUsageResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PlanTier** | **string** | Current plan family, such as free or paid. | 
**BillingMode** | **string** |  | 
**BillingStatus** | Pointer to **NullableString** |  | [optional] 
**FreeWindowLimit** | **int32** |  | 
**FreeWindowHours** | **int32** |  | 
**FreeWeeklyLimit** | **int32** |  | 
**WindowRequestsUsed** | **int32** |  | 
**WeeklyRequestsUsed** | **int32** |  | 
**WindowRequestsRemaining** | **int32** |  | 
**WeeklyRequestsRemaining** | **int32** |  | 
**BillingCycleValueMicros** | Pointer to **NullableInt32** |  | [optional] 
**BillingExtraValueMicros** | **int32** |  | 
**BillingValueMicrosUsed** | **int32** |  | 
**BillingValueMicrosReserved** | Pointer to **int32** | Paid usage value currently reserved by queued or running background jobs. | [optional] 
**BillingValueMicrosRemaining** | Pointer to **NullableInt32** |  | [optional] 
**UsagePercentRemaining** | Pointer to **NullableFloat32** |  | [optional] 
**CurrentPlanFinderDeliverableCostMicros** | Pointer to **NullableInt32** |  | [optional] 
**CurrentPlanFinderUndeliverableCostMicros** | Pointer to **NullableInt32** |  | [optional] 
**CurrentPlanProbeCostMicros** | Pointer to **NullableInt32** |  | [optional] 

## Methods

### NewClientUsageResponse

`func NewClientUsageResponse(planTier string, billingMode string, freeWindowLimit int32, freeWindowHours int32, freeWeeklyLimit int32, windowRequestsUsed int32, weeklyRequestsUsed int32, windowRequestsRemaining int32, weeklyRequestsRemaining int32, billingExtraValueMicros int32, billingValueMicrosUsed int32, ) *ClientUsageResponse`

NewClientUsageResponse instantiates a new ClientUsageResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewClientUsageResponseWithDefaults

`func NewClientUsageResponseWithDefaults() *ClientUsageResponse`

NewClientUsageResponseWithDefaults instantiates a new ClientUsageResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlanTier

`func (o *ClientUsageResponse) GetPlanTier() string`

GetPlanTier returns the PlanTier field if non-nil, zero value otherwise.

### GetPlanTierOk

`func (o *ClientUsageResponse) GetPlanTierOk() (*string, bool)`

GetPlanTierOk returns a tuple with the PlanTier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanTier

`func (o *ClientUsageResponse) SetPlanTier(v string)`

SetPlanTier sets PlanTier field to given value.


### GetBillingMode

`func (o *ClientUsageResponse) GetBillingMode() string`

GetBillingMode returns the BillingMode field if non-nil, zero value otherwise.

### GetBillingModeOk

`func (o *ClientUsageResponse) GetBillingModeOk() (*string, bool)`

GetBillingModeOk returns a tuple with the BillingMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingMode

`func (o *ClientUsageResponse) SetBillingMode(v string)`

SetBillingMode sets BillingMode field to given value.


### GetBillingStatus

`func (o *ClientUsageResponse) GetBillingStatus() string`

GetBillingStatus returns the BillingStatus field if non-nil, zero value otherwise.

### GetBillingStatusOk

`func (o *ClientUsageResponse) GetBillingStatusOk() (*string, bool)`

GetBillingStatusOk returns a tuple with the BillingStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingStatus

`func (o *ClientUsageResponse) SetBillingStatus(v string)`

SetBillingStatus sets BillingStatus field to given value.

### HasBillingStatus

`func (o *ClientUsageResponse) HasBillingStatus() bool`

HasBillingStatus returns a boolean if a field has been set.

### SetBillingStatusNil

`func (o *ClientUsageResponse) SetBillingStatusNil(b bool)`

 SetBillingStatusNil sets the value for BillingStatus to be an explicit nil

### UnsetBillingStatus
`func (o *ClientUsageResponse) UnsetBillingStatus()`

UnsetBillingStatus ensures that no value is present for BillingStatus, not even an explicit nil
### GetFreeWindowLimit

`func (o *ClientUsageResponse) GetFreeWindowLimit() int32`

GetFreeWindowLimit returns the FreeWindowLimit field if non-nil, zero value otherwise.

### GetFreeWindowLimitOk

`func (o *ClientUsageResponse) GetFreeWindowLimitOk() (*int32, bool)`

GetFreeWindowLimitOk returns a tuple with the FreeWindowLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreeWindowLimit

`func (o *ClientUsageResponse) SetFreeWindowLimit(v int32)`

SetFreeWindowLimit sets FreeWindowLimit field to given value.


### GetFreeWindowHours

`func (o *ClientUsageResponse) GetFreeWindowHours() int32`

GetFreeWindowHours returns the FreeWindowHours field if non-nil, zero value otherwise.

### GetFreeWindowHoursOk

`func (o *ClientUsageResponse) GetFreeWindowHoursOk() (*int32, bool)`

GetFreeWindowHoursOk returns a tuple with the FreeWindowHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreeWindowHours

`func (o *ClientUsageResponse) SetFreeWindowHours(v int32)`

SetFreeWindowHours sets FreeWindowHours field to given value.


### GetFreeWeeklyLimit

`func (o *ClientUsageResponse) GetFreeWeeklyLimit() int32`

GetFreeWeeklyLimit returns the FreeWeeklyLimit field if non-nil, zero value otherwise.

### GetFreeWeeklyLimitOk

`func (o *ClientUsageResponse) GetFreeWeeklyLimitOk() (*int32, bool)`

GetFreeWeeklyLimitOk returns a tuple with the FreeWeeklyLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFreeWeeklyLimit

`func (o *ClientUsageResponse) SetFreeWeeklyLimit(v int32)`

SetFreeWeeklyLimit sets FreeWeeklyLimit field to given value.


### GetWindowRequestsUsed

`func (o *ClientUsageResponse) GetWindowRequestsUsed() int32`

GetWindowRequestsUsed returns the WindowRequestsUsed field if non-nil, zero value otherwise.

### GetWindowRequestsUsedOk

`func (o *ClientUsageResponse) GetWindowRequestsUsedOk() (*int32, bool)`

GetWindowRequestsUsedOk returns a tuple with the WindowRequestsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowRequestsUsed

`func (o *ClientUsageResponse) SetWindowRequestsUsed(v int32)`

SetWindowRequestsUsed sets WindowRequestsUsed field to given value.


### GetWeeklyRequestsUsed

`func (o *ClientUsageResponse) GetWeeklyRequestsUsed() int32`

GetWeeklyRequestsUsed returns the WeeklyRequestsUsed field if non-nil, zero value otherwise.

### GetWeeklyRequestsUsedOk

`func (o *ClientUsageResponse) GetWeeklyRequestsUsedOk() (*int32, bool)`

GetWeeklyRequestsUsedOk returns a tuple with the WeeklyRequestsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeeklyRequestsUsed

`func (o *ClientUsageResponse) SetWeeklyRequestsUsed(v int32)`

SetWeeklyRequestsUsed sets WeeklyRequestsUsed field to given value.


### GetWindowRequestsRemaining

`func (o *ClientUsageResponse) GetWindowRequestsRemaining() int32`

GetWindowRequestsRemaining returns the WindowRequestsRemaining field if non-nil, zero value otherwise.

### GetWindowRequestsRemainingOk

`func (o *ClientUsageResponse) GetWindowRequestsRemainingOk() (*int32, bool)`

GetWindowRequestsRemainingOk returns a tuple with the WindowRequestsRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWindowRequestsRemaining

`func (o *ClientUsageResponse) SetWindowRequestsRemaining(v int32)`

SetWindowRequestsRemaining sets WindowRequestsRemaining field to given value.


### GetWeeklyRequestsRemaining

`func (o *ClientUsageResponse) GetWeeklyRequestsRemaining() int32`

GetWeeklyRequestsRemaining returns the WeeklyRequestsRemaining field if non-nil, zero value otherwise.

### GetWeeklyRequestsRemainingOk

`func (o *ClientUsageResponse) GetWeeklyRequestsRemainingOk() (*int32, bool)`

GetWeeklyRequestsRemainingOk returns a tuple with the WeeklyRequestsRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeeklyRequestsRemaining

`func (o *ClientUsageResponse) SetWeeklyRequestsRemaining(v int32)`

SetWeeklyRequestsRemaining sets WeeklyRequestsRemaining field to given value.


### GetBillingCycleValueMicros

`func (o *ClientUsageResponse) GetBillingCycleValueMicros() int32`

GetBillingCycleValueMicros returns the BillingCycleValueMicros field if non-nil, zero value otherwise.

### GetBillingCycleValueMicrosOk

`func (o *ClientUsageResponse) GetBillingCycleValueMicrosOk() (*int32, bool)`

GetBillingCycleValueMicrosOk returns a tuple with the BillingCycleValueMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingCycleValueMicros

`func (o *ClientUsageResponse) SetBillingCycleValueMicros(v int32)`

SetBillingCycleValueMicros sets BillingCycleValueMicros field to given value.

### HasBillingCycleValueMicros

`func (o *ClientUsageResponse) HasBillingCycleValueMicros() bool`

HasBillingCycleValueMicros returns a boolean if a field has been set.

### SetBillingCycleValueMicrosNil

`func (o *ClientUsageResponse) SetBillingCycleValueMicrosNil(b bool)`

 SetBillingCycleValueMicrosNil sets the value for BillingCycleValueMicros to be an explicit nil

### UnsetBillingCycleValueMicros
`func (o *ClientUsageResponse) UnsetBillingCycleValueMicros()`

UnsetBillingCycleValueMicros ensures that no value is present for BillingCycleValueMicros, not even an explicit nil
### GetBillingExtraValueMicros

`func (o *ClientUsageResponse) GetBillingExtraValueMicros() int32`

GetBillingExtraValueMicros returns the BillingExtraValueMicros field if non-nil, zero value otherwise.

### GetBillingExtraValueMicrosOk

`func (o *ClientUsageResponse) GetBillingExtraValueMicrosOk() (*int32, bool)`

GetBillingExtraValueMicrosOk returns a tuple with the BillingExtraValueMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingExtraValueMicros

`func (o *ClientUsageResponse) SetBillingExtraValueMicros(v int32)`

SetBillingExtraValueMicros sets BillingExtraValueMicros field to given value.


### GetBillingValueMicrosUsed

`func (o *ClientUsageResponse) GetBillingValueMicrosUsed() int32`

GetBillingValueMicrosUsed returns the BillingValueMicrosUsed field if non-nil, zero value otherwise.

### GetBillingValueMicrosUsedOk

`func (o *ClientUsageResponse) GetBillingValueMicrosUsedOk() (*int32, bool)`

GetBillingValueMicrosUsedOk returns a tuple with the BillingValueMicrosUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingValueMicrosUsed

`func (o *ClientUsageResponse) SetBillingValueMicrosUsed(v int32)`

SetBillingValueMicrosUsed sets BillingValueMicrosUsed field to given value.


### GetBillingValueMicrosReserved

`func (o *ClientUsageResponse) GetBillingValueMicrosReserved() int32`

GetBillingValueMicrosReserved returns the BillingValueMicrosReserved field if non-nil, zero value otherwise.

### GetBillingValueMicrosReservedOk

`func (o *ClientUsageResponse) GetBillingValueMicrosReservedOk() (*int32, bool)`

GetBillingValueMicrosReservedOk returns a tuple with the BillingValueMicrosReserved field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingValueMicrosReserved

`func (o *ClientUsageResponse) SetBillingValueMicrosReserved(v int32)`

SetBillingValueMicrosReserved sets BillingValueMicrosReserved field to given value.

### HasBillingValueMicrosReserved

`func (o *ClientUsageResponse) HasBillingValueMicrosReserved() bool`

HasBillingValueMicrosReserved returns a boolean if a field has been set.

### GetBillingValueMicrosRemaining

`func (o *ClientUsageResponse) GetBillingValueMicrosRemaining() int32`

GetBillingValueMicrosRemaining returns the BillingValueMicrosRemaining field if non-nil, zero value otherwise.

### GetBillingValueMicrosRemainingOk

`func (o *ClientUsageResponse) GetBillingValueMicrosRemainingOk() (*int32, bool)`

GetBillingValueMicrosRemainingOk returns a tuple with the BillingValueMicrosRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingValueMicrosRemaining

`func (o *ClientUsageResponse) SetBillingValueMicrosRemaining(v int32)`

SetBillingValueMicrosRemaining sets BillingValueMicrosRemaining field to given value.

### HasBillingValueMicrosRemaining

`func (o *ClientUsageResponse) HasBillingValueMicrosRemaining() bool`

HasBillingValueMicrosRemaining returns a boolean if a field has been set.

### SetBillingValueMicrosRemainingNil

`func (o *ClientUsageResponse) SetBillingValueMicrosRemainingNil(b bool)`

 SetBillingValueMicrosRemainingNil sets the value for BillingValueMicrosRemaining to be an explicit nil

### UnsetBillingValueMicrosRemaining
`func (o *ClientUsageResponse) UnsetBillingValueMicrosRemaining()`

UnsetBillingValueMicrosRemaining ensures that no value is present for BillingValueMicrosRemaining, not even an explicit nil
### GetUsagePercentRemaining

`func (o *ClientUsageResponse) GetUsagePercentRemaining() float32`

GetUsagePercentRemaining returns the UsagePercentRemaining field if non-nil, zero value otherwise.

### GetUsagePercentRemainingOk

`func (o *ClientUsageResponse) GetUsagePercentRemainingOk() (*float32, bool)`

GetUsagePercentRemainingOk returns a tuple with the UsagePercentRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsagePercentRemaining

`func (o *ClientUsageResponse) SetUsagePercentRemaining(v float32)`

SetUsagePercentRemaining sets UsagePercentRemaining field to given value.

### HasUsagePercentRemaining

`func (o *ClientUsageResponse) HasUsagePercentRemaining() bool`

HasUsagePercentRemaining returns a boolean if a field has been set.

### SetUsagePercentRemainingNil

`func (o *ClientUsageResponse) SetUsagePercentRemainingNil(b bool)`

 SetUsagePercentRemainingNil sets the value for UsagePercentRemaining to be an explicit nil

### UnsetUsagePercentRemaining
`func (o *ClientUsageResponse) UnsetUsagePercentRemaining()`

UnsetUsagePercentRemaining ensures that no value is present for UsagePercentRemaining, not even an explicit nil
### GetCurrentPlanFinderDeliverableCostMicros

`func (o *ClientUsageResponse) GetCurrentPlanFinderDeliverableCostMicros() int32`

GetCurrentPlanFinderDeliverableCostMicros returns the CurrentPlanFinderDeliverableCostMicros field if non-nil, zero value otherwise.

### GetCurrentPlanFinderDeliverableCostMicrosOk

`func (o *ClientUsageResponse) GetCurrentPlanFinderDeliverableCostMicrosOk() (*int32, bool)`

GetCurrentPlanFinderDeliverableCostMicrosOk returns a tuple with the CurrentPlanFinderDeliverableCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPlanFinderDeliverableCostMicros

`func (o *ClientUsageResponse) SetCurrentPlanFinderDeliverableCostMicros(v int32)`

SetCurrentPlanFinderDeliverableCostMicros sets CurrentPlanFinderDeliverableCostMicros field to given value.

### HasCurrentPlanFinderDeliverableCostMicros

`func (o *ClientUsageResponse) HasCurrentPlanFinderDeliverableCostMicros() bool`

HasCurrentPlanFinderDeliverableCostMicros returns a boolean if a field has been set.

### SetCurrentPlanFinderDeliverableCostMicrosNil

`func (o *ClientUsageResponse) SetCurrentPlanFinderDeliverableCostMicrosNil(b bool)`

 SetCurrentPlanFinderDeliverableCostMicrosNil sets the value for CurrentPlanFinderDeliverableCostMicros to be an explicit nil

### UnsetCurrentPlanFinderDeliverableCostMicros
`func (o *ClientUsageResponse) UnsetCurrentPlanFinderDeliverableCostMicros()`

UnsetCurrentPlanFinderDeliverableCostMicros ensures that no value is present for CurrentPlanFinderDeliverableCostMicros, not even an explicit nil
### GetCurrentPlanFinderUndeliverableCostMicros

`func (o *ClientUsageResponse) GetCurrentPlanFinderUndeliverableCostMicros() int32`

GetCurrentPlanFinderUndeliverableCostMicros returns the CurrentPlanFinderUndeliverableCostMicros field if non-nil, zero value otherwise.

### GetCurrentPlanFinderUndeliverableCostMicrosOk

`func (o *ClientUsageResponse) GetCurrentPlanFinderUndeliverableCostMicrosOk() (*int32, bool)`

GetCurrentPlanFinderUndeliverableCostMicrosOk returns a tuple with the CurrentPlanFinderUndeliverableCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPlanFinderUndeliverableCostMicros

`func (o *ClientUsageResponse) SetCurrentPlanFinderUndeliverableCostMicros(v int32)`

SetCurrentPlanFinderUndeliverableCostMicros sets CurrentPlanFinderUndeliverableCostMicros field to given value.

### HasCurrentPlanFinderUndeliverableCostMicros

`func (o *ClientUsageResponse) HasCurrentPlanFinderUndeliverableCostMicros() bool`

HasCurrentPlanFinderUndeliverableCostMicros returns a boolean if a field has been set.

### SetCurrentPlanFinderUndeliverableCostMicrosNil

`func (o *ClientUsageResponse) SetCurrentPlanFinderUndeliverableCostMicrosNil(b bool)`

 SetCurrentPlanFinderUndeliverableCostMicrosNil sets the value for CurrentPlanFinderUndeliverableCostMicros to be an explicit nil

### UnsetCurrentPlanFinderUndeliverableCostMicros
`func (o *ClientUsageResponse) UnsetCurrentPlanFinderUndeliverableCostMicros()`

UnsetCurrentPlanFinderUndeliverableCostMicros ensures that no value is present for CurrentPlanFinderUndeliverableCostMicros, not even an explicit nil
### GetCurrentPlanProbeCostMicros

`func (o *ClientUsageResponse) GetCurrentPlanProbeCostMicros() int32`

GetCurrentPlanProbeCostMicros returns the CurrentPlanProbeCostMicros field if non-nil, zero value otherwise.

### GetCurrentPlanProbeCostMicrosOk

`func (o *ClientUsageResponse) GetCurrentPlanProbeCostMicrosOk() (*int32, bool)`

GetCurrentPlanProbeCostMicrosOk returns a tuple with the CurrentPlanProbeCostMicros field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrentPlanProbeCostMicros

`func (o *ClientUsageResponse) SetCurrentPlanProbeCostMicros(v int32)`

SetCurrentPlanProbeCostMicros sets CurrentPlanProbeCostMicros field to given value.

### HasCurrentPlanProbeCostMicros

`func (o *ClientUsageResponse) HasCurrentPlanProbeCostMicros() bool`

HasCurrentPlanProbeCostMicros returns a boolean if a field has been set.

### SetCurrentPlanProbeCostMicrosNil

`func (o *ClientUsageResponse) SetCurrentPlanProbeCostMicrosNil(b bool)`

 SetCurrentPlanProbeCostMicrosNil sets the value for CurrentPlanProbeCostMicros to be an explicit nil

### UnsetCurrentPlanProbeCostMicros
`func (o *ClientUsageResponse) UnsetCurrentPlanProbeCostMicros()`

UnsetCurrentPlanProbeCostMicros ensures that no value is present for CurrentPlanProbeCostMicros, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


