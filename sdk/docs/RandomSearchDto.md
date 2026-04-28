# RandomSearchDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlbumIds** | Pointer to **[]string** | Filter by album IDs | [optional] 
**City** | Pointer to **NullableString** | Filter by city name | [optional] 
**Country** | Pointer to **NullableString** | Filter by country name | [optional] 
**CreatedAfter** | Pointer to **time.Time** | Filter by creation date (after) | [optional] 
**CreatedBefore** | Pointer to **time.Time** | Filter by creation date (before) | [optional] 
**IsEncoded** | Pointer to **bool** | Filter by encoded status | [optional] 
**IsFavorite** | Pointer to **bool** | Filter by favorite status | [optional] 
**IsMotion** | Pointer to **bool** | Filter by motion photo status | [optional] 
**IsNotInAlbum** | Pointer to **bool** | Filter assets not in any album | [optional] 
**IsOffline** | Pointer to **bool** | Filter by offline status | [optional] 
**LensModel** | Pointer to **NullableString** | Filter by lens model | [optional] 
**LibraryId** | Pointer to **NullableString** | Library ID to filter by | [optional] 
**Make** | Pointer to **NullableString** | Filter by camera make | [optional] 
**Model** | Pointer to **NullableString** | Filter by camera model | [optional] 
**Ocr** | Pointer to **string** | Filter by OCR text content | [optional] 
**PersonIds** | Pointer to **[]string** | Filter by person IDs | [optional] 
**Rating** | Pointer to **NullableFloat32** | Filter by rating [1-5], or null for unrated | [optional] 
**Size** | Pointer to **float32** | Number of results to return | [optional] 
**State** | Pointer to **NullableString** | Filter by state/province name | [optional] 
**TagIds** | Pointer to **[]string** | Filter by tag IDs | [optional] 
**TakenAfter** | Pointer to **time.Time** | Filter by taken date (after) | [optional] 
**TakenBefore** | Pointer to **time.Time** | Filter by taken date (before) | [optional] 
**TrashedAfter** | Pointer to **time.Time** | Filter by trash date (after) | [optional] 
**TrashedBefore** | Pointer to **time.Time** | Filter by trash date (before) | [optional] 
**Type** | Pointer to [**AssetTypeEnum**](AssetTypeEnum.md) |  | [optional] 
**UpdatedAfter** | Pointer to **time.Time** | Filter by update date (after) | [optional] 
**UpdatedBefore** | Pointer to **time.Time** | Filter by update date (before) | [optional] 
**Visibility** | Pointer to [**AssetVisibility**](AssetVisibility.md) |  | [optional] 
**WithDeleted** | Pointer to **bool** | Include deleted assets | [optional] 
**WithExif** | Pointer to **bool** | Include EXIF data in response | [optional] 
**WithPeople** | Pointer to **bool** | Include people data in response | [optional] 
**WithStacked** | Pointer to **bool** | Include stacked assets | [optional] 

## Methods

### NewRandomSearchDto

`func NewRandomSearchDto() *RandomSearchDto`

NewRandomSearchDto instantiates a new RandomSearchDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRandomSearchDtoWithDefaults

`func NewRandomSearchDtoWithDefaults() *RandomSearchDto`

NewRandomSearchDtoWithDefaults instantiates a new RandomSearchDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbumIds

`func (o *RandomSearchDto) GetAlbumIds() []string`

GetAlbumIds returns the AlbumIds field if non-nil, zero value otherwise.

### GetAlbumIdsOk

`func (o *RandomSearchDto) GetAlbumIdsOk() (*[]string, bool)`

GetAlbumIdsOk returns a tuple with the AlbumIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumIds

`func (o *RandomSearchDto) SetAlbumIds(v []string)`

SetAlbumIds sets AlbumIds field to given value.

### HasAlbumIds

`func (o *RandomSearchDto) HasAlbumIds() bool`

HasAlbumIds returns a boolean if a field has been set.

### GetCity

`func (o *RandomSearchDto) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *RandomSearchDto) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *RandomSearchDto) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *RandomSearchDto) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *RandomSearchDto) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *RandomSearchDto) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetCountry

`func (o *RandomSearchDto) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *RandomSearchDto) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *RandomSearchDto) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *RandomSearchDto) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *RandomSearchDto) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *RandomSearchDto) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetCreatedAfter

`func (o *RandomSearchDto) GetCreatedAfter() time.Time`

GetCreatedAfter returns the CreatedAfter field if non-nil, zero value otherwise.

### GetCreatedAfterOk

`func (o *RandomSearchDto) GetCreatedAfterOk() (*time.Time, bool)`

GetCreatedAfterOk returns a tuple with the CreatedAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAfter

`func (o *RandomSearchDto) SetCreatedAfter(v time.Time)`

SetCreatedAfter sets CreatedAfter field to given value.

### HasCreatedAfter

`func (o *RandomSearchDto) HasCreatedAfter() bool`

HasCreatedAfter returns a boolean if a field has been set.

### GetCreatedBefore

`func (o *RandomSearchDto) GetCreatedBefore() time.Time`

GetCreatedBefore returns the CreatedBefore field if non-nil, zero value otherwise.

### GetCreatedBeforeOk

`func (o *RandomSearchDto) GetCreatedBeforeOk() (*time.Time, bool)`

GetCreatedBeforeOk returns a tuple with the CreatedBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBefore

`func (o *RandomSearchDto) SetCreatedBefore(v time.Time)`

SetCreatedBefore sets CreatedBefore field to given value.

### HasCreatedBefore

`func (o *RandomSearchDto) HasCreatedBefore() bool`

HasCreatedBefore returns a boolean if a field has been set.

### GetIsEncoded

`func (o *RandomSearchDto) GetIsEncoded() bool`

GetIsEncoded returns the IsEncoded field if non-nil, zero value otherwise.

### GetIsEncodedOk

`func (o *RandomSearchDto) GetIsEncodedOk() (*bool, bool)`

GetIsEncodedOk returns a tuple with the IsEncoded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEncoded

`func (o *RandomSearchDto) SetIsEncoded(v bool)`

SetIsEncoded sets IsEncoded field to given value.

### HasIsEncoded

`func (o *RandomSearchDto) HasIsEncoded() bool`

HasIsEncoded returns a boolean if a field has been set.

### GetIsFavorite

`func (o *RandomSearchDto) GetIsFavorite() bool`

GetIsFavorite returns the IsFavorite field if non-nil, zero value otherwise.

### GetIsFavoriteOk

`func (o *RandomSearchDto) GetIsFavoriteOk() (*bool, bool)`

GetIsFavoriteOk returns a tuple with the IsFavorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFavorite

`func (o *RandomSearchDto) SetIsFavorite(v bool)`

SetIsFavorite sets IsFavorite field to given value.

### HasIsFavorite

`func (o *RandomSearchDto) HasIsFavorite() bool`

HasIsFavorite returns a boolean if a field has been set.

### GetIsMotion

`func (o *RandomSearchDto) GetIsMotion() bool`

GetIsMotion returns the IsMotion field if non-nil, zero value otherwise.

### GetIsMotionOk

`func (o *RandomSearchDto) GetIsMotionOk() (*bool, bool)`

GetIsMotionOk returns a tuple with the IsMotion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsMotion

`func (o *RandomSearchDto) SetIsMotion(v bool)`

SetIsMotion sets IsMotion field to given value.

### HasIsMotion

`func (o *RandomSearchDto) HasIsMotion() bool`

HasIsMotion returns a boolean if a field has been set.

### GetIsNotInAlbum

`func (o *RandomSearchDto) GetIsNotInAlbum() bool`

GetIsNotInAlbum returns the IsNotInAlbum field if non-nil, zero value otherwise.

### GetIsNotInAlbumOk

`func (o *RandomSearchDto) GetIsNotInAlbumOk() (*bool, bool)`

GetIsNotInAlbumOk returns a tuple with the IsNotInAlbum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsNotInAlbum

`func (o *RandomSearchDto) SetIsNotInAlbum(v bool)`

SetIsNotInAlbum sets IsNotInAlbum field to given value.

### HasIsNotInAlbum

`func (o *RandomSearchDto) HasIsNotInAlbum() bool`

HasIsNotInAlbum returns a boolean if a field has been set.

### GetIsOffline

`func (o *RandomSearchDto) GetIsOffline() bool`

GetIsOffline returns the IsOffline field if non-nil, zero value otherwise.

### GetIsOfflineOk

`func (o *RandomSearchDto) GetIsOfflineOk() (*bool, bool)`

GetIsOfflineOk returns a tuple with the IsOffline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOffline

`func (o *RandomSearchDto) SetIsOffline(v bool)`

SetIsOffline sets IsOffline field to given value.

### HasIsOffline

`func (o *RandomSearchDto) HasIsOffline() bool`

HasIsOffline returns a boolean if a field has been set.

### GetLensModel

`func (o *RandomSearchDto) GetLensModel() string`

GetLensModel returns the LensModel field if non-nil, zero value otherwise.

### GetLensModelOk

`func (o *RandomSearchDto) GetLensModelOk() (*string, bool)`

GetLensModelOk returns a tuple with the LensModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLensModel

`func (o *RandomSearchDto) SetLensModel(v string)`

SetLensModel sets LensModel field to given value.

### HasLensModel

`func (o *RandomSearchDto) HasLensModel() bool`

HasLensModel returns a boolean if a field has been set.

### SetLensModelNil

`func (o *RandomSearchDto) SetLensModelNil(b bool)`

 SetLensModelNil sets the value for LensModel to be an explicit nil

### UnsetLensModel
`func (o *RandomSearchDto) UnsetLensModel()`

UnsetLensModel ensures that no value is present for LensModel, not even an explicit nil
### GetLibraryId

`func (o *RandomSearchDto) GetLibraryId() string`

GetLibraryId returns the LibraryId field if non-nil, zero value otherwise.

### GetLibraryIdOk

`func (o *RandomSearchDto) GetLibraryIdOk() (*string, bool)`

GetLibraryIdOk returns a tuple with the LibraryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLibraryId

`func (o *RandomSearchDto) SetLibraryId(v string)`

SetLibraryId sets LibraryId field to given value.

### HasLibraryId

`func (o *RandomSearchDto) HasLibraryId() bool`

HasLibraryId returns a boolean if a field has been set.

### SetLibraryIdNil

`func (o *RandomSearchDto) SetLibraryIdNil(b bool)`

 SetLibraryIdNil sets the value for LibraryId to be an explicit nil

### UnsetLibraryId
`func (o *RandomSearchDto) UnsetLibraryId()`

UnsetLibraryId ensures that no value is present for LibraryId, not even an explicit nil
### GetMake

`func (o *RandomSearchDto) GetMake() string`

GetMake returns the Make field if non-nil, zero value otherwise.

### GetMakeOk

`func (o *RandomSearchDto) GetMakeOk() (*string, bool)`

GetMakeOk returns a tuple with the Make field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMake

`func (o *RandomSearchDto) SetMake(v string)`

SetMake sets Make field to given value.

### HasMake

`func (o *RandomSearchDto) HasMake() bool`

HasMake returns a boolean if a field has been set.

### SetMakeNil

`func (o *RandomSearchDto) SetMakeNil(b bool)`

 SetMakeNil sets the value for Make to be an explicit nil

### UnsetMake
`func (o *RandomSearchDto) UnsetMake()`

UnsetMake ensures that no value is present for Make, not even an explicit nil
### GetModel

`func (o *RandomSearchDto) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *RandomSearchDto) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *RandomSearchDto) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *RandomSearchDto) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *RandomSearchDto) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *RandomSearchDto) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetOcr

`func (o *RandomSearchDto) GetOcr() string`

GetOcr returns the Ocr field if non-nil, zero value otherwise.

### GetOcrOk

`func (o *RandomSearchDto) GetOcrOk() (*string, bool)`

GetOcrOk returns a tuple with the Ocr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOcr

`func (o *RandomSearchDto) SetOcr(v string)`

SetOcr sets Ocr field to given value.

### HasOcr

`func (o *RandomSearchDto) HasOcr() bool`

HasOcr returns a boolean if a field has been set.

### GetPersonIds

`func (o *RandomSearchDto) GetPersonIds() []string`

GetPersonIds returns the PersonIds field if non-nil, zero value otherwise.

### GetPersonIdsOk

`func (o *RandomSearchDto) GetPersonIdsOk() (*[]string, bool)`

GetPersonIdsOk returns a tuple with the PersonIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonIds

`func (o *RandomSearchDto) SetPersonIds(v []string)`

SetPersonIds sets PersonIds field to given value.

### HasPersonIds

`func (o *RandomSearchDto) HasPersonIds() bool`

HasPersonIds returns a boolean if a field has been set.

### GetRating

`func (o *RandomSearchDto) GetRating() float32`

GetRating returns the Rating field if non-nil, zero value otherwise.

### GetRatingOk

`func (o *RandomSearchDto) GetRatingOk() (*float32, bool)`

GetRatingOk returns a tuple with the Rating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRating

`func (o *RandomSearchDto) SetRating(v float32)`

SetRating sets Rating field to given value.

### HasRating

`func (o *RandomSearchDto) HasRating() bool`

HasRating returns a boolean if a field has been set.

### SetRatingNil

`func (o *RandomSearchDto) SetRatingNil(b bool)`

 SetRatingNil sets the value for Rating to be an explicit nil

### UnsetRating
`func (o *RandomSearchDto) UnsetRating()`

UnsetRating ensures that no value is present for Rating, not even an explicit nil
### GetSize

`func (o *RandomSearchDto) GetSize() float32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *RandomSearchDto) GetSizeOk() (*float32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *RandomSearchDto) SetSize(v float32)`

SetSize sets Size field to given value.

### HasSize

`func (o *RandomSearchDto) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetState

`func (o *RandomSearchDto) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *RandomSearchDto) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *RandomSearchDto) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *RandomSearchDto) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *RandomSearchDto) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *RandomSearchDto) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetTagIds

`func (o *RandomSearchDto) GetTagIds() []string`

GetTagIds returns the TagIds field if non-nil, zero value otherwise.

### GetTagIdsOk

`func (o *RandomSearchDto) GetTagIdsOk() (*[]string, bool)`

GetTagIdsOk returns a tuple with the TagIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagIds

`func (o *RandomSearchDto) SetTagIds(v []string)`

SetTagIds sets TagIds field to given value.

### HasTagIds

`func (o *RandomSearchDto) HasTagIds() bool`

HasTagIds returns a boolean if a field has been set.

### SetTagIdsNil

`func (o *RandomSearchDto) SetTagIdsNil(b bool)`

 SetTagIdsNil sets the value for TagIds to be an explicit nil

### UnsetTagIds
`func (o *RandomSearchDto) UnsetTagIds()`

UnsetTagIds ensures that no value is present for TagIds, not even an explicit nil
### GetTakenAfter

`func (o *RandomSearchDto) GetTakenAfter() time.Time`

GetTakenAfter returns the TakenAfter field if non-nil, zero value otherwise.

### GetTakenAfterOk

`func (o *RandomSearchDto) GetTakenAfterOk() (*time.Time, bool)`

GetTakenAfterOk returns a tuple with the TakenAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTakenAfter

`func (o *RandomSearchDto) SetTakenAfter(v time.Time)`

SetTakenAfter sets TakenAfter field to given value.

### HasTakenAfter

`func (o *RandomSearchDto) HasTakenAfter() bool`

HasTakenAfter returns a boolean if a field has been set.

### GetTakenBefore

`func (o *RandomSearchDto) GetTakenBefore() time.Time`

GetTakenBefore returns the TakenBefore field if non-nil, zero value otherwise.

### GetTakenBeforeOk

`func (o *RandomSearchDto) GetTakenBeforeOk() (*time.Time, bool)`

GetTakenBeforeOk returns a tuple with the TakenBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTakenBefore

`func (o *RandomSearchDto) SetTakenBefore(v time.Time)`

SetTakenBefore sets TakenBefore field to given value.

### HasTakenBefore

`func (o *RandomSearchDto) HasTakenBefore() bool`

HasTakenBefore returns a boolean if a field has been set.

### GetTrashedAfter

`func (o *RandomSearchDto) GetTrashedAfter() time.Time`

GetTrashedAfter returns the TrashedAfter field if non-nil, zero value otherwise.

### GetTrashedAfterOk

`func (o *RandomSearchDto) GetTrashedAfterOk() (*time.Time, bool)`

GetTrashedAfterOk returns a tuple with the TrashedAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrashedAfter

`func (o *RandomSearchDto) SetTrashedAfter(v time.Time)`

SetTrashedAfter sets TrashedAfter field to given value.

### HasTrashedAfter

`func (o *RandomSearchDto) HasTrashedAfter() bool`

HasTrashedAfter returns a boolean if a field has been set.

### GetTrashedBefore

`func (o *RandomSearchDto) GetTrashedBefore() time.Time`

GetTrashedBefore returns the TrashedBefore field if non-nil, zero value otherwise.

### GetTrashedBeforeOk

`func (o *RandomSearchDto) GetTrashedBeforeOk() (*time.Time, bool)`

GetTrashedBeforeOk returns a tuple with the TrashedBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrashedBefore

`func (o *RandomSearchDto) SetTrashedBefore(v time.Time)`

SetTrashedBefore sets TrashedBefore field to given value.

### HasTrashedBefore

`func (o *RandomSearchDto) HasTrashedBefore() bool`

HasTrashedBefore returns a boolean if a field has been set.

### GetType

`func (o *RandomSearchDto) GetType() AssetTypeEnum`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RandomSearchDto) GetTypeOk() (*AssetTypeEnum, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RandomSearchDto) SetType(v AssetTypeEnum)`

SetType sets Type field to given value.

### HasType

`func (o *RandomSearchDto) HasType() bool`

HasType returns a boolean if a field has been set.

### GetUpdatedAfter

`func (o *RandomSearchDto) GetUpdatedAfter() time.Time`

GetUpdatedAfter returns the UpdatedAfter field if non-nil, zero value otherwise.

### GetUpdatedAfterOk

`func (o *RandomSearchDto) GetUpdatedAfterOk() (*time.Time, bool)`

GetUpdatedAfterOk returns a tuple with the UpdatedAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAfter

`func (o *RandomSearchDto) SetUpdatedAfter(v time.Time)`

SetUpdatedAfter sets UpdatedAfter field to given value.

### HasUpdatedAfter

`func (o *RandomSearchDto) HasUpdatedAfter() bool`

HasUpdatedAfter returns a boolean if a field has been set.

### GetUpdatedBefore

`func (o *RandomSearchDto) GetUpdatedBefore() time.Time`

GetUpdatedBefore returns the UpdatedBefore field if non-nil, zero value otherwise.

### GetUpdatedBeforeOk

`func (o *RandomSearchDto) GetUpdatedBeforeOk() (*time.Time, bool)`

GetUpdatedBeforeOk returns a tuple with the UpdatedBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBefore

`func (o *RandomSearchDto) SetUpdatedBefore(v time.Time)`

SetUpdatedBefore sets UpdatedBefore field to given value.

### HasUpdatedBefore

`func (o *RandomSearchDto) HasUpdatedBefore() bool`

HasUpdatedBefore returns a boolean if a field has been set.

### GetVisibility

`func (o *RandomSearchDto) GetVisibility() AssetVisibility`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *RandomSearchDto) GetVisibilityOk() (*AssetVisibility, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *RandomSearchDto) SetVisibility(v AssetVisibility)`

SetVisibility sets Visibility field to given value.

### HasVisibility

`func (o *RandomSearchDto) HasVisibility() bool`

HasVisibility returns a boolean if a field has been set.

### GetWithDeleted

`func (o *RandomSearchDto) GetWithDeleted() bool`

GetWithDeleted returns the WithDeleted field if non-nil, zero value otherwise.

### GetWithDeletedOk

`func (o *RandomSearchDto) GetWithDeletedOk() (*bool, bool)`

GetWithDeletedOk returns a tuple with the WithDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithDeleted

`func (o *RandomSearchDto) SetWithDeleted(v bool)`

SetWithDeleted sets WithDeleted field to given value.

### HasWithDeleted

`func (o *RandomSearchDto) HasWithDeleted() bool`

HasWithDeleted returns a boolean if a field has been set.

### GetWithExif

`func (o *RandomSearchDto) GetWithExif() bool`

GetWithExif returns the WithExif field if non-nil, zero value otherwise.

### GetWithExifOk

`func (o *RandomSearchDto) GetWithExifOk() (*bool, bool)`

GetWithExifOk returns a tuple with the WithExif field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithExif

`func (o *RandomSearchDto) SetWithExif(v bool)`

SetWithExif sets WithExif field to given value.

### HasWithExif

`func (o *RandomSearchDto) HasWithExif() bool`

HasWithExif returns a boolean if a field has been set.

### GetWithPeople

`func (o *RandomSearchDto) GetWithPeople() bool`

GetWithPeople returns the WithPeople field if non-nil, zero value otherwise.

### GetWithPeopleOk

`func (o *RandomSearchDto) GetWithPeopleOk() (*bool, bool)`

GetWithPeopleOk returns a tuple with the WithPeople field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithPeople

`func (o *RandomSearchDto) SetWithPeople(v bool)`

SetWithPeople sets WithPeople field to given value.

### HasWithPeople

`func (o *RandomSearchDto) HasWithPeople() bool`

HasWithPeople returns a boolean if a field has been set.

### GetWithStacked

`func (o *RandomSearchDto) GetWithStacked() bool`

GetWithStacked returns the WithStacked field if non-nil, zero value otherwise.

### GetWithStackedOk

`func (o *RandomSearchDto) GetWithStackedOk() (*bool, bool)`

GetWithStackedOk returns a tuple with the WithStacked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithStacked

`func (o *RandomSearchDto) SetWithStacked(v bool)`

SetWithStacked sets WithStacked field to given value.

### HasWithStacked

`func (o *RandomSearchDto) HasWithStacked() bool`

HasWithStacked returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


