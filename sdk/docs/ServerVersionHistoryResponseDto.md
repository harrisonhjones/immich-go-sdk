# ServerVersionHistoryResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CreatedAt** | **time.Time** | When this version was first seen | 
**Id** | **string** | Version history entry ID | 
**Version** | **string** | Version string | 

## Methods

### NewServerVersionHistoryResponseDto

`func NewServerVersionHistoryResponseDto(createdAt time.Time, id string, version string, ) *ServerVersionHistoryResponseDto`

NewServerVersionHistoryResponseDto instantiates a new ServerVersionHistoryResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServerVersionHistoryResponseDtoWithDefaults

`func NewServerVersionHistoryResponseDtoWithDefaults() *ServerVersionHistoryResponseDto`

NewServerVersionHistoryResponseDtoWithDefaults instantiates a new ServerVersionHistoryResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreatedAt

`func (o *ServerVersionHistoryResponseDto) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ServerVersionHistoryResponseDto) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ServerVersionHistoryResponseDto) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetId

`func (o *ServerVersionHistoryResponseDto) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ServerVersionHistoryResponseDto) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ServerVersionHistoryResponseDto) SetId(v string)`

SetId sets Id field to given value.


### GetVersion

`func (o *ServerVersionHistoryResponseDto) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ServerVersionHistoryResponseDto) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ServerVersionHistoryResponseDto) SetVersion(v string)`

SetVersion sets Version field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


