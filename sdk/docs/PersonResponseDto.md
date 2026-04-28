# PersonResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BirthDate** | **NullableString** | Person date of birth | 
**Color** | Pointer to **string** | Person color (hex) | [optional] 
**Id** | **string** | Person ID | 
**IsFavorite** | Pointer to **bool** | Is favorite | [optional] 
**IsHidden** | **bool** | Is hidden | 
**Name** | **string** | Person name | 
**ThumbnailPath** | **string** | Thumbnail path | 
**UpdatedAt** | Pointer to **time.Time** | Last update date | [optional] 

## Methods

### NewPersonResponseDto

`func NewPersonResponseDto(birthDate NullableString, id string, isHidden bool, name string, thumbnailPath string, ) *PersonResponseDto`

NewPersonResponseDto instantiates a new PersonResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPersonResponseDtoWithDefaults

`func NewPersonResponseDtoWithDefaults() *PersonResponseDto`

NewPersonResponseDtoWithDefaults instantiates a new PersonResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBirthDate

`func (o *PersonResponseDto) GetBirthDate() string`

GetBirthDate returns the BirthDate field if non-nil, zero value otherwise.

### GetBirthDateOk

`func (o *PersonResponseDto) GetBirthDateOk() (*string, bool)`

GetBirthDateOk returns a tuple with the BirthDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBirthDate

`func (o *PersonResponseDto) SetBirthDate(v string)`

SetBirthDate sets BirthDate field to given value.


### SetBirthDateNil

`func (o *PersonResponseDto) SetBirthDateNil(b bool)`

 SetBirthDateNil sets the value for BirthDate to be an explicit nil

### UnsetBirthDate
`func (o *PersonResponseDto) UnsetBirthDate()`

UnsetBirthDate ensures that no value is present for BirthDate, not even an explicit nil
### GetColor

`func (o *PersonResponseDto) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *PersonResponseDto) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *PersonResponseDto) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *PersonResponseDto) HasColor() bool`

HasColor returns a boolean if a field has been set.

### GetId

`func (o *PersonResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PersonResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PersonResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetIsFavorite

`func (o *PersonResponseDto) GetIsFavorite() bool`

GetIsFavorite returns the IsFavorite field if non-nil, zero value otherwise.

### GetIsFavoriteOk

`func (o *PersonResponseDto) GetIsFavoriteOk() (*bool, bool)`

GetIsFavoriteOk returns a tuple with the IsFavorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFavorite

`func (o *PersonResponseDto) SetIsFavorite(v bool)`

SetIsFavorite sets IsFavorite field to given value.

### HasIsFavorite

`func (o *PersonResponseDto) HasIsFavorite() bool`

HasIsFavorite returns a boolean if a field has been set.

### GetIsHidden

`func (o *PersonResponseDto) GetIsHidden() bool`

GetIsHidden returns the IsHidden field if non-nil, zero value otherwise.

### GetIsHiddenOk

`func (o *PersonResponseDto) GetIsHiddenOk() (*bool, bool)`

GetIsHiddenOk returns a tuple with the IsHidden field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsHidden

`func (o *PersonResponseDto) SetIsHidden(v bool)`

SetIsHidden sets IsHidden field to given value.


### GetName

`func (o *PersonResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PersonResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PersonResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetThumbnailPath

`func (o *PersonResponseDto) GetThumbnailPath() string`

GetThumbnailPath returns the ThumbnailPath field if non-nil, zero value otherwise.

### GetThumbnailPathOk

`func (o *PersonResponseDto) GetThumbnailPathOk() (*string, bool)`

GetThumbnailPathOk returns a tuple with the ThumbnailPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbnailPath

`func (o *PersonResponseDto) SetThumbnailPath(v string)`

SetThumbnailPath sets ThumbnailPath field to given value.


### GetUpdatedAt

`func (o *PersonResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PersonResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PersonResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PersonResponseDto) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


