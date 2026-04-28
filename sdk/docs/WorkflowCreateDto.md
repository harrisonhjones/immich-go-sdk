# WorkflowCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Actions** | [**[]WorkflowActionItemDto**](WorkflowActionItemDto.md) | Workflow actions | 
**Description** | Pointer to **string** | Workflow description | [optional] 
**Enabled** | Pointer to **bool** | Workflow enabled | [optional] 
**Filters** | [**[]WorkflowFilterItemDto**](WorkflowFilterItemDto.md) | Workflow filters | 
**Name** | **string** | Workflow name | 
**TriggerType** | [**PluginTriggerType**](PluginTriggerType.md) |  | 

## Methods

### NewWorkflowCreateDto

`func NewWorkflowCreateDto(actions []WorkflowActionItemDto, filters []WorkflowFilterItemDto, name string, triggerType PluginTriggerType, ) *WorkflowCreateDto`

NewWorkflowCreateDto instantiates a new WorkflowCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowCreateDtoWithDefaults

`func NewWorkflowCreateDtoWithDefaults() *WorkflowCreateDto`

NewWorkflowCreateDtoWithDefaults instantiates a new WorkflowCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActions

`func (o *WorkflowCreateDto) GetActions() []WorkflowActionItemDto`

GetActions returns the Actions field if non-nil, zero value otherwise.

### GetActionsOk

`func (o *WorkflowCreateDto) GetActionsOk() (*[]WorkflowActionItemDto, bool)`

GetActionsOk returns a tuple with the Actions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActions

`func (o *WorkflowCreateDto) SetActions(v []WorkflowActionItemDto)`

SetActions sets Actions field to given value.


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

### GetFilters

`func (o *WorkflowCreateDto) GetFilters() []WorkflowFilterItemDto`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *WorkflowCreateDto) GetFiltersOk() (*[]WorkflowFilterItemDto, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *WorkflowCreateDto) SetFilters(v []WorkflowFilterItemDto)`

SetFilters sets Filters field to given value.


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


### GetTriggerType

`func (o *WorkflowCreateDto) GetTriggerType() PluginTriggerType`

GetTriggerType returns the TriggerType field if non-nil, zero value otherwise.

### GetTriggerTypeOk

`func (o *WorkflowCreateDto) GetTriggerTypeOk() (*PluginTriggerType, bool)`

GetTriggerTypeOk returns a tuple with the TriggerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerType

`func (o *WorkflowCreateDto) SetTriggerType(v PluginTriggerType)`

SetTriggerType sets TriggerType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


