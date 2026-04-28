# \DeprecatedAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreatePartnerDeprecated**](DeprecatedAPI.md#CreatePartnerDeprecated) | **Post** /partners/{id} | Create a partner
[**GetQueuesLegacy**](DeprecatedAPI.md#GetQueuesLegacy) | **Get** /jobs | Retrieve queue counts and status
[**RunQueueCommandLegacy**](DeprecatedAPI.md#RunQueueCommandLegacy) | **Put** /jobs/{name} | Run jobs



## CreatePartnerDeprecated

> PartnerResponseDto CreatePartnerDeprecated(ctx, id).Execute()

Create a partner



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeprecatedAPI.CreatePartnerDeprecated(context.Background(), id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeprecatedAPI.CreatePartnerDeprecated``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePartnerDeprecated`: PartnerResponseDto
	fmt.Fprintf(os.Stdout, "Response from `DeprecatedAPI.CreatePartnerDeprecated`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreatePartnerDeprecatedRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**PartnerResponseDto**](PartnerResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetQueuesLegacy

> QueuesResponseLegacyDto GetQueuesLegacy(ctx).Execute()

Retrieve queue counts and status



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
	resp, r, err := apiClient.DeprecatedAPI.GetQueuesLegacy(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeprecatedAPI.GetQueuesLegacy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetQueuesLegacy`: QueuesResponseLegacyDto
	fmt.Fprintf(os.Stdout, "Response from `DeprecatedAPI.GetQueuesLegacy`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetQueuesLegacyRequest struct via the builder pattern


### Return type

[**QueuesResponseLegacyDto**](QueuesResponseLegacyDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RunQueueCommandLegacy

> QueueResponseLegacyDto RunQueueCommandLegacy(ctx, name).QueueCommandDto(queueCommandDto).Execute()

Run jobs



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
	name := openapiclient.QueueName("thumbnailGeneration") // QueueName | 
	queueCommandDto := *openapiclient.NewQueueCommandDto(openapiclient.QueueCommand("start")) // QueueCommandDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DeprecatedAPI.RunQueueCommandLegacy(context.Background(), name).QueueCommandDto(queueCommandDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DeprecatedAPI.RunQueueCommandLegacy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RunQueueCommandLegacy`: QueueResponseLegacyDto
	fmt.Fprintf(os.Stdout, "Response from `DeprecatedAPI.RunQueueCommandLegacy`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**name** | [**QueueName**](.md) |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRunQueueCommandLegacyRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **queueCommandDto** | [**QueueCommandDto**](QueueCommandDto.md) |  | 

### Return type

[**QueueResponseLegacyDto**](QueueResponseLegacyDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

