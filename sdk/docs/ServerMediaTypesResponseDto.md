# ServerMediaTypesResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Image** | **[]string** | Supported image MIME types | 
**Sidecar** | **[]string** | Supported sidecar MIME types | 
**Video** | **[]string** | Supported video MIME types | 

## Methods

### NewServerMediaTypesResponseDto

`func NewServerMediaTypesResponseDto(image []string, sidecar []string, video []string, ) *ServerMediaTypesResponseDto`

NewServerMediaTypesResponseDto instantiates a new ServerMediaTypesResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServerMediaTypesResponseDtoWithDefaults

`func NewServerMediaTypesResponseDtoWithDefaults() *ServerMediaTypesResponseDto`

NewServerMediaTypesResponseDtoWithDefaults instantiates a new ServerMediaTypesResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImage

`func (o *ServerMediaTypesResponseDto) GetImage() []string`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *ServerMediaTypesResponseDto) GetImageOk() (*[]string, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *ServerMediaTypesResponseDto) SetImage(v []string)`

SetImage sets Image field to given value.


### GetSidecar

`func (o *ServerMediaTypesResponseDto) GetSidecar() []string`

GetSidecar returns the Sidecar field if non-nil, zero value otherwise.

### GetSidecarOk

`func (o *ServerMediaTypesResponseDto) GetSidecarOk() (*[]string, bool)`

GetSidecarOk returns a tuple with the Sidecar field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSidecar

`func (o *ServerMediaTypesResponseDto) SetSidecar(v []string)`

SetSidecar sets Sidecar field to given value.


### GetVideo

`func (o *ServerMediaTypesResponseDto) GetVideo() []string`

GetVideo returns the Video field if non-nil, zero value otherwise.

### GetVideoOk

`func (o *ServerMediaTypesResponseDto) GetVideoOk() (*[]string, bool)`

GetVideoOk returns a tuple with the Video field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideo

`func (o *ServerMediaTypesResponseDto) SetVideo(v []string)`

SetVideo sets Video field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


