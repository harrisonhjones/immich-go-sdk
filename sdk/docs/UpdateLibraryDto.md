# UpdateLibraryDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExclusionPatterns** | Pointer to **[]string** | Exclusion patterns (max 128) | [optional] 
**ImportPaths** | Pointer to **[]string** | Import paths (max 128) | [optional] 
**Name** | Pointer to **string** | Library name | [optional] 

## Methods

### NewUpdateLibraryDto

`func NewUpdateLibraryDto() *UpdateLibraryDto`

NewUpdateLibraryDto instantiates a new UpdateLibraryDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateLibraryDtoWithDefaults

`func NewUpdateLibraryDtoWithDefaults() *UpdateLibraryDto`

NewUpdateLibraryDtoWithDefaults instantiates a new UpdateLibraryDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExclusionPatterns

`func (o *UpdateLibraryDto) GetExclusionPatterns() []string`

GetExclusionPatterns returns the ExclusionPatterns field if non-nil, zero value otherwise.

### GetExclusionPatternsOk

`func (o *UpdateLibraryDto) GetExclusionPatternsOk() (*[]string, bool)`

GetExclusionPatternsOk returns a tuple with the ExclusionPatterns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExclusionPatterns

`func (o *UpdateLibraryDto) SetExclusionPatterns(v []string)`

SetExclusionPatterns sets ExclusionPatterns field to given value.

### HasExclusionPatterns

`func (o *UpdateLibraryDto) HasExclusionPatterns() bool`

HasExclusionPatterns returns a boolean if a field has been set.

### GetImportPaths

`func (o *UpdateLibraryDto) GetImportPaths() []string`

GetImportPaths returns the ImportPaths field if non-nil, zero value otherwise.

### GetImportPathsOk

`func (o *UpdateLibraryDto) GetImportPathsOk() (*[]string, bool)`

GetImportPathsOk returns a tuple with the ImportPaths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportPaths

`func (o *UpdateLibraryDto) SetImportPaths(v []string)`

SetImportPaths sets ImportPaths field to given value.

### HasImportPaths

`func (o *UpdateLibraryDto) HasImportPaths() bool`

HasImportPaths returns a boolean if a field has been set.

### GetName

`func (o *UpdateLibraryDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateLibraryDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateLibraryDto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateLibraryDto) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


