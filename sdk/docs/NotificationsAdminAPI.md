# \NotificationsAdminAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateNotification**](NotificationsAdminAPI.md#CreateNotification) | **Post** /admin/notifications | Create a notification
[**GetNotificationTemplateAdmin**](NotificationsAdminAPI.md#GetNotificationTemplateAdmin) | **Post** /admin/notifications/templates/{name} | Render email template
[**SendTestEmailAdmin**](NotificationsAdminAPI.md#SendTestEmailAdmin) | **Post** /admin/notifications/test-email | Send test email



## CreateNotification

> NotificationDto CreateNotification(ctx).NotificationCreateDto(notificationCreateDto).Execute()

Create a notification



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
	notificationCreateDto := *openapiclient.NewNotificationCreateDto("Title_example", "UserId_example") // NotificationCreateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotificationsAdminAPI.CreateNotification(context.Background()).NotificationCreateDto(notificationCreateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationsAdminAPI.CreateNotification``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateNotification`: NotificationDto
	fmt.Fprintf(os.Stdout, "Response from `NotificationsAdminAPI.CreateNotification`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateNotificationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **notificationCreateDto** | [**NotificationCreateDto**](NotificationCreateDto.md) |  | 

### Return type

[**NotificationDto**](NotificationDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetNotificationTemplateAdmin

> TemplateResponseDto GetNotificationTemplateAdmin(ctx, name).TemplateDto(templateDto).Execute()

Render email template



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
	name := "name_example" // string | 
	templateDto := *openapiclient.NewTemplateDto("Template_example") // TemplateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotificationsAdminAPI.GetNotificationTemplateAdmin(context.Background(), name).TemplateDto(templateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationsAdminAPI.GetNotificationTemplateAdmin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetNotificationTemplateAdmin`: TemplateResponseDto
	fmt.Fprintf(os.Stdout, "Response from `NotificationsAdminAPI.GetNotificationTemplateAdmin`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**name** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetNotificationTemplateAdminRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **templateDto** | [**TemplateDto**](TemplateDto.md) |  | 

### Return type

[**TemplateResponseDto**](TemplateResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SendTestEmailAdmin

> TestEmailResponseDto SendTestEmailAdmin(ctx).SystemConfigSmtpDto(systemConfigSmtpDto).Execute()

Send test email



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
	systemConfigSmtpDto := *openapiclient.NewSystemConfigSmtpDto(false, "From_example", "ReplyTo_example", *openapiclient.NewSystemConfigSmtpTransportDto("Host_example", false, "Password_example", int32(123), false, "Username_example")) // SystemConfigSmtpDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.NotificationsAdminAPI.SendTestEmailAdmin(context.Background()).SystemConfigSmtpDto(systemConfigSmtpDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `NotificationsAdminAPI.SendTestEmailAdmin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SendTestEmailAdmin`: TestEmailResponseDto
	fmt.Fprintf(os.Stdout, "Response from `NotificationsAdminAPI.SendTestEmailAdmin`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSendTestEmailAdminRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **systemConfigSmtpDto** | [**SystemConfigSmtpDto**](SystemConfigSmtpDto.md) |  | 

### Return type

[**TestEmailResponseDto**](TestEmailResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

