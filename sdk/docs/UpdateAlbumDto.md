# UpdateAlbumDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlbumName** | Pointer to **string** | Album name | [optional] 
**AlbumThumbnailAssetId** | Pointer to **string** | Album thumbnail asset ID | [optional] 
**Description** | Pointer to **string** | Album description | [optional] 
**IsActivityEnabled** | Pointer to **bool** | Enable activity feed | [optional] 
**Order** | Pointer to [**AssetOrder**](AssetOrder.md) |  | [optional] 

## Methods

### NewUpdateAlbumDto

`func NewUpdateAlbumDto() *UpdateAlbumDto`

NewUpdateAlbumDto instantiates a new UpdateAlbumDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateAlbumDtoWithDefaults

`func NewUpdateAlbumDtoWithDefaults() *UpdateAlbumDto`

NewUpdateAlbumDtoWithDefaults instantiates a new UpdateAlbumDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbumName

`func (o *UpdateAlbumDto) GetAlbumName() string`

GetAlbumName returns the AlbumName field if non-nil, zero value otherwise.

### GetAlbumNameOk

`func (o *UpdateAlbumDto) GetAlbumNameOk() (*string, bool)`

GetAlbumNameOk returns a tuple with the AlbumName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumName

`func (o *UpdateAlbumDto) SetAlbumName(v string)`

SetAlbumName sets AlbumName field to given value.

### HasAlbumName

`func (o *UpdateAlbumDto) HasAlbumName() bool`

HasAlbumName returns a boolean if a field has been set.

### GetAlbumThumbnailAssetId

`func (o *UpdateAlbumDto) GetAlbumThumbnailAssetId() string`

GetAlbumThumbnailAssetId returns the AlbumThumbnailAssetId field if non-nil, zero value otherwise.

### GetAlbumThumbnailAssetIdOk

`func (o *UpdateAlbumDto) GetAlbumThumbnailAssetIdOk() (*string, bool)`

GetAlbumThumbnailAssetIdOk returns a tuple with the AlbumThumbnailAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumThumbnailAssetId

`func (o *UpdateAlbumDto) SetAlbumThumbnailAssetId(v string)`

SetAlbumThumbnailAssetId sets AlbumThumbnailAssetId field to given value.

### HasAlbumThumbnailAssetId

`func (o *UpdateAlbumDto) HasAlbumThumbnailAssetId() bool`

HasAlbumThumbnailAssetId returns a boolean if a field has been set.

### GetDescription

`func (o *UpdateAlbumDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *UpdateAlbumDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *UpdateAlbumDto) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *UpdateAlbumDto) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIsActivityEnabled

`func (o *UpdateAlbumDto) GetIsActivityEnabled() bool`

GetIsActivityEnabled returns the IsActivityEnabled field if non-nil, zero value otherwise.

### GetIsActivityEnabledOk

`func (o *UpdateAlbumDto) GetIsActivityEnabledOk() (*bool, bool)`

GetIsActivityEnabledOk returns a tuple with the IsActivityEnabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActivityEnabled

`func (o *UpdateAlbumDto) SetIsActivityEnabled(v bool)`

SetIsActivityEnabled sets IsActivityEnabled field to given value.

### HasIsActivityEnabled

`func (o *UpdateAlbumDto) HasIsActivityEnabled() bool`

HasIsActivityEnabled returns a boolean if a field has been set.

### GetOrder

`func (o *UpdateAlbumDto) GetOrder() AssetOrder`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *UpdateAlbumDto) GetOrderOk() (*AssetOrder, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *UpdateAlbumDto) SetOrder(v AssetOrder)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *UpdateAlbumDto) HasOrder() bool`

HasOrder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


