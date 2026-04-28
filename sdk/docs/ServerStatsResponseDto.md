# ServerStatsResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Photos** | **int32** | Total number of photos | 
**Usage** | **int32** | Total storage usage in bytes | 
**UsageByUser** | [**[]UsageByUserDto**](UsageByUserDto.md) | Array of usage for each user | 
**UsagePhotos** | **int32** | Storage usage for photos in bytes | 
**UsageVideos** | **int32** | Storage usage for videos in bytes | 
**Videos** | **int32** | Total number of videos | 

## Methods

### NewServerStatsResponseDto

`func NewServerStatsResponseDto(photos int32, usage int32, usageByUser []UsageByUserDto, usagePhotos int32, usageVideos int32, videos int32, ) *ServerStatsResponseDto`

NewServerStatsResponseDto instantiates a new ServerStatsResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServerStatsResponseDtoWithDefaults

`func NewServerStatsResponseDtoWithDefaults() *ServerStatsResponseDto`

NewServerStatsResponseDtoWithDefaults instantiates a new ServerStatsResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhotos

`func (o *ServerStatsResponseDto) GetPhotos() int32`

GetPhotos returns the Photos field if non-nil, zero value otherwise.

### GetPhotosOk

`func (o *ServerStatsResponseDto) GetPhotosOk() (*int32, bool)`

GetPhotosOk returns a tuple with the Photos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhotos

`func (o *ServerStatsResponseDto) SetPhotos(v int32)`

SetPhotos sets Photos field to given value.


### GetUsage

`func (o *ServerStatsResponseDto) GetUsage() int32`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *ServerStatsResponseDto) GetUsageOk() (*int32, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *ServerStatsResponseDto) SetUsage(v int32)`

SetUsage sets Usage field to given value.


### GetUsageByUser

`func (o *ServerStatsResponseDto) GetUsageByUser() []UsageByUserDto`

GetUsageByUser returns the UsageByUser field if non-nil, zero value otherwise.

### GetUsageByUserOk

`func (o *ServerStatsResponseDto) GetUsageByUserOk() (*[]UsageByUserDto, bool)`

GetUsageByUserOk returns a tuple with the UsageByUser field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageByUser

`func (o *ServerStatsResponseDto) SetUsageByUser(v []UsageByUserDto)`

SetUsageByUser sets UsageByUser field to given value.


### GetUsagePhotos

`func (o *ServerStatsResponseDto) GetUsagePhotos() int32`

GetUsagePhotos returns the UsagePhotos field if non-nil, zero value otherwise.

### GetUsagePhotosOk

`func (o *ServerStatsResponseDto) GetUsagePhotosOk() (*int32, bool)`

GetUsagePhotosOk returns a tuple with the UsagePhotos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsagePhotos

`func (o *ServerStatsResponseDto) SetUsagePhotos(v int32)`

SetUsagePhotos sets UsagePhotos field to given value.


### GetUsageVideos

`func (o *ServerStatsResponseDto) GetUsageVideos() int32`

GetUsageVideos returns the UsageVideos field if non-nil, zero value otherwise.

### GetUsageVideosOk

`func (o *ServerStatsResponseDto) GetUsageVideosOk() (*int32, bool)`

GetUsageVideosOk returns a tuple with the UsageVideos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageVideos

`func (o *ServerStatsResponseDto) SetUsageVideos(v int32)`

SetUsageVideos sets UsageVideos field to given value.


### GetVideos

`func (o *ServerStatsResponseDto) GetVideos() int32`

GetVideos returns the Videos field if non-nil, zero value otherwise.

### GetVideosOk

`func (o *ServerStatsResponseDto) GetVideosOk() (*int32, bool)`

GetVideosOk returns a tuple with the Videos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideos

`func (o *ServerStatsResponseDto) SetVideos(v int32)`

SetVideos sets Videos field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


