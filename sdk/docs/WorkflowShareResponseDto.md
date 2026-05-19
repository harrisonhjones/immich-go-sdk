# WorkflowShareResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | **NullableString** | Workflow description | 
**Name** | **NullableString** | Workflow name | 
**Steps** | [**[]WorkflowShareStepDto**](WorkflowShareStepDto.md) | Workflow steps | 
**Trigger** | [**WorkflowTrigger**](WorkflowTrigger.md) |  | 

## Methods

### NewWorkflowShareResponseDto

`func NewWorkflowShareResponseDto(description NullableString, name NullableString, steps []WorkflowShareStepDto, trigger WorkflowTrigger, ) *WorkflowShareResponseDto`

NewWorkflowShareResponseDto instantiates a new WorkflowShareResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowShareResponseDtoWithDefaults

`func NewWorkflowShareResponseDtoWithDefaults() *WorkflowShareResponseDto`

NewWorkflowShareResponseDtoWithDefaults instantiates a new WorkflowShareResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *WorkflowShareResponseDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *WorkflowShareResponseDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *WorkflowShareResponseDto) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *WorkflowShareResponseDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *WorkflowShareResponseDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetName

`func (o *WorkflowShareResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WorkflowShareResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WorkflowShareResponseDto) SetName(v string)`

SetName sets Name field to given value.


### SetNameNil

`func (o *WorkflowShareResponseDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *WorkflowShareResponseDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetSteps

`func (o *WorkflowShareResponseDto) GetSteps() []WorkflowShareStepDto`

GetSteps returns the Steps field if non-nil, zero value otherwise.

### GetStepsOk

`func (o *WorkflowShareResponseDto) GetStepsOk() (*[]WorkflowShareStepDto, bool)`

GetStepsOk returns a tuple with the Steps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSteps

`func (o *WorkflowShareResponseDto) SetSteps(v []WorkflowShareStepDto)`

SetSteps sets Steps field to given value.


### GetTrigger

`func (o *WorkflowShareResponseDto) GetTrigger() WorkflowTrigger`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *WorkflowShareResponseDto) GetTriggerOk() (*WorkflowTrigger, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *WorkflowShareResponseDto) SetTrigger(v WorkflowTrigger)`

SetTrigger sets Trigger field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


