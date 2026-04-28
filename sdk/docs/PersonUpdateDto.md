# PersonUpdateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BirthDate** | Pointer to **NullableString** | Person date of birth | [optional] 
**Color** | Pointer to **NullableString** | Person color (hex) | [optional] 
**FeatureFaceAssetId** | Pointer to **string** | Asset ID used for feature face thumbnail | [optional] 
**IsFavorite** | Pointer to **bool** | Mark as favorite | [optional] 
**IsHidden** | Pointer to **bool** | Person visibility (hidden) | [optional] 
**Name** | Pointer to **string** | Person name | [optional] 

## Methods

### NewPersonUpdateDto

`func NewPersonUpdateDto() *PersonUpdateDto`

NewPersonUpdateDto instantiates a new PersonUpdateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPersonUpdateDtoWithDefaults

`func NewPersonUpdateDtoWithDefaults() *PersonUpdateDto`

NewPersonUpdateDtoWithDefaults instantiates a new PersonUpdateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBirthDate

`func (o *PersonUpdateDto) GetBirthDate() string`

GetBirthDate returns the BirthDate field if non-nil, zero value otherwise.

### GetBirthDateOk

`func (o *PersonUpdateDto) GetBirthDateOk() (*string, bool)`

GetBirthDateOk returns a tuple with the BirthDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBirthDate

`func (o *PersonUpdateDto) SetBirthDate(v string)`

SetBirthDate sets BirthDate field to given value.

### HasBirthDate

`func (o *PersonUpdateDto) HasBirthDate() bool`

HasBirthDate returns a boolean if a field has been set.

### SetBirthDateNil

`func (o *PersonUpdateDto) SetBirthDateNil(b bool)`

 SetBirthDateNil sets the value for BirthDate to be an explicit nil

### UnsetBirthDate
`func (o *PersonUpdateDto) UnsetBirthDate()`

UnsetBirthDate ensures that no value is present for BirthDate, not even an explicit nil
### GetColor

`func (o *PersonUpdateDto) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *PersonUpdateDto) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *PersonUpdateDto) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *PersonUpdateDto) HasColor() bool`

HasColor returns a boolean if a field has been set.

### SetColorNil

`func (o *PersonUpdateDto) SetColorNil(b bool)`

 SetColorNil sets the value for Color to be an explicit nil

### UnsetColor
`func (o *PersonUpdateDto) UnsetColor()`

UnsetColor ensures that no value is present for Color, not even an explicit nil
### GetFeatureFaceAssetId

`func (o *PersonUpdateDto) GetFeatureFaceAssetId() string`

GetFeatureFaceAssetId returns the FeatureFaceAssetId field if non-nil, zero value otherwise.

### GetFeatureFaceAssetIdOk

`func (o *PersonUpdateDto) GetFeatureFaceAssetIdOk() (*string, bool)`

GetFeatureFaceAssetIdOk returns a tuple with the FeatureFaceAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureFaceAssetId

`func (o *PersonUpdateDto) SetFeatureFaceAssetId(v string)`

SetFeatureFaceAssetId sets FeatureFaceAssetId field to given value.

### HasFeatureFaceAssetId

`func (o *PersonUpdateDto) HasFeatureFaceAssetId() bool`

HasFeatureFaceAssetId returns a boolean if a field has been set.

### GetIsFavorite

`func (o *PersonUpdateDto) GetIsFavorite() bool`

GetIsFavorite returns the IsFavorite field if non-nil, zero value otherwise.

### GetIsFavoriteOk

`func (o *PersonUpdateDto) GetIsFavoriteOk() (*bool, bool)`

GetIsFavoriteOk returns a tuple with the IsFavorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFavorite

`func (o *PersonUpdateDto) SetIsFavorite(v bool)`

SetIsFavorite sets IsFavorite field to given value.

### HasIsFavorite

`func (o *PersonUpdateDto) HasIsFavorite() bool`

HasIsFavorite returns a boolean if a field has been set.

### GetIsHidden

`func (o *PersonUpdateDto) GetIsHidden() bool`

GetIsHidden returns the IsHidden field if non-nil, zero value otherwise.

### GetIsHiddenOk

`func (o *PersonUpdateDto) GetIsHiddenOk() (*bool, bool)`

GetIsHiddenOk returns a tuple with the IsHidden field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsHidden

`func (o *PersonUpdateDto) SetIsHidden(v bool)`

SetIsHidden sets IsHidden field to given value.

### HasIsHidden

`func (o *PersonUpdateDto) HasIsHidden() bool`

HasIsHidden returns a boolean if a field has been set.

### GetName

`func (o *PersonUpdateDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PersonUpdateDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PersonUpdateDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PersonUpdateDto) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


