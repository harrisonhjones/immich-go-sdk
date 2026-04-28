# DuplicateResolveDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Groups** | [**[]DuplicateResolveGroupDto**](DuplicateResolveGroupDto.md) | List of duplicate groups to resolve | 

## Methods

### NewDuplicateResolveDto

`func NewDuplicateResolveDto(groups []DuplicateResolveGroupDto, ) *DuplicateResolveDto`

NewDuplicateResolveDto instantiates a new DuplicateResolveDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDuplicateResolveDtoWithDefaults

`func NewDuplicateResolveDtoWithDefaults() *DuplicateResolveDto`

NewDuplicateResolveDtoWithDefaults instantiates a new DuplicateResolveDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroups

`func (o *DuplicateResolveDto) GetGroups() []DuplicateResolveGroupDto`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *DuplicateResolveDto) GetGroupsOk() (*[]DuplicateResolveGroupDto, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *DuplicateResolveDto) SetGroups(v []DuplicateResolveGroupDto)`

SetGroups sets Groups field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


