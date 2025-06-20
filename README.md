# Genesis Game Instruments

An archive of GenMDM and TFM Music Maker FM instrument patches from over 600 games for the Sega Genesis/Mega Drive.

## About This Collection
These instruments come from a collection of FM patches originally released by [little-scale](https://little-scale.blogspot.com/) in `.tfi` (TFM Music Maker) format. They have been renamed to be easier to understand and also include `.genm` (GenMDM) collections of these instruments for use in apps like [genMDM Editor](https://github.com/2xAA/genmdm-editor).

## TFM Music Maker
Each `.tfi` file is a single FM instrument from a single audio track from a single game.  The format of the naming is as such:

`[xx] <track> n.tfi`

Where `[xx]` is the audio track number, `<track>` is the name of the audio track and `n` is (usually) a unique number across all instruments for this game.  Strangely `n` doesn't seem to follow any rhyme or reason and I'm unsure why they were numbered the way they are.  If you happen to know, please get in touch.

## GenMDM
Each `.genm` file contains up to 128 FM instruments for a single game.  The instrument names in the `.genm` file are formatted the same as the individual .`tfi` files above.  The name of each `.genm` file is formatted from the _no-intro_ romset naming convention for that game.

Some games have more than 128 instruments.  Those that do will will have filenames that end in `[xx-yy]` which are the audio track numbers included in that `.genm` file.

## Acknowledgements
* [little-scale](https://little-scale.blogspot.com/) for doing the hard work of creating/collecting all the `.tfi` files originally as well as making GenMDM.
* [2xAA](https://github.com/2xAA) for [GenMDM Parser](https://github.com/2xAA/genmdm-parser) that allowed me to convert all of the `.tfi` files  to `.genm` format, as well as [genMDM Editor](https://github.com/2xAA/genmdm-editor), the MIDI controller that can use (and modify) all these files.
* [rhargreaves](https://github.com/rhargreaves) for the [Mega Drive MIDI Interface](https://github.com/rhargreaves/mega-drive-midi-interface) that actually plays these instruments through my Genesis.
