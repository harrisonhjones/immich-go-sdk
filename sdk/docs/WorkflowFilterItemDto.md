# WorkflowFilterItemDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FilterConfig** | Pointer to **map[string]interface{}** |  | [optional] 
**PluginFilterId** | **string** | Plugin filter ID | 

## Methods

### NewWorkflowFilterItemDto

`func NewWorkflowFilterItemDto(pluginFilterId string, ) *WorkflowFilterItemDto`

NewWorkflowFilterItemDto instantiates a new WorkflowFilterItemDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowFilterItemDtoWithDefaults

`func NewWorkflowFilterItemDtoWithDefaults() *WorkflowFilterItemDto`

NewWorkflowFilterItemDtoWithDefaults instantiates a new WorkflowFilterItemDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFilterConfig

`func (o *WorkflowFilterItemDto) GetFilterConfig() map[string]interface{}`

GetFilterConfig returns the FilterConfig field if non-nil, zero value otherwise.

### GetFilterConfigOk

`func (o *WorkflowFilterItemDto) GetFilterConfigOk() (*map[string]interface{}, bool)`

GetFilterConfigOk returns a tuple with the FilterConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilterConfig

`func (o *WorkflowFilterItemDto) SetFilterConfig(v map[string]interface{})`

SetFilterConfig sets FilterConfig field to given value.

### HasFilterConfig

`func (o *WorkflowFilterItemDto) HasFilterConfig() bool`

HasFilterConfig returns a boolean if a field has been set.

### GetPluginFilterId

`func (o *WorkflowFilterItemDto) GetPluginFilterId() string`

GetPluginFilterId returns the PluginFilterId field if non-nil, zero value otherwise.

### GetPluginFilterIdOk

`func (o *WorkflowFilterItemDto) GetPluginFilterIdOk() (*string, bool)`

GetPluginFilterIdOk returns a tuple with the PluginFilterId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPluginFilterId

`func (o *WorkflowFilterItemDto) SetPluginFilterId(v string)`

SetPluginFilterId sets PluginFilterId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


