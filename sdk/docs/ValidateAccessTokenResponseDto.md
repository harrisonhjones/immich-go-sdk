# ValidateAccessTokenResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AuthStatus** | **bool** | Authentication status | 

## Methods

### NewValidateAccessTokenResponseDto

`func NewValidateAccessTokenResponseDto(authStatus bool, ) *ValidateAccessTokenResponseDto`

NewValidateAccessTokenResponseDto instantiates a new ValidateAccessTokenResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValidateAccessTokenResponseDtoWithDefaults

`func NewValidateAccessTokenResponseDtoWithDefaults() *ValidateAccessTokenResponseDto`

NewValidateAccessTokenResponseDtoWithDefaults instantiates a new ValidateAccessTokenResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuthStatus

`func (o *ValidateAccessTokenResponseDto) GetAuthStatus() bool`

GetAuthStatus returns the AuthStatus field if non-nil, zero value otherwise.

### GetAuthStatusOk

`func (o *ValidateAccessTokenResponseDto) GetAuthStatusOk() (*bool, bool)`

GetAuthStatusOk returns a tuple with the AuthStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthStatus

`func (o *ValidateAccessTokenResponseDto) SetAuthStatus(v bool)`

SetAuthStatus sets AuthStatus field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


