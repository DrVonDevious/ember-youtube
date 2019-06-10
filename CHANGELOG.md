# Changelog for ember-youtube

### 0.9.5

No longer requires jQuery.

### 0.9.0

New: access the player instance through all youtube events
Fixed async tests by upgrading to ember-cli 3.0.0 and waitFor.

### 0.7.0

Adds a new `lazyload` option to the component (disabled by default). If you're loading one or more players on a page without a `ytid` to start with, this will make sure the API and iframes are not created before a the YouTube ID is there.

### 0.6.1

Options that would be mapped to playerVars have been removed (fs and autoplay) and are now set through a playerVars object on the component. Also through a bit of async trickery, the tests now pass.

### 0.5.3

Extracted custom timestamps from ember-youtube to slim the addon. Moment.js will no longer be included by default. See the readme for instructions for instructions on how to do it manually.

### 0.5.0

Fixed issues with playback and volume not being properly 'set' and 'get'. Loading of the YouTube API should be a bit faster.

### 0.4.0

Thanks to two contributors we have have full control over the volume in the player and it's possible to format the current time and duration of the video using Moment.js.

### 0.2.0

Added an option for autoplay and disabled it by default.

### 0.0.1

First version, published. Playback, controls and progress bar is working.
