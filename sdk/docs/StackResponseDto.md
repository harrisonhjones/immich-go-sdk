# StackResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Assets** | [**[]AssetResponseDto**](AssetResponseDto.md) |  | 
**Id** | **string** | Stack ID | 
**PrimaryAssetId** | **string** | Primary asset ID | 

## Methods

### NewStackResponseDto

`func NewStackResponseDto(assets []AssetResponseDto, id string, primaryAssetId string, ) *StackResponseDto`

NewStackResponseDto instantiates a new StackResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStackResponseDtoWithDefaults

`func NewStackResponseDtoWithDefaults() *StackResponseDto`

NewStackResponseDtoWithDefaults instantiates a new StackResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssets

`func (o *StackResponseDto) GetAssets() []AssetResponseDto`

GetAssets returns the Assets field if non-nil, zero value otherwise.

### GetAssetsOk

`func (o *StackResponseDto) GetAssetsOk() (*[]AssetResponseDto, bool)`

GetAssetsOk returns a tuple with the Assets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssets

`func (o *StackResponseDto) SetAssets(v []AssetResponseDto)`

SetAssets sets Assets field to given value.


### GetId

`func (o *StackResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *StackResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *StackResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetPrimaryAssetId

`func (o *StackResponseDto) GetPrimaryAssetId() string`

GetPrimaryAssetId returns the PrimaryAssetId field if non-nil, zero value otherwise.

### GetPrimaryAssetIdOk

`func (o *StackResponseDto) GetPrimaryAssetIdOk() (*string, bool)`

GetPrimaryAssetIdOk returns a tuple with the PrimaryAssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrimaryAssetId

`func (o *StackResponseDto) SetPrimaryAssetId(v string)`

SetPrimaryAssetId sets PrimaryAssetId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


