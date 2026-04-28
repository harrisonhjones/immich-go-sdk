# WorkflowUpdateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Actions** | Pointer to [**[]WorkflowActionItemDto**](WorkflowActionItemDto.md) | Workflow actions | [optional] 
**Description** | Pointer to **string** | Workflow description | [optional] 
**Enabled** | Pointer to **bool** | Workflow enabled | [optional] 
**Filters** | Pointer to [**[]WorkflowFilterItemDto**](WorkflowFilterItemDto.md) | Workflow filters | [optional] 
**Name** | Pointer to **string** | Workflow name | [optional] 
**TriggerType** | Pointer to [**PluginTriggerType**](PluginTriggerType.md) |  | [optional] 

## Methods

### NewWorkflowUpdateDto

`func NewWorkflowUpdateDto() *WorkflowUpdateDto`

NewWorkflowUpdateDto instantiates a new WorkflowUpdateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowUpdateDtoWithDefaults

`func NewWorkflowUpdateDtoWithDefaults() *WorkflowUpdateDto`

NewWorkflowUpdateDtoWithDefaults instantiates a new WorkflowUpdateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActions

`func (o *WorkflowUpdateDto) GetActions() []WorkflowActionItemDto`

GetActions returns the Actions field if non-nil, zero value otherwise.

### GetActionsOk

`func (o *WorkflowUpdateDto) GetActionsOk() (*[]WorkflowActionItemDto, bool)`

GetActionsOk returns a tuple with the Actions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActions

`func (o *WorkflowUpdateDto) SetActions(v []WorkflowActionItemDto)`

SetActions sets Actions field to given value.

### HasActions

`func (o *WorkflowUpdateDto) HasActions() bool`

HasActions returns a boolean if a field has been set.

### GetDescription

`func (o *WorkflowUpdateDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *WorkflowUpdateDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *WorkflowUpdateDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *WorkflowUpdateDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEnabled

`func (o *WorkflowUpdateDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *WorkflowUpdateDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *WorkflowUpdateDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *WorkflowUpdateDto) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetFilters

`func (o *WorkflowUpdateDto) GetFilters() []WorkflowFilterItemDto`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *WorkflowUpdateDto) GetFiltersOk() (*[]WorkflowFilterItemDto, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *WorkflowUpdateDto) SetFilters(v []WorkflowFilterItemDto)`

SetFilters sets Filters field to given value.

### HasFilters

`func (o *WorkflowUpdateDto) HasFilters() bool`

HasFilters returns a boolean if a field has been set.

### GetName

`func (o *WorkflowUpdateDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WorkflowUpdateDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WorkflowUpdateDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *WorkflowUpdateDto) HasName() bool`

HasName returns a boolean if a field has been set.

### GetTriggerType

`func (o *WorkflowUpdateDto) GetTriggerType() PluginTriggerType`

GetTriggerType returns the TriggerType field if non-nil, zero value otherwise.

### GetTriggerTypeOk

`func (o *WorkflowUpdateDto) GetTriggerTypeOk() (*PluginTriggerType, bool)`

GetTriggerTypeOk returns a tuple with the TriggerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerType

`func (o *WorkflowUpdateDto) SetTriggerType(v PluginTriggerType)`

SetTriggerType sets TriggerType field to given value.

### HasTriggerType

`func (o *WorkflowUpdateDto) HasTriggerType() bool`

HasTriggerType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


