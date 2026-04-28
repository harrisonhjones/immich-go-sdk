# ServerAboutResponseDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Build** | Pointer to **string** | Build identifier | [optional] 
**BuildImage** | Pointer to **string** | Build image name | [optional] 
**BuildImageUrl** | Pointer to **string** | Build image URL | [optional] 
**BuildUrl** | Pointer to **string** | Build URL | [optional] 
**Exiftool** | Pointer to **string** | ExifTool version | [optional] 
**Ffmpeg** | Pointer to **string** | FFmpeg version | [optional] 
**Imagemagick** | Pointer to **string** | ImageMagick version | [optional] 
**Libvips** | Pointer to **string** | libvips version | [optional] 
**Licensed** | **bool** | Whether the server is licensed | 
**Nodejs** | Pointer to **string** | Node.js version | [optional] 
**Repository** | Pointer to **string** | Repository name | [optional] 
**RepositoryUrl** | Pointer to **string** | Repository URL | [optional] 
**SourceCommit** | Pointer to **string** | Source commit hash | [optional] 
**SourceRef** | Pointer to **string** | Source reference (branch/tag) | [optional] 
**SourceUrl** | Pointer to **string** | Source URL | [optional] 
**ThirdPartyBugFeatureUrl** | Pointer to **string** | Third-party bug/feature URL | [optional] 
**ThirdPartyDocumentationUrl** | Pointer to **string** | Third-party documentation URL | [optional] 
**ThirdPartySourceUrl** | Pointer to **string** | Third-party source URL | [optional] 
**ThirdPartySupportUrl** | Pointer to **string** | Third-party support URL | [optional] 
**Version** | **string** | Server version | 
**VersionUrl** | **string** | URL to version information | 

## Methods

### NewServerAboutResponseDto

`func NewServerAboutResponseDto(licensed bool, version string, versionUrl string, ) *ServerAboutResponseDto`

NewServerAboutResponseDto instantiates a new ServerAboutResponseDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServerAboutResponseDtoWithDefaults

`func NewServerAboutResponseDtoWithDefaults() *ServerAboutResponseDto`

NewServerAboutResponseDtoWithDefaults instantiates a new ServerAboutResponseDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBuild

`func (o *ServerAboutResponseDto) GetBuild() string`

GetBuild returns the Build field if non-nil, zero value otherwise.

### GetBuildOk

`func (o *ServerAboutResponseDto) GetBuildOk() (*string, bool)`

GetBuildOk returns a tuple with the Build field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuild

`func (o *ServerAboutResponseDto) SetBuild(v string)`

SetBuild sets Build field to given value.

### HasBuild

`func (o *ServerAboutResponseDto) HasBuild() bool`

HasBuild returns a boolean if a field has been set.

### GetBuildImage

`func (o *ServerAboutResponseDto) GetBuildImage() string`

GetBuildImage returns the BuildImage field if non-nil, zero value otherwise.

### GetBuildImageOk

`func (o *ServerAboutResponseDto) GetBuildImageOk() (*string, bool)`

GetBuildImageOk returns a tuple with the BuildImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildImage

`func (o *ServerAboutResponseDto) SetBuildImage(v string)`

SetBuildImage sets BuildImage field to given value.

### HasBuildImage

`func (o *ServerAboutResponseDto) HasBuildImage() bool`

HasBuildImage returns a boolean if a field has been set.

### GetBuildImageUrl

`func (o *ServerAboutResponseDto) GetBuildImageUrl() string`

GetBuildImageUrl returns the BuildImageUrl field if non-nil, zero value otherwise.

### GetBuildImageUrlOk

`func (o *ServerAboutResponseDto) GetBuildImageUrlOk() (*string, bool)`

GetBuildImageUrlOk returns a tuple with the BuildImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildImageUrl

`func (o *ServerAboutResponseDto) SetBuildImageUrl(v string)`

SetBuildImageUrl sets BuildImageUrl field to given value.

### HasBuildImageUrl

`func (o *ServerAboutResponseDto) HasBuildImageUrl() bool`

HasBuildImageUrl returns a boolean if a field has been set.

### GetBuildUrl

`func (o *ServerAboutResponseDto) GetBuildUrl() string`

GetBuildUrl returns the BuildUrl field if non-nil, zero value otherwise.

### GetBuildUrlOk

`func (o *ServerAboutResponseDto) GetBuildUrlOk() (*string, bool)`

GetBuildUrlOk returns a tuple with the BuildUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuildUrl

`func (o *ServerAboutResponseDto) SetBuildUrl(v string)`

SetBuildUrl sets BuildUrl field to given value.

### HasBuildUrl

`func (o *ServerAboutResponseDto) HasBuildUrl() bool`

HasBuildUrl returns a boolean if a field has been set.

### GetExiftool

`func (o *ServerAboutResponseDto) GetExiftool() string`

GetExiftool returns the Exiftool field if non-nil, zero value otherwise.

### GetExiftoolOk

`func (o *ServerAboutResponseDto) GetExiftoolOk() (*string, bool)`

GetExiftoolOk returns a tuple with the Exiftool field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExiftool

`func (o *ServerAboutResponseDto) SetExiftool(v string)`

SetExiftool sets Exiftool field to given value.

### HasExiftool

`func (o *ServerAboutResponseDto) HasExiftool() bool`

HasExiftool returns a boolean if a field has been set.

### GetFfmpeg

`func (o *ServerAboutResponseDto) GetFfmpeg() string`

GetFfmpeg returns the Ffmpeg field if non-nil, zero value otherwise.

### GetFfmpegOk

`func (o *ServerAboutResponseDto) GetFfmpegOk() (*string, bool)`

GetFfmpegOk returns a tuple with the Ffmpeg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFfmpeg

`func (o *ServerAboutResponseDto) SetFfmpeg(v string)`

SetFfmpeg sets Ffmpeg field to given value.

### HasFfmpeg

`func (o *ServerAboutResponseDto) HasFfmpeg() bool`

HasFfmpeg returns a boolean if a field has been set.

### GetImagemagick

`func (o *ServerAboutResponseDto) GetImagemagick() string`

GetImagemagick returns the Imagemagick field if non-nil, zero value otherwise.

### GetImagemagickOk

`func (o *ServerAboutResponseDto) GetImagemagickOk() (*string, bool)`

GetImagemagickOk returns a tuple with the Imagemagick field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagemagick

`func (o *ServerAboutResponseDto) SetImagemagick(v string)`

SetImagemagick sets Imagemagick field to given value.

### HasImagemagick

`func (o *ServerAboutResponseDto) HasImagemagick() bool`

HasImagemagick returns a boolean if a field has been set.

### GetLibvips

`func (o *ServerAboutResponseDto) GetLibvips() string`

GetLibvips returns the Libvips field if non-nil, zero value otherwise.

### GetLibvipsOk

`func (o *ServerAboutResponseDto) GetLibvipsOk() (*string, bool)`

GetLibvipsOk returns a tuple with the Libvips field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLibvips

`func (o *ServerAboutResponseDto) SetLibvips(v string)`

SetLibvips sets Libvips field to given value.

### HasLibvips

`func (o *ServerAboutResponseDto) HasLibvips() bool`

HasLibvips returns a boolean if a field has been set.

### GetLicensed

`func (o *ServerAboutResponseDto) GetLicensed() bool`

GetLicensed returns the Licensed field if non-nil, zero value otherwise.

### GetLicensedOk

`func (o *ServerAboutResponseDto) GetLicensedOk() (*bool, bool)`

GetLicensedOk returns a tuple with the Licensed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLicensed

`func (o *ServerAboutResponseDto) SetLicensed(v bool)`

SetLicensed sets Licensed field to given value.


### GetNodejs

`func (o *ServerAboutResponseDto) GetNodejs() string`

GetNodejs returns the Nodejs field if non-nil, zero value otherwise.

### GetNodejsOk

`func (o *ServerAboutResponseDto) GetNodejsOk() (*string, bool)`

GetNodejsOk returns a tuple with the Nodejs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNodejs

`func (o *ServerAboutResponseDto) SetNodejs(v string)`

SetNodejs sets Nodejs field to given value.

### HasNodejs

`func (o *ServerAboutResponseDto) HasNodejs() bool`

HasNodejs returns a boolean if a field has been set.

### GetRepository

`func (o *ServerAboutResponseDto) GetRepository() string`

GetRepository returns the Repository field if non-nil, zero value otherwise.

### GetRepositoryOk

`func (o *ServerAboutResponseDto) GetRepositoryOk() (*string, bool)`

GetRepositoryOk returns a tuple with the Repository field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepository

`func (o *ServerAboutResponseDto) SetRepository(v string)`

SetRepository sets Repository field to given value.

### HasRepository

`func (o *ServerAboutResponseDto) HasRepository() bool`

HasRepository returns a boolean if a field has been set.

### GetRepositoryUrl

`func (o *ServerAboutResponseDto) GetRepositoryUrl() string`

GetRepositoryUrl returns the RepositoryUrl field if non-nil, zero value otherwise.

### GetRepositoryUrlOk

`func (o *ServerAboutResponseDto) GetRepositoryUrlOk() (*string, bool)`

GetRepositoryUrlOk returns a tuple with the RepositoryUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepositoryUrl

`func (o *ServerAboutResponseDto) SetRepositoryUrl(v string)`

SetRepositoryUrl sets RepositoryUrl field to given value.

### HasRepositoryUrl

`func (o *ServerAboutResponseDto) HasRepositoryUrl() bool`

HasRepositoryUrl returns a boolean if a field has been set.

### GetSourceCommit

`func (o *ServerAboutResponseDto) GetSourceCommit() string`

GetSourceCommit returns the SourceCommit field if non-nil, zero value otherwise.

### GetSourceCommitOk

`func (o *ServerAboutResponseDto) GetSourceCommitOk() (*string, bool)`

GetSourceCommitOk returns a tuple with the SourceCommit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceCommit

`func (o *ServerAboutResponseDto) SetSourceCommit(v string)`

SetSourceCommit sets SourceCommit field to given value.

### HasSourceCommit

`func (o *ServerAboutResponseDto) HasSourceCommit() bool`

HasSourceCommit returns a boolean if a field has been set.

### GetSourceRef

`func (o *ServerAboutResponseDto) GetSourceRef() string`

GetSourceRef returns the SourceRef field if non-nil, zero value otherwise.

### GetSourceRefOk

`func (o *ServerAboutResponseDto) GetSourceRefOk() (*string, bool)`

GetSourceRefOk returns a tuple with the SourceRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceRef

`func (o *ServerAboutResponseDto) SetSourceRef(v string)`

SetSourceRef sets SourceRef field to given value.

### HasSourceRef

`func (o *ServerAboutResponseDto) HasSourceRef() bool`

HasSourceRef returns a boolean if a field has been set.

### GetSourceUrl

`func (o *ServerAboutResponseDto) GetSourceUrl() string`

GetSourceUrl returns the SourceUrl field if non-nil, zero value otherwise.

### GetSourceUrlOk

`func (o *ServerAboutResponseDto) GetSourceUrlOk() (*string, bool)`

GetSourceUrlOk returns a tuple with the SourceUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceUrl

`func (o *ServerAboutResponseDto) SetSourceUrl(v string)`

SetSourceUrl sets SourceUrl field to given value.

### HasSourceUrl

`func (o *ServerAboutResponseDto) HasSourceUrl() bool`

HasSourceUrl returns a boolean if a field has been set.

### GetThirdPartyBugFeatureUrl

`func (o *ServerAboutResponseDto) GetThirdPartyBugFeatureUrl() string`

GetThirdPartyBugFeatureUrl returns the ThirdPartyBugFeatureUrl field if non-nil, zero value otherwise.

### GetThirdPartyBugFeatureUrlOk

`func (o *ServerAboutResponseDto) GetThirdPartyBugFeatureUrlOk() (*string, bool)`

GetThirdPartyBugFeatureUrlOk returns a tuple with the ThirdPartyBugFeatureUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdPartyBugFeatureUrl

`func (o *ServerAboutResponseDto) SetThirdPartyBugFeatureUrl(v string)`

SetThirdPartyBugFeatureUrl sets ThirdPartyBugFeatureUrl field to given value.

### HasThirdPartyBugFeatureUrl

`func (o *ServerAboutResponseDto) HasThirdPartyBugFeatureUrl() bool`

HasThirdPartyBugFeatureUrl returns a boolean if a field has been set.

### GetThirdPartyDocumentationUrl

`func (o *ServerAboutResponseDto) GetThirdPartyDocumentationUrl() string`

GetThirdPartyDocumentationUrl returns the ThirdPartyDocumentationUrl field if non-nil, zero value otherwise.

### GetThirdPartyDocumentationUrlOk

`func (o *ServerAboutResponseDto) GetThirdPartyDocumentationUrlOk() (*string, bool)`

GetThirdPartyDocumentationUrlOk returns a tuple with the ThirdPartyDocumentationUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdPartyDocumentationUrl

`func (o *ServerAboutResponseDto) SetThirdPartyDocumentationUrl(v string)`

SetThirdPartyDocumentationUrl sets ThirdPartyDocumentationUrl field to given value.

### HasThirdPartyDocumentationUrl

`func (o *ServerAboutResponseDto) HasThirdPartyDocumentationUrl() bool`

HasThirdPartyDocumentationUrl returns a boolean if a field has been set.

### GetThirdPartySourceUrl

`func (o *ServerAboutResponseDto) GetThirdPartySourceUrl() string`

GetThirdPartySourceUrl returns the ThirdPartySourceUrl field if non-nil, zero value otherwise.

### GetThirdPartySourceUrlOk

`func (o *ServerAboutResponseDto) GetThirdPartySourceUrlOk() (*string, bool)`

GetThirdPartySourceUrlOk returns a tuple with the ThirdPartySourceUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdPartySourceUrl

`func (o *ServerAboutResponseDto) SetThirdPartySourceUrl(v string)`

SetThirdPartySourceUrl sets ThirdPartySourceUrl field to given value.

### HasThirdPartySourceUrl

`func (o *ServerAboutResponseDto) HasThirdPartySourceUrl() bool`

HasThirdPartySourceUrl returns a boolean if a field has been set.

### GetThirdPartySupportUrl

`func (o *ServerAboutResponseDto) GetThirdPartySupportUrl() string`

GetThirdPartySupportUrl returns the ThirdPartySupportUrl field if non-nil, zero value otherwise.

### GetThirdPartySupportUrlOk

`func (o *ServerAboutResponseDto) GetThirdPartySupportUrlOk() (*string, bool)`

GetThirdPartySupportUrlOk returns a tuple with the ThirdPartySupportUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThirdPartySupportUrl

`func (o *ServerAboutResponseDto) SetThirdPartySupportUrl(v string)`

SetThirdPartySupportUrl sets ThirdPartySupportUrl field to given value.

### HasThirdPartySupportUrl

`func (o *ServerAboutResponseDto) HasThirdPartySupportUrl() bool`

HasThirdPartySupportUrl returns a boolean if a field has been set.

### GetVersion

`func (o *ServerAboutResponseDto) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *ServerAboutResponseDto) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *ServerAboutResponseDto) SetVersion(v string)`

SetVersion sets Version field to given value.


### GetVersionUrl

`func (o *ServerAboutResponseDto) GetVersionUrl() string`

GetVersionUrl returns the VersionUrl field if non-nil, zero value otherwise.

### GetVersionUrlOk

`func (o *ServerAboutResponseDto) GetVersionUrlOk() (*string, bool)`

GetVersionUrlOk returns a tuple with the VersionUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersionUrl

`func (o *ServerAboutResponseDto) SetVersionUrl(v string)`

SetVersionUrl sets VersionUrl field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


