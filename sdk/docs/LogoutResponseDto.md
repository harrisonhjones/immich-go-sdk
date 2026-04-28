# LogoutResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RedirectUri** | **string** | Redirect URI | 
**Successful** | **bool** | Logout successful | 

## Methods

### NewLogoutResponseDto

`func NewLogoutResponseDto(redirectUri string, successful bool, ) *LogoutResponseDto`

NewLogoutResponseDto instantiates a new LogoutResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLogoutResponseDtoWithDefaults

`func NewLogoutResponseDtoWithDefaults() *LogoutResponseDto`

NewLogoutResponseDtoWithDefaults instantiates a new LogoutResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRedirectUri

`func (o *LogoutResponseDto) GetRedirectUri() string`

GetRedirectUri returns the RedirectUri field if non-nil, zero value otherwise.

### GetRedirectUriOk

`func (o *LogoutResponseDto) GetRedirectUriOk() (*string, bool)`

GetRedirectUriOk returns a tuple with the RedirectUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedirectUri

`func (o *LogoutResponseDto) SetRedirectUri(v string)`

SetRedirectUri sets RedirectUri field to given value.


### GetSuccessful

`func (o *LogoutResponseDto) GetSuccessful() bool`

GetSuccessful returns the Successful field if non-nil, zero value otherwise.

### GetSuccessfulOk

`func (o *LogoutResponseDto) GetSuccessfulOk() (*bool, bool)`

GetSuccessfulOk returns a tuple with the Successful field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccessful

`func (o *LogoutResponseDto) SetSuccessful(v bool)`

SetSuccessful sets Successful field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


