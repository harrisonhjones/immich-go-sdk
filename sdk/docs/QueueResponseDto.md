# QueueResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsPaused** | **bool** | Whether the queue is paused | 
**Name** | [**QueueName**](QueueName.md) |  | 
**Statistics** | [**QueueStatisticsDto**](QueueStatisticsDto.md) |  | 

## Methods

### NewQueueResponseDto

`func NewQueueResponseDto(isPaused bool, name QueueName, statistics QueueStatisticsDto, ) *QueueResponseDto`

NewQueueResponseDto instantiates a new QueueResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueueResponseDtoWithDefaults

`func NewQueueResponseDtoWithDefaults() *QueueResponseDto`

NewQueueResponseDtoWithDefaults instantiates a new QueueResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsPaused

`func (o *QueueResponseDto) GetIsPaused() bool`

GetIsPaused returns the IsPaused field if non-nil, zero value otherwise.

### GetIsPausedOk

`func (o *QueueResponseDto) GetIsPausedOk() (*bool, bool)`

GetIsPausedOk returns a tuple with the IsPaused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPaused

`func (o *QueueResponseDto) SetIsPaused(v bool)`

SetIsPaused sets IsPaused field to given value.


### GetName

`func (o *QueueResponseDto) GetName() QueueName`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *QueueResponseDto) GetNameOk() (*QueueName, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *QueueResponseDto) SetName(v QueueName)`

SetName sets Name field to given value.


### GetStatistics

`func (o *QueueResponseDto) GetStatistics() QueueStatisticsDto`

GetStatistics returns the Statistics field if non-nil, zero value otherwise.

### GetStatisticsOk

`func (o *QueueResponseDto) GetStatisticsOk() (*QueueStatisticsDto, bool)`

GetStatisticsOk returns a tuple with the Statistics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatistics

`func (o *QueueResponseDto) SetStatistics(v QueueStatisticsDto)`

SetStatistics sets Statistics field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


