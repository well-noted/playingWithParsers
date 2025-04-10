# Playing w/ Parsers

<img src="https://github.com/user-attachments/assets/9f74cd5c-4ae8-4a71-b82b-b825e970493e" alt="playingwithparsers" width="250" height="250" style="float: left; margin-right: 10px;">
 <br><br>

 This plugin overrides Tiddlywiki's bare-bones audio and video widgets to access advanced parsing features.

## Features of the Enhanced Audio Widget

* Custom audio player interface with playback controls
* Skip backward button (15-second jumps)
* Skip forward button (15-second jumps)
* Playback position memory across sessions
* Automatic position saving during playback
* Position restoration when reopening audio files
* Media Session API integration for system-level media controls
* Comprehensive debugging system with state tracking
* Batched updates to avoid excessive wiki modifications
* Responsive touch controls for mobile devices
* Button hover effects and visual feedback
* Audio controls overlay for easier access
* Automatic blob URL optimization for better performance
* Error handling with automatic retry mechanism
* Progress tracking during audio loading
* Support for both direct audio sources and tiddler-based audio
* Data URI support for embedded audio content
* Audio playback state synchronization
* Unique hash-based field naming for timestamp storage
* Selective widget refresh for better performance

## Features of the Enhanced Video Widget
• **Position saving** - Automatically saves video playback position
• **Timecode restoration** - Jumps to saved timestamp when video is reloaded
• **Enhanced scrubbing** - Provides better control when navigating through video
• **Buffer visualization** - Visual display of buffered regions for smoother seeking
• **Smart seeking** - Jumps to closest buffered region for better playback experience
• **Keyboard shortcuts** - Arrow keys for navigation and space bar for play/pause
• **Progress tracking** - Visual indicator of current position in video
• **Prebuffering support** - Fetches entire video content for consistent scrubbing
• **Position indicators** - On-screen display showing jumped-to positions
• **Multiple position restoration attempts** - Ensures reliable position restoration
• **Periodic position saving** - Saves position every 30 seconds during playback
• **Debug functionality** - Double-click for debugging information
• **Custom styling options** - Configurable video appearance
• **Source flexibility** - Supports various video source types including data URIs
• **Full browser compatibility** - Works across different web browsers

_____________________________________________________________________________________________________________________

When you want to view a video using this expanded widget, please use, for example
<br><br>
``<$video tiddler="pineapple skins as soap.mp4" />``
<br>
or
<br>
``<$audio tiddler="Benefits of soap as a tropical fruit replacement.mp3" />``
<br><br>
