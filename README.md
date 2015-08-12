# NoteHelper
Command Line Utility for creating new notes with the Mac OSX Notes app using AppleScript

## Running
You can run the AppleScript by using the following command:
```
> /usr/bin/osascript /path/to/NoteHelper/make_note.scpt Hello, world
```
The script will create a note with the text 'Hello, world'

## Running as an alias
To make it easier to run, I recommend using an alias. To do so, pass the arguments to the script so it can create a new note with the text you give it.
```
notes="/usr/bin/osascript /path/to/NoteHelper/make_note.scpt $@"
```
This allows you to create a new note by typing
```
> notes This will be the text in the note
```
Or if you simply want to launch the Notes application, just type
```
> notes
```
