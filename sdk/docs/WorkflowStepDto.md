# WorkflowStepDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Config** | **map[string]interface{}** | Step configuration | 
**Enabled** | Pointer to **bool** | Step is enabled | [optional] 
**Method** | **string** | Step plugin method | 

## Methods

### NewWorkflowStepDto

`func NewWorkflowStepDto(config map[string]interface{}, method string, ) *WorkflowStepDto`

NewWorkflowStepDto instantiates a new WorkflowStepDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkflowStepDtoWithDefaults

`func NewWorkflowStepDtoWithDefaults() *WorkflowStepDto`

NewWorkflowStepDtoWithDefaults instantiates a new WorkflowStepDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfig

`func (o *WorkflowStepDto) GetConfig() map[string]interface{}`

GetConfig returns the Config field if non-nil, zero value otherwise.

### GetConfigOk

`func (o *WorkflowStepDto) GetConfigOk() (*map[string]interface{}, bool)`

GetConfigOk returns a tuple with the Config field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfig

`func (o *WorkflowStepDto) SetConfig(v map[string]interface{})`

SetConfig sets Config field to given value.


### SetConfigNil

`func (o *WorkflowStepDto) SetConfigNil(b bool)`

 SetConfigNil sets the value for Config to be an explicit nil

### UnsetConfig
`func (o *WorkflowStepDto) UnsetConfig()`

UnsetConfig ensures that no value is present for Config, not even an explicit nil
### GetEnabled

`func (o *WorkflowStepDto) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *WorkflowStepDto) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *WorkflowStepDto) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *WorkflowStepDto) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetMethod

`func (o *WorkflowStepDto) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *WorkflowStepDto) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *WorkflowStepDto) SetMethod(v string)`

SetMethod sets Method field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


