# ApiKeyCreateResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ApiKey** | [**ApiKeyResponseDto**](ApiKeyResponseDto.md) |  | 
**Secret** | **string** | API key secret (only shown once) | 

## Methods

### NewApiKeyCreateResponseDto

`func NewApiKeyCreateResponseDto(apiKey ApiKeyResponseDto, secret string, ) *ApiKeyCreateResponseDto`

NewApiKeyCreateResponseDto instantiates a new ApiKeyCreateResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiKeyCreateResponseDtoWithDefaults

`func NewApiKeyCreateResponseDtoWithDefaults() *ApiKeyCreateResponseDto`

NewApiKeyCreateResponseDtoWithDefaults instantiates a new ApiKeyCreateResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetApiKey

`func (o *ApiKeyCreateResponseDto) GetApiKey() ApiKeyResponseDto`

GetApiKey returns the ApiKey field if non-nil, zero value otherwise.

### GetApiKeyOk

`func (o *ApiKeyCreateResponseDto) GetApiKeyOk() (*ApiKeyResponseDto, bool)`

GetApiKeyOk returns a tuple with the ApiKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKey

`func (o *ApiKeyCreateResponseDto) SetApiKey(v ApiKeyResponseDto)`

SetApiKey sets ApiKey field to given value.


### GetSecret

`func (o *ApiKeyCreateResponseDto) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *ApiKeyCreateResponseDto) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *ApiKeyCreateResponseDto) SetSecret(v string)`

SetSecret sets Secret field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


