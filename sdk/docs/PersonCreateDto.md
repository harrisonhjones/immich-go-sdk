# PersonCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BirthDate** | Pointer to **NullableString** | Person date of birth | [optional] 
**Color** | Pointer to **NullableString** | Person color (hex) | [optional] 
**IsFavorite** | Pointer to **bool** | Mark as favorite | [optional] 
**IsHidden** | Pointer to **bool** | Person visibility (hidden) | [optional] 
**Name** | Pointer to **string** | Person name | [optional] 

## Methods

### NewPersonCreateDto

`func NewPersonCreateDto() *PersonCreateDto`

NewPersonCreateDto instantiates a new PersonCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPersonCreateDtoWithDefaults

`func NewPersonCreateDtoWithDefaults() *PersonCreateDto`

NewPersonCreateDtoWithDefaults instantiates a new PersonCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBirthDate

`func (o *PersonCreateDto) GetBirthDate() string`

GetBirthDate returns the BirthDate field if non-nil, zero value otherwise.

### GetBirthDateOk

`func (o *PersonCreateDto) GetBirthDateOk() (*string, bool)`

GetBirthDateOk returns a tuple with the BirthDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBirthDate

`func (o *PersonCreateDto) SetBirthDate(v string)`

SetBirthDate sets BirthDate field to given value.

### HasBirthDate

`func (o *PersonCreateDto) HasBirthDate() bool`

HasBirthDate returns a boolean if a field has been set.

### SetBirthDateNil

`func (o *PersonCreateDto) SetBirthDateNil(b bool)`

 SetBirthDateNil sets the value for BirthDate to be an explicit nil

### UnsetBirthDate
`func (o *PersonCreateDto) UnsetBirthDate()`

UnsetBirthDate ensures that no value is present for BirthDate, not even an explicit nil
### GetColor

`func (o *PersonCreateDto) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *PersonCreateDto) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *PersonCreateDto) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *PersonCreateDto) HasColor() bool`

HasColor returns a boolean if a field has been set.

### SetColorNil

`func (o *PersonCreateDto) SetColorNil(b bool)`

 SetColorNil sets the value for Color to be an explicit nil

### UnsetColor
`func (o *PersonCreateDto) UnsetColor()`

UnsetColor ensures that no value is present for Color, not even an explicit nil
### GetIsFavorite

`func (o *PersonCreateDto) GetIsFavorite() bool`

GetIsFavorite returns the IsFavorite field if non-nil, zero value otherwise.

### GetIsFavoriteOk

`func (o *PersonCreateDto) GetIsFavoriteOk() (*bool, bool)`

GetIsFavoriteOk returns a tuple with the IsFavorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFavorite

`func (o *PersonCreateDto) SetIsFavorite(v bool)`

SetIsFavorite sets IsFavorite field to given value.

### HasIsFavorite

`func (o *PersonCreateDto) HasIsFavorite() bool`

HasIsFavorite returns a boolean if a field has been set.

### GetIsHidden

`func (o *PersonCreateDto) GetIsHidden() bool`

GetIsHidden returns the IsHidden field if non-nil, zero value otherwise.

### GetIsHiddenOk

`func (o *PersonCreateDto) GetIsHiddenOk() (*bool, bool)`

GetIsHiddenOk returns a tuple with the IsHidden field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsHidden

`func (o *PersonCreateDto) SetIsHidden(v bool)`

SetIsHidden sets IsHidden field to given value.

### HasIsHidden

`func (o *PersonCreateDto) HasIsHidden() bool`

HasIsHidden returns a boolean if a field has been set.

### GetName

`func (o *PersonCreateDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PersonCreateDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PersonCreateDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PersonCreateDto) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


