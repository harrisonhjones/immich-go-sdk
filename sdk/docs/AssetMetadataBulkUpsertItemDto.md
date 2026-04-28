# AssetMetadataBulkUpsertItemDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** | Asset ID | 
**Key** | **string** | Metadata key | 
**Value** | **map[string]interface{}** | Metadata value (object) | 

## Methods

### NewAssetMetadataBulkUpsertItemDto

`func NewAssetMetadataBulkUpsertItemDto(assetId string, key string, value map[string]interface{}, ) *AssetMetadataBulkUpsertItemDto`

NewAssetMetadataBulkUpsertItemDto instantiates a new AssetMetadataBulkUpsertItemDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetMetadataBulkUpsertItemDtoWithDefaults

`func NewAssetMetadataBulkUpsertItemDtoWithDefaults() *AssetMetadataBulkUpsertItemDto`

NewAssetMetadataBulkUpsertItemDtoWithDefaults instantiates a new AssetMetadataBulkUpsertItemDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *AssetMetadataBulkUpsertItemDto) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *AssetMetadataBulkUpsertItemDto) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *AssetMetadataBulkUpsertItemDto) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetKey

`func (o *AssetMetadataBulkUpsertItemDto) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *AssetMetadataBulkUpsertItemDto) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *AssetMetadataBulkUpsertItemDto) SetKey(v string)`

SetKey sets Key field to given value.


### GetValue

`func (o *AssetMetadataBulkUpsertItemDto) GetValue() map[string]interface{}`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *AssetMetadataBulkUpsertItemDto) GetValueOk() (*map[string]interface{}, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *AssetMetadataBulkUpsertItemDto) SetValue(v map[string]interface{})`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


