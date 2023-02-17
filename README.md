# Auto Audiobooks
Convert pdf to audiobooks 📚


**Inspiration** : 
I am a Sinework negasi 🤓. I like reading research papers, articles and books. I also travel alot often from my work city to my hometown. During which I tend to feel unwell on account of motion sickness, if I read while travelling. Have been looking for a tool but either some of them had paid implementation or restrictions. Also audiobooks are pretty cool to multitask on and keep them running in the background 🖖🏻

So inspiration was to use existing tech available and with ~20 lines of code, build a simple, pdf -> audiobook generator. 🤞🏻

## Implementation
# text-to-speech_Tkinter
 this is project is a simple text to speech converter which uses Tkinter for the GUI and can also read a pdf.  



#Requirements
So in order to make it work you need to install a few things to get the whole thing working. the project is entierly written in python.

you need to install pyttsx3, which is the python library for text to speech.

      >pip install pyttsx3
      >pip install PyPdf2     

and install PyPDF2, which is the python library for messing around with the pdf files.

after you pip install both of these library. the code should work without any problem.

# Text box
 Enter text in the texbox, then hit enter and you should hear a robotic speech.
 
![](https://github.com/Sineworknegasi/Auto-PDF-to-Audiobook-converter/blob/main/Images/text.png)


# Pdf box
 Select a pdf file and then check the number of pages. 
 Then you can select starting page and end page of the pdf and then open the pdf. The text from defiened pages will get inserted into the textbox, from hear     just hit convert and you can hear the text no problem.

![](https://github.com/Sineworknegasi/Auto-PDF-to-Audiobook-converter/blob/main/Images/pdf.png)

# Settings box
You can select male or female voice here and also the rate at which the speaker talks. 
the rate goes from -100(slowest) to 100(fastest)

![](https://github.com/Sineworknegasi/Auto-PDF-to-Audiobook-converter/blob/main/Images/settings.png)


## License
 
The MIT License (MIT)
Copyright (c) 2023 Sineworknegasi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
