# Software

The software should be as plugable as possible. This means we have a core functionality. Everything above this should come as plugins.

# Core

The core will give us the basic IO, as well as MP3

## IO
IO should be as small as possible on the device. This means we have a big play/pause button.
As we have MP3 on a pre defined foledr as input a selection of the title will be possible with 2 additional buttons.
Those 2 buttons can also be used for mode settings.
A small display may be an option. This should only show us which title we have.

## MP3
MP3 should be stored on a predefined path. This will save us browsing and IO operations.
Playback can be started, stopped and the title can be changed. This should be the limited nummber of interactions.

## API
To have a chance to adopt the functionality a basic API will be implemented. The api will be limited to:
* IO via API
* Browing MP3 tags
* Setting the plugin
* List plugin network ports

## Plugins

TBD!
Idea: A binary that can be called and gives the functionalities like the MP3 player.
