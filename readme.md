# Welcome to the *Rock Band 3 ~~Deluxe~~ Vanilla Plus* repository!

### This is a fork that is simply the base of rb3 dx but without many additional things focused on performance on ps3, currently it is only ark of original tu5 of ps3 with songs updates and correct midi parser

### Installing on PS3
* In the action section you will find the most current build of Vanilla Plus, which will be updated from time to time. You need a GitHub account to download it.
* It's a pkg in .zip just extract it and install it on your ps3
## TODO
 These are features I would like to support in the future, but it may take me a while to read through them before porting them.
* [ ] Author Finder (Source and author name only)
       * The rest of the metadata is not very relevant to be honest.
* [ ] Lyric display
* [ ] Golden Stars Animation
* [ ] Countdown
* [ ] Custom Textures
      * This is what I think will be the most difficult thing to bring here.
This doesn't mean that there may be other functions implemented here, but I need to see their previous importance and if PS3 takes it well.

# 🖥️ Dependencies

[Git for Windows](https://gitforwindows.org/) - CLI application to allow auto updating Deluxe repo files

[Dot Net 6.0 Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime) - Needed to run ArkHelper

[Python](https://www.python.org/downloads/) - For user script functionality (NOTE: 3.9 or newer is highly recommended!)

[Mackiloha](https://github.com/PikminGuts92/Mackiloha) - ArkHelper for building Deluxe - SuperFreq for building .bmp_xbox highway images

[swap_rb_art_bytes.py](https://github.com/PikminGuts92/re-notes/blob/master/scripts/swap_rb_art_bytes.py) - Python script for converting Xbox images to PS3

[dtab](https://github.com/mtolly/dtab) - For serializing `.dtb` script files

[RB3DXBuildPkgPS3](https://github.com/InvoxiPlayGames/RB3DXBuildPkgPS3) - For building an RB3DX PKG for PS3
