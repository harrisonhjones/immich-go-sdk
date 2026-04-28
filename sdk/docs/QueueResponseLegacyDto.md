# QueueResponseLegacyDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JobCounts** | [**QueueStatisticsDto**](QueueStatisticsDto.md) |  | 
**QueueStatus** | [**QueueStatusLegacyDto**](QueueStatusLegacyDto.md) |  | 

## Methods

### NewQueueResponseLegacyDto

`func NewQueueResponseLegacyDto(jobCounts QueueStatisticsDto, queueStatus QueueStatusLegacyDto, ) *QueueResponseLegacyDto`

NewQueueResponseLegacyDto instantiates a new QueueResponseLegacyDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueueResponseLegacyDtoWithDefaults

`func NewQueueResponseLegacyDtoWithDefaults() *QueueResponseLegacyDto`

NewQueueResponseLegacyDtoWithDefaults instantiates a new QueueResponseLegacyDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJobCounts

`func (o *QueueResponseLegacyDto) GetJobCounts() QueueStatisticsDto`

GetJobCounts returns the JobCounts field if non-nil, zero value otherwise.

### GetJobCountsOk

`func (o *QueueResponseLegacyDto) GetJobCountsOk() (*QueueStatisticsDto, bool)`

GetJobCountsOk returns a tuple with the JobCounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobCounts

`func (o *QueueResponseLegacyDto) SetJobCounts(v QueueStatisticsDto)`

SetJobCounts sets JobCounts field to given value.


### GetQueueStatus

`func (o *QueueResponseLegacyDto) GetQueueStatus() QueueStatusLegacyDto`

GetQueueStatus returns the QueueStatus field if non-nil, zero value otherwise.

### GetQueueStatusOk

`func (o *QueueResponseLegacyDto) GetQueueStatusOk() (*QueueStatusLegacyDto, bool)`

GetQueueStatusOk returns a tuple with the QueueStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueueStatus

`func (o *QueueResponseLegacyDto) SetQueueStatus(v QueueStatusLegacyDto)`

SetQueueStatus sets QueueStatus field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


