# SmartSearchDto

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
**Language** | Pointer to **string** | Search language code | [optional] 
**LensModel** | Pointer to **NullableString** | Filter by lens model | [optional] 
**LibraryId** | Pointer to **NullableString** | Library ID to filter by | [optional] 
**Make** | Pointer to **NullableString** | Filter by camera make | [optional] 
**Model** | Pointer to **NullableString** | Filter by camera model | [optional] 
**Ocr** | Pointer to **string** | Filter by OCR text content | [optional] 
**Page** | Pointer to **int32** | Page number | [optional] 
**PersonIds** | Pointer to **[]string** | Filter by person IDs | [optional] 
**Query** | Pointer to **string** | Natural language search query | [optional] 
**QueryAssetId** | Pointer to **string** | Asset ID to use as search reference | [optional] 
**Rating** | Pointer to **NullableInt32** | Filter by rating [1-5], or null for unrated | [optional] 
**Size** | Pointer to **int32** | Number of results to return | [optional] 
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

## Methods

### NewSmartSearchDto

`func NewSmartSearchDto() *SmartSearchDto`

NewSmartSearchDto instantiates a new SmartSearchDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmartSearchDtoWithDefaults

`func NewSmartSearchDtoWithDefaults() *SmartSearchDto`

NewSmartSearchDtoWithDefaults instantiates a new SmartSearchDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbumIds

`func (o *SmartSearchDto) GetAlbumIds() []string`

GetAlbumIds returns the AlbumIds field if non-nil, zero value otherwise.

### GetAlbumIdsOk

`func (o *SmartSearchDto) GetAlbumIdsOk() (*[]string, bool)`

GetAlbumIdsOk returns a tuple with the AlbumIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumIds

`func (o *SmartSearchDto) SetAlbumIds(v []string)`

SetAlbumIds sets AlbumIds field to given value.

### HasAlbumIds

`func (o *SmartSearchDto) HasAlbumIds() bool`

HasAlbumIds returns a boolean if a field has been set.

### GetCity

`func (o *SmartSearchDto) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *SmartSearchDto) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *SmartSearchDto) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *SmartSearchDto) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *SmartSearchDto) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *SmartSearchDto) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetCountry

`func (o *SmartSearchDto) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *SmartSearchDto) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *SmartSearchDto) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *SmartSearchDto) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *SmartSearchDto) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *SmartSearchDto) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetCreatedAfter

`func (o *SmartSearchDto) GetCreatedAfter() time.Time`

GetCreatedAfter returns the CreatedAfter field if non-nil, zero value otherwise.

### GetCreatedAfterOk

`func (o *SmartSearchDto) GetCreatedAfterOk() (*time.Time, bool)`

GetCreatedAfterOk returns a tuple with the CreatedAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAfter

`func (o *SmartSearchDto) SetCreatedAfter(v time.Time)`

SetCreatedAfter sets CreatedAfter field to given value.

### HasCreatedAfter

`func (o *SmartSearchDto) HasCreatedAfter() bool`

HasCreatedAfter returns a boolean if a field has been set.

### GetCreatedBefore

`func (o *SmartSearchDto) GetCreatedBefore() time.Time`

GetCreatedBefore returns the CreatedBefore field if non-nil, zero value otherwise.

### GetCreatedBeforeOk

`func (o *SmartSearchDto) GetCreatedBeforeOk() (*time.Time, bool)`

GetCreatedBeforeOk returns a tuple with the CreatedBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBefore

`func (o *SmartSearchDto) SetCreatedBefore(v time.Time)`

SetCreatedBefore sets CreatedBefore field to given value.

### HasCreatedBefore

`func (o *SmartSearchDto) HasCreatedBefore() bool`

HasCreatedBefore returns a boolean if a field has been set.

### GetIsEncoded

`func (o *SmartSearchDto) GetIsEncoded() bool`

GetIsEncoded returns the IsEncoded field if non-nil, zero value otherwise.

### GetIsEncodedOk

`func (o *SmartSearchDto) GetIsEncodedOk() (*bool, bool)`

GetIsEncodedOk returns a tuple with the IsEncoded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEncoded

`func (o *SmartSearchDto) SetIsEncoded(v bool)`

SetIsEncoded sets IsEncoded field to given value.

### HasIsEncoded

`func (o *SmartSearchDto) HasIsEncoded() bool`

HasIsEncoded returns a boolean if a field has been set.

### GetIsFavorite

`func (o *SmartSearchDto) GetIsFavorite() bool`

GetIsFavorite returns the IsFavorite field if non-nil, zero value otherwise.

### GetIsFavoriteOk

`func (o *SmartSearchDto) GetIsFavoriteOk() (*bool, bool)`

GetIsFavoriteOk returns a tuple with the IsFavorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFavorite

`func (o *SmartSearchDto) SetIsFavorite(v bool)`

SetIsFavorite sets IsFavorite field to given value.

### HasIsFavorite

`func (o *SmartSearchDto) HasIsFavorite() bool`

HasIsFavorite returns a boolean if a field has been set.

### GetIsMotion

`func (o *SmartSearchDto) GetIsMotion() bool`

GetIsMotion returns the IsMotion field if non-nil, zero value otherwise.

### GetIsMotionOk

`func (o *SmartSearchDto) GetIsMotionOk() (*bool, bool)`

GetIsMotionOk returns a tuple with the IsMotion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsMotion

`func (o *SmartSearchDto) SetIsMotion(v bool)`

SetIsMotion sets IsMotion field to given value.

### HasIsMotion

`func (o *SmartSearchDto) HasIsMotion() bool`

HasIsMotion returns a boolean if a field has been set.

### GetIsNotInAlbum

`func (o *SmartSearchDto) GetIsNotInAlbum() bool`

GetIsNotInAlbum returns the IsNotInAlbum field if non-nil, zero value otherwise.

### GetIsNotInAlbumOk

`func (o *SmartSearchDto) GetIsNotInAlbumOk() (*bool, bool)`

GetIsNotInAlbumOk returns a tuple with the IsNotInAlbum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsNotInAlbum

`func (o *SmartSearchDto) SetIsNotInAlbum(v bool)`

SetIsNotInAlbum sets IsNotInAlbum field to given value.

### HasIsNotInAlbum

`func (o *SmartSearchDto) HasIsNotInAlbum() bool`

HasIsNotInAlbum returns a boolean if a field has been set.

### GetIsOffline

`func (o *SmartSearchDto) GetIsOffline() bool`

GetIsOffline returns the IsOffline field if non-nil, zero value otherwise.

### GetIsOfflineOk

`func (o *SmartSearchDto) GetIsOfflineOk() (*bool, bool)`

GetIsOfflineOk returns a tuple with the IsOffline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOffline

`func (o *SmartSearchDto) SetIsOffline(v bool)`

SetIsOffline sets IsOffline field to given value.

### HasIsOffline

`func (o *SmartSearchDto) HasIsOffline() bool`

HasIsOffline returns a boolean if a field has been set.

### GetLanguage

`func (o *SmartSearchDto) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *SmartSearchDto) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *SmartSearchDto) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *SmartSearchDto) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetLensModel

`func (o *SmartSearchDto) GetLensModel() string`

GetLensModel returns the LensModel field if non-nil, zero value otherwise.

### GetLensModelOk

`func (o *SmartSearchDto) GetLensModelOk() (*string, bool)`

GetLensModelOk returns a tuple with the LensModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLensModel

`func (o *SmartSearchDto) SetLensModel(v string)`

SetLensModel sets LensModel field to given value.

### HasLensModel

`func (o *SmartSearchDto) HasLensModel() bool`

HasLensModel returns a boolean if a field has been set.

### SetLensModelNil

`func (o *SmartSearchDto) SetLensModelNil(b bool)`

 SetLensModelNil sets the value for LensModel to be an explicit nil

### UnsetLensModel
`func (o *SmartSearchDto) UnsetLensModel()`

UnsetLensModel ensures that no value is present for LensModel, not even an explicit nil
### GetLibraryId

`func (o *SmartSearchDto) GetLibraryId() string`

GetLibraryId returns the LibraryId field if non-nil, zero value otherwise.

### GetLibraryIdOk

`func (o *SmartSearchDto) GetLibraryIdOk() (*string, bool)`

GetLibraryIdOk returns a tuple with the LibraryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLibraryId

`func (o *SmartSearchDto) SetLibraryId(v string)`

SetLibraryId sets LibraryId field to given value.

### HasLibraryId

`func (o *SmartSearchDto) HasLibraryId() bool`

HasLibraryId returns a boolean if a field has been set.

### SetLibraryIdNil

`func (o *SmartSearchDto) SetLibraryIdNil(b bool)`

 SetLibraryIdNil sets the value for LibraryId to be an explicit nil

### UnsetLibraryId
`func (o *SmartSearchDto) UnsetLibraryId()`

UnsetLibraryId ensures that no value is present for LibraryId, not even an explicit nil
### GetMake

`func (o *SmartSearchDto) GetMake() string`

GetMake returns the Make field if non-nil, zero value otherwise.

### GetMakeOk

`func (o *SmartSearchDto) GetMakeOk() (*string, bool)`

GetMakeOk returns a tuple with the Make field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMake

`func (o *SmartSearchDto) SetMake(v string)`

SetMake sets Make field to given value.

### HasMake

`func (o *SmartSearchDto) HasMake() bool`

HasMake returns a boolean if a field has been set.

### SetMakeNil

`func (o *SmartSearchDto) SetMakeNil(b bool)`

 SetMakeNil sets the value for Make to be an explicit nil

### UnsetMake
`func (o *SmartSearchDto) UnsetMake()`

UnsetMake ensures that no value is present for Make, not even an explicit nil
### GetModel

`func (o *SmartSearchDto) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *SmartSearchDto) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *SmartSearchDto) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *SmartSearchDto) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *SmartSearchDto) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *SmartSearchDto) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetOcr

`func (o *SmartSearchDto) GetOcr() string`

GetOcr returns the Ocr field if non-nil, zero value otherwise.

### GetOcrOk

`func (o *SmartSearchDto) GetOcrOk() (*string, bool)`

GetOcrOk returns a tuple with the Ocr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOcr

`func (o *SmartSearchDto) SetOcr(v string)`

SetOcr sets Ocr field to given value.

### HasOcr

`func (o *SmartSearchDto) HasOcr() bool`

HasOcr returns a boolean if a field has been set.

### GetPage

`func (o *SmartSearchDto) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *SmartSearchDto) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *SmartSearchDto) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *SmartSearchDto) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPersonIds

`func (o *SmartSearchDto) GetPersonIds() []string`

GetPersonIds returns the PersonIds field if non-nil, zero value otherwise.

### GetPersonIdsOk

`func (o *SmartSearchDto) GetPersonIdsOk() (*[]string, bool)`

GetPersonIdsOk returns a tuple with the PersonIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonIds

`func (o *SmartSearchDto) SetPersonIds(v []string)`

SetPersonIds sets PersonIds field to given value.

### HasPersonIds

`func (o *SmartSearchDto) HasPersonIds() bool`

HasPersonIds returns a boolean if a field has been set.

### GetQuery

`func (o *SmartSearchDto) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *SmartSearchDto) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *SmartSearchDto) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *SmartSearchDto) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### GetQueryAssetId

`func (o *SmartSearchDto) GetQueryAssetId() string`

GetQueryAssetId returns the QueryAssetId field if non-nil, zero value otherwise.

### GetQueryAssetIdOk

`func (o *SmartSearchDto) GetQueryAssetIdOk() (*string, bool)`

GetQueryAssetIdOk returns a tuple with the QueryAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueryAssetId

`func (o *SmartSearchDto) SetQueryAssetId(v string)`

SetQueryAssetId sets QueryAssetId field to given value.

### HasQueryAssetId

`func (o *SmartSearchDto) HasQueryAssetId() bool`

HasQueryAssetId returns a boolean if a field has been set.

### GetRating

`func (o *SmartSearchDto) GetRating() int32`

GetRating returns the Rating field if non-nil, zero value otherwise.

### GetRatingOk

`func (o *SmartSearchDto) GetRatingOk() (*int32, bool)`

GetRatingOk returns a tuple with the Rating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRating

`func (o *SmartSearchDto) SetRating(v int32)`

SetRating sets Rating field to given value.

### HasRating

`func (o *SmartSearchDto) HasRating() bool`

HasRating returns a boolean if a field has been set.

### SetRatingNil

`func (o *SmartSearchDto) SetRatingNil(b bool)`

 SetRatingNil sets the value for Rating to be an explicit nil

### UnsetRating
`func (o *SmartSearchDto) UnsetRating()`

UnsetRating ensures that no value is present for Rating, not even an explicit nil
### GetSize

`func (o *SmartSearchDto) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *SmartSearchDto) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *SmartSearchDto) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *SmartSearchDto) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetState

`func (o *SmartSearchDto) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *SmartSearchDto) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *SmartSearchDto) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *SmartSearchDto) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *SmartSearchDto) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *SmartSearchDto) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetTagIds

`func (o *SmartSearchDto) GetTagIds() []string`

GetTagIds returns the TagIds field if non-nil, zero value otherwise.

### GetTagIdsOk

`func (o *SmartSearchDto) GetTagIdsOk() (*[]string, bool)`

GetTagIdsOk returns a tuple with the TagIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagIds

`func (o *SmartSearchDto) SetTagIds(v []string)`

SetTagIds sets TagIds field to given value.

### HasTagIds

`func (o *SmartSearchDto) HasTagIds() bool`

HasTagIds returns a boolean if a field has been set.

### SetTagIdsNil

`func (o *SmartSearchDto) SetTagIdsNil(b bool)`

 SetTagIdsNil sets the value for TagIds to be an explicit nil

### UnsetTagIds
`func (o *SmartSearchDto) UnsetTagIds()`

UnsetTagIds ensures that no value is present for TagIds, not even an explicit nil
### GetTakenAfter

`func (o *SmartSearchDto) GetTakenAfter() time.Time`

GetTakenAfter returns the TakenAfter field if non-nil, zero value otherwise.

### GetTakenAfterOk

`func (o *SmartSearchDto) GetTakenAfterOk() (*time.Time, bool)`

GetTakenAfterOk returns a tuple with the TakenAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTakenAfter

`func (o *SmartSearchDto) SetTakenAfter(v time.Time)`

SetTakenAfter sets TakenAfter field to given value.

### HasTakenAfter

`func (o *SmartSearchDto) HasTakenAfter() bool`

HasTakenAfter returns a boolean if a field has been set.

### GetTakenBefore

`func (o *SmartSearchDto) GetTakenBefore() time.Time`

GetTakenBefore returns the TakenBefore field if non-nil, zero value otherwise.

### GetTakenBeforeOk

`func (o *SmartSearchDto) GetTakenBeforeOk() (*time.Time, bool)`

GetTakenBeforeOk returns a tuple with the TakenBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTakenBefore

`func (o *SmartSearchDto) SetTakenBefore(v time.Time)`

SetTakenBefore sets TakenBefore field to given value.

### HasTakenBefore

`func (o *SmartSearchDto) HasTakenBefore() bool`

HasTakenBefore returns a boolean if a field has been set.

### GetTrashedAfter

`func (o *SmartSearchDto) GetTrashedAfter() time.Time`

GetTrashedAfter returns the TrashedAfter field if non-nil, zero value otherwise.

### GetTrashedAfterOk

`func (o *SmartSearchDto) GetTrashedAfterOk() (*time.Time, bool)`

GetTrashedAfterOk returns a tuple with the TrashedAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrashedAfter

`func (o *SmartSearchDto) SetTrashedAfter(v time.Time)`

SetTrashedAfter sets TrashedAfter field to given value.

### HasTrashedAfter

`func (o *SmartSearchDto) HasTrashedAfter() bool`

HasTrashedAfter returns a boolean if a field has been set.

### GetTrashedBefore

`func (o *SmartSearchDto) GetTrashedBefore() time.Time`

GetTrashedBefore returns the TrashedBefore field if non-nil, zero value otherwise.

### GetTrashedBeforeOk

`func (o *SmartSearchDto) GetTrashedBeforeOk() (*time.Time, bool)`

GetTrashedBeforeOk returns a tuple with the TrashedBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrashedBefore

`func (o *SmartSearchDto) SetTrashedBefore(v time.Time)`

SetTrashedBefore sets TrashedBefore field to given value.

### HasTrashedBefore

`func (o *SmartSearchDto) HasTrashedBefore() bool`

HasTrashedBefore returns a boolean if a field has been set.

### GetType

`func (o *SmartSearchDto) GetType() AssetTypeEnum`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SmartSearchDto) GetTypeOk() (*AssetTypeEnum, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SmartSearchDto) SetType(v AssetTypeEnum)`

SetType sets Type field to given value.

### HasType

`func (o *SmartSearchDto) HasType() bool`

HasType returns a boolean if a field has been set.

### GetUpdatedAfter

`func (o *SmartSearchDto) GetUpdatedAfter() time.Time`

GetUpdatedAfter returns the UpdatedAfter field if non-nil, zero value otherwise.

### GetUpdatedAfterOk

`func (o *SmartSearchDto) GetUpdatedAfterOk() (*time.Time, bool)`

GetUpdatedAfterOk returns a tuple with the UpdatedAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAfter

`func (o *SmartSearchDto) SetUpdatedAfter(v time.Time)`

SetUpdatedAfter sets UpdatedAfter field to given value.

### HasUpdatedAfter

`func (o *SmartSearchDto) HasUpdatedAfter() bool`

HasUpdatedAfter returns a boolean if a field has been set.

### GetUpdatedBefore

`func (o *SmartSearchDto) GetUpdatedBefore() time.Time`

GetUpdatedBefore returns the UpdatedBefore field if non-nil, zero value otherwise.

### GetUpdatedBeforeOk

`func (o *SmartSearchDto) GetUpdatedBeforeOk() (*time.Time, bool)`

GetUpdatedBeforeOk returns a tuple with the UpdatedBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBefore

`func (o *SmartSearchDto) SetUpdatedBefore(v time.Time)`

SetUpdatedBefore sets UpdatedBefore field to given value.

### HasUpdatedBefore

`func (o *SmartSearchDto) HasUpdatedBefore() bool`

HasUpdatedBefore returns a boolean if a field has been set.

### GetVisibility

`func (o *SmartSearchDto) GetVisibility() AssetVisibility`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *SmartSearchDto) GetVisibilityOk() (*AssetVisibility, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *SmartSearchDto) SetVisibility(v AssetVisibility)`

SetVisibility sets Visibility field to given value.

### HasVisibility

`func (o *SmartSearchDto) HasVisibility() bool`

HasVisibility returns a boolean if a field has been set.

### GetWithDeleted

`func (o *SmartSearchDto) GetWithDeleted() bool`

GetWithDeleted returns the WithDeleted field if non-nil, zero value otherwise.

### GetWithDeletedOk

`func (o *SmartSearchDto) GetWithDeletedOk() (*bool, bool)`

GetWithDeletedOk returns a tuple with the WithDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithDeleted

`func (o *SmartSearchDto) SetWithDeleted(v bool)`

SetWithDeleted sets WithDeleted field to given value.

### HasWithDeleted

`func (o *SmartSearchDto) HasWithDeleted() bool`

HasWithDeleted returns a boolean if a field has been set.

### GetWithExif

`func (o *SmartSearchDto) GetWithExif() bool`

GetWithExif returns the WithExif field if non-nil, zero value otherwise.

### GetWithExifOk

`func (o *SmartSearchDto) GetWithExifOk() (*bool, bool)`

GetWithExifOk returns a tuple with the WithExif field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithExif

`func (o *SmartSearchDto) SetWithExif(v bool)`

SetWithExif sets WithExif field to given value.

### HasWithExif

`func (o *SmartSearchDto) HasWithExif() bool`

HasWithExif returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


