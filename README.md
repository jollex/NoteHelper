# NoteHelper
Command Line Utility for creating new notes with the Mac OSX Notes app using AppleScript

## Running
You can run the AppleScript by using the following command:
```
> osascript /path/to/make_note.scpt Hello, world
```
The script will create a note with the text 'Hello, world'

## Running as an alias
To make it easier to run, I recommend using an alias. To do so, you have to define the command you want to use as a function so that you can pass in the arguments:
```
notes () { /path/to/make_note.scpt $@ }
```
This allows you to create a new note by typing
```
> notes This will be the text in the note
```
Or if you simply want to launch the Notes application, just type
```
> notes
```
