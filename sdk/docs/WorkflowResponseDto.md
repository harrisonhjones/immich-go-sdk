# WorkflowResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Actions** | [**[]WorkflowActionResponseDto**](WorkflowActionResponseDto.md) | Workflow actions | 
**CreatedAt** | **string** | Creation date | 
**Description** | **string** | Workflow description | 
**Enabled** | **bool** | Workflow enabled | 
**Filters** | [**[]WorkflowFilterResponseDto**](WorkflowFilterResponseDto.md) | Workflow filters | 
**Id** | **string** | Workflow ID | 
**Name** | **NullableString** | Workflow name | 
**OwnerId** | **string** | Owner user ID | 
**TriggerType** | [**PluginTriggerType**](PluginTriggerType.md) |  | 

## Methods

### NewWorkflowResponseDto

`func NewWorkflowResponseDto(actions []WorkflowActionResponseDto, createdAt string, description string, enabled bool, filters []WorkflowFilterResponseDto, id string, name NullableString, ownerId string, triggerType PluginTriggerType, ) *WorkflowResponseDto`

NewWorkflowResponseDto instantiates a new WorkflowResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowResponseDtoWithDefaults

`func NewWorkflowResponseDtoWithDefaults() *WorkflowResponseDto`

NewWorkflowResponseDtoWithDefaults instantiates a new WorkflowResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActions

`func (o *WorkflowResponseDto) GetActions() []WorkflowActionResponseDto`

GetActions returns the Actions field if non-nil, zero value otherwise.

### GetActionsOk

`func (o *WorkflowResponseDto) GetActionsOk() (*[]WorkflowActionResponseDto, bool)`

GetActionsOk returns a tuple with the Actions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActions

`func (o *WorkflowResponseDto) SetActions(v []WorkflowActionResponseDto)`

SetActions sets Actions field to given value.


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


### GetFilters

`func (o *WorkflowResponseDto) GetFilters() []WorkflowFilterResponseDto`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *WorkflowResponseDto) GetFiltersOk() (*[]WorkflowFilterResponseDto, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *WorkflowResponseDto) SetFilters(v []WorkflowFilterResponseDto)`

SetFilters sets Filters field to given value.


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
### GetOwnerId

`func (o *WorkflowResponseDto) GetOwnerId() string`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *WorkflowResponseDto) GetOwnerIdOk() (*string, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *WorkflowResponseDto) SetOwnerId(v string)`

SetOwnerId sets OwnerId field to given value.


### GetTriggerType

`func (o *WorkflowResponseDto) GetTriggerType() PluginTriggerType`

GetTriggerType returns the TriggerType field if non-nil, zero value otherwise.

### GetTriggerTypeOk

`func (o *WorkflowResponseDto) GetTriggerTypeOk() (*PluginTriggerType, bool)`

GetTriggerTypeOk returns a tuple with the TriggerType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriggerType

`func (o *WorkflowResponseDto) SetTriggerType(v PluginTriggerType)`

SetTriggerType sets TriggerType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


