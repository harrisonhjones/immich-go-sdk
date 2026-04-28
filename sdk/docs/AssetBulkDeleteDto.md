# AssetBulkDeleteDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Force** | Pointer to **bool** | Force delete even if in use | [optional] 
**Ids** | **[]string** | IDs to process | 

## Methods

### NewAssetBulkDeleteDto

`func NewAssetBulkDeleteDto(ids []string, ) *AssetBulkDeleteDto`

NewAssetBulkDeleteDto instantiates a new AssetBulkDeleteDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAssetBulkDeleteDtoWithDefaults

`func NewAssetBulkDeleteDtoWithDefaults() *AssetBulkDeleteDto`

NewAssetBulkDeleteDtoWithDefaults instantiates a new AssetBulkDeleteDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetForce

`func (o *AssetBulkDeleteDto) GetForce() bool`

GetForce returns the Force field if non-nil, zero value otherwise.

### GetForceOk

`func (o *AssetBulkDeleteDto) GetForceOk() (*bool, bool)`

GetForceOk returns a tuple with the Force field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForce

`func (o *AssetBulkDeleteDto) SetForce(v bool)`

SetForce sets Force field to given value.

### HasForce

`func (o *AssetBulkDeleteDto) HasForce() bool`

HasForce returns a boolean if a field has been set.

### GetIds

`func (o *AssetBulkDeleteDto) GetIds() []string`

GetIds returns the Ids field if non-nil, zero value otherwise.

### GetIdsOk

`func (o *AssetBulkDeleteDto) GetIdsOk() (*[]string, bool)`

GetIdsOk returns a tuple with the Ids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIds

`func (o *AssetBulkDeleteDto) SetIds(v []string)`

SetIds sets Ids field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


