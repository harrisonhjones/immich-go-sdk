# DuplicateResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Assets** | [**[]AssetResponseDto**](AssetResponseDto.md) | Duplicate assets | 
**DuplicateId** | **string** | Duplicate group ID | 
**SuggestedKeepAssetIds** | **[]string** | Suggested asset IDs to keep based on file size and EXIF data | 

## Methods

### NewDuplicateResponseDto

`func NewDuplicateResponseDto(assets []AssetResponseDto, duplicateId string, suggestedKeepAssetIds []string, ) *DuplicateResponseDto`

NewDuplicateResponseDto instantiates a new DuplicateResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDuplicateResponseDtoWithDefaults

`func NewDuplicateResponseDtoWithDefaults() *DuplicateResponseDto`

NewDuplicateResponseDtoWithDefaults instantiates a new DuplicateResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssets

`func (o *DuplicateResponseDto) GetAssets() []AssetResponseDto`

GetAssets returns the Assets field if non-nil, zero value otherwise.

### GetAssetsOk

`func (o *DuplicateResponseDto) GetAssetsOk() (*[]AssetResponseDto, bool)`

GetAssetsOk returns a tuple with the Assets field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssets

`func (o *DuplicateResponseDto) SetAssets(v []AssetResponseDto)`

SetAssets sets Assets field to given value.


### GetDuplicateId

`func (o *DuplicateResponseDto) GetDuplicateId() string`

GetDuplicateId returns the DuplicateId field if non-nil, zero value otherwise.

### GetDuplicateIdOk

`func (o *DuplicateResponseDto) GetDuplicateIdOk() (*string, bool)`

GetDuplicateIdOk returns a tuple with the DuplicateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuplicateId

`func (o *DuplicateResponseDto) SetDuplicateId(v string)`

SetDuplicateId sets DuplicateId field to given value.


### GetSuggestedKeepAssetIds

`func (o *DuplicateResponseDto) GetSuggestedKeepAssetIds() []string`

GetSuggestedKeepAssetIds returns the SuggestedKeepAssetIds field if non-nil, zero value otherwise.

### GetSuggestedKeepAssetIdsOk

`func (o *DuplicateResponseDto) GetSuggestedKeepAssetIdsOk() (*[]string, bool)`

GetSuggestedKeepAssetIdsOk returns a tuple with the SuggestedKeepAssetIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestedKeepAssetIds

`func (o *DuplicateResponseDto) SetSuggestedKeepAssetIds(v []string)`

SetSuggestedKeepAssetIds sets SuggestedKeepAssetIds field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


