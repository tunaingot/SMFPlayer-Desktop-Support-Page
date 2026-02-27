# SMFPlayer-Desktop Support Page

[日本語](README.md)

## Overview
This application reads SMF (Standard MIDI File) and sends MIDI data to MIDI devices connected to your Mac.

## Features
1. Displays performance information graphically on the keyboard display.
2. You can create a playlist featuring your favorites.
3. You can play SMF file inside ZIP file.
4. You can view document inside ZIP file.
5. You can enter the song title without changing the file name.

### Support for ZIP files
Starting with version 3.0.0, you can now play SMF files contained within ZIP files.

The following features and limitations apply:

1. Files other than SMF files are also acceptable.
2. If there are multiple MIDI files within a ZIP file, only the first file found will be played.
3. If a ZIP file contains a text file, the "Show Document" option in the context menu becomes available and displays the document's contents in a separate window.

### Changes to File Handling Due to In-App Purchases
Up to version 4.0.0, files were copied within the application's restricted area.  
By making an in-app purchase, users can use MIDI files within the specified folder.  
When you specify cloud storage, you can use the same MIDI files across multiple Macs and share the song titles you've entered.

## Usage
When you download this application and use it for the first time, add the MIDI file you want to use to this application.

If you make an in-app purchase, select the folder containing the MIDI files.。

After that, you can play them back or create a playlist of your favorites.

### When using without in-app purchases
#### Import MIDI files into the application
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

### When making an in-app purchase
#### Select the location of the MIDI file

Select "File > Select MIDI Files Folder..." from the menu bar.  
A panel for selecting a folder will open. From here, please select the folder containing the MIDI files.

<p align="center">
<img width="300" height="246" alt="image" src="images/260en.png" />
</p>

#### Editing Files and Folders
You can edit song titles, but

- Moving files
- Create a new folder
- File deletion

It is not possible.  
Please perform these tasks in Finder.  
Currently, undo is not supported, so these operations are disabled.

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

## Search
File search functionality has been added starting with version 3.0.0.

You can play search results and add search results to a playlist.
<p align="center">
<img width="300" height="221" alt="image" src="images/1250en.png" />
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