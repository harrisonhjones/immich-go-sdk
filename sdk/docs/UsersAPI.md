# \UsersAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateProfileImage**](UsersAPI.md#CreateProfileImage) | **Post** /users/profile-image | Create user profile image
[**DeleteProfileImage**](UsersAPI.md#DeleteProfileImage) | **Delete** /users/profile-image | Delete user profile image
[**DeleteUserLicense**](UsersAPI.md#DeleteUserLicense) | **Delete** /users/me/license | Delete user product key
[**DeleteUserOnboarding**](UsersAPI.md#DeleteUserOnboarding) | **Delete** /users/me/onboarding | Delete user onboarding
[**GetMyPreferences**](UsersAPI.md#GetMyPreferences) | **Get** /users/me/preferences | Get my preferences
[**GetMyUser**](UsersAPI.md#GetMyUser) | **Get** /users/me | Get current user
[**GetProfileImage**](UsersAPI.md#GetProfileImage) | **Get** /users/{id}/profile-image | Retrieve user profile image
[**GetUser**](UsersAPI.md#GetUser) | **Get** /users/{id} | Retrieve a user
[**GetUserLicense**](UsersAPI.md#GetUserLicense) | **Get** /users/me/license | Retrieve user product key
[**GetUserOnboarding**](UsersAPI.md#GetUserOnboarding) | **Get** /users/me/onboarding | Retrieve user onboarding
[**SearchUsers**](UsersAPI.md#SearchUsers) | **Get** /users | Get all users
[**SetUserLicense**](UsersAPI.md#SetUserLicense) | **Put** /users/me/license | Set user product key
[**SetUserOnboarding**](UsersAPI.md#SetUserOnboarding) | **Put** /users/me/onboarding | Update user onboarding
[**UpdateMyPreferences**](UsersAPI.md#UpdateMyPreferences) | **Put** /users/me/preferences | Update my preferences
[**UpdateMyUser**](UsersAPI.md#UpdateMyUser) | **Put** /users/me | Update current user



## CreateProfileImage

> CreateProfileImageResponseDto CreateProfileImage(ctx).File(file).Execute()

Create user profile image



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
	file := os.NewFile(1234, "some_file") // *os.File | Profile image file

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.CreateProfileImage(context.Background()).File(file).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.CreateProfileImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateProfileImage`: CreateProfileImageResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.CreateProfileImage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateProfileImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **file** | ***os.File** | Profile image file | 

### Return type

[**CreateProfileImageResponseDto**](CreateProfileImageResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteProfileImage

> DeleteProfileImage(ctx).Execute()

Delete user profile image



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UsersAPI.DeleteProfileImage(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.DeleteProfileImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteProfileImageRequest struct via the builder pattern


### Return type

 (empty response body)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteUserLicense

> DeleteUserLicense(ctx).Execute()

Delete user product key



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UsersAPI.DeleteUserLicense(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.DeleteUserLicense``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteUserLicenseRequest struct via the builder pattern


### Return type

 (empty response body)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteUserOnboarding

> DeleteUserOnboarding(ctx).Execute()

Delete user onboarding



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.UsersAPI.DeleteUserOnboarding(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.DeleteUserOnboarding``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteUserOnboardingRequest struct via the builder pattern


### Return type

 (empty response body)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMyPreferences

> UserPreferencesResponseDto GetMyPreferences(ctx).Execute()

Get my preferences



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.GetMyPreferences(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.GetMyPreferences``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMyPreferences`: UserPreferencesResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.GetMyPreferences`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetMyPreferencesRequest struct via the builder pattern


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


## GetMyUser

> UserAdminResponseDto GetMyUser(ctx).Execute()

Get current user



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.GetMyUser(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.GetMyUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMyUser`: UserAdminResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.GetMyUser`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetMyUserRequest struct via the builder pattern


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


## GetProfileImage

> *os.File GetProfileImage(ctx, id).Execute()

Retrieve user profile image



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
	resp, r, err := apiClient.UsersAPI.GetProfileImage(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.GetProfileImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetProfileImage`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.GetProfileImage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetProfileImageRequest struct via the builder pattern


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


## GetUser

> UserResponseDto GetUser(ctx, id).Execute()

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
	resp, r, err := apiClient.UsersAPI.GetUser(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.GetUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUser`: UserResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.GetUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**UserResponseDto**](UserResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserLicense

> UserLicense GetUserLicense(ctx).Execute()

Retrieve user product key



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.GetUserLicense(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.GetUserLicense``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserLicense`: UserLicense
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.GetUserLicense`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserLicenseRequest struct via the builder pattern


### Return type

[**UserLicense**](UserLicense.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetUserOnboarding

> OnboardingResponseDto GetUserOnboarding(ctx).Execute()

Retrieve user onboarding



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.GetUserOnboarding(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.GetUserOnboarding``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetUserOnboarding`: OnboardingResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.GetUserOnboarding`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetUserOnboardingRequest struct via the builder pattern


### Return type

[**OnboardingResponseDto**](OnboardingResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SearchUsers

> []UserResponseDto SearchUsers(ctx).Execute()

Get all users



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.SearchUsers(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.SearchUsers``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SearchUsers`: []UserResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.SearchUsers`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiSearchUsersRequest struct via the builder pattern


### Return type

[**[]UserResponseDto**](UserResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetUserLicense

> UserLicense SetUserLicense(ctx).LicenseKeyDto(licenseKeyDto).Execute()

Set user product key



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
	licenseKeyDto := *openapiclient.NewLicenseKeyDto("ActivationKey_example", "LicenseKey_example") // LicenseKeyDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.SetUserLicense(context.Background()).LicenseKeyDto(licenseKeyDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.SetUserLicense``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetUserLicense`: UserLicense
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.SetUserLicense`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSetUserLicenseRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **licenseKeyDto** | [**LicenseKeyDto**](LicenseKeyDto.md) |  | 

### Return type

[**UserLicense**](UserLicense.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SetUserOnboarding

> OnboardingResponseDto SetUserOnboarding(ctx).OnboardingDto(onboardingDto).Execute()

Update user onboarding



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
	onboardingDto := *openapiclient.NewOnboardingDto(false) // OnboardingDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.SetUserOnboarding(context.Background()).OnboardingDto(onboardingDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.SetUserOnboarding``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SetUserOnboarding`: OnboardingResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.SetUserOnboarding`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSetUserOnboardingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **onboardingDto** | [**OnboardingDto**](OnboardingDto.md) |  | 

### Return type

[**OnboardingResponseDto**](OnboardingResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateMyPreferences

> UserPreferencesResponseDto UpdateMyPreferences(ctx).UserPreferencesUpdateDto(userPreferencesUpdateDto).Execute()

Update my preferences



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
	userPreferencesUpdateDto := *openapiclient.NewUserPreferencesUpdateDto() // UserPreferencesUpdateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.UpdateMyPreferences(context.Background()).UserPreferencesUpdateDto(userPreferencesUpdateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.UpdateMyPreferences``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateMyPreferences`: UserPreferencesResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.UpdateMyPreferences`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateMyPreferencesRequest struct via the builder pattern


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


## UpdateMyUser

> UserAdminResponseDto UpdateMyUser(ctx).UserUpdateMeDto(userUpdateMeDto).Execute()

Update current user



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
	userUpdateMeDto := *openapiclient.NewUserUpdateMeDto() // UserUpdateMeDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.UsersAPI.UpdateMyUser(context.Background()).UserUpdateMeDto(userUpdateMeDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `UsersAPI.UpdateMyUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateMyUser`: UserAdminResponseDto
	fmt.Fprintf(os.Stdout, "Response from `UsersAPI.UpdateMyUser`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiUpdateMyUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **userUpdateMeDto** | [**UserUpdateMeDto**](UserUpdateMeDto.md) |  | 

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

