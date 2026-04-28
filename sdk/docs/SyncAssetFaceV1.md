# SyncAssetFaceV1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** | Asset ID | 
**BoundingBoxX1** | **int32** | Bounding box X1 | 
**BoundingBoxX2** | **int32** | Bounding box X2 | 
**BoundingBoxY1** | **int32** | Bounding box Y1 | 
**BoundingBoxY2** | **int32** | Bounding box Y2 | 
**Id** | **string** | Asset face ID | 
**ImageHeight** | **int32** | Image height | 
**ImageWidth** | **int32** | Image width | 
**PersonId** | **NullableString** | Person ID | 
**SourceType** | **string** | Source type | 

## Methods

### NewSyncAssetFaceV1

`func NewSyncAssetFaceV1(assetId string, boundingBoxX1 int32, boundingBoxX2 int32, boundingBoxY1 int32, boundingBoxY2 int32, id string, imageHeight int32, imageWidth int32, personId NullableString, sourceType string, ) *SyncAssetFaceV1`

NewSyncAssetFaceV1 instantiates a new SyncAssetFaceV1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncAssetFaceV1WithDefaults

`func NewSyncAssetFaceV1WithDefaults() *SyncAssetFaceV1`

NewSyncAssetFaceV1WithDefaults instantiates a new SyncAssetFaceV1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *SyncAssetFaceV1) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *SyncAssetFaceV1) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *SyncAssetFaceV1) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetBoundingBoxX1

`func (o *SyncAssetFaceV1) GetBoundingBoxX1() int32`

GetBoundingBoxX1 returns the BoundingBoxX1 field if non-nil, zero value otherwise.

### GetBoundingBoxX1Ok

`func (o *SyncAssetFaceV1) GetBoundingBoxX1Ok() (*int32, bool)`

GetBoundingBoxX1Ok returns a tuple with the BoundingBoxX1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoundingBoxX1

`func (o *SyncAssetFaceV1) SetBoundingBoxX1(v int32)`

SetBoundingBoxX1 sets BoundingBoxX1 field to given value.


### GetBoundingBoxX2

`func (o *SyncAssetFaceV1) GetBoundingBoxX2() int32`

GetBoundingBoxX2 returns the BoundingBoxX2 field if non-nil, zero value otherwise.

### GetBoundingBoxX2Ok

`func (o *SyncAssetFaceV1) GetBoundingBoxX2Ok() (*int32, bool)`

GetBoundingBoxX2Ok returns a tuple with the BoundingBoxX2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoundingBoxX2

`func (o *SyncAssetFaceV1) SetBoundingBoxX2(v int32)`

SetBoundingBoxX2 sets BoundingBoxX2 field to given value.


### GetBoundingBoxY1

`func (o *SyncAssetFaceV1) GetBoundingBoxY1() int32`

GetBoundingBoxY1 returns the BoundingBoxY1 field if non-nil, zero value otherwise.

### GetBoundingBoxY1Ok

`func (o *SyncAssetFaceV1) GetBoundingBoxY1Ok() (*int32, bool)`

GetBoundingBoxY1Ok returns a tuple with the BoundingBoxY1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoundingBoxY1

`func (o *SyncAssetFaceV1) SetBoundingBoxY1(v int32)`

SetBoundingBoxY1 sets BoundingBoxY1 field to given value.


### GetBoundingBoxY2

`func (o *SyncAssetFaceV1) GetBoundingBoxY2() int32`

GetBoundingBoxY2 returns the BoundingBoxY2 field if non-nil, zero value otherwise.

### GetBoundingBoxY2Ok

`func (o *SyncAssetFaceV1) GetBoundingBoxY2Ok() (*int32, bool)`

GetBoundingBoxY2Ok returns a tuple with the BoundingBoxY2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBoundingBoxY2

`func (o *SyncAssetFaceV1) SetBoundingBoxY2(v int32)`

SetBoundingBoxY2 sets BoundingBoxY2 field to given value.


### GetId

`func (o *SyncAssetFaceV1) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SyncAssetFaceV1) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SyncAssetFaceV1) SetId(v string)`

SetId sets Id field to given value.


### GetImageHeight

`func (o *SyncAssetFaceV1) GetImageHeight() int32`

GetImageHeight returns the ImageHeight field if non-nil, zero value otherwise.

### GetImageHeightOk

`func (o *SyncAssetFaceV1) GetImageHeightOk() (*int32, bool)`

GetImageHeightOk returns a tuple with the ImageHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageHeight

`func (o *SyncAssetFaceV1) SetImageHeight(v int32)`

SetImageHeight sets ImageHeight field to given value.


### GetImageWidth

`func (o *SyncAssetFaceV1) GetImageWidth() int32`

GetImageWidth returns the ImageWidth field if non-nil, zero value otherwise.

### GetImageWidthOk

`func (o *SyncAssetFaceV1) GetImageWidthOk() (*int32, bool)`

GetImageWidthOk returns a tuple with the ImageWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageWidth

`func (o *SyncAssetFaceV1) SetImageWidth(v int32)`

SetImageWidth sets ImageWidth field to given value.


### GetPersonId

`func (o *SyncAssetFaceV1) GetPersonId() string`

GetPersonId returns the PersonId field if non-nil, zero value otherwise.

### GetPersonIdOk

`func (o *SyncAssetFaceV1) GetPersonIdOk() (*string, bool)`

GetPersonIdOk returns a tuple with the PersonId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonId

`func (o *SyncAssetFaceV1) SetPersonId(v string)`

SetPersonId sets PersonId field to given value.


### SetPersonIdNil

`func (o *SyncAssetFaceV1) SetPersonIdNil(b bool)`

 SetPersonIdNil sets the value for PersonId to be an explicit nil

### UnsetPersonId
`func (o *SyncAssetFaceV1) UnsetPersonId()`

UnsetPersonId ensures that no value is present for PersonId, not even an explicit nil
### GetSourceType

`func (o *SyncAssetFaceV1) GetSourceType() string`

GetSourceType returns the SourceType field if non-nil, zero value otherwise.

### GetSourceTypeOk

`func (o *SyncAssetFaceV1) GetSourceTypeOk() (*string, bool)`

GetSourceTypeOk returns a tuple with the SourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceType

`func (o *SyncAssetFaceV1) SetSourceType(v string)`

SetSourceType sets SourceType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


