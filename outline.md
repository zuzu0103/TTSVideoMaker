# TTS Video Maker

## UI
    UI interface to set peramaters, maybe with multiple pages, plenty of space for saving settigs.  Need to find what filetype to use to save between restarts - json?

## Audio
### Parse
    Parse text, limit into blocks.  Limited by characters such as "," and "." for stories or ">" for greentexts.  Hold parsed text in a list.
### Tortoise (TTS)
    Start command line Tortoise?  Generate blocks of text using Tortoise as a TTS, allow editing of tortoise yaml from UI.
### RVC
    Convert voice snippets to final voice, save these ready to go into video.  Allow selecting voice model and other inputs in UI, be able to save presets.

## Video
### Images
    Use parse text list to generate images, along with input such as style, username, pfp/photo.
### Video
    Use lenght of single audio clips to dictate when to show next image.  Add minecraft parkour in the back and music, allow selecting path for both of these and selecting frame size.