HOLLOW MAN
=========================

A Halloween Costume
=========================

By Belin Fieldson
_________________________


Server for Android
_________________________
Minimum Function:
An android app which creates an RTSP stream server local to the android device.

Advanced Functions:
1. Notify online server of stream status
2. Start online stream on demand

Proposed Technologies:
* Android SDK has 3 example Streaming Apps, modify Example 1 for primary purpose
* RTSP transport layer
* Look into the use of 3rd party streaming server

The existing app, spyDroid, is a default implementation of the media Streaming API as showin in example 1, and can support all the functions listed as requirements, and is free, and doesn't embed ads in the stream.  Use it instead of building a stream capture system for this instance.


Client for iOS
__________________________
Minimum Function:
A web or app for iOS which displays an RTSP stream playing from the local network

Advanced Functions:
1. AR tag recognition and object insertion to the stream
2. User interaction with AR objects

Proposed Technologies:
* Video playback through standard stream player
* For advanced functions, video playback through an AR filter will be necessary.
* vuforia AR library can be used to manage AR tags
* vuforia also includes a media playback system compatible with Unity and rtsp

Additional Hardware
___________________________
To maintain power through the intended presentation duration, additional battery systems are required for the broadcast unit.  A portable USB battery pack will be used to power the router and act as a backup power for the android encoder.  The router will provide a secure wiFi connection to the encoder and to the presentation player.

A mounting system is required for the playback and the capture devices, and a harness can be adapted from an A-frame shirt and cases designed for the devices being mounted.