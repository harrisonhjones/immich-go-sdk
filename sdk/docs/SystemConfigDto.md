# SystemConfigDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Backup** | [**SystemConfigBackupsDto**](SystemConfigBackupsDto.md) |  | 
**Ffmpeg** | [**SystemConfigFFmpegDto**](SystemConfigFFmpegDto.md) |  | 
**Image** | [**SystemConfigImageDto**](SystemConfigImageDto.md) |  | 
**Job** | [**SystemConfigJobDto**](SystemConfigJobDto.md) |  | 
**Library** | [**SystemConfigLibraryDto**](SystemConfigLibraryDto.md) |  | 
**Logging** | [**SystemConfigLoggingDto**](SystemConfigLoggingDto.md) |  | 
**MachineLearning** | [**SystemConfigMachineLearningDto**](SystemConfigMachineLearningDto.md) |  | 
**Map** | [**SystemConfigMapDto**](SystemConfigMapDto.md) |  | 
**Metadata** | [**SystemConfigMetadataDto**](SystemConfigMetadataDto.md) |  | 
**NewVersionCheck** | [**SystemConfigNewVersionCheckDto**](SystemConfigNewVersionCheckDto.md) |  | 
**NightlyTasks** | [**SystemConfigNightlyTasksDto**](SystemConfigNightlyTasksDto.md) |  | 
**Notifications** | [**SystemConfigNotificationsDto**](SystemConfigNotificationsDto.md) |  | 
**Oauth** | [**SystemConfigOAuthDto**](SystemConfigOAuthDto.md) |  | 
**PasswordLogin** | [**SystemConfigPasswordLoginDto**](SystemConfigPasswordLoginDto.md) |  | 
**ReverseGeocoding** | [**SystemConfigReverseGeocodingDto**](SystemConfigReverseGeocodingDto.md) |  | 
**Server** | [**SystemConfigServerDto**](SystemConfigServerDto.md) |  | 
**StorageTemplate** | [**SystemConfigStorageTemplateDto**](SystemConfigStorageTemplateDto.md) |  | 
**Templates** | [**SystemConfigTemplatesDto**](SystemConfigTemplatesDto.md) |  | 
**Theme** | [**SystemConfigThemeDto**](SystemConfigThemeDto.md) |  | 
**Trash** | [**SystemConfigTrashDto**](SystemConfigTrashDto.md) |  | 
**User** | [**SystemConfigUserDto**](SystemConfigUserDto.md) |  | 

## Methods

### NewSystemConfigDto

`func NewSystemConfigDto(backup SystemConfigBackupsDto, ffmpeg SystemConfigFFmpegDto, image SystemConfigImageDto, job SystemConfigJobDto, library SystemConfigLibraryDto, logging SystemConfigLoggingDto, machineLearning SystemConfigMachineLearningDto, map_ SystemConfigMapDto, metadata SystemConfigMetadataDto, newVersionCheck SystemConfigNewVersionCheckDto, nightlyTasks SystemConfigNightlyTasksDto, notifications SystemConfigNotificationsDto, oauth SystemConfigOAuthDto, passwordLogin SystemConfigPasswordLoginDto, reverseGeocoding SystemConfigReverseGeocodingDto, server SystemConfigServerDto, storageTemplate SystemConfigStorageTemplateDto, templates SystemConfigTemplatesDto, theme SystemConfigThemeDto, trash SystemConfigTrashDto, user SystemConfigUserDto, ) *SystemConfigDto`

NewSystemConfigDto instantiates a new SystemConfigDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigDtoWithDefaults

`func NewSystemConfigDtoWithDefaults() *SystemConfigDto`

NewSystemConfigDtoWithDefaults instantiates a new SystemConfigDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBackup

`func (o *SystemConfigDto) GetBackup() SystemConfigBackupsDto`

GetBackup returns the Backup field if non-nil, zero value otherwise.

### GetBackupOk

`func (o *SystemConfigDto) GetBackupOk() (*SystemConfigBackupsDto, bool)`

GetBackupOk returns a tuple with the Backup field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackup

`func (o *SystemConfigDto) SetBackup(v SystemConfigBackupsDto)`

SetBackup sets Backup field to given value.


### GetFfmpeg

`func (o *SystemConfigDto) GetFfmpeg() SystemConfigFFmpegDto`

GetFfmpeg returns the Ffmpeg field if non-nil, zero value otherwise.

### GetFfmpegOk

`func (o *SystemConfigDto) GetFfmpegOk() (*SystemConfigFFmpegDto, bool)`

GetFfmpegOk returns a tuple with the Ffmpeg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFfmpeg

`func (o *SystemConfigDto) SetFfmpeg(v SystemConfigFFmpegDto)`

SetFfmpeg sets Ffmpeg field to given value.


### GetImage

`func (o *SystemConfigDto) GetImage() SystemConfigImageDto`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *SystemConfigDto) GetImageOk() (*SystemConfigImageDto, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *SystemConfigDto) SetImage(v SystemConfigImageDto)`

SetImage sets Image field to given value.


### GetJob

`func (o *SystemConfigDto) GetJob() SystemConfigJobDto`

GetJob returns the Job field if non-nil, zero value otherwise.

### GetJobOk

`func (o *SystemConfigDto) GetJobOk() (*SystemConfigJobDto, bool)`

GetJobOk returns a tuple with the Job field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJob

`func (o *SystemConfigDto) SetJob(v SystemConfigJobDto)`

SetJob sets Job field to given value.


### GetLibrary

`func (o *SystemConfigDto) GetLibrary() SystemConfigLibraryDto`

GetLibrary returns the Library field if non-nil, zero value otherwise.

### GetLibraryOk

`func (o *SystemConfigDto) GetLibraryOk() (*SystemConfigLibraryDto, bool)`

GetLibraryOk returns a tuple with the Library field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLibrary

`func (o *SystemConfigDto) SetLibrary(v SystemConfigLibraryDto)`

SetLibrary sets Library field to given value.


### GetLogging

`func (o *SystemConfigDto) GetLogging() SystemConfigLoggingDto`

GetLogging returns the Logging field if non-nil, zero value otherwise.

### GetLoggingOk

`func (o *SystemConfigDto) GetLoggingOk() (*SystemConfigLoggingDto, bool)`

GetLoggingOk returns a tuple with the Logging field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLogging

`func (o *SystemConfigDto) SetLogging(v SystemConfigLoggingDto)`

SetLogging sets Logging field to given value.


### GetMachineLearning

`func (o *SystemConfigDto) GetMachineLearning() SystemConfigMachineLearningDto`

GetMachineLearning returns the MachineLearning field if non-nil, zero value otherwise.

### GetMachineLearningOk

`func (o *SystemConfigDto) GetMachineLearningOk() (*SystemConfigMachineLearningDto, bool)`

GetMachineLearningOk returns a tuple with the MachineLearning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMachineLearning

`func (o *SystemConfigDto) SetMachineLearning(v SystemConfigMachineLearningDto)`

SetMachineLearning sets MachineLearning field to given value.


### GetMap

`func (o *SystemConfigDto) GetMap() SystemConfigMapDto`

GetMap returns the Map field if non-nil, zero value otherwise.

### GetMapOk

`func (o *SystemConfigDto) GetMapOk() (*SystemConfigMapDto, bool)`

GetMapOk returns a tuple with the Map field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMap

`func (o *SystemConfigDto) SetMap(v SystemConfigMapDto)`

SetMap sets Map field to given value.


### GetMetadata

`func (o *SystemConfigDto) GetMetadata() SystemConfigMetadataDto`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *SystemConfigDto) GetMetadataOk() (*SystemConfigMetadataDto, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *SystemConfigDto) SetMetadata(v SystemConfigMetadataDto)`

SetMetadata sets Metadata field to given value.


### GetNewVersionCheck

`func (o *SystemConfigDto) GetNewVersionCheck() SystemConfigNewVersionCheckDto`

GetNewVersionCheck returns the NewVersionCheck field if non-nil, zero value otherwise.

### GetNewVersionCheckOk

`func (o *SystemConfigDto) GetNewVersionCheckOk() (*SystemConfigNewVersionCheckDto, bool)`

GetNewVersionCheckOk returns a tuple with the NewVersionCheck field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNewVersionCheck

`func (o *SystemConfigDto) SetNewVersionCheck(v SystemConfigNewVersionCheckDto)`

SetNewVersionCheck sets NewVersionCheck field to given value.


### GetNightlyTasks

`func (o *SystemConfigDto) GetNightlyTasks() SystemConfigNightlyTasksDto`

GetNightlyTasks returns the NightlyTasks field if non-nil, zero value otherwise.

### GetNightlyTasksOk

`func (o *SystemConfigDto) GetNightlyTasksOk() (*SystemConfigNightlyTasksDto, bool)`

GetNightlyTasksOk returns a tuple with the NightlyTasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNightlyTasks

`func (o *SystemConfigDto) SetNightlyTasks(v SystemConfigNightlyTasksDto)`

SetNightlyTasks sets NightlyTasks field to given value.


### GetNotifications

`func (o *SystemConfigDto) GetNotifications() SystemConfigNotificationsDto`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *SystemConfigDto) GetNotificationsOk() (*SystemConfigNotificationsDto, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *SystemConfigDto) SetNotifications(v SystemConfigNotificationsDto)`

SetNotifications sets Notifications field to given value.


### GetOauth

`func (o *SystemConfigDto) GetOauth() SystemConfigOAuthDto`

GetOauth returns the Oauth field if non-nil, zero value otherwise.

### GetOauthOk

`func (o *SystemConfigDto) GetOauthOk() (*SystemConfigOAuthDto, bool)`

GetOauthOk returns a tuple with the Oauth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOauth

`func (o *SystemConfigDto) SetOauth(v SystemConfigOAuthDto)`

SetOauth sets Oauth field to given value.


### GetPasswordLogin

`func (o *SystemConfigDto) GetPasswordLogin() SystemConfigPasswordLoginDto`

GetPasswordLogin returns the PasswordLogin field if non-nil, zero value otherwise.

### GetPasswordLoginOk

`func (o *SystemConfigDto) GetPasswordLoginOk() (*SystemConfigPasswordLoginDto, bool)`

GetPasswordLoginOk returns a tuple with the PasswordLogin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasswordLogin

`func (o *SystemConfigDto) SetPasswordLogin(v SystemConfigPasswordLoginDto)`

SetPasswordLogin sets PasswordLogin field to given value.


### GetReverseGeocoding

`func (o *SystemConfigDto) GetReverseGeocoding() SystemConfigReverseGeocodingDto`

GetReverseGeocoding returns the ReverseGeocoding field if non-nil, zero value otherwise.

### GetReverseGeocodingOk

`func (o *SystemConfigDto) GetReverseGeocodingOk() (*SystemConfigReverseGeocodingDto, bool)`

GetReverseGeocodingOk returns a tuple with the ReverseGeocoding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReverseGeocoding

`func (o *SystemConfigDto) SetReverseGeocoding(v SystemConfigReverseGeocodingDto)`

SetReverseGeocoding sets ReverseGeocoding field to given value.


### GetServer

`func (o *SystemConfigDto) GetServer() SystemConfigServerDto`

GetServer returns the Server field if non-nil, zero value otherwise.

### GetServerOk

`func (o *SystemConfigDto) GetServerOk() (*SystemConfigServerDto, bool)`

GetServerOk returns a tuple with the Server field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServer

`func (o *SystemConfigDto) SetServer(v SystemConfigServerDto)`

SetServer sets Server field to given value.


### GetStorageTemplate

`func (o *SystemConfigDto) GetStorageTemplate() SystemConfigStorageTemplateDto`

GetStorageTemplate returns the StorageTemplate field if non-nil, zero value otherwise.

### GetStorageTemplateOk

`func (o *SystemConfigDto) GetStorageTemplateOk() (*SystemConfigStorageTemplateDto, bool)`

GetStorageTemplateOk returns a tuple with the StorageTemplate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageTemplate

`func (o *SystemConfigDto) SetStorageTemplate(v SystemConfigStorageTemplateDto)`

SetStorageTemplate sets StorageTemplate field to given value.


### GetTemplates

`func (o *SystemConfigDto) GetTemplates() SystemConfigTemplatesDto`

GetTemplates returns the Templates field if non-nil, zero value otherwise.

### GetTemplatesOk

`func (o *SystemConfigDto) GetTemplatesOk() (*SystemConfigTemplatesDto, bool)`

GetTemplatesOk returns a tuple with the Templates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplates

`func (o *SystemConfigDto) SetTemplates(v SystemConfigTemplatesDto)`

SetTemplates sets Templates field to given value.


### GetTheme

`func (o *SystemConfigDto) GetTheme() SystemConfigThemeDto`

GetTheme returns the Theme field if non-nil, zero value otherwise.

### GetThemeOk

`func (o *SystemConfigDto) GetThemeOk() (*SystemConfigThemeDto, bool)`

GetThemeOk returns a tuple with the Theme field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTheme

`func (o *SystemConfigDto) SetTheme(v SystemConfigThemeDto)`

SetTheme sets Theme field to given value.


### GetTrash

`func (o *SystemConfigDto) GetTrash() SystemConfigTrashDto`

GetTrash returns the Trash field if non-nil, zero value otherwise.

### GetTrashOk

`func (o *SystemConfigDto) GetTrashOk() (*SystemConfigTrashDto, bool)`

GetTrashOk returns a tuple with the Trash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrash

`func (o *SystemConfigDto) SetTrash(v SystemConfigTrashDto)`

SetTrash sets Trash field to given value.


### GetUser

`func (o *SystemConfigDto) GetUser() SystemConfigUserDto`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *SystemConfigDto) GetUserOk() (*SystemConfigUserDto, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *SystemConfigDto) SetUser(v SystemConfigUserDto)`

SetUser sets User field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


