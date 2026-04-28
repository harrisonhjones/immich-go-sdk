# \SystemMetadataAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetAdminOnboarding**](SystemMetadataAPI.md#GetAdminOnboarding) | **Get** /system-metadata/admin-onboarding | Retrieve admin onboarding
[**GetReverseGeocodingState**](SystemMetadataAPI.md#GetReverseGeocodingState) | **Get** /system-metadata/reverse-geocoding-state | Retrieve reverse geocoding state
[**GetVersionCheckState**](SystemMetadataAPI.md#GetVersionCheckState) | **Get** /system-metadata/version-check-state | Retrieve version check state
[**UpdateAdminOnboarding**](SystemMetadataAPI.md#UpdateAdminOnboarding) | **Post** /system-metadata/admin-onboarding | Update admin onboarding



## GetAdminOnboarding

> AdminOnboardingUpdateDto GetAdminOnboarding(ctx).Execute()

Retrieve admin onboarding



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
	resp, r, err := apiClient.SystemMetadataAPI.GetAdminOnboarding(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SystemMetadataAPI.GetAdminOnboarding``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAdminOnboarding`: AdminOnboardingUpdateDto
	fmt.Fprintf(os.Stdout, "Response from `SystemMetadataAPI.GetAdminOnboarding`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetAdminOnboardingRequest struct via the builder pattern


### Return type

[**AdminOnboardingUpdateDto**](AdminOnboardingUpdateDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetReverseGeocodingState

> ReverseGeocodingStateResponseDto GetReverseGeocodingState(ctx).Execute()

Retrieve reverse geocoding state



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
	resp, r, err := apiClient.SystemMetadataAPI.GetReverseGeocodingState(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SystemMetadataAPI.GetReverseGeocodingState``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetReverseGeocodingState`: ReverseGeocodingStateResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SystemMetadataAPI.GetReverseGeocodingState`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetReverseGeocodingStateRequest struct via the builder pattern


### Return type

[**ReverseGeocodingStateResponseDto**](ReverseGeocodingStateResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVersionCheckState

> VersionCheckStateResponseDto GetVersionCheckState(ctx).Execute()

Retrieve version check state



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
	resp, r, err := apiClient.SystemMetadataAPI.GetVersionCheckState(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SystemMetadataAPI.GetVersionCheckState``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVersionCheckState`: VersionCheckStateResponseDto
	fmt.Fprintf(os.Stdout, "Response from `SystemMetadataAPI.GetVersionCheckState`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetVersionCheckStateRequest struct via the builder pattern


### Return type

[**VersionCheckStateResponseDto**](VersionCheckStateResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAdminOnboarding

> UpdateAdminOnboarding(ctx).AdminOnboardingUpdateDto(adminOnboardingUpdateDto).Execute()

Update admin onboarding



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
	adminOnboardingUpdateDto := *openapiclient.NewAdminOnboardingUpdateDto(false) // AdminOnboardingUpdateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.SystemMetadataAPI.UpdateAdminOnboarding(context.Background()).AdminOnboardingUpdateDto(adminOnboardingUpdateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `SystemMetadataAPI.UpdateAdminOnboarding``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAdminOnboardingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **adminOnboardingUpdateDto** | [**AdminOnboardingUpdateDto**](AdminOnboardingUpdateDto.md) |  | 

### Return type

 (empty response body)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

