# AssetMetadataBulkResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** | Asset ID | 
**Key** | **string** | Metadata key | 
**UpdatedAt** | **time.Time** | Last update date | 
**Value** | **map[string]interface{}** | Metadata value (object) | 

## Methods

### NewAssetMetadataBulkResponseDto

`func NewAssetMetadataBulkResponseDto(assetId string, key string, updatedAt time.Time, value map[string]interface{}, ) *AssetMetadataBulkResponseDto`

NewAssetMetadataBulkResponseDto instantiates a new AssetMetadataBulkResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetMetadataBulkResponseDtoWithDefaults

`func NewAssetMetadataBulkResponseDtoWithDefaults() *AssetMetadataBulkResponseDto`

NewAssetMetadataBulkResponseDtoWithDefaults instantiates a new AssetMetadataBulkResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *AssetMetadataBulkResponseDto) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *AssetMetadataBulkResponseDto) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *AssetMetadataBulkResponseDto) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetKey

`func (o *AssetMetadataBulkResponseDto) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *AssetMetadataBulkResponseDto) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *AssetMetadataBulkResponseDto) SetKey(v string)`

SetKey sets Key field to given value.


### GetUpdatedAt

`func (o *AssetMetadataBulkResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *AssetMetadataBulkResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *AssetMetadataBulkResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetValue

`func (o *AssetMetadataBulkResponseDto) GetValue() map[string]interface{}`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *AssetMetadataBulkResponseDto) GetValueOk() (*map[string]interface{}, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *AssetMetadataBulkResponseDto) SetValue(v map[string]interface{})`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


