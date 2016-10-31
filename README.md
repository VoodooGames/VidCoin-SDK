# VidCoin-SDK
A github repository for the VidCoin iOS SDK.

Current SDK version : 1.4.0

Updating to v1.4.0
If you're updating from a SDK version prior to v1.4.0, make sure to add WebKit.framework to the target's linked libraries, and mark it as Optional.
Also, MediaPlayer.framework is not used anymore. Feel free to remove it, if you don't use it elsewhere in your project.
