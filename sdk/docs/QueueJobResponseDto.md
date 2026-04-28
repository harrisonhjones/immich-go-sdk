# QueueJobResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | **map[string]interface{}** | Job data payload | 
**Id** | Pointer to **string** | Job ID | [optional] 
**Name** | [**JobName**](JobName.md) |  | 
**Timestamp** | **int32** | Job creation timestamp | 

## Methods

### NewQueueJobResponseDto

`func NewQueueJobResponseDto(data map[string]interface{}, name JobName, timestamp int32, ) *QueueJobResponseDto`

NewQueueJobResponseDto instantiates a new QueueJobResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueueJobResponseDtoWithDefaults

`func NewQueueJobResponseDtoWithDefaults() *QueueJobResponseDto`

NewQueueJobResponseDtoWithDefaults instantiates a new QueueJobResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *QueueJobResponseDto) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *QueueJobResponseDto) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *QueueJobResponseDto) SetData(v map[string]interface{})`

SetData sets Data field to given value.


### GetId

`func (o *QueueJobResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *QueueJobResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *QueueJobResponseDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *QueueJobResponseDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *QueueJobResponseDto) GetName() JobName`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *QueueJobResponseDto) GetNameOk() (*JobName, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *QueueJobResponseDto) SetName(v JobName)`

SetName sets Name field to given value.


### GetTimestamp

`func (o *QueueJobResponseDto) GetTimestamp() int32`

GetTimestamp returns the Timestamp field if non-nil, zero value otherwise.

### GetTimestampOk

`func (o *QueueJobResponseDto) GetTimestampOk() (*int32, bool)`

GetTimestampOk returns a tuple with the Timestamp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimestamp

`func (o *QueueJobResponseDto) SetTimestamp(v int32)`

SetTimestamp sets Timestamp field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


