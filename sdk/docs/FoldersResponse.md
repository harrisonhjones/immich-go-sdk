# FoldersResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** | Whether folders are enabled | 
**SidebarWeb** | **bool** | Whether folders appear in web sidebar | 

## Methods

### NewFoldersResponse

`func NewFoldersResponse(enabled bool, sidebarWeb bool, ) *FoldersResponse`

NewFoldersResponse instantiates a new FoldersResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFoldersResponseWithDefaults

`func NewFoldersResponseWithDefaults() *FoldersResponse`

NewFoldersResponseWithDefaults instantiates a new FoldersResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *FoldersResponse) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *FoldersResponse) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *FoldersResponse) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetSidebarWeb

`func (o *FoldersResponse) GetSidebarWeb() bool`

GetSidebarWeb returns the SidebarWeb field if non-nil, zero value otherwise.

### GetSidebarWebOk

`func (o *FoldersResponse) GetSidebarWebOk() (*bool, bool)`

GetSidebarWebOk returns a tuple with the SidebarWeb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSidebarWeb

`func (o *FoldersResponse) SetSidebarWeb(v bool)`

SetSidebarWeb sets SidebarWeb field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


