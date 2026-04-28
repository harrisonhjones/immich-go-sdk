# QueueStatisticsDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Active** | **int32** | Number of active jobs | 
**Completed** | **int32** | Number of completed jobs | 
**Delayed** | **int32** | Number of delayed jobs | 
**Failed** | **int32** | Number of failed jobs | 
**Paused** | **int32** | Number of paused jobs | 
**Waiting** | **int32** | Number of waiting jobs | 

## Methods

### NewQueueStatisticsDto

`func NewQueueStatisticsDto(active int32, completed int32, delayed int32, failed int32, paused int32, waiting int32, ) *QueueStatisticsDto`

NewQueueStatisticsDto instantiates a new QueueStatisticsDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueueStatisticsDtoWithDefaults

`func NewQueueStatisticsDtoWithDefaults() *QueueStatisticsDto`

NewQueueStatisticsDtoWithDefaults instantiates a new QueueStatisticsDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActive

`func (o *QueueStatisticsDto) GetActive() int32`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *QueueStatisticsDto) GetActiveOk() (*int32, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *QueueStatisticsDto) SetActive(v int32)`

SetActive sets Active field to given value.


### GetCompleted

`func (o *QueueStatisticsDto) GetCompleted() int32`

GetCompleted returns the Completed field if non-nil, zero value otherwise.

### GetCompletedOk

`func (o *QueueStatisticsDto) GetCompletedOk() (*int32, bool)`

GetCompletedOk returns a tuple with the Completed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompleted

`func (o *QueueStatisticsDto) SetCompleted(v int32)`

SetCompleted sets Completed field to given value.


### GetDelayed

`func (o *QueueStatisticsDto) GetDelayed() int32`

GetDelayed returns the Delayed field if non-nil, zero value otherwise.

### GetDelayedOk

`func (o *QueueStatisticsDto) GetDelayedOk() (*int32, bool)`

GetDelayedOk returns a tuple with the Delayed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDelayed

`func (o *QueueStatisticsDto) SetDelayed(v int32)`

SetDelayed sets Delayed field to given value.


### GetFailed

`func (o *QueueStatisticsDto) GetFailed() int32`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *QueueStatisticsDto) GetFailedOk() (*int32, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *QueueStatisticsDto) SetFailed(v int32)`

SetFailed sets Failed field to given value.


### GetPaused

`func (o *QueueStatisticsDto) GetPaused() int32`

GetPaused returns the Paused field if non-nil, zero value otherwise.

### GetPausedOk

`func (o *QueueStatisticsDto) GetPausedOk() (*int32, bool)`

GetPausedOk returns a tuple with the Paused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaused

`func (o *QueueStatisticsDto) SetPaused(v int32)`

SetPaused sets Paused field to given value.


### GetWaiting

`func (o *QueueStatisticsDto) GetWaiting() int32`

GetWaiting returns the Waiting field if non-nil, zero value otherwise.

### GetWaitingOk

`func (o *QueueStatisticsDto) GetWaitingOk() (*int32, bool)`

GetWaitingOk returns a tuple with the Waiting field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWaiting

`func (o *QueueStatisticsDto) SetWaiting(v int32)`

SetWaiting sets Waiting field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


