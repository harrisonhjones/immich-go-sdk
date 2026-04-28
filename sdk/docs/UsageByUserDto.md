# UsageByUserDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Photos** | **int32** | Number of photos | 
**QuotaSizeInBytes** | **NullableInt32** | User quota size in bytes (null if unlimited) | 
**Usage** | **int32** | Total storage usage in bytes | 
**UsagePhotos** | **int32** | Storage usage for photos in bytes | 
**UsageVideos** | **int32** | Storage usage for videos in bytes | 
**UserId** | **string** | User ID | 
**UserName** | **string** | User name | 
**Videos** | **int32** | Number of videos | 

## Methods

### NewUsageByUserDto

`func NewUsageByUserDto(photos int32, quotaSizeInBytes NullableInt32, usage int32, usagePhotos int32, usageVideos int32, userId string, userName string, videos int32, ) *UsageByUserDto`

NewUsageByUserDto instantiates a new UsageByUserDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUsageByUserDtoWithDefaults

`func NewUsageByUserDtoWithDefaults() *UsageByUserDto`

NewUsageByUserDtoWithDefaults instantiates a new UsageByUserDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhotos

`func (o *UsageByUserDto) GetPhotos() int32`

GetPhotos returns the Photos field if non-nil, zero value otherwise.

### GetPhotosOk

`func (o *UsageByUserDto) GetPhotosOk() (*int32, bool)`

GetPhotosOk returns a tuple with the Photos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhotos

`func (o *UsageByUserDto) SetPhotos(v int32)`

SetPhotos sets Photos field to given value.


### GetQuotaSizeInBytes

`func (o *UsageByUserDto) GetQuotaSizeInBytes() int32`

GetQuotaSizeInBytes returns the QuotaSizeInBytes field if non-nil, zero value otherwise.

### GetQuotaSizeInBytesOk

`func (o *UsageByUserDto) GetQuotaSizeInBytesOk() (*int32, bool)`

GetQuotaSizeInBytesOk returns a tuple with the QuotaSizeInBytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotaSizeInBytes

`func (o *UsageByUserDto) SetQuotaSizeInBytes(v int32)`

SetQuotaSizeInBytes sets QuotaSizeInBytes field to given value.


### SetQuotaSizeInBytesNil

`func (o *UsageByUserDto) SetQuotaSizeInBytesNil(b bool)`

 SetQuotaSizeInBytesNil sets the value for QuotaSizeInBytes to be an explicit nil

### UnsetQuotaSizeInBytes
`func (o *UsageByUserDto) UnsetQuotaSizeInBytes()`

UnsetQuotaSizeInBytes ensures that no value is present for QuotaSizeInBytes, not even an explicit nil
### GetUsage

`func (o *UsageByUserDto) GetUsage() int32`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *UsageByUserDto) GetUsageOk() (*int32, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *UsageByUserDto) SetUsage(v int32)`

SetUsage sets Usage field to given value.


### GetUsagePhotos

`func (o *UsageByUserDto) GetUsagePhotos() int32`

GetUsagePhotos returns the UsagePhotos field if non-nil, zero value otherwise.

### GetUsagePhotosOk

`func (o *UsageByUserDto) GetUsagePhotosOk() (*int32, bool)`

GetUsagePhotosOk returns a tuple with the UsagePhotos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsagePhotos

`func (o *UsageByUserDto) SetUsagePhotos(v int32)`

SetUsagePhotos sets UsagePhotos field to given value.


### GetUsageVideos

`func (o *UsageByUserDto) GetUsageVideos() int32`

GetUsageVideos returns the UsageVideos field if non-nil, zero value otherwise.

### GetUsageVideosOk

`func (o *UsageByUserDto) GetUsageVideosOk() (*int32, bool)`

GetUsageVideosOk returns a tuple with the UsageVideos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageVideos

`func (o *UsageByUserDto) SetUsageVideos(v int32)`

SetUsageVideos sets UsageVideos field to given value.


### GetUserId

`func (o *UsageByUserDto) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *UsageByUserDto) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *UsageByUserDto) SetUserId(v string)`

SetUserId sets UserId field to given value.


### GetUserName

`func (o *UsageByUserDto) GetUserName() string`

GetUserName returns the UserName field if non-nil, zero value otherwise.

### GetUserNameOk

`func (o *UsageByUserDto) GetUserNameOk() (*string, bool)`

GetUserNameOk returns a tuple with the UserName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserName

`func (o *UsageByUserDto) SetUserName(v string)`

SetUserName sets UserName field to given value.


### GetVideos

`func (o *UsageByUserDto) GetVideos() int32`

GetVideos returns the Videos field if non-nil, zero value otherwise.

### GetVideosOk

`func (o *UsageByUserDto) GetVideosOk() (*int32, bool)`

GetVideosOk returns a tuple with the Videos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideos

`func (o *UsageByUserDto) SetVideos(v int32)`

SetVideos sets Videos field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


