# PluginJsonSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdditionalPropertiesField** | Pointer to **bool** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Properties** | Pointer to [**map[string]PluginJsonSchemaProperty**](PluginJsonSchemaProperty.md) |  | [optional] 
**Required** | Pointer to **[]string** |  | [optional] 
**Type** | Pointer to [**PluginJsonSchemaType**](PluginJsonSchemaType.md) |  | [optional] 

## Methods

### NewPluginJsonSchema

`func NewPluginJsonSchema() *PluginJsonSchema`

NewPluginJsonSchema instantiates a new PluginJsonSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginJsonSchemaWithDefaults

`func NewPluginJsonSchemaWithDefaults() *PluginJsonSchema`

NewPluginJsonSchemaWithDefaults instantiates a new PluginJsonSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdditionalPropertiesField

`func (o *PluginJsonSchema) GetAdditionalPropertiesField() bool`

GetAdditionalPropertiesField returns the AdditionalPropertiesField field if non-nil, zero value otherwise.

### GetAdditionalPropertiesFieldOk

`func (o *PluginJsonSchema) GetAdditionalPropertiesFieldOk() (*bool, bool)`

GetAdditionalPropertiesFieldOk returns a tuple with the AdditionalPropertiesField field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalPropertiesField

`func (o *PluginJsonSchema) SetAdditionalPropertiesField(v bool)`

SetAdditionalPropertiesField sets AdditionalPropertiesField field to given value.

### HasAdditionalPropertiesField

`func (o *PluginJsonSchema) HasAdditionalPropertiesField() bool`

HasAdditionalPropertiesField returns a boolean if a field has been set.

### GetDescription

`func (o *PluginJsonSchema) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PluginJsonSchema) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PluginJsonSchema) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PluginJsonSchema) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetProperties

`func (o *PluginJsonSchema) GetProperties() map[string]PluginJsonSchemaProperty`

GetProperties returns the Properties field if non-nil, zero value otherwise.

### GetPropertiesOk

`func (o *PluginJsonSchema) GetPropertiesOk() (*map[string]PluginJsonSchemaProperty, bool)`

GetPropertiesOk returns a tuple with the Properties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperties

`func (o *PluginJsonSchema) SetProperties(v map[string]PluginJsonSchemaProperty)`

SetProperties sets Properties field to given value.

### HasProperties

`func (o *PluginJsonSchema) HasProperties() bool`

HasProperties returns a boolean if a field has been set.

### GetRequired

`func (o *PluginJsonSchema) GetRequired() []string`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *PluginJsonSchema) GetRequiredOk() (*[]string, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *PluginJsonSchema) SetRequired(v []string)`

SetRequired sets Required field to given value.

### HasRequired

`func (o *PluginJsonSchema) HasRequired() bool`

HasRequired returns a boolean if a field has been set.

### GetType

`func (o *PluginJsonSchema) GetType() PluginJsonSchemaType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PluginJsonSchema) GetTypeOk() (*PluginJsonSchemaType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PluginJsonSchema) SetType(v PluginJsonSchemaType)`

SetType sets Type field to given value.

### HasType

`func (o *PluginJsonSchema) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


