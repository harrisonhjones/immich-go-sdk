# \SystemConfigAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetConfig**](SystemConfigAPI.md#GetConfig) | **Get** /system-config | Get system configuration
[**GetConfigDefaults**](SystemConfigAPI.md#GetConfigDefaults) | **Get** /system-config/defaults | Get system configuration defaults
[**GetStorageTemplateOptions**](SystemConfigAPI.md#GetStorageTemplateOptions) | **Get** /system-config/storage-template-options | Get storage template options
[**UpdateConfig**](SystemConfigAPI.md#UpdateConfig) | **Put** /system-config | Update system configuration



## GetConfig

> SystemConfigDto GetConfig(ctx).Execute()

Get system configuration



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SystemConfigAPI.GetConfig(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SystemConfigAPI.GetConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetConfig`: SystemConfigDto
	fmt.Fprintf(os.Stdout, "Response from `SystemConfigAPI.GetConfig`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetConfigRequest struct via the builder pattern


### Return type

[**SystemConfigDto**](SystemConfigDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetConfigDefaults

> SystemConfigDto GetConfigDefaults(ctx).Execute()

Get system configuration defaults



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SystemConfigAPI.GetConfigDefaults(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SystemConfigAPI.GetConfigDefaults``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetConfigDefaults`: SystemConfigDto
	fmt.Fprintf(os.Stdout, "Response from `SystemConfigAPI.GetConfigDefaults`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetConfigDefaultsRequest struct via the builder pattern


### Return type

[**SystemConfigDto**](SystemConfigDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetStorageTemplateOptions

> SystemConfigTemplateStorageOptionDto GetStorageTemplateOptions(ctx).Execute()

Get storage template options



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SystemConfigAPI.GetStorageTemplateOptions(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SystemConfigAPI.GetStorageTemplateOptions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetStorageTemplateOptions`: SystemConfigTemplateStorageOptionDto
	fmt.Fprintf(os.Stdout, "Response from `SystemConfigAPI.GetStorageTemplateOptions`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetStorageTemplateOptionsRequest struct via the builder pattern


### Return type

[**SystemConfigTemplateStorageOptionDto**](SystemConfigTemplateStorageOptionDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateConfig

> SystemConfigDto UpdateConfig(ctx).SystemConfigDto(systemConfigDto).Execute()

Update system configuration



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	systemConfigDto := *openapiclient.NewSystemConfigDto(*openapiclient.NewSystemConfigBackupsDto(*openapiclient.NewDatabaseBackupConfig("CronExpression_example", false, float32(123))), *openapiclient.NewSystemConfigFFmpegDto(openapiclient.TranscodeHWAccel("nvenc"), false, []openapiclient.AudioCodec{openapiclient.AudioCodec("mp3")}, []openapiclient.VideoContainer{openapiclient.VideoContainer("mov")}, []openapiclient.VideoCodec{openapiclient.VideoCodec("h264")}, int32(123), openapiclient.CQMode("auto"), int32(123), int32(123), "MaxBitrate_example", "PreferredHwDevice_example", "Preset_example", int32(123), openapiclient.AudioCodec("mp3"), "TargetResolution_example", openapiclient.VideoCodec("h264"), false, int32(123), openapiclient.ToneMapping("hable"), openapiclient.TranscodePolicy("all"), false), *openapiclient.NewSystemConfigImageDto(openapiclient.Colorspace("srgb"), false, *openapiclient.NewSystemConfigGeneratedFullsizeImageDto(false, openapiclient.ImageFormat("jpeg"), int32(123)), *openapiclient.NewSystemConfigGeneratedImageDto(openapiclient.ImageFormat("jpeg"), int32(123), int32(123)), *openapiclient.NewSystemConfigGeneratedImageDto(openapiclient.ImageFormat("jpeg"), int32(123), int32(123))), *openapiclient.NewSystemConfigJobDto(*openapiclient.NewJobSettingsDto(int32(123)), *openapiclient.NewJobSettingsDto(int32(123)), *openapiclient.NewJobSettingsDto(int32(123)), *openapiclient.NewJobSettingsDto(int32(123)), *openapiclient.NewJobSettingsDto(int32(123)), *openapiclient.NewJobSettingsDto(int32(123)), *openapiclient.NewJobSettingsDto(int32(123)), *openapiclient.NewJobSettingsDto(int32(123)), *openapiclient.NewJobSettingsDto(int32(123)), *openapiclient.NewJobSettingsDto(int32(123)), *openapiclient.NewJobSettingsDto(int32(123)), *openapiclient.NewJobSettingsDto(int32(123)), *openapiclient.NewJobSettingsDto(int32(123)), *openapiclient.NewJobSettingsDto(int32(123))), *openapiclient.NewSystemConfigLibraryDto(*openapiclient.NewSystemConfigLibraryScanDto("CronExpression_example", false), *openapiclient.NewSystemConfigLibraryWatchDto(false)), *openapiclient.NewSystemConfigLoggingDto(false, openapiclient.LogLevel("verbose")), *openapiclient.NewSystemConfigMachineLearningDto(*openapiclient.NewMachineLearningAvailabilityChecksDto(false, float32(123), float32(123)), *openapiclient.NewCLIPConfig(false, "ModelName_example"), *openapiclient.NewDuplicateDetectionConfig(false, float64(123)), false, *openapiclient.NewFacialRecognitionConfig(false, float64(123), int32(123), float64(123), "ModelName_example"), *openapiclient.NewOcrConfig(false, int32(123), float64(123), float64(123), "ModelName_example"), []string{"Urls_example"}), *openapiclient.NewSystemConfigMapDto("DarkStyle_example", false, "LightStyle_example"), *openapiclient.NewSystemConfigMetadataDto(*openapiclient.NewSystemConfigFacesDto(false)), *openapiclient.NewSystemConfigNewVersionCheckDto(false), *openapiclient.NewSystemConfigNightlyTasksDto(false, false, false, false, "StartTime_example", false), *openapiclient.NewSystemConfigNotificationsDto(*openapiclient.NewSystemConfigSmtpDto(false, "From_example", "ReplyTo_example", *openapiclient.NewSystemConfigSmtpTransportDto("Host_example", false, "Password_example", float32(123), false, "Username_example"))), *openapiclient.NewSystemConfigOAuthDto(false, false, false, "ButtonText_example", "ClientId_example", "ClientSecret_example", NullableFloat32(123), false, "EndSessionEndpoint_example", "IssuerUrl_example", false, "MobileRedirectUri_example", "ProfileSigningAlgorithm_example", "Prompt_example", "RoleClaim_example", "Scope_example", "SigningAlgorithm_example", "StorageLabelClaim_example", "StorageQuotaClaim_example", int32(123), openapiclient.OAuthTokenEndpointAuthMethod("client_secret_post")), *openapiclient.NewSystemConfigPasswordLoginDto(false), *openapiclient.NewSystemConfigReverseGeocodingDto(false), *openapiclient.NewSystemConfigServerDto("ExternalDomain_example", "LoginPageMessage_example", false), *openapiclient.NewSystemConfigStorageTemplateDto(false, false, "Template_example"), *openapiclient.NewSystemConfigTemplatesDto(*openapiclient.NewSystemConfigTemplateEmailsDto("AlbumInviteTemplate_example", "AlbumUpdateTemplate_example", "WelcomeTemplate_example")), *openapiclient.NewSystemConfigThemeDto("CustomCss_example"), *openapiclient.NewSystemConfigTrashDto(int32(123), false), *openapiclient.NewSystemConfigUserDto(int32(123))) // SystemConfigDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.SystemConfigAPI.UpdateConfig(context.Background()).SystemConfigDto(systemConfigDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SystemConfigAPI.UpdateConfig``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateConfig`: SystemConfigDto
	fmt.Fprintf(os.Stdout, "Response from `SystemConfigAPI.UpdateConfig`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateConfigRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **systemConfigDto** | [**SystemConfigDto**](SystemConfigDto.md) |  | 

### Return type

[**SystemConfigDto**](SystemConfigDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

