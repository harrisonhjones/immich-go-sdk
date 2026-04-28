# PurchaseResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HideBuyButtonUntil** | **string** | Date until which to hide buy button | 
**ShowSupportBadge** | **bool** | Whether to show support badge | 

## Methods

### NewPurchaseResponse

`func NewPurchaseResponse(hideBuyButtonUntil string, showSupportBadge bool, ) *PurchaseResponse`

NewPurchaseResponse instantiates a new PurchaseResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPurchaseResponseWithDefaults

`func NewPurchaseResponseWithDefaults() *PurchaseResponse`

NewPurchaseResponseWithDefaults instantiates a new PurchaseResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHideBuyButtonUntil

`func (o *PurchaseResponse) GetHideBuyButtonUntil() string`

GetHideBuyButtonUntil returns the HideBuyButtonUntil field if non-nil, zero value otherwise.

### GetHideBuyButtonUntilOk

`func (o *PurchaseResponse) GetHideBuyButtonUntilOk() (*string, bool)`

GetHideBuyButtonUntilOk returns a tuple with the HideBuyButtonUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHideBuyButtonUntil

`func (o *PurchaseResponse) SetHideBuyButtonUntil(v string)`

SetHideBuyButtonUntil sets HideBuyButtonUntil field to given value.


### GetShowSupportBadge

`func (o *PurchaseResponse) GetShowSupportBadge() bool`

GetShowSupportBadge returns the ShowSupportBadge field if non-nil, zero value otherwise.

### GetShowSupportBadgeOk

`func (o *PurchaseResponse) GetShowSupportBadgeOk() (*bool, bool)`

GetShowSupportBadgeOk returns a tuple with the ShowSupportBadge field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShowSupportBadge

`func (o *PurchaseResponse) SetShowSupportBadge(v bool)`

SetShowSupportBadge sets ShowSupportBadge field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


