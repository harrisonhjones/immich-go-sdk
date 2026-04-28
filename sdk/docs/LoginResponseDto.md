# LoginResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessToken** | **string** | Access token | 
**IsAdmin** | **bool** | Is admin user | 
**IsOnboarded** | **bool** | Is onboarded | 
**Name** | **string** | User name | 
**ProfileImagePath** | **string** | Profile image path | 
**ShouldChangePassword** | **bool** | Should change password | 
**UserEmail** | **string** | User email | 
**UserId** | **string** | User ID | 

## Methods

### NewLoginResponseDto

`func NewLoginResponseDto(accessToken string, isAdmin bool, isOnboarded bool, name string, profileImagePath string, shouldChangePassword bool, userEmail string, userId string, ) *LoginResponseDto`

NewLoginResponseDto instantiates a new LoginResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLoginResponseDtoWithDefaults

`func NewLoginResponseDtoWithDefaults() *LoginResponseDto`

NewLoginResponseDtoWithDefaults instantiates a new LoginResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessToken

`func (o *LoginResponseDto) GetAccessToken() string`

GetAccessToken returns the AccessToken field if non-nil, zero value otherwise.

### GetAccessTokenOk

`func (o *LoginResponseDto) GetAccessTokenOk() (*string, bool)`

GetAccessTokenOk returns a tuple with the AccessToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessToken

`func (o *LoginResponseDto) SetAccessToken(v string)`

SetAccessToken sets AccessToken field to given value.


### GetIsAdmin

`func (o *LoginResponseDto) GetIsAdmin() bool`

GetIsAdmin returns the IsAdmin field if non-nil, zero value otherwise.

### GetIsAdminOk

`func (o *LoginResponseDto) GetIsAdminOk() (*bool, bool)`

GetIsAdminOk returns a tuple with the IsAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAdmin

`func (o *LoginResponseDto) SetIsAdmin(v bool)`

SetIsAdmin sets IsAdmin field to given value.


### GetIsOnboarded

`func (o *LoginResponseDto) GetIsOnboarded() bool`

GetIsOnboarded returns the IsOnboarded field if non-nil, zero value otherwise.

### GetIsOnboardedOk

`func (o *LoginResponseDto) GetIsOnboardedOk() (*bool, bool)`

GetIsOnboardedOk returns a tuple with the IsOnboarded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOnboarded

`func (o *LoginResponseDto) SetIsOnboarded(v bool)`

SetIsOnboarded sets IsOnboarded field to given value.


### GetName

`func (o *LoginResponseDto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *LoginResponseDto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *LoginResponseDto) SetName(v string)`

SetName sets Name field to given value.


### GetProfileImagePath

`func (o *LoginResponseDto) GetProfileImagePath() string`

GetProfileImagePath returns the ProfileImagePath field if non-nil, zero value otherwise.

### GetProfileImagePathOk

`func (o *LoginResponseDto) GetProfileImagePathOk() (*string, bool)`

GetProfileImagePathOk returns a tuple with the ProfileImagePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileImagePath

`func (o *LoginResponseDto) SetProfileImagePath(v string)`

SetProfileImagePath sets ProfileImagePath field to given value.


### GetShouldChangePassword

`func (o *LoginResponseDto) GetShouldChangePassword() bool`

GetShouldChangePassword returns the ShouldChangePassword field if non-nil, zero value otherwise.

### GetShouldChangePasswordOk

`func (o *LoginResponseDto) GetShouldChangePasswordOk() (*bool, bool)`

GetShouldChangePasswordOk returns a tuple with the ShouldChangePassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShouldChangePassword

`func (o *LoginResponseDto) SetShouldChangePassword(v bool)`

SetShouldChangePassword sets ShouldChangePassword field to given value.


### GetUserEmail

`func (o *LoginResponseDto) GetUserEmail() string`

GetUserEmail returns the UserEmail field if non-nil, zero value otherwise.

### GetUserEmailOk

`func (o *LoginResponseDto) GetUserEmailOk() (*string, bool)`

GetUserEmailOk returns a tuple with the UserEmail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserEmail

`func (o *LoginResponseDto) SetUserEmail(v string)`

SetUserEmail sets UserEmail field to given value.


### GetUserId

`func (o *LoginResponseDto) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *LoginResponseDto) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *LoginResponseDto) SetUserId(v string)`

SetUserId sets UserId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


