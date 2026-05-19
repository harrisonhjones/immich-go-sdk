# PluginMethodResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | **string** | Description | 
**HostFunctions** | **bool** |  | 
**Key** | **string** | Key | 
**Name** | **string** | Name | 
**Schema** | Pointer to **map[string]interface{}** |  | [optional] 
**Title** | **string** | Title | 
**Types** | [**[]WorkflowType**](WorkflowType.md) | Workflow types | 
**UiHints** | **[]string** | Ui hints | 

## Methods

### NewPluginMethodResponseDto

`func NewPluginMethodResponseDto(description string, hostFunctions bool, key string, name string, title string, types []WorkflowType, uiHints []string, ) *PluginMethodResponseDto`

NewPluginMethodResponseDto instantiates a new PluginMethodResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginMethodResponseDtoWithDefaults

`func NewPluginMethodResponseDtoWithDefaults() *PluginMethodResponseDto`

NewPluginMethodResponseDtoWithDefaults instantiates a new PluginMethodResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *PluginMethodResponseDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PluginMethodResponseDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PluginMethodResponseDto) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetHostFunctions

`func (o *PluginMethodResponseDto) GetHostFunctions() bool`

GetHostFunctions returns the HostFunctions field if non-nil, zero value otherwise.

### GetHostFunctionsOk

`func (o *PluginMethodResponseDto) GetHostFunctionsOk() (*bool, bool)`

GetHostFunctionsOk returns a tuple with the HostFunctions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHostFunctions

`func (o *PluginMethodResponseDto) SetHostFunctions(v bool)`

SetHostFunctions sets HostFunctions field to given value.


### GetKey

`func (o *PluginMethodResponseDto) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *PluginMethodResponseDto) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *PluginMethodResponseDto) SetKey(v string)`

SetKey sets Key field to given value.


### GetName

`func (o *PluginMethodResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PluginMethodResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PluginMethodResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetSchema

`func (o *PluginMethodResponseDto) GetSchema() map[string]interface{}`

GetSchema returns the Schema field if non-nil, zero value otherwise.

### GetSchemaOk

`func (o *PluginMethodResponseDto) GetSchemaOk() (*map[string]interface{}, bool)`

GetSchemaOk returns a tuple with the Schema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchema

`func (o *PluginMethodResponseDto) SetSchema(v map[string]interface{})`

SetSchema sets Schema field to given value.

### HasSchema

`func (o *PluginMethodResponseDto) HasSchema() bool`

HasSchema returns a boolean if a field has been set.

### GetTitle

`func (o *PluginMethodResponseDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *PluginMethodResponseDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *PluginMethodResponseDto) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetTypes

`func (o *PluginMethodResponseDto) GetTypes() []WorkflowType`

GetTypes returns the Types field if non-nil, zero value otherwise.

### GetTypesOk

`func (o *PluginMethodResponseDto) GetTypesOk() (*[]WorkflowType, bool)`

GetTypesOk returns a tuple with the Types field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypes

`func (o *PluginMethodResponseDto) SetTypes(v []WorkflowType)`

SetTypes sets Types field to given value.


### GetUiHints

`func (o *PluginMethodResponseDto) GetUiHints() []string`

GetUiHints returns the UiHints field if non-nil, zero value otherwise.

### GetUiHintsOk

`func (o *PluginMethodResponseDto) GetUiHintsOk() (*[]string, bool)`

GetUiHintsOk returns a tuple with the UiHints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUiHints

`func (o *PluginMethodResponseDto) SetUiHints(v []string)`

SetUiHints sets UiHints field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


