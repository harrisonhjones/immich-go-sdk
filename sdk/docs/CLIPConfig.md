# CLIPConfig

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** | Whether the task is enabled | 
**ModelName** | **string** | Name of the model to use | 

## Methods

### NewCLIPConfig

`func NewCLIPConfig(enabled bool, modelName string, ) *CLIPConfig`

NewCLIPConfig instantiates a new CLIPConfig object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCLIPConfigWithDefaults

`func NewCLIPConfigWithDefaults() *CLIPConfig`

NewCLIPConfigWithDefaults instantiates a new CLIPConfig object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *CLIPConfig) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *CLIPConfig) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *CLIPConfig) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetModelName

`func (o *CLIPConfig) GetModelName() string`

GetModelName returns the ModelName field if non-nil, zero value otherwise.

### GetModelNameOk

`func (o *CLIPConfig) GetModelNameOk() (*string, bool)`

GetModelNameOk returns a tuple with the ModelName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelName

`func (o *CLIPConfig) SetModelName(v string)`

SetModelName sets ModelName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


