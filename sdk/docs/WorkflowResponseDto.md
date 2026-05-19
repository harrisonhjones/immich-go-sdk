# WorkflowResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **string** | Creation date | 
**Description** | **NullableString** | Workflow description | 
**Enabled** | **bool** | Workflow enabled | 
**Id** | **string** | Workflow ID | 
**Name** | **NullableString** | Workflow name | 
**Steps** | [**[]WorkflowStepDto**](WorkflowStepDto.md) | Workflow steps | 
**Trigger** | [**WorkflowTrigger**](WorkflowTrigger.md) |  | 
**UpdatedAt** | **string** | Update date | 

## Methods

### NewWorkflowResponseDto

`func NewWorkflowResponseDto(createdAt string, description NullableString, enabled bool, id string, name NullableString, steps []WorkflowStepDto, trigger WorkflowTrigger, updatedAt string, ) *WorkflowResponseDto`

NewWorkflowResponseDto instantiates a new WorkflowResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowResponseDtoWithDefaults

`func NewWorkflowResponseDtoWithDefaults() *WorkflowResponseDto`

NewWorkflowResponseDtoWithDefaults instantiates a new WorkflowResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *WorkflowResponseDto) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *WorkflowResponseDto) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *WorkflowResponseDto) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDescription

`func (o *WorkflowResponseDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *WorkflowResponseDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *WorkflowResponseDto) SetDescription(v string)`

SetDescription sets Description field to given value.


### SetDescriptionNil

`func (o *WorkflowResponseDto) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *WorkflowResponseDto) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetEnabled

`func (o *WorkflowResponseDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *WorkflowResponseDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *WorkflowResponseDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetId

`func (o *WorkflowResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkflowResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkflowResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *WorkflowResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WorkflowResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WorkflowResponseDto) SetName(v string)`

SetName sets Name field to given value.


### SetNameNil

`func (o *WorkflowResponseDto) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *WorkflowResponseDto) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetSteps

`func (o *WorkflowResponseDto) GetSteps() []WorkflowStepDto`

GetSteps returns the Steps field if non-nil, zero value otherwise.

### GetStepsOk

`func (o *WorkflowResponseDto) GetStepsOk() (*[]WorkflowStepDto, bool)`

GetStepsOk returns a tuple with the Steps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSteps

`func (o *WorkflowResponseDto) SetSteps(v []WorkflowStepDto)`

SetSteps sets Steps field to given value.


### GetTrigger

`func (o *WorkflowResponseDto) GetTrigger() WorkflowTrigger`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *WorkflowResponseDto) GetTriggerOk() (*WorkflowTrigger, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *WorkflowResponseDto) SetTrigger(v WorkflowTrigger)`

SetTrigger sets Trigger field to given value.


### GetUpdatedAt

`func (o *WorkflowResponseDto) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *WorkflowResponseDto) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *WorkflowResponseDto) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


