# Audiobook-Generator
![audiobook](https://buggyprogrammer.com/wp-content/uploads/2021/05/Voice-Cloning.png)
---

Reading books in Audio format now becomes a trend, it’s productive, entertaining, and time-saving. You may have seen many companies selling these audiobooks and you might be using one. But do you know you can create an audiobook using python by yourself using python or you create a voiceover for any video or script? It won’t be good as them as they hire voice artists for that but yeah it’s good to some extent and most important thing is that it’s fun, informative, and entertaining. 

I have demonstrated two ways for doing this task, first one is using pyttsx3, which works offline which means you will not need any internet for that and another way is using gTTS which is a Python library and CLI tool to interface with Google Translate text-to-speech API

Checkout this project on my website [buggyprogrammer](https://buggyprogrammer.com/how-to-create-an-audiobook-using-python-in-2021/), where I have explained everything step by step.

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

Since the github markdown dosen't support audio files, I have uploaded the generated audio in my [website](https://buggyprogrammer.com/wp-content/uploads/2021/05/Audiobook-1.mp3) so you can hear that there.



## Library used
|Library|Desc|
|:-:|:-|
|`GTTS`|_GTTS stands for google text to speech, it is a google api for converting text to speech (tts). It support multiple language or accents for tts such as Hindi, English and Arabic_ <br> **[Read more about it here](https://gtts.readthedocs.io/en/latest/)**|
|`pyttsx3`|_pyttsx3 is a text-to-speech conversion library in Python. Unlike alternative libraries, it works offline, and is compatible with both Python 2 and 3_. It uses local system's voice_ <br> **[Read more about it here](https://pypi.org/project/pyttsx3/)**|
|`pyPDF2`|_I have utilized this library for reading and extracting text. `pyPDF2` is one of python library used for handling pdf files._ <br>**[Read more about it here](https://pypi.org/project/PyPDF2/)**|
|`re`|_A Python's built-in package, which can be used to work with Regular Expressions. I have utilized this for little text filtering_ <br> **[Read more about it here](https://docs.python.org/3/library/re.html)**|

And some other basic library library..
