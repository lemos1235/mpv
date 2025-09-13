# mpv

my settings for MPV (Windows/Mac/Linux Compatible)

might not be suitable for your pc, but if you have any recommendations, just tell me, 
or just make a pull request. If i like it, i put it in.

# Documentation
Here goes all information about scripts and upscaler used. (WIP)

# List of Scripts used in my mpv-settings:

- Mac_Integration.lua - This script enables a few shortcuts which Mac users are familiar with. See scripts/Mac_Integration.lua for more infos.
- acompressor.lua - a simple audio compression script which can normalize your audio of the files played with mpv. See scripts/acompressor.lua for more infos.
- appendURL.lua - when mpv is opened, you can copy paste a URL in to play from.
- audio-osc.lua - different on screen controls for audio-only playback.
- autoload.lua - preloads all files in a folder into a playlist.
- seek-to.lua - when "t" is pressed, you can seek to a specific part of the video/audio you are currently watching.
- webm.lua - Simple WebM maker for mpv. By default, the script is activated by the W (shift+w) key.
- playlistmanager.lua - This script allows you to see and interact with your playlist in an intuitive way. SHIFT+ENTER = playlist
- modernx.lua - A modern OSC UI replacement for MPV that retains the functionality of the default OSC. 
- quality-menu.lua - Allows you to change the streamed video and audio quality (ytdl-format) on the fly. Simply open the video or audio menu, select your prefered format and confirm your choice. The keybindings for opening the menus are configured in input.conf, and everthing else is configured in quality-menu.conf. By default: List Video Formats: F (shift+f), List Audio Formats: Alt+f, Reload: Ctrl+r

# Installation
Depending on your Operating System, you need to place the stuff inside the zip in a certain directory.
The root directory needs to look like this (Should be considered a Tree View example):


>Roaming

>>mpv

>>>input.conf

>>>mpv.conf

>>>shaders

>>>script-opts

>>>scripts

>>>fonts
