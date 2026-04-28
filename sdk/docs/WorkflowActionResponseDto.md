# WorkflowActionResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActionConfig** | **map[string]interface{}** |  | 
**Id** | **string** | Action ID | 
**Order** | **int32** | Action order | 
**PluginActionId** | **string** | Plugin action ID | 
**WorkflowId** | **string** | Workflow ID | 

## Methods

### NewWorkflowActionResponseDto

`func NewWorkflowActionResponseDto(actionConfig map[string]interface{}, id string, order int32, pluginActionId string, workflowId string, ) *WorkflowActionResponseDto`

NewWorkflowActionResponseDto instantiates a new WorkflowActionResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowActionResponseDtoWithDefaults

`func NewWorkflowActionResponseDtoWithDefaults() *WorkflowActionResponseDto`

NewWorkflowActionResponseDtoWithDefaults instantiates a new WorkflowActionResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActionConfig

`func (o *WorkflowActionResponseDto) GetActionConfig() map[string]interface{}`

GetActionConfig returns the ActionConfig field if non-nil, zero value otherwise.

### GetActionConfigOk

`func (o *WorkflowActionResponseDto) GetActionConfigOk() (*map[string]interface{}, bool)`

GetActionConfigOk returns a tuple with the ActionConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActionConfig

`func (o *WorkflowActionResponseDto) SetActionConfig(v map[string]interface{})`

SetActionConfig sets ActionConfig field to given value.


### SetActionConfigNil

`func (o *WorkflowActionResponseDto) SetActionConfigNil(b bool)`

 SetActionConfigNil sets the value for ActionConfig to be an explicit nil

### UnsetActionConfig
`func (o *WorkflowActionResponseDto) UnsetActionConfig()`

UnsetActionConfig ensures that no value is present for ActionConfig, not even an explicit nil
### GetId

`func (o *WorkflowActionResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkflowActionResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkflowActionResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetOrder

`func (o *WorkflowActionResponseDto) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *WorkflowActionResponseDto) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *WorkflowActionResponseDto) SetOrder(v int32)`

SetOrder sets Order field to given value.


### GetPluginActionId

`func (o *WorkflowActionResponseDto) GetPluginActionId() string`

GetPluginActionId returns the PluginActionId field if non-nil, zero value otherwise.

### GetPluginActionIdOk

`func (o *WorkflowActionResponseDto) GetPluginActionIdOk() (*string, bool)`

GetPluginActionIdOk returns a tuple with the PluginActionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPluginActionId

`func (o *WorkflowActionResponseDto) SetPluginActionId(v string)`

SetPluginActionId sets PluginActionId field to given value.


### GetWorkflowId

`func (o *WorkflowActionResponseDto) GetWorkflowId() string`

GetWorkflowId returns the WorkflowId field if non-nil, zero value otherwise.

### GetWorkflowIdOk

`func (o *WorkflowActionResponseDto) GetWorkflowIdOk() (*string, bool)`

GetWorkflowIdOk returns a tuple with the WorkflowId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowId

`func (o *WorkflowActionResponseDto) SetWorkflowId(v string)`

SetWorkflowId sets WorkflowId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


