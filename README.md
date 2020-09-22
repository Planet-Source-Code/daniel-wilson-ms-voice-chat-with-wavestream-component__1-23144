<div align="center">

## MS Voice Chat with Wavestream Component


</div>

### Description

This code is a modified version of MS Voice Chat from the Visual Basic 5 CD. I noticed some viewers were having problems with wavestream.dll eather not existing on their system, or a modifed version of it. This project contains wavestream.dll hardcoded into the application and does not require the actual DLL what so ever. I expect this will help speed things up and prevent future problems with different versions of the wavestream.dll. A few minor bugs were also fixed. this should work in VB5, 6 and 7 with no problems, as long as you have the Microsoft GSM 6.10 Codec (i belive its shipped with MSWin9x) If not look in the Form_load of frmChat, comment out the line with WAVE_FORMAT_GSM610 and uncomment the line with WAVE_FORMAT_PCM or WAVE_FORMAT_MSN_AUDIO
 
### More Info
 
Voice

Voice data will occasionaly be obliterated for some as yet unknown reason and remains that way until winsock catches up and stops recieving. If you find the cause i would love to hear an explination.


<span>             |<span>
---                |---
**Submitted On**   |2001-05-12 13:20:02
**By**             |[Daniel Wilson](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/daniel-wilson.md)
**Level**          |Advanced
**User Rating**    |4.8 (106 globes from 22 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Sound/MP3](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/sound-mp3__1-45.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[MS Voice C195525122001\.zip](https://github.com/Planet-Source-Code/daniel-wilson-ms-voice-chat-with-wavestream-component__1-23144/archive/master.zip)








