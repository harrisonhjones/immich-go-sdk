# AssetEditsResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetId** | **string** | Asset ID these edits belong to | 
**Edits** | [**[]AssetEditActionItemResponseDto**](AssetEditActionItemResponseDto.md) | List of edit actions applied to the asset | 

## Methods

### NewAssetEditsResponseDto

`func NewAssetEditsResponseDto(assetId string, edits []AssetEditActionItemResponseDto, ) *AssetEditsResponseDto`

NewAssetEditsResponseDto instantiates a new AssetEditsResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetEditsResponseDtoWithDefaults

`func NewAssetEditsResponseDtoWithDefaults() *AssetEditsResponseDto`

NewAssetEditsResponseDtoWithDefaults instantiates a new AssetEditsResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetId

`func (o *AssetEditsResponseDto) GetAssetId() string`

GetAssetId returns the AssetId field if non-nil, zero value otherwise.

### GetAssetIdOk

`func (o *AssetEditsResponseDto) GetAssetIdOk() (*string, bool)`

GetAssetIdOk returns a tuple with the AssetId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetId

`func (o *AssetEditsResponseDto) SetAssetId(v string)`

SetAssetId sets AssetId field to given value.


### GetEdits

`func (o *AssetEditsResponseDto) GetEdits() []AssetEditActionItemResponseDto`

GetEdits returns the Edits field if non-nil, zero value otherwise.

### GetEditsOk

`func (o *AssetEditsResponseDto) GetEditsOk() (*[]AssetEditActionItemResponseDto, bool)`

GetEditsOk returns a tuple with the Edits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdits

`func (o *AssetEditsResponseDto) SetEdits(v []AssetEditActionItemResponseDto)`

SetEdits sets Edits field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


