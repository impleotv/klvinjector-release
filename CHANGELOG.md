Change Log
==========

### Ver. 4.2.10 (12/05/25)
- Low level Ver. 1.7.13 (11/5/25)
	- Fix decoder state machine stability while playing corrupted content

### Ver. 4.2.8 (10/04/25)
- Low level Ver. 1.7.11 (9/4/25)
	- Fix exception on decoding stop 

### Ver. 4.2.7 (03/04/25)
- Low level 1.7.10 
	- Fixing demux of h265 with bad syntax

### Ver. 4.2.6 (16/03/25)
- Modify setup

### Ver. 4.2.5 (24/02/25)
- low level Ver. 1.7.9 (23/2/25)
	- Added API for enable/disable transport discontinuity events (default is ignore discontinuity)

### Ver. 4.2.4 (19/02/25)
- Replace x32 h264 encoder with x64
- low level Ver. 1.7.8 (19/2/25)
	- Fixed resolution detection in HEVC
	- supporting synthetic video insertion and dynamic input resolution change in encoder
	- fixing a regression bug in video capture mode
	- Supporting aspect ration dynamic change in encoder

### Ver. 4.2.3 (09/02/25)
- Update time server implementation

### Ver. 4.2.2 (04/02/25)
- low level
	- MPEG-TS detection fixes

### Ver. 4.2.1 (30/01/25)
- low level
 - Adding support for AV1 in RTP input and in decoding
 - AV1 stabilization fixes

### Ver. 4.2.0 (12/01/25)
- low level
 - Upgrading ffmpeg to 5.1.2
 - Use Filters v1.7

### Ver. 4.1.4 (15/11/24)
- low level
	- support decoding of H265 with P10 pixel format

### Ver. 4.1.2 (16/10/24)
- low level
	- Fix RTSP if more than 4 tracks
	- Fix Directx renderer dead-lock in low delay

### Ver. 4.1.0 (12/08/24)
- low level modifications
- MisbCore VMTI modifications
	- Add MISB903.6 support 

### Ver. 4.0.7 (05/06/24)
- low level
	- Fix aspect ratio and vertical flip in video snapshot
	- Fix handling of H265 decoding using Elecard, when callback requires RGB

### Ver. 4.0.6 (26/05/24)
- low level 
	- Add an option to select the gpu device performing the hw accelerated decoding

### Ver. 4.0.5 (19/05/24)
- low level 
	- Complete support for pull demux with MPEG-PROGRAM input
	- Complete fix for IIS crash

### Ver. 4.0.2 (5/05/24)
- Modify JWT license implementation

### Ver. 4.0.1 (2/05/24)
- low level 
	- Fix pause handling in VideoOverlayMixer
	- improve D3d video renderer performance

### Ver. 4.0.0 (1/05/24)
- Move to .Net 4.7.2
- Add JWT license

- Modify low level 
	- Add delay option in videoOverlayMixer
	- Add option to override aspect ratio in VideoOverlayMixer
	- Improvements in presentation filters

### Ver. 3.12.0 (26/03/24)
- Modify NodeInfo format
Low level:
- Improving performance in D3d rendering
- Fixing VideoOverlayMixer in handling I420 pixel format

### Ver. 3.11.5 (24/03/24)
- Update MisbCore
	- Remove length from VMTI Location (tag 17)
	- Remove length from VMTI Velocity and Acceleration DLP 

### Ver. 3.10.15 (29/01/24)
- Update low level

### Ver. 3.10.11 (03/01/24)
- Update low level
- Fix vmti number of targets. Move filehelper to misbCore (json2Klv)

### Ver. 3.10.10 (14/12/23)
- Update low level

### Ver. 3.10.4 (12/10-/23)
- Fix long VMTI tracker (over 14 items)

### Ver. 3.10.3 (23/08/23)
- Low level update. 
- Support the sps information provided in an rtp packet with a format STAP-A 
- Fix the SequenceHeaderInsertionOnKeyFrames property did not reach its destination in the DVR mode


### Ver. 3.10.2 (16/07/23)
- Fix BER-OID Encoding/Decoding for VMTI Target ID

### Ver. 3.10.1 (27/06/23)
- Low level update. Decoder memory leak fix

### Ver. 3.10.0 (23/05/23)
- Low level update. FFmpeg version change
- Add api for configuring decoding hw acceleration type

### Ver. 3.9.4 (3/04/23)
- Update low level. Fix Metadata_AU_cell () size 

### Ver. 3.9.3 (12/02/23)
- Update low level 

### Ver. 3.9.2 (14/08/22)
- Add tags 115, 116, 121, 122, 128, 138, 139
- Update MisbCore (fix VMTI target id)
- Update low level 

### Ver. 3.9.1 (08/22)
 - Support default packet with "Items" (exported from KlvInspector.

### Ver. 3.9.0 (12/05/22)
- Add deepstack object detection (VMTI)
- Modify Mission and Options dlgs
- Modifiy nodeinfo

### Ver. 3.8.13 (01/02/22)
- Check for non ascii file name
- Fix Merge Default packet
- Update license persistence

### Ver. 3.8.12 (20/01/22)
- Fix crash on KlvBaseTypes loading

### Ver. 3.8.11 (19/12/21)
- Update low level

### Ver. 3.8.10 (23/11/21)
- Update low level
- Add time restricted license support
- Boost v142
- STANAG Player SDK v3.8.10

### Ver. 3.8.9.1 (14/11/21)
- Low level update. VS2019 resistributables

### Ver. 3.8.9.0 (14/10/21)
- Low level update. Move to VS2019
- Add FrameAccuracyRequiresSequenceHeaders 

### Ver. 3.8.7.5 (13/05/21)
- Low level update

### Ver. 3.8.7.2 (25/04/21)
- Low level update

### Ver. 3.8.7.1 (08/04/21)
- Low level update

### Ver. 3.8.7 (31/03/21)
- Low level update

### Ver. 3.8.6 (18/01/21)
- Add ContiguousDemuxedVideo
- Low level update

### Ver. 3.8.5.0
- Low level update
- Fix Big Endian Unicode in UTF-16

### Ver. 3.8.4.2
- Replace data strings to (JObject)kf.decodedData
- Add min insertion interval to merged packet

### Ver. 3.8.4.1
- Fix Tag 20 ( Sensor Relative Roll Angle) validation

### Ver. 3.8.4
- Fix RTSP (tcp)
- Enable FIPS Compliant authorization

### Ver. 3.8.3
- Add OrderByTags option

### Ver. 3.8.2.1
- DecodedData as string

### Ver. 3.8.2
- Low level update

### Ver. 3.8.1
- MisbCore update
- Low level RAW Klv processing

### Ver. 3.8.0
- Low level update - StCore 3.8.0 (MISBCore)
- MisbCore
- Move to .NET 4.6.1

### Ver. 3.7.18
- Movie Win32 binaries of Encoder Process to a subfolder

### Ver. 3.7.17
- Frame Accuracy stability fixes for reverse playback

### Ver. 3.7.16.1
- Live Json encode

### Ver. 3.7.16
- Add low latency mode

### Ver. 3.7.15
- Low level update

### Ver. 3.7.14.3
- Error notifications

### Ver. 3.7.14.2
- Fix  each stop->start creates additional output channel with the same IP and port.

### Ver. 3.7.14,1
- Change elevation server
- Low level update

### Ver. 3.7.14
- Add Frame Grabber (capture)
- Add Ttl

### Ver. 3.7.13
- Low level update

### Ver. 3.7.11
- Low delay fixes
- Adding option to modify incoming PTS in Injector according to local CPU time

### Ver. 3.7.10
- Low level update
- 0.0.0.0 binding


### Ver. 3.7.10
- Low level update (StCore 3.7.10)
- Add back 2013 redistributables for Chromium
- 0.0.0.0 video source

### Ver. 3.7.6
- Low level changes (Injector robustness)
- Fix missing Klv after seek
- Fix audio pid mux

### Ver. 3.7.5
- Low level update

### Ver. 3.7.4
- Elevation server access improvements
- Error handling
- Fix Start button delayed update

### Ver. 3.7.3.1
- Low level update

### Ver. 3.7.3
- Low level update

### Ver. 3.7.0
- BER-OID tags
- Fix DJI telemetry gimabl / platform pitch. 
- Synthetic Video fixes in low level filters and StCore.dll
- Add Limit to Revision 12 option (To exclude long form BER-OID tags)
- Add Slant Range, Target Width and extended info tags

### Ver. 3.0.3
- Change altitude implementation for DjiTXTlog (add home height)
- Remove Impleo Test SecurityLocalSetJson

### Ver. 3.0.2
- CSV data import (DJI and MISB)

### Ver. 3.0.1
- Restamp klv added

### Ver. 3.0.0
- Major rewrite (based on StCore SDK)

### Ver. 1.0.0
- Initial version.



    