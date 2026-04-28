# ValidateLibraryResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImportPaths** | Pointer to [**[]ValidateLibraryImportPathResponseDto**](ValidateLibraryImportPathResponseDto.md) | Validation results for import paths | [optional] 

## Methods

### NewValidateLibraryResponseDto

`func NewValidateLibraryResponseDto() *ValidateLibraryResponseDto`

NewValidateLibraryResponseDto instantiates a new ValidateLibraryResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidateLibraryResponseDtoWithDefaults

`func NewValidateLibraryResponseDtoWithDefaults() *ValidateLibraryResponseDto`

NewValidateLibraryResponseDtoWithDefaults instantiates a new ValidateLibraryResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImportPaths

`func (o *ValidateLibraryResponseDto) GetImportPaths() []ValidateLibraryImportPathResponseDto`

GetImportPaths returns the ImportPaths field if non-nil, zero value otherwise.

### GetImportPathsOk

`func (o *ValidateLibraryResponseDto) GetImportPathsOk() (*[]ValidateLibraryImportPathResponseDto, bool)`

GetImportPathsOk returns a tuple with the ImportPaths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportPaths

`func (o *ValidateLibraryResponseDto) SetImportPaths(v []ValidateLibraryImportPathResponseDto)`

SetImportPaths sets ImportPaths field to given value.

### HasImportPaths

`func (o *ValidateLibraryResponseDto) HasImportPaths() bool`

HasImportPaths returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


