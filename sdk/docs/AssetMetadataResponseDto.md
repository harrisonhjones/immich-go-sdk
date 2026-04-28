# AssetMetadataResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | **string** | Metadata key | 
**UpdatedAt** | **time.Time** | Last update date | 
**Value** | **map[string]interface{}** | Metadata value (object) | 

## Methods

### NewAssetMetadataResponseDto

`func NewAssetMetadataResponseDto(key string, updatedAt time.Time, value map[string]interface{}, ) *AssetMetadataResponseDto`

NewAssetMetadataResponseDto instantiates a new AssetMetadataResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetMetadataResponseDtoWithDefaults

`func NewAssetMetadataResponseDtoWithDefaults() *AssetMetadataResponseDto`

NewAssetMetadataResponseDtoWithDefaults instantiates a new AssetMetadataResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *AssetMetadataResponseDto) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *AssetMetadataResponseDto) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *AssetMetadataResponseDto) SetKey(v string)`

SetKey sets Key field to given value.


### GetUpdatedAt

`func (o *AssetMetadataResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *AssetMetadataResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *AssetMetadataResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetValue

`func (o *AssetMetadataResponseDto) GetValue() map[string]interface{}`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *AssetMetadataResponseDto) GetValueOk() (*map[string]interface{}, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *AssetMetadataResponseDto) SetValue(v map[string]interface{})`

SetValue sets Value field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


