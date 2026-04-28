# VersionCheckStateResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CheckedAt** | **NullableString** | Last check timestamp | 
**ReleaseVersion** | **NullableString** | Release version | 

## Methods

### NewVersionCheckStateResponseDto

`func NewVersionCheckStateResponseDto(checkedAt NullableString, releaseVersion NullableString, ) *VersionCheckStateResponseDto`

NewVersionCheckStateResponseDto instantiates a new VersionCheckStateResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVersionCheckStateResponseDtoWithDefaults

`func NewVersionCheckStateResponseDtoWithDefaults() *VersionCheckStateResponseDto`

NewVersionCheckStateResponseDtoWithDefaults instantiates a new VersionCheckStateResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCheckedAt

`func (o *VersionCheckStateResponseDto) GetCheckedAt() string`

GetCheckedAt returns the CheckedAt field if non-nil, zero value otherwise.

### GetCheckedAtOk

`func (o *VersionCheckStateResponseDto) GetCheckedAtOk() (*string, bool)`

GetCheckedAtOk returns a tuple with the CheckedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckedAt

`func (o *VersionCheckStateResponseDto) SetCheckedAt(v string)`

SetCheckedAt sets CheckedAt field to given value.


### SetCheckedAtNil

`func (o *VersionCheckStateResponseDto) SetCheckedAtNil(b bool)`

 SetCheckedAtNil sets the value for CheckedAt to be an explicit nil

### UnsetCheckedAt
`func (o *VersionCheckStateResponseDto) UnsetCheckedAt()`

UnsetCheckedAt ensures that no value is present for CheckedAt, not even an explicit nil
### GetReleaseVersion

`func (o *VersionCheckStateResponseDto) GetReleaseVersion() string`

GetReleaseVersion returns the ReleaseVersion field if non-nil, zero value otherwise.

### GetReleaseVersionOk

`func (o *VersionCheckStateResponseDto) GetReleaseVersionOk() (*string, bool)`

GetReleaseVersionOk returns a tuple with the ReleaseVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReleaseVersion

`func (o *VersionCheckStateResponseDto) SetReleaseVersion(v string)`

SetReleaseVersion sets ReleaseVersion field to given value.


### SetReleaseVersionNil

`func (o *VersionCheckStateResponseDto) SetReleaseVersionNil(b bool)`

 SetReleaseVersionNil sets the value for ReleaseVersion to be an explicit nil

### UnsetReleaseVersion
`func (o *VersionCheckStateResponseDto) UnsetReleaseVersion()`

UnsetReleaseVersion ensures that no value is present for ReleaseVersion, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


