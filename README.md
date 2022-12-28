Test of MetaSound (for framework comparison).

## Steps to repro

- Added a track (under audio)
- Added a MetaSound to play the track
- Promoted the playback speed to a graph input
- Chaged the output to stereo and routed the playback to the output
- Added an audio component to the character and added the metasound as the sound of the component
- Triggered the component on Begin Play
- Linked the character's velocity to the playback speed