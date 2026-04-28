# SystemConfigImageDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Colorspace** | [**Colorspace**](Colorspace.md) |  | 
**ExtractEmbedded** | **bool** | Extract embedded | 
**Fullsize** | [**SystemConfigGeneratedFullsizeImageDto**](SystemConfigGeneratedFullsizeImageDto.md) |  | 
**Preview** | [**SystemConfigGeneratedImageDto**](SystemConfigGeneratedImageDto.md) |  | 
**Thumbnail** | [**SystemConfigGeneratedImageDto**](SystemConfigGeneratedImageDto.md) |  | 

## Methods

### NewSystemConfigImageDto

`func NewSystemConfigImageDto(colorspace Colorspace, extractEmbedded bool, fullsize SystemConfigGeneratedFullsizeImageDto, preview SystemConfigGeneratedImageDto, thumbnail SystemConfigGeneratedImageDto, ) *SystemConfigImageDto`

NewSystemConfigImageDto instantiates a new SystemConfigImageDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigImageDtoWithDefaults

`func NewSystemConfigImageDtoWithDefaults() *SystemConfigImageDto`

NewSystemConfigImageDtoWithDefaults instantiates a new SystemConfigImageDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetColorspace

`func (o *SystemConfigImageDto) GetColorspace() Colorspace`

GetColorspace returns the Colorspace field if non-nil, zero value otherwise.

### GetColorspaceOk

`func (o *SystemConfigImageDto) GetColorspaceOk() (*Colorspace, bool)`

GetColorspaceOk returns a tuple with the Colorspace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColorspace

`func (o *SystemConfigImageDto) SetColorspace(v Colorspace)`

SetColorspace sets Colorspace field to given value.


### GetExtractEmbedded

`func (o *SystemConfigImageDto) GetExtractEmbedded() bool`

GetExtractEmbedded returns the ExtractEmbedded field if non-nil, zero value otherwise.

### GetExtractEmbeddedOk

`func (o *SystemConfigImageDto) GetExtractEmbeddedOk() (*bool, bool)`

GetExtractEmbeddedOk returns a tuple with the ExtractEmbedded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractEmbedded

`func (o *SystemConfigImageDto) SetExtractEmbedded(v bool)`

SetExtractEmbedded sets ExtractEmbedded field to given value.


### GetFullsize

`func (o *SystemConfigImageDto) GetFullsize() SystemConfigGeneratedFullsizeImageDto`

GetFullsize returns the Fullsize field if non-nil, zero value otherwise.

### GetFullsizeOk

`func (o *SystemConfigImageDto) GetFullsizeOk() (*SystemConfigGeneratedFullsizeImageDto, bool)`

GetFullsizeOk returns a tuple with the Fullsize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFullsize

`func (o *SystemConfigImageDto) SetFullsize(v SystemConfigGeneratedFullsizeImageDto)`

SetFullsize sets Fullsize field to given value.


### GetPreview

`func (o *SystemConfigImageDto) GetPreview() SystemConfigGeneratedImageDto`

GetPreview returns the Preview field if non-nil, zero value otherwise.

### GetPreviewOk

`func (o *SystemConfigImageDto) GetPreviewOk() (*SystemConfigGeneratedImageDto, bool)`

GetPreviewOk returns a tuple with the Preview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreview

`func (o *SystemConfigImageDto) SetPreview(v SystemConfigGeneratedImageDto)`

SetPreview sets Preview field to given value.


### GetThumbnail

`func (o *SystemConfigImageDto) GetThumbnail() SystemConfigGeneratedImageDto`

GetThumbnail returns the Thumbnail field if non-nil, zero value otherwise.

### GetThumbnailOk

`func (o *SystemConfigImageDto) GetThumbnailOk() (*SystemConfigGeneratedImageDto, bool)`

GetThumbnailOk returns a tuple with the Thumbnail field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbnail

`func (o *SystemConfigImageDto) SetThumbnail(v SystemConfigGeneratedImageDto)`

SetThumbnail sets Thumbnail field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


