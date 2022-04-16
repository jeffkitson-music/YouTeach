# Need Instructions?
[HERE IS THE INSTRUCTIONS PAGE!](INSTRUCTIONS.MD)

# 🎓 YouTeach
A minimalist GUI wrapper of [pytube](https://github.com/pytube/pytube) specifically designed for teachers. 

## 📚 About
**The Goal**

Create a barebones tool for teachers to use to download YouTube videos for class presentation.

**The Problem**

There are essentially two problems with showing/downloading YT videos for class:
- If you don't download the video, you are likely to get ads when presenting. 
   - Ads are **NOT** appropriate in a classroom.
   - Ads will be based on the teacher's personal account (if that's what they're using)  
   - Additionally, this might potentially expose other personal information (recommended videos, etc.) based on the teacher's personal YT account. 
- If you do download the video, you usually have to rely on untrustworthy sites that are 
  - Ad-heavy at best
  - Malicious at worst

**The Solution/What YouTeach does**

YouTeach allows teachers to easily download videos from YouTube to include in PowerPoints for presentation in class lectures. This tool is designed with the idea that teachers will download a video, edit to the most relevant portion (or trim in the built-in PowerPoint Tool), and then embed the video in PowerPoint for east of use. This is something that I have nicknamed, "Just push play..." 

## :thumbsup: :thumbsdown: Trade-offs/Balancing Act
This is **not** a general purpose video downloader. 

While pytube is a powerful library, YouTeach is designed to be as barebones as possible and to "just work" for teachers in limited conditions and circumstances. The highest quality MP4/MP3 file is chosen and English is the default subtitle language. These are purposeful decisions made to strike a balance between functionality and ease-of-use and ultimaetly to limit the scope of the project. In essence this is a "quick-and-dirty" tool to help teachers avoid the problems mentioned above. 

## :memo: Saving Captions/Subtitles
As schools transition toward Universal Design for Learning (UDL) principles, it is often more important than ever to include subtitles on video content used in the classroom. 

YouTeach attempts to download the English subtitles of the selected video. The captions are then converted to webvtt format (used by PowerPoint) and saved to the same directory as the video. For now, teachers will need to manually associate the caption file with the video file in their PowerPoint presentation. 

## 	⚖️: Ethics/Fair Use
Creators deserve to be paid for their content. Additionally, in the era of views counting for clout and channel advancement, teachers **must** stay within the ethical boundaries of [Academic Fair Use](https://www.lib.uchicago.edu/copyrightinfo/fairuse.html) and not steal or economically harm creators. 

## ⚠️ Disclaimer
**This is a hobby project and a proof-of-concept.** 

This is not intended for real-world use. 

## :mega: Shoutouts
- [appJar](https://appjar.info) a simple tKinter wrapper for beginners. Made by a teacher!
- [pytube](https://github.com/pytube/pytube) for the original repo.
- [webvtt-py](https://github.com/glut23/webvtt-py) for their srt to webvtt conversion tool. So easy!


