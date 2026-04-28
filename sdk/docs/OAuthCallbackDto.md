# OAuthCallbackDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CodeVerifier** | Pointer to **string** | OAuth code verifier (PKCE) | [optional] 
**State** | Pointer to **string** | OAuth state parameter | [optional] 
**Url** | **string** | OAuth callback URL | 

## Methods

### NewOAuthCallbackDto

`func NewOAuthCallbackDto(url string, ) *OAuthCallbackDto`

NewOAuthCallbackDto instantiates a new OAuthCallbackDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOAuthCallbackDtoWithDefaults

`func NewOAuthCallbackDtoWithDefaults() *OAuthCallbackDto`

NewOAuthCallbackDtoWithDefaults instantiates a new OAuthCallbackDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCodeVerifier

`func (o *OAuthCallbackDto) GetCodeVerifier() string`

GetCodeVerifier returns the CodeVerifier field if non-nil, zero value otherwise.

### GetCodeVerifierOk

`func (o *OAuthCallbackDto) GetCodeVerifierOk() (*string, bool)`

GetCodeVerifierOk returns a tuple with the CodeVerifier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeVerifier

`func (o *OAuthCallbackDto) SetCodeVerifier(v string)`

SetCodeVerifier sets CodeVerifier field to given value.

### HasCodeVerifier

`func (o *OAuthCallbackDto) HasCodeVerifier() bool`

HasCodeVerifier returns a boolean if a field has been set.

### GetState

`func (o *OAuthCallbackDto) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *OAuthCallbackDto) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *OAuthCallbackDto) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *OAuthCallbackDto) HasState() bool`

HasState returns a boolean if a field has been set.

### GetUrl

`func (o *OAuthCallbackDto) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *OAuthCallbackDto) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *OAuthCallbackDto) SetUrl(v string)`

SetUrl sets Url field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


