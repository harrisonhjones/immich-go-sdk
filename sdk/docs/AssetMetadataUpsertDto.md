# AssetMetadataUpsertDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]AssetMetadataUpsertItemDto**](AssetMetadataUpsertItemDto.md) | Metadata items to upsert | 

## Methods

### NewAssetMetadataUpsertDto

`func NewAssetMetadataUpsertDto(items []AssetMetadataUpsertItemDto, ) *AssetMetadataUpsertDto`

NewAssetMetadataUpsertDto instantiates a new AssetMetadataUpsertDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetMetadataUpsertDtoWithDefaults

`func NewAssetMetadataUpsertDtoWithDefaults() *AssetMetadataUpsertDto`

NewAssetMetadataUpsertDtoWithDefaults instantiates a new AssetMetadataUpsertDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *AssetMetadataUpsertDto) GetItems() []AssetMetadataUpsertItemDto`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *AssetMetadataUpsertDto) GetItemsOk() (*[]AssetMetadataUpsertItemDto, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *AssetMetadataUpsertDto) SetItems(v []AssetMetadataUpsertItemDto)`

SetItems sets Items field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


