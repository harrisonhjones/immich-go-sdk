# WorkflowCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **NullableString** | Workflow description | [optional] 
**Enabled** | Pointer to **bool** | Workflow enabled | [optional] 
**Name** | Pointer to **NullableString** | Workflow name | [optional] 
**Steps** | Pointer to [**[]WorkflowStepDto**](WorkflowStepDto.md) |  | [optional] 
**Trigger** | [**WorkflowTrigger**](WorkflowTrigger.md) |  | 

## Methods

### NewWorkflowCreateDto

`func NewWorkflowCreateDto(trigger WorkflowTrigger, ) *WorkflowCreateDto`

NewWorkflowCreateDto instantiates a new WorkflowCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowCreateDtoWithDefaults

`func NewWorkflowCreateDtoWithDefaults() *WorkflowCreateDto`

NewWorkflowCreateDtoWithDefaults instantiates a new WorkflowCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *WorkflowCreateDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *WorkflowCreateDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *WorkflowCreateDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *WorkflowCreateDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *WorkflowCreateDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *WorkflowCreateDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetEnabled

`func (o *WorkflowCreateDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *WorkflowCreateDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *WorkflowCreateDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *WorkflowCreateDto) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetName

`func (o *WorkflowCreateDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WorkflowCreateDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WorkflowCreateDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *WorkflowCreateDto) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *WorkflowCreateDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *WorkflowCreateDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetSteps

`func (o *WorkflowCreateDto) GetSteps() []WorkflowStepDto`

GetSteps returns the Steps field if non-nil, zero value otherwise.

### GetStepsOk

`func (o *WorkflowCreateDto) GetStepsOk() (*[]WorkflowStepDto, bool)`

GetStepsOk returns a tuple with the Steps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSteps

`func (o *WorkflowCreateDto) SetSteps(v []WorkflowStepDto)`

SetSteps sets Steps field to given value.

### HasSteps

`func (o *WorkflowCreateDto) HasSteps() bool`

HasSteps returns a boolean if a field has been set.

### GetTrigger

`func (o *WorkflowCreateDto) GetTrigger() WorkflowTrigger`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *WorkflowCreateDto) GetTriggerOk() (*WorkflowTrigger, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *WorkflowCreateDto) SetTrigger(v WorkflowTrigger)`

SetTrigger sets Trigger field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


