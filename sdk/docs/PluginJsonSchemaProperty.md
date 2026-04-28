# PluginJsonSchemaProperty

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AdditionalPropertiesField** | Pointer to [**PluginJsonSchemaPropertyAdditionalProperties**](PluginJsonSchemaPropertyAdditionalProperties.md) |  | [optional] 
**Default** | Pointer to **interface{}** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**Enum** | Pointer to **[]string** |  | [optional] 
**Items** | Pointer to [**PluginJsonSchemaProperty**](PluginJsonSchemaProperty.md) |  | [optional] 
**Properties** | Pointer to [**map[string]PluginJsonSchemaProperty**](PluginJsonSchemaProperty.md) |  | [optional] 
**Required** | Pointer to **[]string** |  | [optional] 
**Type** | Pointer to [**PluginJsonSchemaType**](PluginJsonSchemaType.md) |  | [optional] 

## Methods

### NewPluginJsonSchemaProperty

`func NewPluginJsonSchemaProperty() *PluginJsonSchemaProperty`

NewPluginJsonSchemaProperty instantiates a new PluginJsonSchemaProperty object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginJsonSchemaPropertyWithDefaults

`func NewPluginJsonSchemaPropertyWithDefaults() *PluginJsonSchemaProperty`

NewPluginJsonSchemaPropertyWithDefaults instantiates a new PluginJsonSchemaProperty object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAdditionalPropertiesField

`func (o *PluginJsonSchemaProperty) GetAdditionalPropertiesField() PluginJsonSchemaPropertyAdditionalProperties`

GetAdditionalPropertiesField returns the AdditionalPropertiesField field if non-nil, zero value otherwise.

### GetAdditionalPropertiesFieldOk

`func (o *PluginJsonSchemaProperty) GetAdditionalPropertiesFieldOk() (*PluginJsonSchemaPropertyAdditionalProperties, bool)`

GetAdditionalPropertiesFieldOk returns a tuple with the AdditionalPropertiesField field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalPropertiesField

`func (o *PluginJsonSchemaProperty) SetAdditionalPropertiesField(v PluginJsonSchemaPropertyAdditionalProperties)`

SetAdditionalPropertiesField sets AdditionalPropertiesField field to given value.

### HasAdditionalPropertiesField

`func (o *PluginJsonSchemaProperty) HasAdditionalPropertiesField() bool`

HasAdditionalPropertiesField returns a boolean if a field has been set.

### GetDefault

`func (o *PluginJsonSchemaProperty) GetDefault() interface{}`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *PluginJsonSchemaProperty) GetDefaultOk() (*interface{}, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *PluginJsonSchemaProperty) SetDefault(v interface{})`

SetDefault sets Default field to given value.

### HasDefault

`func (o *PluginJsonSchemaProperty) HasDefault() bool`

HasDefault returns a boolean if a field has been set.

### SetDefaultNil

`func (o *PluginJsonSchemaProperty) SetDefaultNil(b bool)`

 SetDefaultNil sets the value for Default to be an explicit nil

### UnsetDefault
`func (o *PluginJsonSchemaProperty) UnsetDefault()`

UnsetDefault ensures that no value is present for Default, not even an explicit nil
### GetDescription

`func (o *PluginJsonSchemaProperty) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PluginJsonSchemaProperty) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PluginJsonSchemaProperty) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *PluginJsonSchemaProperty) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEnum

`func (o *PluginJsonSchemaProperty) GetEnum() []string`

GetEnum returns the Enum field if non-nil, zero value otherwise.

### GetEnumOk

`func (o *PluginJsonSchemaProperty) GetEnumOk() (*[]string, bool)`

GetEnumOk returns a tuple with the Enum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnum

`func (o *PluginJsonSchemaProperty) SetEnum(v []string)`

SetEnum sets Enum field to given value.

### HasEnum

`func (o *PluginJsonSchemaProperty) HasEnum() bool`

HasEnum returns a boolean if a field has been set.

### GetItems

`func (o *PluginJsonSchemaProperty) GetItems() PluginJsonSchemaProperty`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *PluginJsonSchemaProperty) GetItemsOk() (*PluginJsonSchemaProperty, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *PluginJsonSchemaProperty) SetItems(v PluginJsonSchemaProperty)`

SetItems sets Items field to given value.

### HasItems

`func (o *PluginJsonSchemaProperty) HasItems() bool`

HasItems returns a boolean if a field has been set.

### GetProperties

`func (o *PluginJsonSchemaProperty) GetProperties() map[string]PluginJsonSchemaProperty`

GetProperties returns the Properties field if non-nil, zero value otherwise.

### GetPropertiesOk

`func (o *PluginJsonSchemaProperty) GetPropertiesOk() (*map[string]PluginJsonSchemaProperty, bool)`

GetPropertiesOk returns a tuple with the Properties field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProperties

`func (o *PluginJsonSchemaProperty) SetProperties(v map[string]PluginJsonSchemaProperty)`

SetProperties sets Properties field to given value.

### HasProperties

`func (o *PluginJsonSchemaProperty) HasProperties() bool`

HasProperties returns a boolean if a field has been set.

### GetRequired

`func (o *PluginJsonSchemaProperty) GetRequired() []string`

GetRequired returns the Required field if non-nil, zero value otherwise.

### GetRequiredOk

`func (o *PluginJsonSchemaProperty) GetRequiredOk() (*[]string, bool)`

GetRequiredOk returns a tuple with the Required field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequired

`func (o *PluginJsonSchemaProperty) SetRequired(v []string)`

SetRequired sets Required field to given value.

### HasRequired

`func (o *PluginJsonSchemaProperty) HasRequired() bool`

HasRequired returns a boolean if a field has been set.

### GetType

`func (o *PluginJsonSchemaProperty) GetType() PluginJsonSchemaType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PluginJsonSchemaProperty) GetTypeOk() (*PluginJsonSchemaType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PluginJsonSchemaProperty) SetType(v PluginJsonSchemaType)`

SetType sets Type field to given value.

### HasType

`func (o *PluginJsonSchemaProperty) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


