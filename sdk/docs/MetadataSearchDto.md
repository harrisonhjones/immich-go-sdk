# MetadataSearchDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlbumIds** | Pointer to **[]string** | Filter by album IDs | [optional] 
**Checksum** | Pointer to **string** | Filter by file checksum | [optional] 
**City** | Pointer to **NullableString** | Filter by city name | [optional] 
**Country** | Pointer to **NullableString** | Filter by country name | [optional] 
**CreatedAfter** | Pointer to **time.Time** | Filter by creation date (after) | [optional] 
**CreatedBefore** | Pointer to **time.Time** | Filter by creation date (before) | [optional] 
**Description** | Pointer to **string** | Filter by description text | [optional] 
**EncodedVideoPath** | Pointer to **string** | Filter by encoded video file path | [optional] 
**Id** | Pointer to **string** | Filter by asset ID | [optional] 
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
**Order** | Pointer to [**AssetOrder**](AssetOrder.md) |  | [optional] 
**OriginalFileName** | Pointer to **string** | Filter by original file name | [optional] 
**OriginalPath** | Pointer to **string** | Filter by original file path | [optional] 
**Page** | Pointer to **float32** | Page number | [optional] 
**PersonIds** | Pointer to **[]string** | Filter by person IDs | [optional] 
**PreviewPath** | Pointer to **string** | Filter by preview file path | [optional] 
**Rating** | Pointer to **NullableFloat32** | Filter by rating [1-5], or null for unrated | [optional] 
**Size** | Pointer to **float32** | Number of results to return | [optional] 
**State** | Pointer to **NullableString** | Filter by state/province name | [optional] 
**TagIds** | Pointer to **[]string** | Filter by tag IDs | [optional] 
**TakenAfter** | Pointer to **time.Time** | Filter by taken date (after) | [optional] 
**TakenBefore** | Pointer to **time.Time** | Filter by taken date (before) | [optional] 
**ThumbnailPath** | Pointer to **string** | Filter by thumbnail file path | [optional] 
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

### NewMetadataSearchDto

`func NewMetadataSearchDto() *MetadataSearchDto`

NewMetadataSearchDto instantiates a new MetadataSearchDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMetadataSearchDtoWithDefaults

`func NewMetadataSearchDtoWithDefaults() *MetadataSearchDto`

NewMetadataSearchDtoWithDefaults instantiates a new MetadataSearchDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbumIds

`func (o *MetadataSearchDto) GetAlbumIds() []string`

GetAlbumIds returns the AlbumIds field if non-nil, zero value otherwise.

### GetAlbumIdsOk

`func (o *MetadataSearchDto) GetAlbumIdsOk() (*[]string, bool)`

GetAlbumIdsOk returns a tuple with the AlbumIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumIds

`func (o *MetadataSearchDto) SetAlbumIds(v []string)`

SetAlbumIds sets AlbumIds field to given value.

### HasAlbumIds

`func (o *MetadataSearchDto) HasAlbumIds() bool`

HasAlbumIds returns a boolean if a field has been set.

### GetChecksum

`func (o *MetadataSearchDto) GetChecksum() string`

GetChecksum returns the Checksum field if non-nil, zero value otherwise.

### GetChecksumOk

`func (o *MetadataSearchDto) GetChecksumOk() (*string, bool)`

GetChecksumOk returns a tuple with the Checksum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecksum

`func (o *MetadataSearchDto) SetChecksum(v string)`

SetChecksum sets Checksum field to given value.

### HasChecksum

`func (o *MetadataSearchDto) HasChecksum() bool`

HasChecksum returns a boolean if a field has been set.

### GetCity

`func (o *MetadataSearchDto) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *MetadataSearchDto) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *MetadataSearchDto) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *MetadataSearchDto) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *MetadataSearchDto) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *MetadataSearchDto) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetCountry

`func (o *MetadataSearchDto) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *MetadataSearchDto) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *MetadataSearchDto) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *MetadataSearchDto) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *MetadataSearchDto) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *MetadataSearchDto) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetCreatedAfter

`func (o *MetadataSearchDto) GetCreatedAfter() time.Time`

GetCreatedAfter returns the CreatedAfter field if non-nil, zero value otherwise.

### GetCreatedAfterOk

`func (o *MetadataSearchDto) GetCreatedAfterOk() (*time.Time, bool)`

GetCreatedAfterOk returns a tuple with the CreatedAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAfter

`func (o *MetadataSearchDto) SetCreatedAfter(v time.Time)`

SetCreatedAfter sets CreatedAfter field to given value.

### HasCreatedAfter

`func (o *MetadataSearchDto) HasCreatedAfter() bool`

HasCreatedAfter returns a boolean if a field has been set.

### GetCreatedBefore

`func (o *MetadataSearchDto) GetCreatedBefore() time.Time`

GetCreatedBefore returns the CreatedBefore field if non-nil, zero value otherwise.

### GetCreatedBeforeOk

`func (o *MetadataSearchDto) GetCreatedBeforeOk() (*time.Time, bool)`

GetCreatedBeforeOk returns a tuple with the CreatedBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBefore

`func (o *MetadataSearchDto) SetCreatedBefore(v time.Time)`

SetCreatedBefore sets CreatedBefore field to given value.

### HasCreatedBefore

`func (o *MetadataSearchDto) HasCreatedBefore() bool`

HasCreatedBefore returns a boolean if a field has been set.

### GetDescription

`func (o *MetadataSearchDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *MetadataSearchDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *MetadataSearchDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *MetadataSearchDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetEncodedVideoPath

`func (o *MetadataSearchDto) GetEncodedVideoPath() string`

GetEncodedVideoPath returns the EncodedVideoPath field if non-nil, zero value otherwise.

### GetEncodedVideoPathOk

`func (o *MetadataSearchDto) GetEncodedVideoPathOk() (*string, bool)`

GetEncodedVideoPathOk returns a tuple with the EncodedVideoPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncodedVideoPath

`func (o *MetadataSearchDto) SetEncodedVideoPath(v string)`

SetEncodedVideoPath sets EncodedVideoPath field to given value.

### HasEncodedVideoPath

`func (o *MetadataSearchDto) HasEncodedVideoPath() bool`

HasEncodedVideoPath returns a boolean if a field has been set.

### GetId

`func (o *MetadataSearchDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MetadataSearchDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MetadataSearchDto) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *MetadataSearchDto) HasId() bool`

HasId returns a boolean if a field has been set.

### GetIsEncoded

`func (o *MetadataSearchDto) GetIsEncoded() bool`

GetIsEncoded returns the IsEncoded field if non-nil, zero value otherwise.

### GetIsEncodedOk

`func (o *MetadataSearchDto) GetIsEncodedOk() (*bool, bool)`

GetIsEncodedOk returns a tuple with the IsEncoded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsEncoded

`func (o *MetadataSearchDto) SetIsEncoded(v bool)`

SetIsEncoded sets IsEncoded field to given value.

### HasIsEncoded

`func (o *MetadataSearchDto) HasIsEncoded() bool`

HasIsEncoded returns a boolean if a field has been set.

### GetIsFavorite

`func (o *MetadataSearchDto) GetIsFavorite() bool`

GetIsFavorite returns the IsFavorite field if non-nil, zero value otherwise.

### GetIsFavoriteOk

`func (o *MetadataSearchDto) GetIsFavoriteOk() (*bool, bool)`

GetIsFavoriteOk returns a tuple with the IsFavorite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsFavorite

`func (o *MetadataSearchDto) SetIsFavorite(v bool)`

SetIsFavorite sets IsFavorite field to given value.

### HasIsFavorite

`func (o *MetadataSearchDto) HasIsFavorite() bool`

HasIsFavorite returns a boolean if a field has been set.

### GetIsMotion

`func (o *MetadataSearchDto) GetIsMotion() bool`

GetIsMotion returns the IsMotion field if non-nil, zero value otherwise.

### GetIsMotionOk

`func (o *MetadataSearchDto) GetIsMotionOk() (*bool, bool)`

GetIsMotionOk returns a tuple with the IsMotion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsMotion

`func (o *MetadataSearchDto) SetIsMotion(v bool)`

SetIsMotion sets IsMotion field to given value.

### HasIsMotion

`func (o *MetadataSearchDto) HasIsMotion() bool`

HasIsMotion returns a boolean if a field has been set.

### GetIsNotInAlbum

`func (o *MetadataSearchDto) GetIsNotInAlbum() bool`

GetIsNotInAlbum returns the IsNotInAlbum field if non-nil, zero value otherwise.

### GetIsNotInAlbumOk

`func (o *MetadataSearchDto) GetIsNotInAlbumOk() (*bool, bool)`

GetIsNotInAlbumOk returns a tuple with the IsNotInAlbum field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsNotInAlbum

`func (o *MetadataSearchDto) SetIsNotInAlbum(v bool)`

SetIsNotInAlbum sets IsNotInAlbum field to given value.

### HasIsNotInAlbum

`func (o *MetadataSearchDto) HasIsNotInAlbum() bool`

HasIsNotInAlbum returns a boolean if a field has been set.

### GetIsOffline

`func (o *MetadataSearchDto) GetIsOffline() bool`

GetIsOffline returns the IsOffline field if non-nil, zero value otherwise.

### GetIsOfflineOk

`func (o *MetadataSearchDto) GetIsOfflineOk() (*bool, bool)`

GetIsOfflineOk returns a tuple with the IsOffline field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOffline

`func (o *MetadataSearchDto) SetIsOffline(v bool)`

SetIsOffline sets IsOffline field to given value.

### HasIsOffline

`func (o *MetadataSearchDto) HasIsOffline() bool`

HasIsOffline returns a boolean if a field has been set.

### GetLensModel

`func (o *MetadataSearchDto) GetLensModel() string`

GetLensModel returns the LensModel field if non-nil, zero value otherwise.

### GetLensModelOk

`func (o *MetadataSearchDto) GetLensModelOk() (*string, bool)`

GetLensModelOk returns a tuple with the LensModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLensModel

`func (o *MetadataSearchDto) SetLensModel(v string)`

SetLensModel sets LensModel field to given value.

### HasLensModel

`func (o *MetadataSearchDto) HasLensModel() bool`

HasLensModel returns a boolean if a field has been set.

### SetLensModelNil

`func (o *MetadataSearchDto) SetLensModelNil(b bool)`

 SetLensModelNil sets the value for LensModel to be an explicit nil

### UnsetLensModel
`func (o *MetadataSearchDto) UnsetLensModel()`

UnsetLensModel ensures that no value is present for LensModel, not even an explicit nil
### GetLibraryId

`func (o *MetadataSearchDto) GetLibraryId() string`

GetLibraryId returns the LibraryId field if non-nil, zero value otherwise.

### GetLibraryIdOk

`func (o *MetadataSearchDto) GetLibraryIdOk() (*string, bool)`

GetLibraryIdOk returns a tuple with the LibraryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLibraryId

`func (o *MetadataSearchDto) SetLibraryId(v string)`

SetLibraryId sets LibraryId field to given value.

### HasLibraryId

`func (o *MetadataSearchDto) HasLibraryId() bool`

HasLibraryId returns a boolean if a field has been set.

### SetLibraryIdNil

`func (o *MetadataSearchDto) SetLibraryIdNil(b bool)`

 SetLibraryIdNil sets the value for LibraryId to be an explicit nil

### UnsetLibraryId
`func (o *MetadataSearchDto) UnsetLibraryId()`

UnsetLibraryId ensures that no value is present for LibraryId, not even an explicit nil
### GetMake

`func (o *MetadataSearchDto) GetMake() string`

GetMake returns the Make field if non-nil, zero value otherwise.

### GetMakeOk

`func (o *MetadataSearchDto) GetMakeOk() (*string, bool)`

GetMakeOk returns a tuple with the Make field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMake

`func (o *MetadataSearchDto) SetMake(v string)`

SetMake sets Make field to given value.

### HasMake

`func (o *MetadataSearchDto) HasMake() bool`

HasMake returns a boolean if a field has been set.

### SetMakeNil

`func (o *MetadataSearchDto) SetMakeNil(b bool)`

 SetMakeNil sets the value for Make to be an explicit nil

### UnsetMake
`func (o *MetadataSearchDto) UnsetMake()`

UnsetMake ensures that no value is present for Make, not even an explicit nil
### GetModel

`func (o *MetadataSearchDto) GetModel() string`

GetModel returns the Model field if non-nil, zero value otherwise.

### GetModelOk

`func (o *MetadataSearchDto) GetModelOk() (*string, bool)`

GetModelOk returns a tuple with the Model field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModel

`func (o *MetadataSearchDto) SetModel(v string)`

SetModel sets Model field to given value.

### HasModel

`func (o *MetadataSearchDto) HasModel() bool`

HasModel returns a boolean if a field has been set.

### SetModelNil

`func (o *MetadataSearchDto) SetModelNil(b bool)`

 SetModelNil sets the value for Model to be an explicit nil

### UnsetModel
`func (o *MetadataSearchDto) UnsetModel()`

UnsetModel ensures that no value is present for Model, not even an explicit nil
### GetOcr

`func (o *MetadataSearchDto) GetOcr() string`

GetOcr returns the Ocr field if non-nil, zero value otherwise.

### GetOcrOk

`func (o *MetadataSearchDto) GetOcrOk() (*string, bool)`

GetOcrOk returns a tuple with the Ocr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOcr

`func (o *MetadataSearchDto) SetOcr(v string)`

SetOcr sets Ocr field to given value.

### HasOcr

`func (o *MetadataSearchDto) HasOcr() bool`

HasOcr returns a boolean if a field has been set.

### GetOrder

`func (o *MetadataSearchDto) GetOrder() AssetOrder`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *MetadataSearchDto) GetOrderOk() (*AssetOrder, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *MetadataSearchDto) SetOrder(v AssetOrder)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *MetadataSearchDto) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetOriginalFileName

`func (o *MetadataSearchDto) GetOriginalFileName() string`

GetOriginalFileName returns the OriginalFileName field if non-nil, zero value otherwise.

### GetOriginalFileNameOk

`func (o *MetadataSearchDto) GetOriginalFileNameOk() (*string, bool)`

GetOriginalFileNameOk returns a tuple with the OriginalFileName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalFileName

`func (o *MetadataSearchDto) SetOriginalFileName(v string)`

SetOriginalFileName sets OriginalFileName field to given value.

### HasOriginalFileName

`func (o *MetadataSearchDto) HasOriginalFileName() bool`

HasOriginalFileName returns a boolean if a field has been set.

### GetOriginalPath

`func (o *MetadataSearchDto) GetOriginalPath() string`

GetOriginalPath returns the OriginalPath field if non-nil, zero value otherwise.

### GetOriginalPathOk

`func (o *MetadataSearchDto) GetOriginalPathOk() (*string, bool)`

GetOriginalPathOk returns a tuple with the OriginalPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalPath

`func (o *MetadataSearchDto) SetOriginalPath(v string)`

SetOriginalPath sets OriginalPath field to given value.

### HasOriginalPath

`func (o *MetadataSearchDto) HasOriginalPath() bool`

HasOriginalPath returns a boolean if a field has been set.

### GetPage

`func (o *MetadataSearchDto) GetPage() float32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *MetadataSearchDto) GetPageOk() (*float32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *MetadataSearchDto) SetPage(v float32)`

SetPage sets Page field to given value.

### HasPage

`func (o *MetadataSearchDto) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetPersonIds

`func (o *MetadataSearchDto) GetPersonIds() []string`

GetPersonIds returns the PersonIds field if non-nil, zero value otherwise.

### GetPersonIdsOk

`func (o *MetadataSearchDto) GetPersonIdsOk() (*[]string, bool)`

GetPersonIdsOk returns a tuple with the PersonIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonIds

`func (o *MetadataSearchDto) SetPersonIds(v []string)`

SetPersonIds sets PersonIds field to given value.

### HasPersonIds

`func (o *MetadataSearchDto) HasPersonIds() bool`

HasPersonIds returns a boolean if a field has been set.

### GetPreviewPath

`func (o *MetadataSearchDto) GetPreviewPath() string`

GetPreviewPath returns the PreviewPath field if non-nil, zero value otherwise.

### GetPreviewPathOk

`func (o *MetadataSearchDto) GetPreviewPathOk() (*string, bool)`

GetPreviewPathOk returns a tuple with the PreviewPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviewPath

`func (o *MetadataSearchDto) SetPreviewPath(v string)`

SetPreviewPath sets PreviewPath field to given value.

### HasPreviewPath

`func (o *MetadataSearchDto) HasPreviewPath() bool`

HasPreviewPath returns a boolean if a field has been set.

### GetRating

`func (o *MetadataSearchDto) GetRating() float32`

GetRating returns the Rating field if non-nil, zero value otherwise.

### GetRatingOk

`func (o *MetadataSearchDto) GetRatingOk() (*float32, bool)`

GetRatingOk returns a tuple with the Rating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRating

`func (o *MetadataSearchDto) SetRating(v float32)`

SetRating sets Rating field to given value.

### HasRating

`func (o *MetadataSearchDto) HasRating() bool`

HasRating returns a boolean if a field has been set.

### SetRatingNil

`func (o *MetadataSearchDto) SetRatingNil(b bool)`

 SetRatingNil sets the value for Rating to be an explicit nil

### UnsetRating
`func (o *MetadataSearchDto) UnsetRating()`

UnsetRating ensures that no value is present for Rating, not even an explicit nil
### GetSize

`func (o *MetadataSearchDto) GetSize() float32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *MetadataSearchDto) GetSizeOk() (*float32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *MetadataSearchDto) SetSize(v float32)`

SetSize sets Size field to given value.

### HasSize

`func (o *MetadataSearchDto) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetState

`func (o *MetadataSearchDto) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *MetadataSearchDto) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *MetadataSearchDto) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *MetadataSearchDto) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *MetadataSearchDto) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *MetadataSearchDto) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetTagIds

`func (o *MetadataSearchDto) GetTagIds() []string`

GetTagIds returns the TagIds field if non-nil, zero value otherwise.

### GetTagIdsOk

`func (o *MetadataSearchDto) GetTagIdsOk() (*[]string, bool)`

GetTagIdsOk returns a tuple with the TagIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagIds

`func (o *MetadataSearchDto) SetTagIds(v []string)`

SetTagIds sets TagIds field to given value.

### HasTagIds

`func (o *MetadataSearchDto) HasTagIds() bool`

HasTagIds returns a boolean if a field has been set.

### SetTagIdsNil

`func (o *MetadataSearchDto) SetTagIdsNil(b bool)`

 SetTagIdsNil sets the value for TagIds to be an explicit nil

### UnsetTagIds
`func (o *MetadataSearchDto) UnsetTagIds()`

UnsetTagIds ensures that no value is present for TagIds, not even an explicit nil
### GetTakenAfter

`func (o *MetadataSearchDto) GetTakenAfter() time.Time`

GetTakenAfter returns the TakenAfter field if non-nil, zero value otherwise.

### GetTakenAfterOk

`func (o *MetadataSearchDto) GetTakenAfterOk() (*time.Time, bool)`

GetTakenAfterOk returns a tuple with the TakenAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTakenAfter

`func (o *MetadataSearchDto) SetTakenAfter(v time.Time)`

SetTakenAfter sets TakenAfter field to given value.

### HasTakenAfter

`func (o *MetadataSearchDto) HasTakenAfter() bool`

HasTakenAfter returns a boolean if a field has been set.

### GetTakenBefore

`func (o *MetadataSearchDto) GetTakenBefore() time.Time`

GetTakenBefore returns the TakenBefore field if non-nil, zero value otherwise.

### GetTakenBeforeOk

`func (o *MetadataSearchDto) GetTakenBeforeOk() (*time.Time, bool)`

GetTakenBeforeOk returns a tuple with the TakenBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTakenBefore

`func (o *MetadataSearchDto) SetTakenBefore(v time.Time)`

SetTakenBefore sets TakenBefore field to given value.

### HasTakenBefore

`func (o *MetadataSearchDto) HasTakenBefore() bool`

HasTakenBefore returns a boolean if a field has been set.

### GetThumbnailPath

`func (o *MetadataSearchDto) GetThumbnailPath() string`

GetThumbnailPath returns the ThumbnailPath field if non-nil, zero value otherwise.

### GetThumbnailPathOk

`func (o *MetadataSearchDto) GetThumbnailPathOk() (*string, bool)`

GetThumbnailPathOk returns a tuple with the ThumbnailPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbnailPath

`func (o *MetadataSearchDto) SetThumbnailPath(v string)`

SetThumbnailPath sets ThumbnailPath field to given value.

### HasThumbnailPath

`func (o *MetadataSearchDto) HasThumbnailPath() bool`

HasThumbnailPath returns a boolean if a field has been set.

### GetTrashedAfter

`func (o *MetadataSearchDto) GetTrashedAfter() time.Time`

GetTrashedAfter returns the TrashedAfter field if non-nil, zero value otherwise.

### GetTrashedAfterOk

`func (o *MetadataSearchDto) GetTrashedAfterOk() (*time.Time, bool)`

GetTrashedAfterOk returns a tuple with the TrashedAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrashedAfter

`func (o *MetadataSearchDto) SetTrashedAfter(v time.Time)`

SetTrashedAfter sets TrashedAfter field to given value.

### HasTrashedAfter

`func (o *MetadataSearchDto) HasTrashedAfter() bool`

HasTrashedAfter returns a boolean if a field has been set.

### GetTrashedBefore

`func (o *MetadataSearchDto) GetTrashedBefore() time.Time`

GetTrashedBefore returns the TrashedBefore field if non-nil, zero value otherwise.

### GetTrashedBeforeOk

`func (o *MetadataSearchDto) GetTrashedBeforeOk() (*time.Time, bool)`

GetTrashedBeforeOk returns a tuple with the TrashedBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrashedBefore

`func (o *MetadataSearchDto) SetTrashedBefore(v time.Time)`

SetTrashedBefore sets TrashedBefore field to given value.

### HasTrashedBefore

`func (o *MetadataSearchDto) HasTrashedBefore() bool`

HasTrashedBefore returns a boolean if a field has been set.

### GetType

`func (o *MetadataSearchDto) GetType() AssetTypeEnum`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *MetadataSearchDto) GetTypeOk() (*AssetTypeEnum, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *MetadataSearchDto) SetType(v AssetTypeEnum)`

SetType sets Type field to given value.

### HasType

`func (o *MetadataSearchDto) HasType() bool`

HasType returns a boolean if a field has been set.

### GetUpdatedAfter

`func (o *MetadataSearchDto) GetUpdatedAfter() time.Time`

GetUpdatedAfter returns the UpdatedAfter field if non-nil, zero value otherwise.

### GetUpdatedAfterOk

`func (o *MetadataSearchDto) GetUpdatedAfterOk() (*time.Time, bool)`

GetUpdatedAfterOk returns a tuple with the UpdatedAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAfter

`func (o *MetadataSearchDto) SetUpdatedAfter(v time.Time)`

SetUpdatedAfter sets UpdatedAfter field to given value.

### HasUpdatedAfter

`func (o *MetadataSearchDto) HasUpdatedAfter() bool`

HasUpdatedAfter returns a boolean if a field has been set.

### GetUpdatedBefore

`func (o *MetadataSearchDto) GetUpdatedBefore() time.Time`

GetUpdatedBefore returns the UpdatedBefore field if non-nil, zero value otherwise.

### GetUpdatedBeforeOk

`func (o *MetadataSearchDto) GetUpdatedBeforeOk() (*time.Time, bool)`

GetUpdatedBeforeOk returns a tuple with the UpdatedBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedBefore

`func (o *MetadataSearchDto) SetUpdatedBefore(v time.Time)`

SetUpdatedBefore sets UpdatedBefore field to given value.

### HasUpdatedBefore

`func (o *MetadataSearchDto) HasUpdatedBefore() bool`

HasUpdatedBefore returns a boolean if a field has been set.

### GetVisibility

`func (o *MetadataSearchDto) GetVisibility() AssetVisibility`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *MetadataSearchDto) GetVisibilityOk() (*AssetVisibility, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *MetadataSearchDto) SetVisibility(v AssetVisibility)`

SetVisibility sets Visibility field to given value.

### HasVisibility

`func (o *MetadataSearchDto) HasVisibility() bool`

HasVisibility returns a boolean if a field has been set.

### GetWithDeleted

`func (o *MetadataSearchDto) GetWithDeleted() bool`

GetWithDeleted returns the WithDeleted field if non-nil, zero value otherwise.

### GetWithDeletedOk

`func (o *MetadataSearchDto) GetWithDeletedOk() (*bool, bool)`

GetWithDeletedOk returns a tuple with the WithDeleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithDeleted

`func (o *MetadataSearchDto) SetWithDeleted(v bool)`

SetWithDeleted sets WithDeleted field to given value.

### HasWithDeleted

`func (o *MetadataSearchDto) HasWithDeleted() bool`

HasWithDeleted returns a boolean if a field has been set.

### GetWithExif

`func (o *MetadataSearchDto) GetWithExif() bool`

GetWithExif returns the WithExif field if non-nil, zero value otherwise.

### GetWithExifOk

`func (o *MetadataSearchDto) GetWithExifOk() (*bool, bool)`

GetWithExifOk returns a tuple with the WithExif field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithExif

`func (o *MetadataSearchDto) SetWithExif(v bool)`

SetWithExif sets WithExif field to given value.

### HasWithExif

`func (o *MetadataSearchDto) HasWithExif() bool`

HasWithExif returns a boolean if a field has been set.

### GetWithPeople

`func (o *MetadataSearchDto) GetWithPeople() bool`

GetWithPeople returns the WithPeople field if non-nil, zero value otherwise.

### GetWithPeopleOk

`func (o *MetadataSearchDto) GetWithPeopleOk() (*bool, bool)`

GetWithPeopleOk returns a tuple with the WithPeople field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithPeople

`func (o *MetadataSearchDto) SetWithPeople(v bool)`

SetWithPeople sets WithPeople field to given value.

### HasWithPeople

`func (o *MetadataSearchDto) HasWithPeople() bool`

HasWithPeople returns a boolean if a field has been set.

### GetWithStacked

`func (o *MetadataSearchDto) GetWithStacked() bool`

GetWithStacked returns the WithStacked field if non-nil, zero value otherwise.

### GetWithStackedOk

`func (o *MetadataSearchDto) GetWithStackedOk() (*bool, bool)`

GetWithStackedOk returns a tuple with the WithStacked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithStacked

`func (o *MetadataSearchDto) SetWithStacked(v bool)`

SetWithStacked sets WithStacked field to given value.

### HasWithStacked

`func (o *MetadataSearchDto) HasWithStacked() bool`

HasWithStacked returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


