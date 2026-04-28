# ValidateLibraryImportPathResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImportPath** | **string** | Import path | 
**IsValid** | **bool** | Is valid | 
**Message** | Pointer to **string** | Validation message | [optional] 

## Methods

### NewValidateLibraryImportPathResponseDto

`func NewValidateLibraryImportPathResponseDto(importPath string, isValid bool, ) *ValidateLibraryImportPathResponseDto`

NewValidateLibraryImportPathResponseDto instantiates a new ValidateLibraryImportPathResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidateLibraryImportPathResponseDtoWithDefaults

`func NewValidateLibraryImportPathResponseDtoWithDefaults() *ValidateLibraryImportPathResponseDto`

NewValidateLibraryImportPathResponseDtoWithDefaults instantiates a new ValidateLibraryImportPathResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImportPath

`func (o *ValidateLibraryImportPathResponseDto) GetImportPath() string`

GetImportPath returns the ImportPath field if non-nil, zero value otherwise.

### GetImportPathOk

`func (o *ValidateLibraryImportPathResponseDto) GetImportPathOk() (*string, bool)`

GetImportPathOk returns a tuple with the ImportPath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportPath

`func (o *ValidateLibraryImportPathResponseDto) SetImportPath(v string)`

SetImportPath sets ImportPath field to given value.


### GetIsValid

`func (o *ValidateLibraryImportPathResponseDto) GetIsValid() bool`

GetIsValid returns the IsValid field if non-nil, zero value otherwise.

### GetIsValidOk

`func (o *ValidateLibraryImportPathResponseDto) GetIsValidOk() (*bool, bool)`

GetIsValidOk returns a tuple with the IsValid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsValid

`func (o *ValidateLibraryImportPathResponseDto) SetIsValid(v bool)`

SetIsValid sets IsValid field to given value.


### GetMessage

`func (o *ValidateLibraryImportPathResponseDto) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ValidateLibraryImportPathResponseDto) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ValidateLibraryImportPathResponseDto) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ValidateLibraryImportPathResponseDto) HasMessage() bool`

HasMessage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


