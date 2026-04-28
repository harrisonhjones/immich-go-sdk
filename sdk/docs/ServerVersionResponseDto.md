# ServerVersionResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Major** | **int32** | Major version number | 
**Minor** | **int32** | Minor version number | 
**Patch** | **int32** | Patch version number | 

## Methods

### NewServerVersionResponseDto

`func NewServerVersionResponseDto(major int32, minor int32, patch int32, ) *ServerVersionResponseDto`

NewServerVersionResponseDto instantiates a new ServerVersionResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServerVersionResponseDtoWithDefaults

`func NewServerVersionResponseDtoWithDefaults() *ServerVersionResponseDto`

NewServerVersionResponseDtoWithDefaults instantiates a new ServerVersionResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMajor

`func (o *ServerVersionResponseDto) GetMajor() int32`

GetMajor returns the Major field if non-nil, zero value otherwise.

### GetMajorOk

`func (o *ServerVersionResponseDto) GetMajorOk() (*int32, bool)`

GetMajorOk returns a tuple with the Major field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMajor

`func (o *ServerVersionResponseDto) SetMajor(v int32)`

SetMajor sets Major field to given value.


### GetMinor

`func (o *ServerVersionResponseDto) GetMinor() int32`

GetMinor returns the Minor field if non-nil, zero value otherwise.

### GetMinorOk

`func (o *ServerVersionResponseDto) GetMinorOk() (*int32, bool)`

GetMinorOk returns a tuple with the Minor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinor

`func (o *ServerVersionResponseDto) SetMinor(v int32)`

SetMinor sets Minor field to given value.


### GetPatch

`func (o *ServerVersionResponseDto) GetPatch() int32`

GetPatch returns the Patch field if non-nil, zero value otherwise.

### GetPatchOk

`func (o *ServerVersionResponseDto) GetPatchOk() (*int32, bool)`

GetPatchOk returns a tuple with the Patch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPatch

`func (o *ServerVersionResponseDto) SetPatch(v int32)`

SetPatch sets Patch field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


