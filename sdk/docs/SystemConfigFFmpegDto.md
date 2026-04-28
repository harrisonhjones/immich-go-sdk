# SystemConfigFFmpegDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Accel** | [**TranscodeHWAccel**](TranscodeHWAccel.md) |  | 
**AccelDecode** | **bool** | Accelerated decode | 
**AcceptedAudioCodecs** | [**[]AudioCodec**](AudioCodec.md) | Accepted audio codecs | 
**AcceptedContainers** | [**[]VideoContainer**](VideoContainer.md) | Accepted containers | 
**AcceptedVideoCodecs** | [**[]VideoCodec**](VideoCodec.md) | Accepted video codecs | 
**Bframes** | **int32** | B-frames | 
**CqMode** | [**CQMode**](CQMode.md) |  | 
**Crf** | **int32** | CRF | 
**GopSize** | **int32** | GOP size | 
**MaxBitrate** | **string** | Max bitrate | 
**PreferredHwDevice** | **string** | Preferred hardware device | 
**Preset** | **string** | Preset | 
**Refs** | **int32** | References | 
**TargetAudioCodec** | [**AudioCodec**](AudioCodec.md) |  | 
**TargetResolution** | **string** | Target resolution | 
**TargetVideoCodec** | [**VideoCodec**](VideoCodec.md) |  | 
**TemporalAQ** | **bool** | Temporal AQ | 
**Threads** | **int32** | Threads | 
**Tonemap** | [**ToneMapping**](ToneMapping.md) |  | 
**Transcode** | [**TranscodePolicy**](TranscodePolicy.md) |  | 
**TwoPass** | **bool** | Two pass | 

## Methods

### NewSystemConfigFFmpegDto

`func NewSystemConfigFFmpegDto(accel TranscodeHWAccel, accelDecode bool, acceptedAudioCodecs []AudioCodec, acceptedContainers []VideoContainer, acceptedVideoCodecs []VideoCodec, bframes int32, cqMode CQMode, crf int32, gopSize int32, maxBitrate string, preferredHwDevice string, preset string, refs int32, targetAudioCodec AudioCodec, targetResolution string, targetVideoCodec VideoCodec, temporalAQ bool, threads int32, tonemap ToneMapping, transcode TranscodePolicy, twoPass bool, ) *SystemConfigFFmpegDto`

NewSystemConfigFFmpegDto instantiates a new SystemConfigFFmpegDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemConfigFFmpegDtoWithDefaults

`func NewSystemConfigFFmpegDtoWithDefaults() *SystemConfigFFmpegDto`

NewSystemConfigFFmpegDtoWithDefaults instantiates a new SystemConfigFFmpegDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccel

`func (o *SystemConfigFFmpegDto) GetAccel() TranscodeHWAccel`

GetAccel returns the Accel field if non-nil, zero value otherwise.

### GetAccelOk

`func (o *SystemConfigFFmpegDto) GetAccelOk() (*TranscodeHWAccel, bool)`

GetAccelOk returns a tuple with the Accel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccel

`func (o *SystemConfigFFmpegDto) SetAccel(v TranscodeHWAccel)`

SetAccel sets Accel field to given value.


### GetAccelDecode

`func (o *SystemConfigFFmpegDto) GetAccelDecode() bool`

GetAccelDecode returns the AccelDecode field if non-nil, zero value otherwise.

### GetAccelDecodeOk

`func (o *SystemConfigFFmpegDto) GetAccelDecodeOk() (*bool, bool)`

GetAccelDecodeOk returns a tuple with the AccelDecode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccelDecode

`func (o *SystemConfigFFmpegDto) SetAccelDecode(v bool)`

SetAccelDecode sets AccelDecode field to given value.


### GetAcceptedAudioCodecs

`func (o *SystemConfigFFmpegDto) GetAcceptedAudioCodecs() []AudioCodec`

GetAcceptedAudioCodecs returns the AcceptedAudioCodecs field if non-nil, zero value otherwise.

### GetAcceptedAudioCodecsOk

`func (o *SystemConfigFFmpegDto) GetAcceptedAudioCodecsOk() (*[]AudioCodec, bool)`

GetAcceptedAudioCodecsOk returns a tuple with the AcceptedAudioCodecs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptedAudioCodecs

`func (o *SystemConfigFFmpegDto) SetAcceptedAudioCodecs(v []AudioCodec)`

SetAcceptedAudioCodecs sets AcceptedAudioCodecs field to given value.


### GetAcceptedContainers

`func (o *SystemConfigFFmpegDto) GetAcceptedContainers() []VideoContainer`

GetAcceptedContainers returns the AcceptedContainers field if non-nil, zero value otherwise.

### GetAcceptedContainersOk

`func (o *SystemConfigFFmpegDto) GetAcceptedContainersOk() (*[]VideoContainer, bool)`

GetAcceptedContainersOk returns a tuple with the AcceptedContainers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptedContainers

`func (o *SystemConfigFFmpegDto) SetAcceptedContainers(v []VideoContainer)`

SetAcceptedContainers sets AcceptedContainers field to given value.


### GetAcceptedVideoCodecs

`func (o *SystemConfigFFmpegDto) GetAcceptedVideoCodecs() []VideoCodec`

GetAcceptedVideoCodecs returns the AcceptedVideoCodecs field if non-nil, zero value otherwise.

### GetAcceptedVideoCodecsOk

`func (o *SystemConfigFFmpegDto) GetAcceptedVideoCodecsOk() (*[]VideoCodec, bool)`

GetAcceptedVideoCodecsOk returns a tuple with the AcceptedVideoCodecs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcceptedVideoCodecs

`func (o *SystemConfigFFmpegDto) SetAcceptedVideoCodecs(v []VideoCodec)`

SetAcceptedVideoCodecs sets AcceptedVideoCodecs field to given value.


### GetBframes

`func (o *SystemConfigFFmpegDto) GetBframes() int32`

GetBframes returns the Bframes field if non-nil, zero value otherwise.

### GetBframesOk

`func (o *SystemConfigFFmpegDto) GetBframesOk() (*int32, bool)`

GetBframesOk returns a tuple with the Bframes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBframes

`func (o *SystemConfigFFmpegDto) SetBframes(v int32)`

SetBframes sets Bframes field to given value.


### GetCqMode

`func (o *SystemConfigFFmpegDto) GetCqMode() CQMode`

GetCqMode returns the CqMode field if non-nil, zero value otherwise.

### GetCqModeOk

`func (o *SystemConfigFFmpegDto) GetCqModeOk() (*CQMode, bool)`

GetCqModeOk returns a tuple with the CqMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCqMode

`func (o *SystemConfigFFmpegDto) SetCqMode(v CQMode)`

SetCqMode sets CqMode field to given value.


### GetCrf

`func (o *SystemConfigFFmpegDto) GetCrf() int32`

GetCrf returns the Crf field if non-nil, zero value otherwise.

### GetCrfOk

`func (o *SystemConfigFFmpegDto) GetCrfOk() (*int32, bool)`

GetCrfOk returns a tuple with the Crf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrf

`func (o *SystemConfigFFmpegDto) SetCrf(v int32)`

SetCrf sets Crf field to given value.


### GetGopSize

`func (o *SystemConfigFFmpegDto) GetGopSize() int32`

GetGopSize returns the GopSize field if non-nil, zero value otherwise.

### GetGopSizeOk

`func (o *SystemConfigFFmpegDto) GetGopSizeOk() (*int32, bool)`

GetGopSizeOk returns a tuple with the GopSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGopSize

`func (o *SystemConfigFFmpegDto) SetGopSize(v int32)`

SetGopSize sets GopSize field to given value.


### GetMaxBitrate

`func (o *SystemConfigFFmpegDto) GetMaxBitrate() string`

GetMaxBitrate returns the MaxBitrate field if non-nil, zero value otherwise.

### GetMaxBitrateOk

`func (o *SystemConfigFFmpegDto) GetMaxBitrateOk() (*string, bool)`

GetMaxBitrateOk returns a tuple with the MaxBitrate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxBitrate

`func (o *SystemConfigFFmpegDto) SetMaxBitrate(v string)`

SetMaxBitrate sets MaxBitrate field to given value.


### GetPreferredHwDevice

`func (o *SystemConfigFFmpegDto) GetPreferredHwDevice() string`

GetPreferredHwDevice returns the PreferredHwDevice field if non-nil, zero value otherwise.

### GetPreferredHwDeviceOk

`func (o *SystemConfigFFmpegDto) GetPreferredHwDeviceOk() (*string, bool)`

GetPreferredHwDeviceOk returns a tuple with the PreferredHwDevice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreferredHwDevice

`func (o *SystemConfigFFmpegDto) SetPreferredHwDevice(v string)`

SetPreferredHwDevice sets PreferredHwDevice field to given value.


### GetPreset

`func (o *SystemConfigFFmpegDto) GetPreset() string`

GetPreset returns the Preset field if non-nil, zero value otherwise.

### GetPresetOk

`func (o *SystemConfigFFmpegDto) GetPresetOk() (*string, bool)`

GetPresetOk returns a tuple with the Preset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreset

`func (o *SystemConfigFFmpegDto) SetPreset(v string)`

SetPreset sets Preset field to given value.


### GetRefs

`func (o *SystemConfigFFmpegDto) GetRefs() int32`

GetRefs returns the Refs field if non-nil, zero value otherwise.

### GetRefsOk

`func (o *SystemConfigFFmpegDto) GetRefsOk() (*int32, bool)`

GetRefsOk returns a tuple with the Refs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefs

`func (o *SystemConfigFFmpegDto) SetRefs(v int32)`

SetRefs sets Refs field to given value.


### GetTargetAudioCodec

`func (o *SystemConfigFFmpegDto) GetTargetAudioCodec() AudioCodec`

GetTargetAudioCodec returns the TargetAudioCodec field if non-nil, zero value otherwise.

### GetTargetAudioCodecOk

`func (o *SystemConfigFFmpegDto) GetTargetAudioCodecOk() (*AudioCodec, bool)`

GetTargetAudioCodecOk returns a tuple with the TargetAudioCodec field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetAudioCodec

`func (o *SystemConfigFFmpegDto) SetTargetAudioCodec(v AudioCodec)`

SetTargetAudioCodec sets TargetAudioCodec field to given value.


### GetTargetResolution

`func (o *SystemConfigFFmpegDto) GetTargetResolution() string`

GetTargetResolution returns the TargetResolution field if non-nil, zero value otherwise.

### GetTargetResolutionOk

`func (o *SystemConfigFFmpegDto) GetTargetResolutionOk() (*string, bool)`

GetTargetResolutionOk returns a tuple with the TargetResolution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetResolution

`func (o *SystemConfigFFmpegDto) SetTargetResolution(v string)`

SetTargetResolution sets TargetResolution field to given value.


### GetTargetVideoCodec

`func (o *SystemConfigFFmpegDto) GetTargetVideoCodec() VideoCodec`

GetTargetVideoCodec returns the TargetVideoCodec field if non-nil, zero value otherwise.

### GetTargetVideoCodecOk

`func (o *SystemConfigFFmpegDto) GetTargetVideoCodecOk() (*VideoCodec, bool)`

GetTargetVideoCodecOk returns a tuple with the TargetVideoCodec field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetVideoCodec

`func (o *SystemConfigFFmpegDto) SetTargetVideoCodec(v VideoCodec)`

SetTargetVideoCodec sets TargetVideoCodec field to given value.


### GetTemporalAQ

`func (o *SystemConfigFFmpegDto) GetTemporalAQ() bool`

GetTemporalAQ returns the TemporalAQ field if non-nil, zero value otherwise.

### GetTemporalAQOk

`func (o *SystemConfigFFmpegDto) GetTemporalAQOk() (*bool, bool)`

GetTemporalAQOk returns a tuple with the TemporalAQ field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemporalAQ

`func (o *SystemConfigFFmpegDto) SetTemporalAQ(v bool)`

SetTemporalAQ sets TemporalAQ field to given value.


### GetThreads

`func (o *SystemConfigFFmpegDto) GetThreads() int32`

GetThreads returns the Threads field if non-nil, zero value otherwise.

### GetThreadsOk

`func (o *SystemConfigFFmpegDto) GetThreadsOk() (*int32, bool)`

GetThreadsOk returns a tuple with the Threads field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreads

`func (o *SystemConfigFFmpegDto) SetThreads(v int32)`

SetThreads sets Threads field to given value.


### GetTonemap

`func (o *SystemConfigFFmpegDto) GetTonemap() ToneMapping`

GetTonemap returns the Tonemap field if non-nil, zero value otherwise.

### GetTonemapOk

`func (o *SystemConfigFFmpegDto) GetTonemapOk() (*ToneMapping, bool)`

GetTonemapOk returns a tuple with the Tonemap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTonemap

`func (o *SystemConfigFFmpegDto) SetTonemap(v ToneMapping)`

SetTonemap sets Tonemap field to given value.


### GetTranscode

`func (o *SystemConfigFFmpegDto) GetTranscode() TranscodePolicy`

GetTranscode returns the Transcode field if non-nil, zero value otherwise.

### GetTranscodeOk

`func (o *SystemConfigFFmpegDto) GetTranscodeOk() (*TranscodePolicy, bool)`

GetTranscodeOk returns a tuple with the Transcode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTranscode

`func (o *SystemConfigFFmpegDto) SetTranscode(v TranscodePolicy)`

SetTranscode sets Transcode field to given value.


### GetTwoPass

`func (o *SystemConfigFFmpegDto) GetTwoPass() bool`

GetTwoPass returns the TwoPass field if non-nil, zero value otherwise.

### GetTwoPassOk

`func (o *SystemConfigFFmpegDto) GetTwoPassOk() (*bool, bool)`

GetTwoPassOk returns a tuple with the TwoPass field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTwoPass

`func (o *SystemConfigFFmpegDto) SetTwoPass(v bool)`

SetTwoPass sets TwoPass field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


