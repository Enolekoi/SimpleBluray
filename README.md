# SimpleBluray
A very simple shell script that automatically unlocks a bluray disk using MakeMkv and then plays it in MPV. 

Playing a bluray in Linux (or on any operating system really) is unnessecarily complicated and annoying, so I wrote this little script which allows the user to play one by running a simple command.
# Dependencies
- [**MakeMkvKey**](https://github.com/Enolekoi/MakeMkvKey) *(optional)*
- [**MakeMkv**](https://forum.makemkv.com/forum/viewtopic.php?f=3&t=224)
- [**MPV**](https://github.com/mpv-player/mpv)

# Installation
1. Place the script somewhere in your path.
2. Edit the variable `drive` with the location of the bluray drive you want to use (the default location is `/dev/sr0` ).
3. If you **don't** want to automatically update the Beta Key of MakeMkv when trying to play a disk comment out `MakeMkvKey` *(optional, not recommended)*.

# Usage
Play a bluray by running the script using `$ bluray`.
