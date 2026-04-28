# CreateLibraryDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExclusionPatterns** | Pointer to **[]string** | Exclusion patterns (max 128) | [optional] 
**ImportPaths** | Pointer to **[]string** | Import paths (max 128) | [optional] 
**Name** | Pointer to **string** | Library name | [optional] 
**OwnerId** | **string** | Owner user ID | 

## Methods

### NewCreateLibraryDto

`func NewCreateLibraryDto(ownerId string, ) *CreateLibraryDto`

NewCreateLibraryDto instantiates a new CreateLibraryDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateLibraryDtoWithDefaults

`func NewCreateLibraryDtoWithDefaults() *CreateLibraryDto`

NewCreateLibraryDtoWithDefaults instantiates a new CreateLibraryDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExclusionPatterns

`func (o *CreateLibraryDto) GetExclusionPatterns() []string`

GetExclusionPatterns returns the ExclusionPatterns field if non-nil, zero value otherwise.

### GetExclusionPatternsOk

`func (o *CreateLibraryDto) GetExclusionPatternsOk() (*[]string, bool)`

GetExclusionPatternsOk returns a tuple with the ExclusionPatterns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExclusionPatterns

`func (o *CreateLibraryDto) SetExclusionPatterns(v []string)`

SetExclusionPatterns sets ExclusionPatterns field to given value.

### HasExclusionPatterns

`func (o *CreateLibraryDto) HasExclusionPatterns() bool`

HasExclusionPatterns returns a boolean if a field has been set.

### GetImportPaths

`func (o *CreateLibraryDto) GetImportPaths() []string`

GetImportPaths returns the ImportPaths field if non-nil, zero value otherwise.

### GetImportPathsOk

`func (o *CreateLibraryDto) GetImportPathsOk() (*[]string, bool)`

GetImportPathsOk returns a tuple with the ImportPaths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportPaths

`func (o *CreateLibraryDto) SetImportPaths(v []string)`

SetImportPaths sets ImportPaths field to given value.

### HasImportPaths

`func (o *CreateLibraryDto) HasImportPaths() bool`

HasImportPaths returns a boolean if a field has been set.

### GetName

`func (o *CreateLibraryDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateLibraryDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateLibraryDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CreateLibraryDto) HasName() bool`

HasName returns a boolean if a field has been set.

### GetOwnerId

`func (o *CreateLibraryDto) GetOwnerId() string`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *CreateLibraryDto) GetOwnerIdOk() (*string, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *CreateLibraryDto) SetOwnerId(v string)`

SetOwnerId sets OwnerId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


