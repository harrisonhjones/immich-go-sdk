# EmailNotificationsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AlbumInvite** | **bool** | Whether to receive email notifications for album invites | 
**AlbumUpdate** | **bool** | Whether to receive email notifications for album updates | 
**Enabled** | **bool** | Whether email notifications are enabled | 

## Methods

### NewEmailNotificationsResponse

`func NewEmailNotificationsResponse(albumInvite bool, albumUpdate bool, enabled bool, ) *EmailNotificationsResponse`

NewEmailNotificationsResponse instantiates a new EmailNotificationsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmailNotificationsResponseWithDefaults

`func NewEmailNotificationsResponseWithDefaults() *EmailNotificationsResponse`

NewEmailNotificationsResponseWithDefaults instantiates a new EmailNotificationsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAlbumInvite

`func (o *EmailNotificationsResponse) GetAlbumInvite() bool`

GetAlbumInvite returns the AlbumInvite field if non-nil, zero value otherwise.

### GetAlbumInviteOk

`func (o *EmailNotificationsResponse) GetAlbumInviteOk() (*bool, bool)`

GetAlbumInviteOk returns a tuple with the AlbumInvite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumInvite

`func (o *EmailNotificationsResponse) SetAlbumInvite(v bool)`

SetAlbumInvite sets AlbumInvite field to given value.


### GetAlbumUpdate

`func (o *EmailNotificationsResponse) GetAlbumUpdate() bool`

GetAlbumUpdate returns the AlbumUpdate field if non-nil, zero value otherwise.

### GetAlbumUpdateOk

`func (o *EmailNotificationsResponse) GetAlbumUpdateOk() (*bool, bool)`

GetAlbumUpdateOk returns a tuple with the AlbumUpdate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlbumUpdate

`func (o *EmailNotificationsResponse) SetAlbumUpdate(v bool)`

SetAlbumUpdate sets AlbumUpdate field to given value.


### GetEnabled

`func (o *EmailNotificationsResponse) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *EmailNotificationsResponse) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *EmailNotificationsResponse) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


