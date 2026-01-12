Church of Agranari

# Episode Creation Instructions

These instructions were based on the process used for episode 2, about New Year’s Resolutions.

## Script

Tool: Microsoft Word w/ Writage

1.  Sections
    1.  Teaser
        1.  Main question of the episode
    2.  Intro
        1.  Introduce yourself
        2.  Starting prayer
    3.  Topic
    4.  Conclusion
    5.  Outro
        1.  Ending Prayer
        2.  Recommended song
        3.  Request for comment
2.  Save file
    1.  Location: AgranariChurch/Scripts/
    2.  File format: [XXX]-[EpisodeTitle]
        1.  ex: 002-NewYearsResolution
    3.  file type: .md
3.  Commit to GitHub
    1.  Commit message: [XXX] [EpisodeTitle] script

## Admin Step

Tool: File Explorer

1.  Go to AgranariChurch/Episodes
2.  Create folder for episode
    1.  Format: [XXX]-[EpisodeTitle]
        1.  ex: 002-NewYearsResolution
3.  This is the main folder for the episode.

## Audio

Tool: Audacity

1.  Setup good recording mic (don’t use webcam!)
2.  Record audio in one take
3.  Save file
    1.  Location: episode folder
    2.  File type: .aup
4.  Export audio
    1.  File type: .wav

## Video

Tool: DaVinci Resolve

1.  Create Project
    1.  New Project
    2.  Name: episode title
    3.  Change location to episode folder
2.  Set resolution
    1.  Workspace: Deliver
    2.  Resolution: 1920x1080 HD
3.  Add media
    1.  workspace: Media
    2.  Add images and audio from episode folder
4.  Edit video
    1.  Place audio in first, edit it
    2.  Place deer avatar
        1.  Zoom 0.55
        2.  Position (-1285, -300)
5.  Render video
    1.  Workspace: Deliver
    2.  Filename
    3.  Location
    4.  Format: MP4
    5.  Resolution: 1920x1080
    6.  Render (bottom of render settings)
    7.  Render all (in top right panel, in the bottom right)

# YouTube

Title: a question

Description: include sources and tools

Thumbnail: 1280 x 720, black with white logo in bottom left corner, with icon of main topic front and center (theres a PDN in episode 1’s folder that you can use easily)

Tags, I guess

Playlist: Weekly videos

End card to other video if you feel like it

# Short

## DaVinci Resolve

1.  Change project settings to be vertical
    1.  Edit teaser to be vertical
        1.  Workspace: Deliver
            1.  Type: MP4
            2.  Resolution: Custom / Vertical / 1080x1920
        2.  Render

## YouTube

1.  Title: same as video, include **\#shorts**
    1.  Reuse details from main video
        1.  Playlist: Weekly videos (shorts)
            1.  Set as related to main video

# Cheat Sheet

| **Key**              | **Value**               | **Example**            |
|----------------------|-------------------------|------------------------|
| Scripts Folder       | AgranariChurch/Scripts/ |                        |
| Episode Title Format |  [XXX]-[EpisodeTitle]   | 002-NewYearsResolution |
| Episode folder       | AgranariChurch/Episodes |                        |
| Audio file type      | .WAV                    |                        |
| Resolution           | 1920x1080               |                        |
| Thumbnail            | 1280x720                |                        |
| Export file type     | MP4                     |                        |
| Key Split            | CTRL+\\                 |                        |
| Key Begin Spot       | I                       | selective rendering    |
| Key End Spot         | O                       | selective rendering    |
