# SyncAssetFaceV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** | Asset ID | 
**BoundingBoxX1** | **int32** | Bounding box X1 | 
**BoundingBoxX2** | **int32** | Bounding box X2 | 
**BoundingBoxY1** | **int32** | Bounding box Y1 | 
**BoundingBoxY2** | **int32** | Bounding box Y2 | 
**DeletedAt** | **NullableTime** | Face deleted at | 
**Id** | **string** | Asset face ID | 
**ImageHeight** | **int32** | Image height | 
**ImageWidth** | **int32** | Image width | 
**IsVisible** | **bool** | Is the face visible in the asset | 
**PersonId** | **NullableString** | Person ID | 
**SourceType** | **string** | Source type | 

## Methods

### NewSyncAssetFaceV2

`func NewSyncAssetFaceV2(assetId string, boundingBoxX1 int32, boundingBoxX2 int32, boundingBoxY1 int32, boundingBoxY2 int32, deletedAt NullableTime, id string, imageHeight int32, imageWidth int32, isVisible bool, personId NullableString, sourceType string, ) *SyncAssetFaceV2`

NewSyncAssetFaceV2 instantiates a new SyncAssetFaceV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncAssetFaceV2WithDefaults

`func NewSyncAssetFaceV2WithDefaults() *SyncAssetFaceV2`

NewSyncAssetFaceV2WithDefaults instantiates a new SyncAssetFaceV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *SyncAssetFaceV2) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *SyncAssetFaceV2) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *SyncAssetFaceV2) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetBoundingBoxX1

`func (o *SyncAssetFaceV2) GetBoundingBoxX1() int32`

GetBoundingBoxX1 returns the BoundingBoxX1 field if non-nil, zero value otherwise.

### GetBoundingBoxX1Ok

`func (o *SyncAssetFaceV2) GetBoundingBoxX1Ok() (*int32, bool)`

GetBoundingBoxX1Ok returns a tuple with the BoundingBoxX1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoundingBoxX1

`func (o *SyncAssetFaceV2) SetBoundingBoxX1(v int32)`

SetBoundingBoxX1 sets BoundingBoxX1 field to given value.


### GetBoundingBoxX2

`func (o *SyncAssetFaceV2) GetBoundingBoxX2() int32`

GetBoundingBoxX2 returns the BoundingBoxX2 field if non-nil, zero value otherwise.

### GetBoundingBoxX2Ok

`func (o *SyncAssetFaceV2) GetBoundingBoxX2Ok() (*int32, bool)`

GetBoundingBoxX2Ok returns a tuple with the BoundingBoxX2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoundingBoxX2

`func (o *SyncAssetFaceV2) SetBoundingBoxX2(v int32)`

SetBoundingBoxX2 sets BoundingBoxX2 field to given value.


### GetBoundingBoxY1

`func (o *SyncAssetFaceV2) GetBoundingBoxY1() int32`

GetBoundingBoxY1 returns the BoundingBoxY1 field if non-nil, zero value otherwise.

### GetBoundingBoxY1Ok

`func (o *SyncAssetFaceV2) GetBoundingBoxY1Ok() (*int32, bool)`

GetBoundingBoxY1Ok returns a tuple with the BoundingBoxY1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoundingBoxY1

`func (o *SyncAssetFaceV2) SetBoundingBoxY1(v int32)`

SetBoundingBoxY1 sets BoundingBoxY1 field to given value.


### GetBoundingBoxY2

`func (o *SyncAssetFaceV2) GetBoundingBoxY2() int32`

GetBoundingBoxY2 returns the BoundingBoxY2 field if non-nil, zero value otherwise.

### GetBoundingBoxY2Ok

`func (o *SyncAssetFaceV2) GetBoundingBoxY2Ok() (*int32, bool)`

GetBoundingBoxY2Ok returns a tuple with the BoundingBoxY2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoundingBoxY2

`func (o *SyncAssetFaceV2) SetBoundingBoxY2(v int32)`

SetBoundingBoxY2 sets BoundingBoxY2 field to given value.


### GetDeletedAt

`func (o *SyncAssetFaceV2) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *SyncAssetFaceV2) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *SyncAssetFaceV2) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.


### SetDeletedAtNil

`func (o *SyncAssetFaceV2) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *SyncAssetFaceV2) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil
### GetId

`func (o *SyncAssetFaceV2) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SyncAssetFaceV2) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SyncAssetFaceV2) SetId(v string)`

SetId sets Id field to given value.


### GetImageHeight

`func (o *SyncAssetFaceV2) GetImageHeight() int32`

GetImageHeight returns the ImageHeight field if non-nil, zero value otherwise.

### GetImageHeightOk

`func (o *SyncAssetFaceV2) GetImageHeightOk() (*int32, bool)`

GetImageHeightOk returns a tuple with the ImageHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageHeight

`func (o *SyncAssetFaceV2) SetImageHeight(v int32)`

SetImageHeight sets ImageHeight field to given value.


### GetImageWidth

`func (o *SyncAssetFaceV2) GetImageWidth() int32`

GetImageWidth returns the ImageWidth field if non-nil, zero value otherwise.

### GetImageWidthOk

`func (o *SyncAssetFaceV2) GetImageWidthOk() (*int32, bool)`

GetImageWidthOk returns a tuple with the ImageWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageWidth

`func (o *SyncAssetFaceV2) SetImageWidth(v int32)`

SetImageWidth sets ImageWidth field to given value.


### GetIsVisible

`func (o *SyncAssetFaceV2) GetIsVisible() bool`

GetIsVisible returns the IsVisible field if non-nil, zero value otherwise.

### GetIsVisibleOk

`func (o *SyncAssetFaceV2) GetIsVisibleOk() (*bool, bool)`

GetIsVisibleOk returns a tuple with the IsVisible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsVisible

`func (o *SyncAssetFaceV2) SetIsVisible(v bool)`

SetIsVisible sets IsVisible field to given value.


### GetPersonId

`func (o *SyncAssetFaceV2) GetPersonId() string`

GetPersonId returns the PersonId field if non-nil, zero value otherwise.

### GetPersonIdOk

`func (o *SyncAssetFaceV2) GetPersonIdOk() (*string, bool)`

GetPersonIdOk returns a tuple with the PersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonId

`func (o *SyncAssetFaceV2) SetPersonId(v string)`

SetPersonId sets PersonId field to given value.


### SetPersonIdNil

`func (o *SyncAssetFaceV2) SetPersonIdNil(b bool)`

 SetPersonIdNil sets the value for PersonId to be an explicit nil

### UnsetPersonId
`func (o *SyncAssetFaceV2) UnsetPersonId()`

UnsetPersonId ensures that no value is present for PersonId, not even an explicit nil
### GetSourceType

`func (o *SyncAssetFaceV2) GetSourceType() string`

GetSourceType returns the SourceType field if non-nil, zero value otherwise.

### GetSourceTypeOk

`func (o *SyncAssetFaceV2) GetSourceTypeOk() (*string, bool)`

GetSourceTypeOk returns a tuple with the SourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceType

`func (o *SyncAssetFaceV2) SetSourceType(v string)`

SetSourceType sets SourceType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


