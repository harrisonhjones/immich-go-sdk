# \MaintenanceAdminAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DetectPriorInstall**](MaintenanceAdminAPI.md#DetectPriorInstall) | **Get** /admin/maintenance/detect-install | Detect existing install
[**GetMaintenanceStatus**](MaintenanceAdminAPI.md#GetMaintenanceStatus) | **Get** /admin/maintenance/status | Get maintenance mode status
[**MaintenanceLogin**](MaintenanceAdminAPI.md#MaintenanceLogin) | **Post** /admin/maintenance/login | Log into maintenance mode
[**SetMaintenanceMode**](MaintenanceAdminAPI.md#SetMaintenanceMode) | **Post** /admin/maintenance | Set maintenance mode



## DetectPriorInstall

> MaintenanceDetectInstallResponseDto DetectPriorInstall(ctx).Execute()

Detect existing install



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
	resp, r, err := apiClient.MaintenanceAdminAPI.DetectPriorInstall(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MaintenanceAdminAPI.DetectPriorInstall``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DetectPriorInstall`: MaintenanceDetectInstallResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MaintenanceAdminAPI.DetectPriorInstall`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDetectPriorInstallRequest struct via the builder pattern


### Return type

[**MaintenanceDetectInstallResponseDto**](MaintenanceDetectInstallResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMaintenanceStatus

> MaintenanceStatusResponseDto GetMaintenanceStatus(ctx).Execute()

Get maintenance mode status



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
	resp, r, err := apiClient.MaintenanceAdminAPI.GetMaintenanceStatus(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MaintenanceAdminAPI.GetMaintenanceStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMaintenanceStatus`: MaintenanceStatusResponseDto
	fmt.Fprintf(os.Stdout, "Response from `MaintenanceAdminAPI.GetMaintenanceStatus`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetMaintenanceStatusRequest struct via the builder pattern


### Return type

[**MaintenanceStatusResponseDto**](MaintenanceStatusResponseDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## MaintenanceLogin

> MaintenanceAuthDto MaintenanceLogin(ctx).MaintenanceLoginDto(maintenanceLoginDto).Execute()

Log into maintenance mode



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
	maintenanceLoginDto := *openapiclient.NewMaintenanceLoginDto() // MaintenanceLoginDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MaintenanceAdminAPI.MaintenanceLogin(context.Background()).MaintenanceLoginDto(maintenanceLoginDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MaintenanceAdminAPI.MaintenanceLogin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `MaintenanceLogin`: MaintenanceAuthDto
	fmt.Fprintf(os.Stdout, "Response from `MaintenanceAdminAPI.MaintenanceLogin`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiMaintenanceLoginRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **maintenanceLoginDto** | [**MaintenanceLoginDto**](MaintenanceLoginDto.md) |  | 

### Return type

[**MaintenanceAuthDto**](MaintenanceAuthDto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetMaintenanceMode

> SetMaintenanceMode(ctx).SetMaintenanceModeDto(setMaintenanceModeDto).Execute()

Set maintenance mode



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
	setMaintenanceModeDto := *openapiclient.NewSetMaintenanceModeDto(openapiclient.MaintenanceAction("start")) // SetMaintenanceModeDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.MaintenanceAdminAPI.SetMaintenanceMode(context.Background()).SetMaintenanceModeDto(setMaintenanceModeDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MaintenanceAdminAPI.SetMaintenanceMode``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSetMaintenanceModeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **setMaintenanceModeDto** | [**SetMaintenanceModeDto**](SetMaintenanceModeDto.md) |  | 

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

