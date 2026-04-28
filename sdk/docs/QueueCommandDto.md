# QueueCommandDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Command** | [**QueueCommand**](QueueCommand.md) |  | 
**Force** | Pointer to **bool** | Force the command execution (if applicable) | [optional] 

## Methods

### NewQueueCommandDto

`func NewQueueCommandDto(command QueueCommand, ) *QueueCommandDto`

NewQueueCommandDto instantiates a new QueueCommandDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueueCommandDtoWithDefaults

`func NewQueueCommandDtoWithDefaults() *QueueCommandDto`

NewQueueCommandDtoWithDefaults instantiates a new QueueCommandDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCommand

`func (o *QueueCommandDto) GetCommand() QueueCommand`

GetCommand returns the Command field if non-nil, zero value otherwise.

### GetCommandOk

`func (o *QueueCommandDto) GetCommandOk() (*QueueCommand, bool)`

GetCommandOk returns a tuple with the Command field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommand

`func (o *QueueCommandDto) SetCommand(v QueueCommand)`

SetCommand sets Command field to given value.


### GetForce

`func (o *QueueCommandDto) GetForce() bool`

GetForce returns the Force field if non-nil, zero value otherwise.

### GetForceOk

`func (o *QueueCommandDto) GetForceOk() (*bool, bool)`

GetForceOk returns a tuple with the Force field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForce

`func (o *QueueCommandDto) SetForce(v bool)`

SetForce sets Force field to given value.

### HasForce

`func (o *QueueCommandDto) HasForce() bool`

HasForce returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


