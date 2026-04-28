# TimeBucketsResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **int32** | Number of assets in this time bucket | 
**TimeBucket** | **string** | Time bucket identifier in YYYY-MM-DD format representing the start of the time period | 

## Methods

### NewTimeBucketsResponseDto

`func NewTimeBucketsResponseDto(count int32, timeBucket string, ) *TimeBucketsResponseDto`

NewTimeBucketsResponseDto instantiates a new TimeBucketsResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTimeBucketsResponseDtoWithDefaults

`func NewTimeBucketsResponseDtoWithDefaults() *TimeBucketsResponseDto`

NewTimeBucketsResponseDtoWithDefaults instantiates a new TimeBucketsResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCount

`func (o *TimeBucketsResponseDto) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *TimeBucketsResponseDto) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *TimeBucketsResponseDto) SetCount(v int32)`

SetCount sets Count field to given value.


### GetTimeBucket

`func (o *TimeBucketsResponseDto) GetTimeBucket() string`

GetTimeBucket returns the TimeBucket field if non-nil, zero value otherwise.

### GetTimeBucketOk

`func (o *TimeBucketsResponseDto) GetTimeBucketOk() (*string, bool)`

GetTimeBucketOk returns a tuple with the TimeBucket field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeBucket

`func (o *TimeBucketsResponseDto) SetTimeBucket(v string)`

SetTimeBucket sets TimeBucket field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


