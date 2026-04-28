# \UsersAdminAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateUserAdmin**](UsersAdminAPI.md#CreateUserAdmin) | **Post** /admin/users | Create a user
[**DeleteUserAdmin**](UsersAdminAPI.md#DeleteUserAdmin) | **Delete** /admin/users/{id} | Delete a user
[**GetUserAdmin**](UsersAdminAPI.md#GetUserAdmin) | **Get** /admin/users/{id} | Retrieve a user
[**GetUserPreferencesAdmin**](UsersAdminAPI.md#GetUserPreferencesAdmin) | **Get** /admin/users/{id}/preferences | Retrieve user preferences
[**GetUserSessionsAdmin**](UsersAdminAPI.md#GetUserSessionsAdmin) | **Get** /admin/users/{id}/sessions | Retrieve user sessions
[**GetUserStatisticsAdmin**](UsersAdminAPI.md#GetUserStatisticsAdmin) | **Get** /admin/users/{id}/statistics | Retrieve user statistics
[**RestoreUserAdmin**](UsersAdminAPI.md#RestoreUserAdmin) | **Post** /admin/users/{id}/restore | Restore a deleted user
[**SearchUsersAdmin**](UsersAdminAPI.md#SearchUsersAdmin) | **Get** /admin/users | Search users
[**UpdateUserAdmin**](UsersAdminAPI.md#UpdateUserAdmin) | **Put** /admin/users/{id} | Update a user
[**UpdateUserPreferencesAdmin**](UsersAdminAPI.md#UpdateUserPreferencesAdmin) | **Put** /admin/users/{id}/preferences | Update user preferences



## CreateUserAdmin

> UserAdminResponseDto CreateUserAdmin(ctx).UserAdminCreateDto(userAdminCreateDto).Execute()

Create a user



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	userAdminCreateDto := *openapiclient.NewUserAdminCreateDto("Email_example", "Name_example", "Password_example") // UserAdminCreateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAdminAPI.CreateUserAdmin(context.Background()).UserAdminCreateDto(userAdminCreateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAdminAPI.CreateUserAdmin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateUserAdmin`: UserAdminResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAdminAPI.CreateUserAdmin`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateUserAdminRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userAdminCreateDto** | [**UserAdminCreateDto**](UserAdminCreateDto.md) |  | 

### Return type

[**UserAdminResponseDto**](UserAdminResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteUserAdmin

> UserAdminResponseDto DeleteUserAdmin(ctx, id).UserAdminDeleteDto(userAdminDeleteDto).Execute()

Delete a user



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	userAdminDeleteDto := *openapiclient.NewUserAdminDeleteDto() // UserAdminDeleteDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAdminAPI.DeleteUserAdmin(context.Background(), id).UserAdminDeleteDto(userAdminDeleteDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAdminAPI.DeleteUserAdmin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteUserAdmin`: UserAdminResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAdminAPI.DeleteUserAdmin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteUserAdminRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **userAdminDeleteDto** | [**UserAdminDeleteDto**](UserAdminDeleteDto.md) |  | 

### Return type

[**UserAdminResponseDto**](UserAdminResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserAdmin

> UserAdminResponseDto GetUserAdmin(ctx, id).Execute()

Retrieve a user



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAdminAPI.GetUserAdmin(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAdminAPI.GetUserAdmin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserAdmin`: UserAdminResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAdminAPI.GetUserAdmin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserAdminRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**UserAdminResponseDto**](UserAdminResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserPreferencesAdmin

> UserPreferencesResponseDto GetUserPreferencesAdmin(ctx, id).Execute()

Retrieve user preferences



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAdminAPI.GetUserPreferencesAdmin(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAdminAPI.GetUserPreferencesAdmin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserPreferencesAdmin`: UserPreferencesResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAdminAPI.GetUserPreferencesAdmin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserPreferencesAdminRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**UserPreferencesResponseDto**](UserPreferencesResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserSessionsAdmin

> []SessionResponseDto GetUserSessionsAdmin(ctx, id).Execute()

Retrieve user sessions



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAdminAPI.GetUserSessionsAdmin(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAdminAPI.GetUserSessionsAdmin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserSessionsAdmin`: []SessionResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAdminAPI.GetUserSessionsAdmin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserSessionsAdminRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**[]SessionResponseDto**](SessionResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserStatisticsAdmin

> AssetStatsResponseDto GetUserStatisticsAdmin(ctx, id).IsFavorite(isFavorite).IsTrashed(isTrashed).Visibility(visibility).Execute()

Retrieve user statistics



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	isFavorite := true // bool | Filter by favorite status (optional)
	isTrashed := true // bool | Filter by trash status (optional)
	visibility := openapiclient.AssetVisibility("archive") // AssetVisibility |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAdminAPI.GetUserStatisticsAdmin(context.Background(), id).IsFavorite(isFavorite).IsTrashed(isTrashed).Visibility(visibility).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAdminAPI.GetUserStatisticsAdmin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserStatisticsAdmin`: AssetStatsResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAdminAPI.GetUserStatisticsAdmin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserStatisticsAdminRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **isFavorite** | **bool** | Filter by favorite status | 
 **isTrashed** | **bool** | Filter by trash status | 
 **visibility** | [**AssetVisibility**](AssetVisibility.md) |  | 

### Return type

[**AssetStatsResponseDto**](AssetStatsResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RestoreUserAdmin

> UserAdminResponseDto RestoreUserAdmin(ctx, id).Execute()

Restore a deleted user



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAdminAPI.RestoreUserAdmin(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAdminAPI.RestoreUserAdmin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RestoreUserAdmin`: UserAdminResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAdminAPI.RestoreUserAdmin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRestoreUserAdminRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**UserAdminResponseDto**](UserAdminResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchUsersAdmin

> []UserAdminResponseDto SearchUsersAdmin(ctx).Id(id).WithDeleted(withDeleted).Execute()

Search users



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | User ID filter (optional)
	withDeleted := true // bool | Include deleted users (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAdminAPI.SearchUsersAdmin(context.Background()).Id(id).WithDeleted(withDeleted).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAdminAPI.SearchUsersAdmin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchUsersAdmin`: []UserAdminResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAdminAPI.SearchUsersAdmin`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSearchUsersAdminRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string** | User ID filter | 
 **withDeleted** | **bool** | Include deleted users | 

### Return type

[**[]UserAdminResponseDto**](UserAdminResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateUserAdmin

> UserAdminResponseDto UpdateUserAdmin(ctx, id).UserAdminUpdateDto(userAdminUpdateDto).Execute()

Update a user



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	userAdminUpdateDto := *openapiclient.NewUserAdminUpdateDto() // UserAdminUpdateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAdminAPI.UpdateUserAdmin(context.Background(), id).UserAdminUpdateDto(userAdminUpdateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAdminAPI.UpdateUserAdmin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateUserAdmin`: UserAdminResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAdminAPI.UpdateUserAdmin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateUserAdminRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **userAdminUpdateDto** | [**UserAdminUpdateDto**](UserAdminUpdateDto.md) |  | 

### Return type

[**UserAdminResponseDto**](UserAdminResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateUserPreferencesAdmin

> UserPreferencesResponseDto UpdateUserPreferencesAdmin(ctx, id).UserPreferencesUpdateDto(userPreferencesUpdateDto).Execute()

Update user preferences



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	userPreferencesUpdateDto := *openapiclient.NewUserPreferencesUpdateDto() // UserPreferencesUpdateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAdminAPI.UpdateUserPreferencesAdmin(context.Background(), id).UserPreferencesUpdateDto(userPreferencesUpdateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAdminAPI.UpdateUserPreferencesAdmin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateUserPreferencesAdmin`: UserPreferencesResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAdminAPI.UpdateUserPreferencesAdmin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateUserPreferencesAdminRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **userPreferencesUpdateDto** | [**UserPreferencesUpdateDto**](UserPreferencesUpdateDto.md) |  | 

### Return type

[**UserPreferencesResponseDto**](UserPreferencesResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

