# PeopleUpdateItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BirthDate** | Pointer to **NullableString** | Person date of birth | [optional] 
**Color** | Pointer to **NullableString** | Person color (hex) | [optional] 
**FeatureFaceAssetId** | Pointer to **string** | Asset ID used for feature face thumbnail | [optional] 
**Id** | **string** | Person ID | 
**IsFavorite** | Pointer to **bool** | Mark as favorite | [optional] 
**IsHidden** | Pointer to **bool** | Person visibility (hidden) | [optional] 
**Name** | Pointer to **string** | Person name | [optional] 

## Methods

### NewPeopleUpdateItem

`func NewPeopleUpdateItem(id string, ) *PeopleUpdateItem`

NewPeopleUpdateItem instantiates a new PeopleUpdateItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPeopleUpdateItemWithDefaults

`func NewPeopleUpdateItemWithDefaults() *PeopleUpdateItem`

NewPeopleUpdateItemWithDefaults instantiates a new PeopleUpdateItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBirthDate

`func (o *PeopleUpdateItem) GetBirthDate() string`

GetBirthDate returns the BirthDate field if non-nil, zero value otherwise.

### GetBirthDateOk

`func (o *PeopleUpdateItem) GetBirthDateOk() (*string, bool)`

GetBirthDateOk returns a tuple with the BirthDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBirthDate

`func (o *PeopleUpdateItem) SetBirthDate(v string)`

SetBirthDate sets BirthDate field to given value.

### HasBirthDate

`func (o *PeopleUpdateItem) HasBirthDate() bool`

HasBirthDate returns a boolean if a field has been set.

### SetBirthDateNil

`func (o *PeopleUpdateItem) SetBirthDateNil(b bool)`

 SetBirthDateNil sets the value for BirthDate to be an explicit nil

### UnsetBirthDate
`func (o *PeopleUpdateItem) UnsetBirthDate()`

UnsetBirthDate ensures that no value is present for BirthDate, not even an explicit nil
### GetColor

`func (o *PeopleUpdateItem) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *PeopleUpdateItem) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *PeopleUpdateItem) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *PeopleUpdateItem) HasColor() bool`

HasColor returns a boolean if a field has been set.

### SetColorNil

`func (o *PeopleUpdateItem) SetColorNil(b bool)`

 SetColorNil sets the value for Color to be an explicit nil

### UnsetColor
`func (o *PeopleUpdateItem) UnsetColor()`

UnsetColor ensures that no value is present for Color, not even an explicit nil
### GetFeatureFaceAssetId

`func (o *PeopleUpdateItem) GetFeatureFaceAssetId() string`

GetFeatureFaceAssetId returns the FeatureFaceAssetId field if non-nil, zero value otherwise.

### GetFeatureFaceAssetIdOk

`func (o *PeopleUpdateItem) GetFeatureFaceAssetIdOk() (*string, bool)`

GetFeatureFaceAssetIdOk returns a tuple with the FeatureFaceAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureFaceAssetId

`func (o *PeopleUpdateItem) SetFeatureFaceAssetId(v string)`

SetFeatureFaceAssetId sets FeatureFaceAssetId field to given value.

### HasFeatureFaceAssetId

`func (o *PeopleUpdateItem) HasFeatureFaceAssetId() bool`

HasFeatureFaceAssetId returns a boolean if a field has been set.

### GetId

`func (o *PeopleUpdateItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PeopleUpdateItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PeopleUpdateItem) SetId(v string)`

SetId sets Id field to given value.


### GetIsFavorite

`func (o *PeopleUpdateItem) GetIsFavorite() bool`

GetIsFavorite returns the IsFavorite field if non-nil, zero value otherwise.

### GetIsFavoriteOk

`func (o *PeopleUpdateItem) GetIsFavoriteOk() (*bool, bool)`

GetIsFavoriteOk returns a tuple with the IsFavorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFavorite

`func (o *PeopleUpdateItem) SetIsFavorite(v bool)`

SetIsFavorite sets IsFavorite field to given value.

### HasIsFavorite

`func (o *PeopleUpdateItem) HasIsFavorite() bool`

HasIsFavorite returns a boolean if a field has been set.

### GetIsHidden

`func (o *PeopleUpdateItem) GetIsHidden() bool`

GetIsHidden returns the IsHidden field if non-nil, zero value otherwise.

### GetIsHiddenOk

`func (o *PeopleUpdateItem) GetIsHiddenOk() (*bool, bool)`

GetIsHiddenOk returns a tuple with the IsHidden field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsHidden

`func (o *PeopleUpdateItem) SetIsHidden(v bool)`

SetIsHidden sets IsHidden field to given value.

### HasIsHidden

`func (o *PeopleUpdateItem) HasIsHidden() bool`

HasIsHidden returns a boolean if a field has been set.

### GetName

`func (o *PeopleUpdateItem) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PeopleUpdateItem) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PeopleUpdateItem) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *PeopleUpdateItem) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


