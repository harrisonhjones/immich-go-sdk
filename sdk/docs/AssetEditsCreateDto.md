# AssetEditsCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Edits** | [**[]AssetEditActionItemDto**](AssetEditActionItemDto.md) | List of edit actions to apply (crop, rotate, or mirror) | 

## Methods

### NewAssetEditsCreateDto

`func NewAssetEditsCreateDto(edits []AssetEditActionItemDto, ) *AssetEditsCreateDto`

NewAssetEditsCreateDto instantiates a new AssetEditsCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetEditsCreateDtoWithDefaults

`func NewAssetEditsCreateDtoWithDefaults() *AssetEditsCreateDto`

NewAssetEditsCreateDtoWithDefaults instantiates a new AssetEditsCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEdits

`func (o *AssetEditsCreateDto) GetEdits() []AssetEditActionItemDto`

GetEdits returns the Edits field if non-nil, zero value otherwise.

### GetEditsOk

`func (o *AssetEditsCreateDto) GetEditsOk() (*[]AssetEditActionItemDto, bool)`

GetEditsOk returns a tuple with the Edits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEdits

`func (o *AssetEditsCreateDto) SetEdits(v []AssetEditActionItemDto)`

SetEdits sets Edits field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


