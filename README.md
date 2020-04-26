# Text-to-speech-convert

Here we simply convert any text to speech and we can also change the pitch and speed of the speech

## Dependency

for material text design, we simple add material dependency in `build.gradle` **App** module 

<img src="texttospeech/Capture1.JPG">

and add **maven** in `build.gradle` **Project**
module

<img src="texttospeech/Capture2.JPG">

## Getting Started

In **XML** file we need to add `TextView` for entering the text, here material textview is used

<img src="texttospeech/Capture3.JPG">

for changing the **pitch** of the voice `SeekBar` is used

<img src="texttospeech/Capture4.JPG">

and for changing the **speed** of the voice also `SeekBar` is used

<img src="texttospeech/Capture5.JPG">

and used a `Button` to hear the voice

<img src="texttospeech/Capture6.JPG">

In **JAVA** file, first we used `TextToSpeech` property to convert the text to speech and as per your requirement you can change the 
**LOCAL** language. Here by default, **ENGLISH** is used to speech

<img src="texttospeech/Capture7.JPG">

Then create a funtion where *pitch* and *speed* limits are set and call the **TextToSpeech** and also set the pitch and speed variables with 
it.

<img src="texttospeech/Capture8.JPG">

After that, when **SPEAK IT** button clicked *speak* function called.

<img src="texttospeech/Capture9.JPG">

## Want to hear that

https://github.com/barmangolap15/Text-to-speech-convert/blob/master/texttospeech/20200423-234133-480x1028.mp4






