# AssetIdsResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** | Asset ID | 
**Error** | Pointer to [**AssetIdErrorReason**](AssetIdErrorReason.md) |  | [optional] 
**Success** | **bool** | Whether operation succeeded | 

## Methods

### NewAssetIdsResponseDto

`func NewAssetIdsResponseDto(assetId string, success bool, ) *AssetIdsResponseDto`

NewAssetIdsResponseDto instantiates a new AssetIdsResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetIdsResponseDtoWithDefaults

`func NewAssetIdsResponseDtoWithDefaults() *AssetIdsResponseDto`

NewAssetIdsResponseDtoWithDefaults instantiates a new AssetIdsResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *AssetIdsResponseDto) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *AssetIdsResponseDto) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *AssetIdsResponseDto) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetError

`func (o *AssetIdsResponseDto) GetError() AssetIdErrorReason`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AssetIdsResponseDto) GetErrorOk() (*AssetIdErrorReason, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AssetIdsResponseDto) SetError(v AssetIdErrorReason)`

SetError sets Error field to given value.

### HasError

`func (o *AssetIdsResponseDto) HasError() bool`

HasError returns a boolean if a field has been set.

### GetSuccess

`func (o *AssetIdsResponseDto) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AssetIdsResponseDto) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AssetIdsResponseDto) SetSuccess(v bool)`

SetSuccess sets Success field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


