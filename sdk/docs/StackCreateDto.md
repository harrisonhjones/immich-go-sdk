# StackCreateDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetIds** | **[]string** | Asset IDs (first becomes primary, min 2) | 

## Methods

### NewStackCreateDto

`func NewStackCreateDto(assetIds []string, ) *StackCreateDto`

NewStackCreateDto instantiates a new StackCreateDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStackCreateDtoWithDefaults

`func NewStackCreateDtoWithDefaults() *StackCreateDto`

NewStackCreateDtoWithDefaults instantiates a new StackCreateDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetIds

`func (o *StackCreateDto) GetAssetIds() []string`

GetAssetIds returns the AssetIds field if non-nil, zero value otherwise.

### GetAssetIdsOk

`func (o *StackCreateDto) GetAssetIdsOk() (*[]string, bool)`

GetAssetIdsOk returns a tuple with the AssetIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetIds

`func (o *StackCreateDto) SetAssetIds(v []string)`

SetAssetIds sets AssetIds field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


