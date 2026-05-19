# WorkflowTriggerResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Trigger** | [**WorkflowTrigger**](WorkflowTrigger.md) |  | 
**Types** | [**[]WorkflowType**](WorkflowType.md) | Workflow types | 

## Methods

### NewWorkflowTriggerResponseDto

`func NewWorkflowTriggerResponseDto(trigger WorkflowTrigger, types []WorkflowType, ) *WorkflowTriggerResponseDto`

NewWorkflowTriggerResponseDto instantiates a new WorkflowTriggerResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowTriggerResponseDtoWithDefaults

`func NewWorkflowTriggerResponseDtoWithDefaults() *WorkflowTriggerResponseDto`

NewWorkflowTriggerResponseDtoWithDefaults instantiates a new WorkflowTriggerResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTrigger

`func (o *WorkflowTriggerResponseDto) GetTrigger() WorkflowTrigger`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *WorkflowTriggerResponseDto) GetTriggerOk() (*WorkflowTrigger, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *WorkflowTriggerResponseDto) SetTrigger(v WorkflowTrigger)`

SetTrigger sets Trigger field to given value.


### GetTypes

`func (o *WorkflowTriggerResponseDto) GetTypes() []WorkflowType`

GetTypes returns the Types field if non-nil, zero value otherwise.

### GetTypesOk

`func (o *WorkflowTriggerResponseDto) GetTypesOk() (*[]WorkflowType, bool)`

GetTypesOk returns a tuple with the Types field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypes

`func (o *WorkflowTriggerResponseDto) SetTypes(v []WorkflowType)`

SetTypes sets Types field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


