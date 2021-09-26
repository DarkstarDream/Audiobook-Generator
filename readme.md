# Audiobook-Generator
![audiobook](https://buggyprogrammer.com/wp-content/uploads/2021/05/Voice-Cloning.png)
---

Reading books in Audio format now becomes a trend, it’s productive, entertaining, and time-saving. You may have seen many companies selling these audiobooks and you might be using one. But do you know you can create an audiobook using python by yourself using python or you create a voiceover for any video or script? It won’t be good as them as they hire voice artists for that but yeah it’s good to some extent and most important thing is that it’s fun, informative, and entertaining. 

I have demonstrated two ways for doing this task, first one is using pyttsx3, which works offline which means you will not need any internet for that and another way is using gTTS which is a Python library and CLI tool to interface with Google Translate text-to-speech API

## Project sample
I have used first two page of the book "Clean Code" for creating audiobook.
<table>
<td>
<img src="https://github.com/DarkstarDream/Audiobook-Generator/blob/master/files/page1.jpg" style="width:500px">
<td>

<td>
<img src="https://github.com/DarkstarDream/Audiobook-Generator/blob/master/files/page2.jpg" style="width:500px">
<td>
</table>

Since the github markdown doesnot support audio files, I have uploaded the generated audio in soudcloud.

<iframe width="100%" height="100" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1131161374&color=%23ff9900&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true&visual=true"></iframe><div style="font-size: 6px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 10;"><a href="https://soundcloud.com/dhruv-singh-811539000" title="Dhruv" target="_blank" style="color: #cccccc; text-decoration: none;">Dhruv</a> · <a href="https://soundcloud.com/dhruv-singh-811539000/elonpdf" title="Elonpdf" target="_blank" style="color: #cccccc; text-decoration: none;">Elonpdf</a></div>


## Library used
|Library|Desc|
|:-:|:-|
|`GTTS`|_GTTS stands for google text to speech, it is a google api for converting text to speech (tts). It support multiple language or accents for tts such as Hindi, English and Arabic_ <br> **[Read more about it here](https://gtts.readthedocs.io/en/latest/)**|
|`pyttsx3`|_pyttsx3 is a text-to-speech conversion library in Python. Unlike alternative libraries, it works offline, and is compatible with both Python 2 and 3_. It uses local system's voice_ <br> **[Read more about it here](https://pypi.org/project/pyttsx3/)**|
|`pyPDF2`|I have utilized this library for reading and extracting text. `pyPDF2` is one of python library used for handling pdf files.<br>**[Read more about it here](https://pypi.org/project/PyPDF2/)**|
|`re`|A Python's built-in package, which can be used to work with Regular Expressions. I have utilized this for little text filtering <br> **[Read more about it here](https://docs.python.org/3/library/re.html)**|

And some other basic library library..
