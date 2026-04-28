# PersonWithFacesResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BirthDate** | **NullableString** | Person date of birth | 
**Color** | Pointer to **string** | Person color (hex) | [optional] 
**Faces** | [**[]AssetFaceWithoutPersonResponseDto**](AssetFaceWithoutPersonResponseDto.md) |  | 
**Id** | **string** | Person ID | 
**IsFavorite** | Pointer to **bool** | Is favorite | [optional] 
**IsHidden** | **bool** | Is hidden | 
**Name** | **string** | Person name | 
**ThumbnailPath** | **string** | Thumbnail path | 
**UpdatedAt** | Pointer to **time.Time** | Last update date | [optional] 

## Methods

### NewPersonWithFacesResponseDto

`func NewPersonWithFacesResponseDto(birthDate NullableString, faces []AssetFaceWithoutPersonResponseDto, id string, isHidden bool, name string, thumbnailPath string, ) *PersonWithFacesResponseDto`

NewPersonWithFacesResponseDto instantiates a new PersonWithFacesResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPersonWithFacesResponseDtoWithDefaults

`func NewPersonWithFacesResponseDtoWithDefaults() *PersonWithFacesResponseDto`

NewPersonWithFacesResponseDtoWithDefaults instantiates a new PersonWithFacesResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBirthDate

`func (o *PersonWithFacesResponseDto) GetBirthDate() string`

GetBirthDate returns the BirthDate field if non-nil, zero value otherwise.

### GetBirthDateOk

`func (o *PersonWithFacesResponseDto) GetBirthDateOk() (*string, bool)`

GetBirthDateOk returns a tuple with the BirthDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBirthDate

`func (o *PersonWithFacesResponseDto) SetBirthDate(v string)`

SetBirthDate sets BirthDate field to given value.


### SetBirthDateNil

`func (o *PersonWithFacesResponseDto) SetBirthDateNil(b bool)`

 SetBirthDateNil sets the value for BirthDate to be an explicit nil

### UnsetBirthDate
`func (o *PersonWithFacesResponseDto) UnsetBirthDate()`

UnsetBirthDate ensures that no value is present for BirthDate, not even an explicit nil
### GetColor

`func (o *PersonWithFacesResponseDto) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *PersonWithFacesResponseDto) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *PersonWithFacesResponseDto) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *PersonWithFacesResponseDto) HasColor() bool`

HasColor returns a boolean if a field has been set.

### GetFaces

`func (o *PersonWithFacesResponseDto) GetFaces() []AssetFaceWithoutPersonResponseDto`

GetFaces returns the Faces field if non-nil, zero value otherwise.

### GetFacesOk

`func (o *PersonWithFacesResponseDto) GetFacesOk() (*[]AssetFaceWithoutPersonResponseDto, bool)`

GetFacesOk returns a tuple with the Faces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFaces

`func (o *PersonWithFacesResponseDto) SetFaces(v []AssetFaceWithoutPersonResponseDto)`

SetFaces sets Faces field to given value.


### GetId

`func (o *PersonWithFacesResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PersonWithFacesResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PersonWithFacesResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetIsFavorite

`func (o *PersonWithFacesResponseDto) GetIsFavorite() bool`

GetIsFavorite returns the IsFavorite field if non-nil, zero value otherwise.

### GetIsFavoriteOk

`func (o *PersonWithFacesResponseDto) GetIsFavoriteOk() (*bool, bool)`

GetIsFavoriteOk returns a tuple with the IsFavorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFavorite

`func (o *PersonWithFacesResponseDto) SetIsFavorite(v bool)`

SetIsFavorite sets IsFavorite field to given value.

### HasIsFavorite

`func (o *PersonWithFacesResponseDto) HasIsFavorite() bool`

HasIsFavorite returns a boolean if a field has been set.

### GetIsHidden

`func (o *PersonWithFacesResponseDto) GetIsHidden() bool`

GetIsHidden returns the IsHidden field if non-nil, zero value otherwise.

### GetIsHiddenOk

`func (o *PersonWithFacesResponseDto) GetIsHiddenOk() (*bool, bool)`

GetIsHiddenOk returns a tuple with the IsHidden field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsHidden

`func (o *PersonWithFacesResponseDto) SetIsHidden(v bool)`

SetIsHidden sets IsHidden field to given value.


### GetName

`func (o *PersonWithFacesResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PersonWithFacesResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PersonWithFacesResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetThumbnailPath

`func (o *PersonWithFacesResponseDto) GetThumbnailPath() string`

GetThumbnailPath returns the ThumbnailPath field if non-nil, zero value otherwise.

### GetThumbnailPathOk

`func (o *PersonWithFacesResponseDto) GetThumbnailPathOk() (*string, bool)`

GetThumbnailPathOk returns a tuple with the ThumbnailPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbnailPath

`func (o *PersonWithFacesResponseDto) SetThumbnailPath(v string)`

SetThumbnailPath sets ThumbnailPath field to given value.


### GetUpdatedAt

`func (o *PersonWithFacesResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PersonWithFacesResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PersonWithFacesResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *PersonWithFacesResponseDto) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


