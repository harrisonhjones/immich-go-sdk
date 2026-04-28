# SyncAlbumV2

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **time.Time** | Created at | 
**Description** | **string** | Album description | 
**Id** | **string** | Album ID | 
**IsActivityEnabled** | **bool** | Is activity enabled | 
**Name** | **string** | Album name | 
**Order** | [**AssetOrder**](AssetOrder.md) |  | 
**ThumbnailAssetId** | **NullableString** | Thumbnail asset ID | 
**UpdatedAt** | **time.Time** | Updated at | 

## Methods

### NewSyncAlbumV2

`func NewSyncAlbumV2(createdAt time.Time, description string, id string, isActivityEnabled bool, name string, order AssetOrder, thumbnailAssetId NullableString, updatedAt time.Time, ) *SyncAlbumV2`

NewSyncAlbumV2 instantiates a new SyncAlbumV2 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSyncAlbumV2WithDefaults

`func NewSyncAlbumV2WithDefaults() *SyncAlbumV2`

NewSyncAlbumV2WithDefaults instantiates a new SyncAlbumV2 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *SyncAlbumV2) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SyncAlbumV2) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SyncAlbumV2) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDescription

`func (o *SyncAlbumV2) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *SyncAlbumV2) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *SyncAlbumV2) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetId

`func (o *SyncAlbumV2) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SyncAlbumV2) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SyncAlbumV2) SetId(v string)`

SetId sets Id field to given value.


### GetIsActivityEnabled

`func (o *SyncAlbumV2) GetIsActivityEnabled() bool`

GetIsActivityEnabled returns the IsActivityEnabled field if non-nil, zero value otherwise.

### GetIsActivityEnabledOk

`func (o *SyncAlbumV2) GetIsActivityEnabledOk() (*bool, bool)`

GetIsActivityEnabledOk returns a tuple with the IsActivityEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActivityEnabled

`func (o *SyncAlbumV2) SetIsActivityEnabled(v bool)`

SetIsActivityEnabled sets IsActivityEnabled field to given value.


### GetName

`func (o *SyncAlbumV2) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SyncAlbumV2) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SyncAlbumV2) SetName(v string)`

SetName sets Name field to given value.


### GetOrder

`func (o *SyncAlbumV2) GetOrder() AssetOrder`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *SyncAlbumV2) GetOrderOk() (*AssetOrder, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *SyncAlbumV2) SetOrder(v AssetOrder)`

SetOrder sets Order field to given value.


### GetThumbnailAssetId

`func (o *SyncAlbumV2) GetThumbnailAssetId() string`

GetThumbnailAssetId returns the ThumbnailAssetId field if non-nil, zero value otherwise.

### GetThumbnailAssetIdOk

`func (o *SyncAlbumV2) GetThumbnailAssetIdOk() (*string, bool)`

GetThumbnailAssetIdOk returns a tuple with the ThumbnailAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbnailAssetId

`func (o *SyncAlbumV2) SetThumbnailAssetId(v string)`

SetThumbnailAssetId sets ThumbnailAssetId field to given value.


### SetThumbnailAssetIdNil

`func (o *SyncAlbumV2) SetThumbnailAssetIdNil(b bool)`

 SetThumbnailAssetIdNil sets the value for ThumbnailAssetId to be an explicit nil

### UnsetThumbnailAssetId
`func (o *SyncAlbumV2) UnsetThumbnailAssetId()`

UnsetThumbnailAssetId ensures that no value is present for ThumbnailAssetId, not even an explicit nil
### GetUpdatedAt

`func (o *SyncAlbumV2) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *SyncAlbumV2) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *SyncAlbumV2) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


