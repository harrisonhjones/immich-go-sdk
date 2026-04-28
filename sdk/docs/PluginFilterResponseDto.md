# PluginFilterResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | **string** | Filter description | 
**Id** | **string** | Filter ID | 
**MethodName** | **string** | Method name | 
**PluginId** | **string** | Plugin ID | 
**Schema** | [**NullablePluginJsonSchema**](PluginJsonSchema.md) | Filter schema | 
**SupportedContexts** | [**[]PluginContextType**](PluginContextType.md) | Supported contexts | 
**Title** | **string** | Filter title | 

## Methods

### NewPluginFilterResponseDto

`func NewPluginFilterResponseDto(description string, id string, methodName string, pluginId string, schema NullablePluginJsonSchema, supportedContexts []PluginContextType, title string, ) *PluginFilterResponseDto`

NewPluginFilterResponseDto instantiates a new PluginFilterResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginFilterResponseDtoWithDefaults

`func NewPluginFilterResponseDtoWithDefaults() *PluginFilterResponseDto`

NewPluginFilterResponseDtoWithDefaults instantiates a new PluginFilterResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *PluginFilterResponseDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PluginFilterResponseDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PluginFilterResponseDto) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetId

`func (o *PluginFilterResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PluginFilterResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PluginFilterResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetMethodName

`func (o *PluginFilterResponseDto) GetMethodName() string`

GetMethodName returns the MethodName field if non-nil, zero value otherwise.

### GetMethodNameOk

`func (o *PluginFilterResponseDto) GetMethodNameOk() (*string, bool)`

GetMethodNameOk returns a tuple with the MethodName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethodName

`func (o *PluginFilterResponseDto) SetMethodName(v string)`

SetMethodName sets MethodName field to given value.


### GetPluginId

`func (o *PluginFilterResponseDto) GetPluginId() string`

GetPluginId returns the PluginId field if non-nil, zero value otherwise.

### GetPluginIdOk

`func (o *PluginFilterResponseDto) GetPluginIdOk() (*string, bool)`

GetPluginIdOk returns a tuple with the PluginId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPluginId

`func (o *PluginFilterResponseDto) SetPluginId(v string)`

SetPluginId sets PluginId field to given value.


### GetSchema

`func (o *PluginFilterResponseDto) GetSchema() PluginJsonSchema`

GetSchema returns the Schema field if non-nil, zero value otherwise.

### GetSchemaOk

`func (o *PluginFilterResponseDto) GetSchemaOk() (*PluginJsonSchema, bool)`

GetSchemaOk returns a tuple with the Schema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchema

`func (o *PluginFilterResponseDto) SetSchema(v PluginJsonSchema)`

SetSchema sets Schema field to given value.


### SetSchemaNil

`func (o *PluginFilterResponseDto) SetSchemaNil(b bool)`

 SetSchemaNil sets the value for Schema to be an explicit nil

### UnsetSchema
`func (o *PluginFilterResponseDto) UnsetSchema()`

UnsetSchema ensures that no value is present for Schema, not even an explicit nil
### GetSupportedContexts

`func (o *PluginFilterResponseDto) GetSupportedContexts() []PluginContextType`

GetSupportedContexts returns the SupportedContexts field if non-nil, zero value otherwise.

### GetSupportedContextsOk

`func (o *PluginFilterResponseDto) GetSupportedContextsOk() (*[]PluginContextType, bool)`

GetSupportedContextsOk returns a tuple with the SupportedContexts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportedContexts

`func (o *PluginFilterResponseDto) SetSupportedContexts(v []PluginContextType)`

SetSupportedContexts sets SupportedContexts field to given value.


### GetTitle

`func (o *PluginFilterResponseDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *PluginFilterResponseDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *PluginFilterResponseDto) SetTitle(v string)`

SetTitle sets Title field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


