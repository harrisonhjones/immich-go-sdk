# AssetJobsDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetIds** | **[]string** | Asset IDs | 
**Name** | [**AssetJobName**](AssetJobName.md) |  | 

## Methods

### NewAssetJobsDto

`func NewAssetJobsDto(assetIds []string, name AssetJobName, ) *AssetJobsDto`

NewAssetJobsDto instantiates a new AssetJobsDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetJobsDtoWithDefaults

`func NewAssetJobsDtoWithDefaults() *AssetJobsDto`

NewAssetJobsDtoWithDefaults instantiates a new AssetJobsDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetIds

`func (o *AssetJobsDto) GetAssetIds() []string`

GetAssetIds returns the AssetIds field if non-nil, zero value otherwise.

### GetAssetIdsOk

`func (o *AssetJobsDto) GetAssetIdsOk() (*[]string, bool)`

GetAssetIdsOk returns a tuple with the AssetIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetIds

`func (o *AssetJobsDto) SetAssetIds(v []string)`

SetAssetIds sets AssetIds field to given value.


### GetName

`func (o *AssetJobsDto) GetName() AssetJobName`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AssetJobsDto) GetNameOk() (*AssetJobName, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AssetJobsDto) SetName(v AssetJobName)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


