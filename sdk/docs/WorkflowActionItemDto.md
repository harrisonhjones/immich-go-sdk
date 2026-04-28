# WorkflowActionItemDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActionConfig** | Pointer to **map[string]interface{}** |  | [optional] 
**PluginActionId** | **string** | Plugin action ID | 

## Methods

### NewWorkflowActionItemDto

`func NewWorkflowActionItemDto(pluginActionId string, ) *WorkflowActionItemDto`

NewWorkflowActionItemDto instantiates a new WorkflowActionItemDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowActionItemDtoWithDefaults

`func NewWorkflowActionItemDtoWithDefaults() *WorkflowActionItemDto`

NewWorkflowActionItemDtoWithDefaults instantiates a new WorkflowActionItemDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActionConfig

`func (o *WorkflowActionItemDto) GetActionConfig() map[string]interface{}`

GetActionConfig returns the ActionConfig field if non-nil, zero value otherwise.

### GetActionConfigOk

`func (o *WorkflowActionItemDto) GetActionConfigOk() (*map[string]interface{}, bool)`

GetActionConfigOk returns a tuple with the ActionConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionConfig

`func (o *WorkflowActionItemDto) SetActionConfig(v map[string]interface{})`

SetActionConfig sets ActionConfig field to given value.

### HasActionConfig

`func (o *WorkflowActionItemDto) HasActionConfig() bool`

HasActionConfig returns a boolean if a field has been set.

### GetPluginActionId

`func (o *WorkflowActionItemDto) GetPluginActionId() string`

GetPluginActionId returns the PluginActionId field if non-nil, zero value otherwise.

### GetPluginActionIdOk

`func (o *WorkflowActionItemDto) GetPluginActionIdOk() (*string, bool)`

GetPluginActionIdOk returns a tuple with the PluginActionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPluginActionId

`func (o *WorkflowActionItemDto) SetPluginActionId(v string)`

SetPluginActionId sets PluginActionId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


