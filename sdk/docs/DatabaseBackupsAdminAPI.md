# \DatabaseBackupsAdminAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteDatabaseBackup**](DatabaseBackupsAdminAPI.md#DeleteDatabaseBackup) | **Delete** /admin/database-backups | Delete database backup
[**DownloadDatabaseBackup**](DatabaseBackupsAdminAPI.md#DownloadDatabaseBackup) | **Get** /admin/database-backups/{filename} | Download database backup
[**ListDatabaseBackups**](DatabaseBackupsAdminAPI.md#ListDatabaseBackups) | **Get** /admin/database-backups | List database backups
[**StartDatabaseRestoreFlow**](DatabaseBackupsAdminAPI.md#StartDatabaseRestoreFlow) | **Post** /admin/database-backups/start-restore | Start database backup restore flow
[**UploadDatabaseBackup**](DatabaseBackupsAdminAPI.md#UploadDatabaseBackup) | **Post** /admin/database-backups/upload | Upload database backup



## DeleteDatabaseBackup

> DeleteDatabaseBackup(ctx).DatabaseBackupDeleteDto(databaseBackupDeleteDto).Execute()

Delete database backup



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
	databaseBackupDeleteDto := *openapiclient.NewDatabaseBackupDeleteDto([]string{"Backups_example"}) // DatabaseBackupDeleteDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DatabaseBackupsAdminAPI.DeleteDatabaseBackup(context.Background()).DatabaseBackupDeleteDto(databaseBackupDeleteDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatabaseBackupsAdminAPI.DeleteDatabaseBackup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDatabaseBackupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **databaseBackupDeleteDto** | [**DatabaseBackupDeleteDto**](DatabaseBackupDeleteDto.md) |  | 

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


## DownloadDatabaseBackup

> *os.File DownloadDatabaseBackup(ctx, filename).Execute()

Download database backup



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
	filename := "filename_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DatabaseBackupsAdminAPI.DownloadDatabaseBackup(context.Background(), filename).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatabaseBackupsAdminAPI.DownloadDatabaseBackup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DownloadDatabaseBackup`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `DatabaseBackupsAdminAPI.DownloadDatabaseBackup`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**filename** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDownloadDatabaseBackupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[***os.File**](*os.File.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDatabaseBackups

> DatabaseBackupListResponseDto ListDatabaseBackups(ctx).Execute()

List database backups



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
	resp, r, err := apiClient.DatabaseBackupsAdminAPI.ListDatabaseBackups(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatabaseBackupsAdminAPI.ListDatabaseBackups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDatabaseBackups`: DatabaseBackupListResponseDto
	fmt.Fprintf(os.Stdout, "Response from `DatabaseBackupsAdminAPI.ListDatabaseBackups`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListDatabaseBackupsRequest struct via the builder pattern


### Return type

[**DatabaseBackupListResponseDto**](DatabaseBackupListResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StartDatabaseRestoreFlow

> StartDatabaseRestoreFlow(ctx).Execute()

Start database backup restore flow



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
	r, err := apiClient.DatabaseBackupsAdminAPI.StartDatabaseRestoreFlow(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatabaseBackupsAdminAPI.StartDatabaseRestoreFlow``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiStartDatabaseRestoreFlowRequest struct via the builder pattern


### Return type

 (empty response body)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadDatabaseBackup

> UploadDatabaseBackup(ctx).File(file).Execute()

Upload database backup



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
	file := os.NewFile(1234, "some_file") // *os.File | Database backup file (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.DatabaseBackupsAdminAPI.UploadDatabaseBackup(context.Background()).File(file).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DatabaseBackupsAdminAPI.UploadDatabaseBackup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUploadDatabaseBackupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | ***os.File** | Database backup file | 

### Return type

 (empty response body)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

