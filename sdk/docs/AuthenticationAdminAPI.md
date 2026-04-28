# \AuthenticationAdminAPI

All URIs are relative to */api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**UnlinkAllOAuthAccountsAdmin**](AuthenticationAdminAPI.md#UnlinkAllOAuthAccountsAdmin) | **Post** /admin/auth/unlink-all | Unlink all OAuth accounts



## UnlinkAllOAuthAccountsAdmin

> UnlinkAllOAuthAccountsAdmin(ctx).Execute()

Unlink all OAuth accounts



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
	r, err := apiClient.AuthenticationAdminAPI.UnlinkAllOAuthAccountsAdmin(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AuthenticationAdminAPI.UnlinkAllOAuthAccountsAdmin``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiUnlinkAllOAuthAccountsAdminRequest struct via the builder pattern


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

