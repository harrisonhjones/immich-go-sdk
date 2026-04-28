# LibraryResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetCount** | **int32** | Number of assets | 
**CreatedAt** | **time.Time** | Creation date | 
**ExclusionPatterns** | **[]string** | Exclusion patterns | 
**Id** | **string** | Library ID | 
**ImportPaths** | **[]string** | Import paths | 
**Name** | **string** | Library name | 
**OwnerId** | **string** | Owner user ID | 
**RefreshedAt** | **NullableTime** | Last refresh date | 
**UpdatedAt** | **time.Time** | Last update date | 

## Methods

### NewLibraryResponseDto

`func NewLibraryResponseDto(assetCount int32, createdAt time.Time, exclusionPatterns []string, id string, importPaths []string, name string, ownerId string, refreshedAt NullableTime, updatedAt time.Time, ) *LibraryResponseDto`

NewLibraryResponseDto instantiates a new LibraryResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLibraryResponseDtoWithDefaults

`func NewLibraryResponseDtoWithDefaults() *LibraryResponseDto`

NewLibraryResponseDtoWithDefaults instantiates a new LibraryResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetCount

`func (o *LibraryResponseDto) GetAssetCount() int32`

GetAssetCount returns the AssetCount field if non-nil, zero value otherwise.

### GetAssetCountOk

`func (o *LibraryResponseDto) GetAssetCountOk() (*int32, bool)`

GetAssetCountOk returns a tuple with the AssetCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetCount

`func (o *LibraryResponseDto) SetAssetCount(v int32)`

SetAssetCount sets AssetCount field to given value.


### GetCreatedAt

`func (o *LibraryResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *LibraryResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *LibraryResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetExclusionPatterns

`func (o *LibraryResponseDto) GetExclusionPatterns() []string`

GetExclusionPatterns returns the ExclusionPatterns field if non-nil, zero value otherwise.

### GetExclusionPatternsOk

`func (o *LibraryResponseDto) GetExclusionPatternsOk() (*[]string, bool)`

GetExclusionPatternsOk returns a tuple with the ExclusionPatterns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExclusionPatterns

`func (o *LibraryResponseDto) SetExclusionPatterns(v []string)`

SetExclusionPatterns sets ExclusionPatterns field to given value.


### GetId

`func (o *LibraryResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *LibraryResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *LibraryResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetImportPaths

`func (o *LibraryResponseDto) GetImportPaths() []string`

GetImportPaths returns the ImportPaths field if non-nil, zero value otherwise.

### GetImportPathsOk

`func (o *LibraryResponseDto) GetImportPathsOk() (*[]string, bool)`

GetImportPathsOk returns a tuple with the ImportPaths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportPaths

`func (o *LibraryResponseDto) SetImportPaths(v []string)`

SetImportPaths sets ImportPaths field to given value.


### GetName

`func (o *LibraryResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *LibraryResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *LibraryResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetOwnerId

`func (o *LibraryResponseDto) GetOwnerId() string`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *LibraryResponseDto) GetOwnerIdOk() (*string, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *LibraryResponseDto) SetOwnerId(v string)`

SetOwnerId sets OwnerId field to given value.


### GetRefreshedAt

`func (o *LibraryResponseDto) GetRefreshedAt() time.Time`

GetRefreshedAt returns the RefreshedAt field if non-nil, zero value otherwise.

### GetRefreshedAtOk

`func (o *LibraryResponseDto) GetRefreshedAtOk() (*time.Time, bool)`

GetRefreshedAtOk returns a tuple with the RefreshedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefreshedAt

`func (o *LibraryResponseDto) SetRefreshedAt(v time.Time)`

SetRefreshedAt sets RefreshedAt field to given value.


### SetRefreshedAtNil

`func (o *LibraryResponseDto) SetRefreshedAtNil(b bool)`

 SetRefreshedAtNil sets the value for RefreshedAt to be an explicit nil

### UnsetRefreshedAt
`func (o *LibraryResponseDto) UnsetRefreshedAt()`

UnsetRefreshedAt ensures that no value is present for RefreshedAt, not even an explicit nil
### GetUpdatedAt

`func (o *LibraryResponseDto) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *LibraryResponseDto) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *LibraryResponseDto) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


