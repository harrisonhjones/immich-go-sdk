# PluginTemplateResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | **string** | Template description | 
**Key** | **string** | Template key (unique across all templates) | 
**Steps** | [**[]PluginTemplateStepResponseDto**](PluginTemplateStepResponseDto.md) | Workflow steps | 
**Title** | **string** | Template title | 
**Trigger** | [**WorkflowTrigger**](WorkflowTrigger.md) |  | 

## Methods

### NewPluginTemplateResponseDto

`func NewPluginTemplateResponseDto(description string, key string, steps []PluginTemplateStepResponseDto, title string, trigger WorkflowTrigger, ) *PluginTemplateResponseDto`

NewPluginTemplateResponseDto instantiates a new PluginTemplateResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginTemplateResponseDtoWithDefaults

`func NewPluginTemplateResponseDtoWithDefaults() *PluginTemplateResponseDto`

NewPluginTemplateResponseDtoWithDefaults instantiates a new PluginTemplateResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *PluginTemplateResponseDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PluginTemplateResponseDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PluginTemplateResponseDto) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetKey

`func (o *PluginTemplateResponseDto) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *PluginTemplateResponseDto) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *PluginTemplateResponseDto) SetKey(v string)`

SetKey sets Key field to given value.


### GetSteps

`func (o *PluginTemplateResponseDto) GetSteps() []PluginTemplateStepResponseDto`

GetSteps returns the Steps field if non-nil, zero value otherwise.

### GetStepsOk

`func (o *PluginTemplateResponseDto) GetStepsOk() (*[]PluginTemplateStepResponseDto, bool)`

GetStepsOk returns a tuple with the Steps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSteps

`func (o *PluginTemplateResponseDto) SetSteps(v []PluginTemplateStepResponseDto)`

SetSteps sets Steps field to given value.


### GetTitle

`func (o *PluginTemplateResponseDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *PluginTemplateResponseDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *PluginTemplateResponseDto) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetTrigger

`func (o *PluginTemplateResponseDto) GetTrigger() WorkflowTrigger`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *PluginTemplateResponseDto) GetTriggerOk() (*WorkflowTrigger, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *PluginTemplateResponseDto) SetTrigger(v WorkflowTrigger)`

SetTrigger sets Trigger field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


