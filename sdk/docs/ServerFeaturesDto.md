# ServerFeaturesDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ConfigFile** | **bool** | Whether config file is available | 
**DuplicateDetection** | **bool** | Whether duplicate detection is enabled | 
**Email** | **bool** | Whether email notifications are enabled | 
**FacialRecognition** | **bool** | Whether facial recognition is enabled | 
**ImportFaces** | **bool** | Whether face import is enabled | 
**Map** | **bool** | Whether map feature is enabled | 
**Oauth** | **bool** | Whether OAuth is enabled | 
**OauthAutoLaunch** | **bool** | Whether OAuth auto-launch is enabled | 
**Ocr** | **bool** | Whether OCR is enabled | 
**PasswordLogin** | **bool** | Whether password login is enabled | 
**ReverseGeocoding** | **bool** | Whether reverse geocoding is enabled | 
**Search** | **bool** | Whether search is enabled | 
**Sidecar** | **bool** | Whether sidecar files are supported | 
**SmartSearch** | **bool** | Whether smart search is enabled | 
**Trash** | **bool** | Whether trash feature is enabled | 

## Methods

### NewServerFeaturesDto

`func NewServerFeaturesDto(configFile bool, duplicateDetection bool, email bool, facialRecognition bool, importFaces bool, map_ bool, oauth bool, oauthAutoLaunch bool, ocr bool, passwordLogin bool, reverseGeocoding bool, search bool, sidecar bool, smartSearch bool, trash bool, ) *ServerFeaturesDto`

NewServerFeaturesDto instantiates a new ServerFeaturesDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServerFeaturesDtoWithDefaults

`func NewServerFeaturesDtoWithDefaults() *ServerFeaturesDto`

NewServerFeaturesDtoWithDefaults instantiates a new ServerFeaturesDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetConfigFile

`func (o *ServerFeaturesDto) GetConfigFile() bool`

GetConfigFile returns the ConfigFile field if non-nil, zero value otherwise.

### GetConfigFileOk

`func (o *ServerFeaturesDto) GetConfigFileOk() (*bool, bool)`

GetConfigFileOk returns a tuple with the ConfigFile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigFile

`func (o *ServerFeaturesDto) SetConfigFile(v bool)`

SetConfigFile sets ConfigFile field to given value.


### GetDuplicateDetection

`func (o *ServerFeaturesDto) GetDuplicateDetection() bool`

GetDuplicateDetection returns the DuplicateDetection field if non-nil, zero value otherwise.

### GetDuplicateDetectionOk

`func (o *ServerFeaturesDto) GetDuplicateDetectionOk() (*bool, bool)`

GetDuplicateDetectionOk returns a tuple with the DuplicateDetection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDuplicateDetection

`func (o *ServerFeaturesDto) SetDuplicateDetection(v bool)`

SetDuplicateDetection sets DuplicateDetection field to given value.


### GetEmail

`func (o *ServerFeaturesDto) GetEmail() bool`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *ServerFeaturesDto) GetEmailOk() (*bool, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *ServerFeaturesDto) SetEmail(v bool)`

SetEmail sets Email field to given value.


### GetFacialRecognition

`func (o *ServerFeaturesDto) GetFacialRecognition() bool`

GetFacialRecognition returns the FacialRecognition field if non-nil, zero value otherwise.

### GetFacialRecognitionOk

`func (o *ServerFeaturesDto) GetFacialRecognitionOk() (*bool, bool)`

GetFacialRecognitionOk returns a tuple with the FacialRecognition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFacialRecognition

`func (o *ServerFeaturesDto) SetFacialRecognition(v bool)`

SetFacialRecognition sets FacialRecognition field to given value.


### GetImportFaces

`func (o *ServerFeaturesDto) GetImportFaces() bool`

GetImportFaces returns the ImportFaces field if non-nil, zero value otherwise.

### GetImportFacesOk

`func (o *ServerFeaturesDto) GetImportFacesOk() (*bool, bool)`

GetImportFacesOk returns a tuple with the ImportFaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportFaces

`func (o *ServerFeaturesDto) SetImportFaces(v bool)`

SetImportFaces sets ImportFaces field to given value.


### GetMap

`func (o *ServerFeaturesDto) GetMap() bool`

GetMap returns the Map field if non-nil, zero value otherwise.

### GetMapOk

`func (o *ServerFeaturesDto) GetMapOk() (*bool, bool)`

GetMapOk returns a tuple with the Map field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMap

`func (o *ServerFeaturesDto) SetMap(v bool)`

SetMap sets Map field to given value.


### GetOauth

`func (o *ServerFeaturesDto) GetOauth() bool`

GetOauth returns the Oauth field if non-nil, zero value otherwise.

### GetOauthOk

`func (o *ServerFeaturesDto) GetOauthOk() (*bool, bool)`

GetOauthOk returns a tuple with the Oauth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOauth

`func (o *ServerFeaturesDto) SetOauth(v bool)`

SetOauth sets Oauth field to given value.


### GetOauthAutoLaunch

`func (o *ServerFeaturesDto) GetOauthAutoLaunch() bool`

GetOauthAutoLaunch returns the OauthAutoLaunch field if non-nil, zero value otherwise.

### GetOauthAutoLaunchOk

`func (o *ServerFeaturesDto) GetOauthAutoLaunchOk() (*bool, bool)`

GetOauthAutoLaunchOk returns a tuple with the OauthAutoLaunch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOauthAutoLaunch

`func (o *ServerFeaturesDto) SetOauthAutoLaunch(v bool)`

SetOauthAutoLaunch sets OauthAutoLaunch field to given value.


### GetOcr

`func (o *ServerFeaturesDto) GetOcr() bool`

GetOcr returns the Ocr field if non-nil, zero value otherwise.

### GetOcrOk

`func (o *ServerFeaturesDto) GetOcrOk() (*bool, bool)`

GetOcrOk returns a tuple with the Ocr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOcr

`func (o *ServerFeaturesDto) SetOcr(v bool)`

SetOcr sets Ocr field to given value.


### GetPasswordLogin

`func (o *ServerFeaturesDto) GetPasswordLogin() bool`

GetPasswordLogin returns the PasswordLogin field if non-nil, zero value otherwise.

### GetPasswordLoginOk

`func (o *ServerFeaturesDto) GetPasswordLoginOk() (*bool, bool)`

GetPasswordLoginOk returns a tuple with the PasswordLogin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasswordLogin

`func (o *ServerFeaturesDto) SetPasswordLogin(v bool)`

SetPasswordLogin sets PasswordLogin field to given value.


### GetReverseGeocoding

`func (o *ServerFeaturesDto) GetReverseGeocoding() bool`

GetReverseGeocoding returns the ReverseGeocoding field if non-nil, zero value otherwise.

### GetReverseGeocodingOk

`func (o *ServerFeaturesDto) GetReverseGeocodingOk() (*bool, bool)`

GetReverseGeocodingOk returns a tuple with the ReverseGeocoding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReverseGeocoding

`func (o *ServerFeaturesDto) SetReverseGeocoding(v bool)`

SetReverseGeocoding sets ReverseGeocoding field to given value.


### GetSearch

`func (o *ServerFeaturesDto) GetSearch() bool`

GetSearch returns the Search field if non-nil, zero value otherwise.

### GetSearchOk

`func (o *ServerFeaturesDto) GetSearchOk() (*bool, bool)`

GetSearchOk returns a tuple with the Search field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearch

`func (o *ServerFeaturesDto) SetSearch(v bool)`

SetSearch sets Search field to given value.


### GetSidecar

`func (o *ServerFeaturesDto) GetSidecar() bool`

GetSidecar returns the Sidecar field if non-nil, zero value otherwise.

### GetSidecarOk

`func (o *ServerFeaturesDto) GetSidecarOk() (*bool, bool)`

GetSidecarOk returns a tuple with the Sidecar field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSidecar

`func (o *ServerFeaturesDto) SetSidecar(v bool)`

SetSidecar sets Sidecar field to given value.


### GetSmartSearch

`func (o *ServerFeaturesDto) GetSmartSearch() bool`

GetSmartSearch returns the SmartSearch field if non-nil, zero value otherwise.

### GetSmartSearchOk

`func (o *ServerFeaturesDto) GetSmartSearchOk() (*bool, bool)`

GetSmartSearchOk returns a tuple with the SmartSearch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmartSearch

`func (o *ServerFeaturesDto) SetSmartSearch(v bool)`

SetSmartSearch sets SmartSearch field to given value.


### GetTrash

`func (o *ServerFeaturesDto) GetTrash() bool`

GetTrash returns the Trash field if non-nil, zero value otherwise.

### GetTrashOk

`func (o *ServerFeaturesDto) GetTrashOk() (*bool, bool)`

GetTrashOk returns a tuple with the Trash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrash

`func (o *ServerFeaturesDto) SetTrash(v bool)`

SetTrash sets Trash field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


