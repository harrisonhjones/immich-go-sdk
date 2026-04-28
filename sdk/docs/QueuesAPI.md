# \QueuesAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**EmptyQueue**](QueuesAPI.md#EmptyQueue) | **Delete** /queues/{name}/jobs | Empty a queue
[**GetQueue**](QueuesAPI.md#GetQueue) | **Get** /queues/{name} | Retrieve a queue
[**GetQueueJobs**](QueuesAPI.md#GetQueueJobs) | **Get** /queues/{name}/jobs | Retrieve queue jobs
[**GetQueues**](QueuesAPI.md#GetQueues) | **Get** /queues | List all queues
[**UpdateQueue**](QueuesAPI.md#UpdateQueue) | **Put** /queues/{name} | Update a queue



## EmptyQueue

> EmptyQueue(ctx, name).QueueDeleteDto(queueDeleteDto).Execute()

Empty a queue



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
	queueDeleteDto := *openapiclient.NewQueueDeleteDto() // QueueDeleteDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.QueuesAPI.EmptyQueue(context.Background(), name).QueueDeleteDto(queueDeleteDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QueuesAPI.EmptyQueue``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**name** | [**QueueName**](.md) |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiEmptyQueueRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **queueDeleteDto** | [**QueueDeleteDto**](QueueDeleteDto.md) |  | 

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


## GetQueue

> QueueResponseDto GetQueue(ctx, name).Execute()

Retrieve a queue



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QueuesAPI.GetQueue(context.Background(), name).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QueuesAPI.GetQueue``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetQueue`: QueueResponseDto
	fmt.Fprintf(os.Stdout, "Response from `QueuesAPI.GetQueue`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**name** | [**QueueName**](.md) |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetQueueRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**QueueResponseDto**](QueueResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetQueueJobs

> []QueueJobResponseDto GetQueueJobs(ctx, name).Status(status).Execute()

Retrieve queue jobs



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
	status := []openapiclient.QueueJobStatus{openapiclient.QueueJobStatus("active")} // []QueueJobStatus | Filter jobs by status (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QueuesAPI.GetQueueJobs(context.Background(), name).Status(status).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QueuesAPI.GetQueueJobs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetQueueJobs`: []QueueJobResponseDto
	fmt.Fprintf(os.Stdout, "Response from `QueuesAPI.GetQueueJobs`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**name** | [**QueueName**](.md) |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetQueueJobsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **status** | [**[]QueueJobStatus**](QueueJobStatus.md) | Filter jobs by status | 

### Return type

[**[]QueueJobResponseDto**](QueueJobResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetQueues

> []QueueResponseDto GetQueues(ctx).Execute()

List all queues



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
	resp, r, err := apiClient.QueuesAPI.GetQueues(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QueuesAPI.GetQueues``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetQueues`: []QueueResponseDto
	fmt.Fprintf(os.Stdout, "Response from `QueuesAPI.GetQueues`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiGetQueuesRequest struct via the builder pattern


### Return type

[**[]QueueResponseDto**](QueueResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateQueue

> QueueResponseDto UpdateQueue(ctx, name).QueueUpdateDto(queueUpdateDto).Execute()

Update a queue



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
	queueUpdateDto := *openapiclient.NewQueueUpdateDto() // QueueUpdateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QueuesAPI.UpdateQueue(context.Background(), name).QueueUpdateDto(queueUpdateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QueuesAPI.UpdateQueue``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateQueue`: QueueResponseDto
	fmt.Fprintf(os.Stdout, "Response from `QueuesAPI.UpdateQueue`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**name** | [**QueueName**](.md) |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateQueueRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **queueUpdateDto** | [**QueueUpdateDto**](QueueUpdateDto.md) |  | 

### Return type

[**QueueResponseDto**](QueueResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

