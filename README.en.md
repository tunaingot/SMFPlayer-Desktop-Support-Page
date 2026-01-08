# SMFPlayer-Desktop Support Page

[日本語](README.md)

## Overview
This application reads SMF (Standard MIDI File) and sends MIDI data to MIDI devices connected to your Mac.

## Features
1. MIDI data is copied to the storage area used by the application for processing, so the original data is never edited or deleted.
2. Displays performance information graphically on the keyboard display.
3. You can create a playlist featuring your favorites.

## Usage
When you download this application and use it for the first time, add the MIDI file you want to use to this application.

After that, you can play them back or create a playlist of your favorites.

### Import MIDI files into the application
Drag and drop MIDI files into the application.

When you drag and drop a folder, it will be added to the application while preserving its folder hierarchy.
<p align="center">
<img width="300" height="282" alt="image" src="images/100en.png" />
</p>

- The list of imported files can be viewed in the application like the Finder.
- Clicking the “SMF Folder” button in the upper-right corner of the window will open the location where imported files are saved in Finder.
- MIDI files and folders added or removed in Finder will be reflected in the application, even if they are not dragged and dropped into the application.

<p align="center">
<img width="300" height="246" alt="image" src="images/200en.png" />
</p>

#### Editing imported files
Imported files can be moved, deleted, have folders created for them, or have their names changed in Finder, but they can also be edited in the same way within the application.

File movement is possible via drag and drop.

The following operations will display a context menu when you press Control + click or right-click.

- Display the file in Finder
- Create folder
- Renaming files and folders
- Deleting files and folders
<p align="center">
<img width="300" height="246" alt="image" src="images/250en.png" />
</p>

- You can also create folders via the menu bar: “File > New > New Folder,” and a keyboard shortcut is assigned.
- You can also delete files via the menu bar's “Edit > Delete” option, and a keyboard shortcut is assigned.
- To rename files or folders, click the list to enable editing.

### Selecting a MIDI Device
Pressing the “MIDI” button in the upper-right corner of the window displays a pop-up list of MIDI devices connected to your Mac.

Please select the device to which you wish to send MIDI data.

<p align="center">
<img width="300" height="265" alt="image" src="images/300en.png" />
</p>

### Play MIDI files
Select the file you want to play, then press the play button to play the MIDI file.

<p align="center">
<img width="300" height="260" alt="image" src="images/400en.png" />
</p>

### Playback Controls
Only buttons that can be used are highlighted.

<p align="center">
<img width="500" height="131" alt="image" src="images/500en.png" />
</p>

- If the filename being played does not fit within the playback control width, scroll to display the filename.
- The Repeat Mode button lets you choose between Repeat, Repeat One Track, or No Repeat.
- Use the forward and rewind buttons to move to the previous or next track while playing.
- "Control + click" displays the context menu, allowing you to switch to the mini player.

## Playlist
You can create a “playlist” to collect your favorite tracks from MIDI files imported from Finder.

### Create Playlist
A context menu appears on the sidebar.

Selecting “New Playlist” will create a new playlist.

<p align="center">
<img width="300" height="246" alt="image" src="images/600en.png" />
</p>

You can also create a new playlist by selecting “File > New > New Playlist.”

### Add songs to the playlist
Click “All SMF” in the sidebar to view the files imported into the application.

Select the songs you want to add to your playlist from the displayed file list, then drag and drop them into the playlist you want to add them to.

<p align="center">
<img width="300" height="246" alt="image" src="images/700en.png" />
</p>

You can select files and folders from the “All SMF” list and drag and drop them into the playlist.

When you drag and drop a folder, all files within it will be added, but the directory structure will be lost.

### Playlist Editing
#### Change in song order
Select the files you want to reorder, then drag and drop them to swap their positions.

<p align="center">
<img width="300" height="246" alt="image" src="images/800en.png" />
</p>

#### Delete songs
Select the song you want to delete, then choose “Remove” from the context menu.

<p align="center">
<img width="300" height="246" alt="image" src="images/850en.png" />
</p>

#### Renaming a Playlist
Clicking the playlist name will make it editable.

Enter a new playlist name, then press the Return or Enter key to finish editing.

<p align="center">
<img width="300" height="246" alt="image" src="images/900en.png" />
</p>

#### Reordering Playlists
Select the playlist whose order you want to change, then drag and drop to rearrange it.。

<p align="center">
<img width="300" height="246" alt="image" src="images/1000en.png" />
</p>

#### Deleting Playlists
Select the playlist you want to delete, then choose “Remove” from the context menu.

<p align="center">
<img width="300" height="246" alt="image" src="images/1100en.png" />
</p>

## Setting
Clicking the “Setting” button in the upper-right corner of the window displays a popover showing the settings.

<p align="center">
<img width="300" height="246" alt="image" src="images/1200en.png" />
</p>

### Playback Device
#### Digital Piano
If the MIDI device connected to your Mac is a digital piano, select it if necessary.

Some MIDI files for piano pieces are created by splitting the harmonies across multiple channels.

Most digital pianos treat any MIDI channel they transmit on as MIDI channel 1.

However, if the digital piano is not configured this way, only data from MIDI channel 1 will be played.

Therefore, with this setting, SMFPlayer converts all MIDI data to channel 1 and sends it.
#### MIDI Tone Module
SMFPlayer sends MIDI data to MIDI tone module without performing any data conversion.

### Velocity Display
You can choose how to display the strength of your keystrokes.

Selecting “Keyboard Intensity” changes the color intensity based on how hard you press the keys.

“None” is always displayed in the bright color.

### Filename Reduce
Mainly use it for classical music.

When this setting's checkbox is selected, if the directory name where the file is located is included at the beginning of the filename, the included string will be omitted from display.

This is useful when you want to display a lot of song information in a narrow width.

<p align="center">
<img width="300" height="200" alt="image" src="images/1300en.png" />
</p>

## Media
[YouTube (SMFPlayer Desktop Quick Start Guide)](https://youtu.be/ZjoeS2dyPVk)