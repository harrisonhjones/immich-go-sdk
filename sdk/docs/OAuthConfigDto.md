# OAuthConfigDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CodeChallenge** | Pointer to **string** | OAuth code challenge (PKCE) | [optional] 
**RedirectUri** | **string** | OAuth redirect URI | 
**State** | Pointer to **string** | OAuth state parameter | [optional] 

## Methods

### NewOAuthConfigDto

`func NewOAuthConfigDto(redirectUri string, ) *OAuthConfigDto`

NewOAuthConfigDto instantiates a new OAuthConfigDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOAuthConfigDtoWithDefaults

`func NewOAuthConfigDtoWithDefaults() *OAuthConfigDto`

NewOAuthConfigDtoWithDefaults instantiates a new OAuthConfigDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCodeChallenge

`func (o *OAuthConfigDto) GetCodeChallenge() string`

GetCodeChallenge returns the CodeChallenge field if non-nil, zero value otherwise.

### GetCodeChallengeOk

`func (o *OAuthConfigDto) GetCodeChallengeOk() (*string, bool)`

GetCodeChallengeOk returns a tuple with the CodeChallenge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeChallenge

`func (o *OAuthConfigDto) SetCodeChallenge(v string)`

SetCodeChallenge sets CodeChallenge field to given value.

### HasCodeChallenge

`func (o *OAuthConfigDto) HasCodeChallenge() bool`

HasCodeChallenge returns a boolean if a field has been set.

### GetRedirectUri

`func (o *OAuthConfigDto) GetRedirectUri() string`

GetRedirectUri returns the RedirectUri field if non-nil, zero value otherwise.

### GetRedirectUriOk

`func (o *OAuthConfigDto) GetRedirectUriOk() (*string, bool)`

GetRedirectUriOk returns a tuple with the RedirectUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedirectUri

`func (o *OAuthConfigDto) SetRedirectUri(v string)`

SetRedirectUri sets RedirectUri field to given value.


### GetState

`func (o *OAuthConfigDto) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *OAuthConfigDto) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *OAuthConfigDto) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *OAuthConfigDto) HasState() bool`

HasState returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


