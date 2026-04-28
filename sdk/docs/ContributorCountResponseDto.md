# ContributorCountResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssetCount** | **int32** | Number of assets contributed | 
**UserId** | **string** | User ID | 

## Methods

### NewContributorCountResponseDto

`func NewContributorCountResponseDto(assetCount int32, userId string, ) *ContributorCountResponseDto`

NewContributorCountResponseDto instantiates a new ContributorCountResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContributorCountResponseDtoWithDefaults

`func NewContributorCountResponseDtoWithDefaults() *ContributorCountResponseDto`

NewContributorCountResponseDtoWithDefaults instantiates a new ContributorCountResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAssetCount

`func (o *ContributorCountResponseDto) GetAssetCount() int32`

GetAssetCount returns the AssetCount field if non-nil, zero value otherwise.

### GetAssetCountOk

`func (o *ContributorCountResponseDto) GetAssetCountOk() (*int32, bool)`

GetAssetCountOk returns a tuple with the AssetCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssetCount

`func (o *ContributorCountResponseDto) SetAssetCount(v int32)`

SetAssetCount sets AssetCount field to given value.


### GetUserId

`func (o *ContributorCountResponseDto) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *ContributorCountResponseDto) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *ContributorCountResponseDto) SetUserId(v string)`

SetUserId sets UserId field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


