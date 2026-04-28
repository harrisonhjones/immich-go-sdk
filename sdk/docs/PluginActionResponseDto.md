# PluginActionResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | **string** | Action description | 
**Id** | **string** | Action ID | 
**MethodName** | **string** | Method name | 
**PluginId** | **string** | Plugin ID | 
**Schema** | [**NullablePluginJsonSchema**](PluginJsonSchema.md) | Action schema | 
**SupportedContexts** | [**[]PluginContextType**](PluginContextType.md) | Supported contexts | 
**Title** | **string** | Action title | 

## Methods

### NewPluginActionResponseDto

`func NewPluginActionResponseDto(description string, id string, methodName string, pluginId string, schema NullablePluginJsonSchema, supportedContexts []PluginContextType, title string, ) *PluginActionResponseDto`

NewPluginActionResponseDto instantiates a new PluginActionResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginActionResponseDtoWithDefaults

`func NewPluginActionResponseDtoWithDefaults() *PluginActionResponseDto`

NewPluginActionResponseDtoWithDefaults instantiates a new PluginActionResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *PluginActionResponseDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PluginActionResponseDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PluginActionResponseDto) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetId

`func (o *PluginActionResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PluginActionResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PluginActionResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetMethodName

`func (o *PluginActionResponseDto) GetMethodName() string`

GetMethodName returns the MethodName field if non-nil, zero value otherwise.

### GetMethodNameOk

`func (o *PluginActionResponseDto) GetMethodNameOk() (*string, bool)`

GetMethodNameOk returns a tuple with the MethodName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethodName

`func (o *PluginActionResponseDto) SetMethodName(v string)`

SetMethodName sets MethodName field to given value.


### GetPluginId

`func (o *PluginActionResponseDto) GetPluginId() string`

GetPluginId returns the PluginId field if non-nil, zero value otherwise.

### GetPluginIdOk

`func (o *PluginActionResponseDto) GetPluginIdOk() (*string, bool)`

GetPluginIdOk returns a tuple with the PluginId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPluginId

`func (o *PluginActionResponseDto) SetPluginId(v string)`

SetPluginId sets PluginId field to given value.


### GetSchema

`func (o *PluginActionResponseDto) GetSchema() PluginJsonSchema`

GetSchema returns the Schema field if non-nil, zero value otherwise.

### GetSchemaOk

`func (o *PluginActionResponseDto) GetSchemaOk() (*PluginJsonSchema, bool)`

GetSchemaOk returns a tuple with the Schema field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchema

`func (o *PluginActionResponseDto) SetSchema(v PluginJsonSchema)`

SetSchema sets Schema field to given value.


### SetSchemaNil

`func (o *PluginActionResponseDto) SetSchemaNil(b bool)`

 SetSchemaNil sets the value for Schema to be an explicit nil

### UnsetSchema
`func (o *PluginActionResponseDto) UnsetSchema()`

UnsetSchema ensures that no value is present for Schema, not even an explicit nil
### GetSupportedContexts

`func (o *PluginActionResponseDto) GetSupportedContexts() []PluginContextType`

GetSupportedContexts returns the SupportedContexts field if non-nil, zero value otherwise.

### GetSupportedContextsOk

`func (o *PluginActionResponseDto) GetSupportedContextsOk() (*[]PluginContextType, bool)`

GetSupportedContextsOk returns a tuple with the SupportedContexts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportedContexts

`func (o *PluginActionResponseDto) SetSupportedContexts(v []PluginContextType)`

SetSupportedContexts sets SupportedContexts field to given value.


### GetTitle

`func (o *PluginActionResponseDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *PluginActionResponseDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *PluginActionResponseDto) SetTitle(v string)`

SetTitle sets Title field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


