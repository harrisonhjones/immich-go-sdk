# QueueStatusLegacyDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IsActive** | **bool** | Whether the queue is currently active (has running jobs) | 
**IsPaused** | **bool** | Whether the queue is paused | 

## Methods

### NewQueueStatusLegacyDto

`func NewQueueStatusLegacyDto(isActive bool, isPaused bool, ) *QueueStatusLegacyDto`

NewQueueStatusLegacyDto instantiates a new QueueStatusLegacyDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueueStatusLegacyDtoWithDefaults

`func NewQueueStatusLegacyDtoWithDefaults() *QueueStatusLegacyDto`

NewQueueStatusLegacyDtoWithDefaults instantiates a new QueueStatusLegacyDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIsActive

`func (o *QueueStatusLegacyDto) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *QueueStatusLegacyDto) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *QueueStatusLegacyDto) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.


### GetIsPaused

`func (o *QueueStatusLegacyDto) GetIsPaused() bool`

GetIsPaused returns the IsPaused field if non-nil, zero value otherwise.

### GetIsPausedOk

`func (o *QueueStatusLegacyDto) GetIsPausedOk() (*bool, bool)`

GetIsPausedOk returns a tuple with the IsPaused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsPaused

`func (o *QueueStatusLegacyDto) SetIsPaused(v bool)`

SetIsPaused sets IsPaused field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


