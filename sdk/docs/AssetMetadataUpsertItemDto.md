# AssetMetadataUpsertItemDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** | Metadata key | 
**Value** | **map[string]interface{}** | Metadata value (object) | 

## Methods

### NewAssetMetadataUpsertItemDto

`func NewAssetMetadataUpsertItemDto(key string, value map[string]interface{}, ) *AssetMetadataUpsertItemDto`

NewAssetMetadataUpsertItemDto instantiates a new AssetMetadataUpsertItemDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetMetadataUpsertItemDtoWithDefaults

`func NewAssetMetadataUpsertItemDtoWithDefaults() *AssetMetadataUpsertItemDto`

NewAssetMetadataUpsertItemDtoWithDefaults instantiates a new AssetMetadataUpsertItemDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *AssetMetadataUpsertItemDto) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *AssetMetadataUpsertItemDto) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *AssetMetadataUpsertItemDto) SetKey(v string)`

SetKey sets Key field to given value.


### GetValue

`func (o *AssetMetadataUpsertItemDto) GetValue() map[string]interface{}`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *AssetMetadataUpsertItemDto) GetValueOk() (*map[string]interface{}, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *AssetMetadataUpsertItemDto) SetValue(v map[string]interface{})`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


