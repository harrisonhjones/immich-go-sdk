# DuplicateResolveGroupDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DuplicateId** | **string** |  | 
**KeepAssetIds** | **[]string** | Asset IDs to keep | 
**TrashAssetIds** | **[]string** | Asset IDs to trash or delete | 

## Methods

### NewDuplicateResolveGroupDto

`func NewDuplicateResolveGroupDto(duplicateId string, keepAssetIds []string, trashAssetIds []string, ) *DuplicateResolveGroupDto`

NewDuplicateResolveGroupDto instantiates a new DuplicateResolveGroupDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDuplicateResolveGroupDtoWithDefaults

`func NewDuplicateResolveGroupDtoWithDefaults() *DuplicateResolveGroupDto`

NewDuplicateResolveGroupDtoWithDefaults instantiates a new DuplicateResolveGroupDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDuplicateId

`func (o *DuplicateResolveGroupDto) GetDuplicateId() string`

GetDuplicateId returns the DuplicateId field if non-nil, zero value otherwise.

### GetDuplicateIdOk

`func (o *DuplicateResolveGroupDto) GetDuplicateIdOk() (*string, bool)`

GetDuplicateIdOk returns a tuple with the DuplicateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuplicateId

`func (o *DuplicateResolveGroupDto) SetDuplicateId(v string)`

SetDuplicateId sets DuplicateId field to given value.


### GetKeepAssetIds

`func (o *DuplicateResolveGroupDto) GetKeepAssetIds() []string`

GetKeepAssetIds returns the KeepAssetIds field if non-nil, zero value otherwise.

### GetKeepAssetIdsOk

`func (o *DuplicateResolveGroupDto) GetKeepAssetIdsOk() (*[]string, bool)`

GetKeepAssetIdsOk returns a tuple with the KeepAssetIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepAssetIds

`func (o *DuplicateResolveGroupDto) SetKeepAssetIds(v []string)`

SetKeepAssetIds sets KeepAssetIds field to given value.


### GetTrashAssetIds

`func (o *DuplicateResolveGroupDto) GetTrashAssetIds() []string`

GetTrashAssetIds returns the TrashAssetIds field if non-nil, zero value otherwise.

### GetTrashAssetIdsOk

`func (o *DuplicateResolveGroupDto) GetTrashAssetIdsOk() (*[]string, bool)`

GetTrashAssetIdsOk returns a tuple with the TrashAssetIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrashAssetIds

`func (o *DuplicateResolveGroupDto) SetTrashAssetIds(v []string)`

SetTrashAssetIds sets TrashAssetIds field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


