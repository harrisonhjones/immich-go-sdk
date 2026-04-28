# PluginResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Actions** | [**[]PluginActionResponseDto**](PluginActionResponseDto.md) | Plugin actions | 
**Author** | **string** | Plugin author | 
**CreatedAt** | **string** | Creation date | 
**Description** | **string** | Plugin description | 
**Filters** | [**[]PluginFilterResponseDto**](PluginFilterResponseDto.md) | Plugin filters | 
**Id** | **string** | Plugin ID | 
**Name** | **string** | Plugin name | 
**Title** | **string** | Plugin title | 
**UpdatedAt** | **string** | Last update date | 
**Version** | **string** | Plugin version | 

## Methods

### NewPluginResponseDto

`func NewPluginResponseDto(actions []PluginActionResponseDto, author string, createdAt string, description string, filters []PluginFilterResponseDto, id string, name string, title string, updatedAt string, version string, ) *PluginResponseDto`

NewPluginResponseDto instantiates a new PluginResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginResponseDtoWithDefaults

`func NewPluginResponseDtoWithDefaults() *PluginResponseDto`

NewPluginResponseDtoWithDefaults instantiates a new PluginResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActions

`func (o *PluginResponseDto) GetActions() []PluginActionResponseDto`

GetActions returns the Actions field if non-nil, zero value otherwise.

### GetActionsOk

`func (o *PluginResponseDto) GetActionsOk() (*[]PluginActionResponseDto, bool)`

GetActionsOk returns a tuple with the Actions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActions

`func (o *PluginResponseDto) SetActions(v []PluginActionResponseDto)`

SetActions sets Actions field to given value.


### GetAuthor

`func (o *PluginResponseDto) GetAuthor() string`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *PluginResponseDto) GetAuthorOk() (*string, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *PluginResponseDto) SetAuthor(v string)`

SetAuthor sets Author field to given value.


### GetCreatedAt

`func (o *PluginResponseDto) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *PluginResponseDto) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *PluginResponseDto) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetDescription

`func (o *PluginResponseDto) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *PluginResponseDto) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *PluginResponseDto) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetFilters

`func (o *PluginResponseDto) GetFilters() []PluginFilterResponseDto`

GetFilters returns the Filters field if non-nil, zero value otherwise.

### GetFiltersOk

`func (o *PluginResponseDto) GetFiltersOk() (*[]PluginFilterResponseDto, bool)`

GetFiltersOk returns a tuple with the Filters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilters

`func (o *PluginResponseDto) SetFilters(v []PluginFilterResponseDto)`

SetFilters sets Filters field to given value.


### GetId

`func (o *PluginResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PluginResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PluginResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *PluginResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PluginResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PluginResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetTitle

`func (o *PluginResponseDto) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *PluginResponseDto) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *PluginResponseDto) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetUpdatedAt

`func (o *PluginResponseDto) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *PluginResponseDto) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *PluginResponseDto) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetVersion

`func (o *PluginResponseDto) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *PluginResponseDto) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *PluginResponseDto) SetVersion(v string)`

SetVersion sets Version field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


