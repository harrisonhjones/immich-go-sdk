# \JobsAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateJob**](JobsAPI.md#CreateJob) | **Post** /jobs | Create a manual job
[**GetQueuesLegacy**](JobsAPI.md#GetQueuesLegacy) | **Get** /jobs | Retrieve queue counts and status
[**RunQueueCommandLegacy**](JobsAPI.md#RunQueueCommandLegacy) | **Put** /jobs/{name} | Run jobs



## CreateJob

> CreateJob(ctx).JobCreateDto(jobCreateDto).Execute()

Create a manual job



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
	jobCreateDto := *openapiclient.NewJobCreateDto(openapiclient.ManualJobName("person-cleanup")) // JobCreateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.JobsAPI.CreateJob(context.Background()).JobCreateDto(jobCreateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.CreateJob``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateJobRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **jobCreateDto** | [**JobCreateDto**](JobCreateDto.md) |  | 

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
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobsAPI.GetQueuesLegacy(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.GetQueuesLegacy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetQueuesLegacy`: QueuesResponseLegacyDto
	fmt.Fprintf(os.Stdout, "Response from `JobsAPI.GetQueuesLegacy`: %v\n", resp)
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
	openapiclient "harrisonhjones.com/immich-go-sdk/sdk"
)

func main() {
	name := openapiclient.QueueName("thumbnailGeneration") // QueueName | 
	queueCommandDto := *openapiclient.NewQueueCommandDto(openapiclient.QueueCommand("start")) // QueueCommandDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.JobsAPI.RunQueueCommandLegacy(context.Background(), name).QueueCommandDto(queueCommandDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `JobsAPI.RunQueueCommandLegacy``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RunQueueCommandLegacy`: QueueResponseLegacyDto
	fmt.Fprintf(os.Stdout, "Response from `JobsAPI.RunQueueCommandLegacy`: %v\n", resp)
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

