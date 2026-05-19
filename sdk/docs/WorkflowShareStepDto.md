# WorkflowShareStepDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | **map[string]interface{}** | Step configuration | 
**Enabled** | Pointer to **bool** | Step is enabled | [optional] 
**Method** | **string** | Step plugin method | 

## Methods

### NewWorkflowShareStepDto

`func NewWorkflowShareStepDto(config map[string]interface{}, method string, ) *WorkflowShareStepDto`

NewWorkflowShareStepDto instantiates a new WorkflowShareStepDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowShareStepDtoWithDefaults

`func NewWorkflowShareStepDtoWithDefaults() *WorkflowShareStepDto`

NewWorkflowShareStepDtoWithDefaults instantiates a new WorkflowShareStepDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *WorkflowShareStepDto) GetConfig() map[string]interface{}`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *WorkflowShareStepDto) GetConfigOk() (*map[string]interface{}, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *WorkflowShareStepDto) SetConfig(v map[string]interface{})`

SetConfig sets Config field to given value.


### SetConfigNil

`func (o *WorkflowShareStepDto) SetConfigNil(b bool)`

 SetConfigNil sets the value for Config to be an explicit nil

### UnsetConfig
`func (o *WorkflowShareStepDto) UnsetConfig()`

UnsetConfig ensures that no value is present for Config, not even an explicit nil
### GetEnabled

`func (o *WorkflowShareStepDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *WorkflowShareStepDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *WorkflowShareStepDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *WorkflowShareStepDto) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetMethod

`func (o *WorkflowShareStepDto) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *WorkflowShareStepDto) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *WorkflowShareStepDto) SetMethod(v string)`

SetMethod sets Method field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


