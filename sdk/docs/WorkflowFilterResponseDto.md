# WorkflowFilterResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FilterConfig** | **map[string]interface{}** |  | 
**Id** | **string** | Filter ID | 
**Order** | **float32** | Filter order | 
**PluginFilterId** | **string** | Plugin filter ID | 
**WorkflowId** | **string** | Workflow ID | 

## Methods

### NewWorkflowFilterResponseDto

`func NewWorkflowFilterResponseDto(filterConfig map[string]interface{}, id string, order float32, pluginFilterId string, workflowId string, ) *WorkflowFilterResponseDto`

NewWorkflowFilterResponseDto instantiates a new WorkflowFilterResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowFilterResponseDtoWithDefaults

`func NewWorkflowFilterResponseDtoWithDefaults() *WorkflowFilterResponseDto`

NewWorkflowFilterResponseDtoWithDefaults instantiates a new WorkflowFilterResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFilterConfig

`func (o *WorkflowFilterResponseDto) GetFilterConfig() map[string]interface{}`

GetFilterConfig returns the FilterConfig field if non-nil, zero value otherwise.

### GetFilterConfigOk

`func (o *WorkflowFilterResponseDto) GetFilterConfigOk() (*map[string]interface{}, bool)`

GetFilterConfigOk returns a tuple with the FilterConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterConfig

`func (o *WorkflowFilterResponseDto) SetFilterConfig(v map[string]interface{})`

SetFilterConfig sets FilterConfig field to given value.


### SetFilterConfigNil

`func (o *WorkflowFilterResponseDto) SetFilterConfigNil(b bool)`

 SetFilterConfigNil sets the value for FilterConfig to be an explicit nil

### UnsetFilterConfig
`func (o *WorkflowFilterResponseDto) UnsetFilterConfig()`

UnsetFilterConfig ensures that no value is present for FilterConfig, not even an explicit nil
### GetId

`func (o *WorkflowFilterResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WorkflowFilterResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WorkflowFilterResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetOrder

`func (o *WorkflowFilterResponseDto) GetOrder() float32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *WorkflowFilterResponseDto) GetOrderOk() (*float32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *WorkflowFilterResponseDto) SetOrder(v float32)`

SetOrder sets Order field to given value.


### GetPluginFilterId

`func (o *WorkflowFilterResponseDto) GetPluginFilterId() string`

GetPluginFilterId returns the PluginFilterId field if non-nil, zero value otherwise.

### GetPluginFilterIdOk

`func (o *WorkflowFilterResponseDto) GetPluginFilterIdOk() (*string, bool)`

GetPluginFilterIdOk returns a tuple with the PluginFilterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPluginFilterId

`func (o *WorkflowFilterResponseDto) SetPluginFilterId(v string)`

SetPluginFilterId sets PluginFilterId field to given value.


### GetWorkflowId

`func (o *WorkflowFilterResponseDto) GetWorkflowId() string`

GetWorkflowId returns the WorkflowId field if non-nil, zero value otherwise.

### GetWorkflowIdOk

`func (o *WorkflowFilterResponseDto) GetWorkflowIdOk() (*string, bool)`

GetWorkflowIdOk returns a tuple with the WorkflowId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowId

`func (o *WorkflowFilterResponseDto) SetWorkflowId(v string)`

SetWorkflowId sets WorkflowId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


