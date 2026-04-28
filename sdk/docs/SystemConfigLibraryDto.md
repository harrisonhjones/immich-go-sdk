# SystemConfigLibraryDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Scan** | [**SystemConfigLibraryScanDto**](SystemConfigLibraryScanDto.md) |  | 
**Watch** | [**SystemConfigLibraryWatchDto**](SystemConfigLibraryWatchDto.md) |  | 

## Methods

### NewSystemConfigLibraryDto

`func NewSystemConfigLibraryDto(scan SystemConfigLibraryScanDto, watch SystemConfigLibraryWatchDto, ) *SystemConfigLibraryDto`

NewSystemConfigLibraryDto instantiates a new SystemConfigLibraryDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigLibraryDtoWithDefaults

`func NewSystemConfigLibraryDtoWithDefaults() *SystemConfigLibraryDto`

NewSystemConfigLibraryDtoWithDefaults instantiates a new SystemConfigLibraryDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetScan

`func (o *SystemConfigLibraryDto) GetScan() SystemConfigLibraryScanDto`

GetScan returns the Scan field if non-nil, zero value otherwise.

### GetScanOk

`func (o *SystemConfigLibraryDto) GetScanOk() (*SystemConfigLibraryScanDto, bool)`

GetScanOk returns a tuple with the Scan field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScan

`func (o *SystemConfigLibraryDto) SetScan(v SystemConfigLibraryScanDto)`

SetScan sets Scan field to given value.


### GetWatch

`func (o *SystemConfigLibraryDto) GetWatch() SystemConfigLibraryWatchDto`

GetWatch returns the Watch field if non-nil, zero value otherwise.

### GetWatchOk

`func (o *SystemConfigLibraryDto) GetWatchOk() (*SystemConfigLibraryWatchDto, bool)`

GetWatchOk returns a tuple with the Watch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWatch

`func (o *SystemConfigLibraryDto) SetWatch(v SystemConfigLibraryWatchDto)`

SetWatch sets Watch field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


