# TagCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Color** | Pointer to **NullableString** | Tag color (hex) | [optional] 
**Name** | **string** | Tag name | 
**ParentId** | Pointer to **NullableString** | Parent tag ID | [optional] 

## Methods

### NewTagCreateDto

`func NewTagCreateDto(name string, ) *TagCreateDto`

NewTagCreateDto instantiates a new TagCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTagCreateDtoWithDefaults

`func NewTagCreateDtoWithDefaults() *TagCreateDto`

NewTagCreateDtoWithDefaults instantiates a new TagCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetColor

`func (o *TagCreateDto) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *TagCreateDto) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *TagCreateDto) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *TagCreateDto) HasColor() bool`

HasColor returns a boolean if a field has been set.

### SetColorNil

`func (o *TagCreateDto) SetColorNil(b bool)`

 SetColorNil sets the value for Color to be an explicit nil

### UnsetColor
`func (o *TagCreateDto) UnsetColor()`

UnsetColor ensures that no value is present for Color, not even an explicit nil
### GetName

`func (o *TagCreateDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TagCreateDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TagCreateDto) SetName(v string)`

SetName sets Name field to given value.


### GetParentId

`func (o *TagCreateDto) GetParentId() string`

GetParentId returns the ParentId field if non-nil, zero value otherwise.

### GetParentIdOk

`func (o *TagCreateDto) GetParentIdOk() (*string, bool)`

GetParentIdOk returns a tuple with the ParentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParentId

`func (o *TagCreateDto) SetParentId(v string)`

SetParentId sets ParentId field to given value.

### HasParentId

`func (o *TagCreateDto) HasParentId() bool`

HasParentId returns a boolean if a field has been set.

### SetParentIdNil

`func (o *TagCreateDto) SetParentIdNil(b bool)`

 SetParentIdNil sets the value for ParentId to be an explicit nil

### UnsetParentId
`func (o *TagCreateDto) UnsetParentId()`

UnsetParentId ensures that no value is present for ParentId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


