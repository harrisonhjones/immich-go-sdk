# AssetStackResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetCount** | **int32** | Number of assets in stack | 
**Id** | **string** | Stack ID | 
**PrimaryAssetId** | **string** | Primary asset ID | 

## Methods

### NewAssetStackResponseDto

`func NewAssetStackResponseDto(assetCount int32, id string, primaryAssetId string, ) *AssetStackResponseDto`

NewAssetStackResponseDto instantiates a new AssetStackResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetStackResponseDtoWithDefaults

`func NewAssetStackResponseDtoWithDefaults() *AssetStackResponseDto`

NewAssetStackResponseDtoWithDefaults instantiates a new AssetStackResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetCount

`func (o *AssetStackResponseDto) GetAssetCount() int32`

GetAssetCount returns the AssetCount field if non-nil, zero value otherwise.

### GetAssetCountOk

`func (o *AssetStackResponseDto) GetAssetCountOk() (*int32, bool)`

GetAssetCountOk returns a tuple with the AssetCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetCount

`func (o *AssetStackResponseDto) SetAssetCount(v int32)`

SetAssetCount sets AssetCount field to given value.


### GetId

`func (o *AssetStackResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AssetStackResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AssetStackResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetPrimaryAssetId

`func (o *AssetStackResponseDto) GetPrimaryAssetId() string`

GetPrimaryAssetId returns the PrimaryAssetId field if non-nil, zero value otherwise.

### GetPrimaryAssetIdOk

`func (o *AssetStackResponseDto) GetPrimaryAssetIdOk() (*string, bool)`

GetPrimaryAssetIdOk returns a tuple with the PrimaryAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryAssetId

`func (o *AssetStackResponseDto) SetPrimaryAssetId(v string)`

SetPrimaryAssetId sets PrimaryAssetId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


