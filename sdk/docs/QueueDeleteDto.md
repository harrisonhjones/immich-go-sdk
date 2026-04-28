# QueueDeleteDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Failed** | Pointer to **bool** | If true, will also remove failed jobs from the queue. | [optional] 

## Methods

### NewQueueDeleteDto

`func NewQueueDeleteDto() *QueueDeleteDto`

NewQueueDeleteDto instantiates a new QueueDeleteDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueueDeleteDtoWithDefaults

`func NewQueueDeleteDtoWithDefaults() *QueueDeleteDto`

NewQueueDeleteDtoWithDefaults instantiates a new QueueDeleteDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFailed

`func (o *QueueDeleteDto) GetFailed() bool`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *QueueDeleteDto) GetFailedOk() (*bool, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *QueueDeleteDto) SetFailed(v bool)`

SetFailed sets Failed field to given value.

### HasFailed

`func (o *QueueDeleteDto) HasFailed() bool`

HasFailed returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


