# \FacesAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateFace**](FacesAPI.md#CreateFace) | **Post** /faces | Create a face
[**DeleteFace**](FacesAPI.md#DeleteFace) | **Delete** /faces/{id} | Delete a face
[**GetFaces**](FacesAPI.md#GetFaces) | **Get** /faces | Retrieve faces for asset
[**ReassignFacesById**](FacesAPI.md#ReassignFacesById) | **Put** /faces/{id} | Re-assign a face to another person



## CreateFace

> CreateFace(ctx).AssetFaceCreateDto(assetFaceCreateDto).Execute()

Create a face



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
	assetFaceCreateDto := *openapiclient.NewAssetFaceCreateDto("AssetId_example", int32(123), int32(123), int32(123), "PersonId_example", int32(123), int32(123), int32(123)) // AssetFaceCreateDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FacesAPI.CreateFace(context.Background()).AssetFaceCreateDto(assetFaceCreateDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FacesAPI.CreateFace``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateFaceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **assetFaceCreateDto** | [**AssetFaceCreateDto**](AssetFaceCreateDto.md) |  | 

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


## DeleteFace

> DeleteFace(ctx, id).AssetFaceDeleteDto(assetFaceDeleteDto).Execute()

Delete a face



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
	assetFaceDeleteDto := *openapiclient.NewAssetFaceDeleteDto(false) // AssetFaceDeleteDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.FacesAPI.DeleteFace(context.Background(), id).AssetFaceDeleteDto(assetFaceDeleteDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FacesAPI.DeleteFace``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteFaceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **assetFaceDeleteDto** | [**AssetFaceDeleteDto**](AssetFaceDeleteDto.md) |  | 

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


## GetFaces

> []AssetFaceResponseDto GetFaces(ctx).Id(id).Execute()

Retrieve faces for asset



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
	id := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | Face ID

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FacesAPI.GetFaces(context.Background()).Id(id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FacesAPI.GetFaces``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetFaces`: []AssetFaceResponseDto
	fmt.Fprintf(os.Stdout, "Response from `FacesAPI.GetFaces`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetFacesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **id** | **string** | Face ID | 

### Return type

[**[]AssetFaceResponseDto**](AssetFaceResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReassignFacesById

> PersonResponseDto ReassignFacesById(ctx, id).FaceDto(faceDto).Execute()

Re-assign a face to another person



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
	faceDto := *openapiclient.NewFaceDto("Id_example") // FaceDto | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FacesAPI.ReassignFacesById(context.Background(), id).FaceDto(faceDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FacesAPI.ReassignFacesById``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReassignFacesById`: PersonResponseDto
	fmt.Fprintf(os.Stdout, "Response from `FacesAPI.ReassignFacesById`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiReassignFacesByIdRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **faceDto** | [**FaceDto**](FaceDto.md) |  | 

### Return type

[**PersonResponseDto**](PersonResponseDto.md)

### Authorization

[cookie](../README.md#cookie), [api_key](../README.md#api_key), [bearer](../README.md#bearer)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

