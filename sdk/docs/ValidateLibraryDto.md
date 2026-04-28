# ValidateLibraryDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ExclusionPatterns** | Pointer to **[]string** | Exclusion patterns (max 128) | [optional] 
**ImportPaths** | Pointer to **[]string** | Import paths to validate (max 128) | [optional] 

## Methods

### NewValidateLibraryDto

`func NewValidateLibraryDto() *ValidateLibraryDto`

NewValidateLibraryDto instantiates a new ValidateLibraryDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidateLibraryDtoWithDefaults

`func NewValidateLibraryDtoWithDefaults() *ValidateLibraryDto`

NewValidateLibraryDtoWithDefaults instantiates a new ValidateLibraryDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetExclusionPatterns

`func (o *ValidateLibraryDto) GetExclusionPatterns() []string`

GetExclusionPatterns returns the ExclusionPatterns field if non-nil, zero value otherwise.

### GetExclusionPatternsOk

`func (o *ValidateLibraryDto) GetExclusionPatternsOk() (*[]string, bool)`

GetExclusionPatternsOk returns a tuple with the ExclusionPatterns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExclusionPatterns

`func (o *ValidateLibraryDto) SetExclusionPatterns(v []string)`

SetExclusionPatterns sets ExclusionPatterns field to given value.

### HasExclusionPatterns

`func (o *ValidateLibraryDto) HasExclusionPatterns() bool`

HasExclusionPatterns returns a boolean if a field has been set.

### GetImportPaths

`func (o *ValidateLibraryDto) GetImportPaths() []string`

GetImportPaths returns the ImportPaths field if non-nil, zero value otherwise.

### GetImportPathsOk

`func (o *ValidateLibraryDto) GetImportPathsOk() (*[]string, bool)`

GetImportPathsOk returns a tuple with the ImportPaths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportPaths

`func (o *ValidateLibraryDto) SetImportPaths(v []string)`

SetImportPaths sets ImportPaths field to given value.

### HasImportPaths

`func (o *ValidateLibraryDto) HasImportPaths() bool`

HasImportPaths returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


