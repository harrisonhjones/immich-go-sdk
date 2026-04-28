# ServerStorageResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DiskAvailable** | **string** | Available disk space (human-readable format) | 
**DiskAvailableRaw** | **int32** | Available disk space in bytes | 
**DiskSize** | **string** | Total disk size (human-readable format) | 
**DiskSizeRaw** | **int32** | Total disk size in bytes | 
**DiskUsagePercentage** | **float64** | Disk usage percentage (0-100) | 
**DiskUse** | **string** | Used disk space (human-readable format) | 
**DiskUseRaw** | **int32** | Used disk space in bytes | 

## Methods

### NewServerStorageResponseDto

`func NewServerStorageResponseDto(diskAvailable string, diskAvailableRaw int32, diskSize string, diskSizeRaw int32, diskUsagePercentage float64, diskUse string, diskUseRaw int32, ) *ServerStorageResponseDto`

NewServerStorageResponseDto instantiates a new ServerStorageResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServerStorageResponseDtoWithDefaults

`func NewServerStorageResponseDtoWithDefaults() *ServerStorageResponseDto`

NewServerStorageResponseDtoWithDefaults instantiates a new ServerStorageResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDiskAvailable

`func (o *ServerStorageResponseDto) GetDiskAvailable() string`

GetDiskAvailable returns the DiskAvailable field if non-nil, zero value otherwise.

### GetDiskAvailableOk

`func (o *ServerStorageResponseDto) GetDiskAvailableOk() (*string, bool)`

GetDiskAvailableOk returns a tuple with the DiskAvailable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskAvailable

`func (o *ServerStorageResponseDto) SetDiskAvailable(v string)`

SetDiskAvailable sets DiskAvailable field to given value.


### GetDiskAvailableRaw

`func (o *ServerStorageResponseDto) GetDiskAvailableRaw() int32`

GetDiskAvailableRaw returns the DiskAvailableRaw field if non-nil, zero value otherwise.

### GetDiskAvailableRawOk

`func (o *ServerStorageResponseDto) GetDiskAvailableRawOk() (*int32, bool)`

GetDiskAvailableRawOk returns a tuple with the DiskAvailableRaw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskAvailableRaw

`func (o *ServerStorageResponseDto) SetDiskAvailableRaw(v int32)`

SetDiskAvailableRaw sets DiskAvailableRaw field to given value.


### GetDiskSize

`func (o *ServerStorageResponseDto) GetDiskSize() string`

GetDiskSize returns the DiskSize field if non-nil, zero value otherwise.

### GetDiskSizeOk

`func (o *ServerStorageResponseDto) GetDiskSizeOk() (*string, bool)`

GetDiskSizeOk returns a tuple with the DiskSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskSize

`func (o *ServerStorageResponseDto) SetDiskSize(v string)`

SetDiskSize sets DiskSize field to given value.


### GetDiskSizeRaw

`func (o *ServerStorageResponseDto) GetDiskSizeRaw() int32`

GetDiskSizeRaw returns the DiskSizeRaw field if non-nil, zero value otherwise.

### GetDiskSizeRawOk

`func (o *ServerStorageResponseDto) GetDiskSizeRawOk() (*int32, bool)`

GetDiskSizeRawOk returns a tuple with the DiskSizeRaw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskSizeRaw

`func (o *ServerStorageResponseDto) SetDiskSizeRaw(v int32)`

SetDiskSizeRaw sets DiskSizeRaw field to given value.


### GetDiskUsagePercentage

`func (o *ServerStorageResponseDto) GetDiskUsagePercentage() float64`

GetDiskUsagePercentage returns the DiskUsagePercentage field if non-nil, zero value otherwise.

### GetDiskUsagePercentageOk

`func (o *ServerStorageResponseDto) GetDiskUsagePercentageOk() (*float64, bool)`

GetDiskUsagePercentageOk returns a tuple with the DiskUsagePercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskUsagePercentage

`func (o *ServerStorageResponseDto) SetDiskUsagePercentage(v float64)`

SetDiskUsagePercentage sets DiskUsagePercentage field to given value.


### GetDiskUse

`func (o *ServerStorageResponseDto) GetDiskUse() string`

GetDiskUse returns the DiskUse field if non-nil, zero value otherwise.

### GetDiskUseOk

`func (o *ServerStorageResponseDto) GetDiskUseOk() (*string, bool)`

GetDiskUseOk returns a tuple with the DiskUse field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskUse

`func (o *ServerStorageResponseDto) SetDiskUse(v string)`

SetDiskUse sets DiskUse field to given value.


### GetDiskUseRaw

`func (o *ServerStorageResponseDto) GetDiskUseRaw() int32`

GetDiskUseRaw returns the DiskUseRaw field if non-nil, zero value otherwise.

### GetDiskUseRawOk

`func (o *ServerStorageResponseDto) GetDiskUseRawOk() (*int32, bool)`

GetDiskUseRawOk returns a tuple with the DiskUseRaw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiskUseRaw

`func (o *ServerStorageResponseDto) SetDiskUseRaw(v int32)`

SetDiskUseRaw sets DiskUseRaw field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


