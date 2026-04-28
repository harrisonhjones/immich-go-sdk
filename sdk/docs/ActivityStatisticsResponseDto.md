# ActivityStatisticsResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Comments** | **int32** | Number of comments | 
**Likes** | **int32** | Number of likes | 

## Methods

### NewActivityStatisticsResponseDto

`func NewActivityStatisticsResponseDto(comments int32, likes int32, ) *ActivityStatisticsResponseDto`

NewActivityStatisticsResponseDto instantiates a new ActivityStatisticsResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewActivityStatisticsResponseDtoWithDefaults

`func NewActivityStatisticsResponseDtoWithDefaults() *ActivityStatisticsResponseDto`

NewActivityStatisticsResponseDtoWithDefaults instantiates a new ActivityStatisticsResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComments

`func (o *ActivityStatisticsResponseDto) GetComments() int32`

GetComments returns the Comments field if non-nil, zero value otherwise.

### GetCommentsOk

`func (o *ActivityStatisticsResponseDto) GetCommentsOk() (*int32, bool)`

GetCommentsOk returns a tuple with the Comments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComments

`func (o *ActivityStatisticsResponseDto) SetComments(v int32)`

SetComments sets Comments field to given value.


### GetLikes

`func (o *ActivityStatisticsResponseDto) GetLikes() int32`

GetLikes returns the Likes field if non-nil, zero value otherwise.

### GetLikesOk

`func (o *ActivityStatisticsResponseDto) GetLikesOk() (*int32, bool)`

GetLikesOk returns a tuple with the Likes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLikes

`func (o *ActivityStatisticsResponseDto) SetLikes(v int32)`

SetLikes sets Likes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


