# TagsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** | Whether tags are enabled | 
**SidebarWeb** | **bool** | Whether tags appear in web sidebar | 

## Methods

### NewTagsResponse

`func NewTagsResponse(enabled bool, sidebarWeb bool, ) *TagsResponse`

NewTagsResponse instantiates a new TagsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTagsResponseWithDefaults

`func NewTagsResponseWithDefaults() *TagsResponse`

NewTagsResponseWithDefaults instantiates a new TagsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *TagsResponse) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *TagsResponse) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *TagsResponse) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetSidebarWeb

`func (o *TagsResponse) GetSidebarWeb() bool`

GetSidebarWeb returns the SidebarWeb field if non-nil, zero value otherwise.

### GetSidebarWebOk

`func (o *TagsResponse) GetSidebarWebOk() (*bool, bool)`

GetSidebarWebOk returns a tuple with the SidebarWeb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSidebarWeb

`func (o *TagsResponse) SetSidebarWeb(v bool)`

SetSidebarWeb sets SidebarWeb field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


