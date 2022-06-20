# text_to_speech
It is a technology that allows a computer to convert a written text into speech via a microphone or telephone. As an emerging technology, not all developers are familiar with speech technology. While the basic functions of both speech synthesis and speech recognition takes only minutes to understand, there are subtle and powerful capabilities provided by computerized speech that developers will want to understand and utilize. Automatic  speech synthesis  is one  of the  fastest  developing fields  in the  framework  of speech  science and engineering. As the new  generation of computing technology, it  comes as  the next  major innovation  in man-machine  interaction, after  functionality of Speech  recognition (TTS),  supporting Interactive  Voice Response (IVR) systems. 
The basic idea of text-to-speech (TTS)  technology is to convert  written input  to spoken  output by generating synthetic speech. There are several ways of performing speech synthesis: 
1. Simple voice recording and playing on demand; 
2. Splitting of speech into 30-50 phonemes (basic linguistic units) and their re-assembly in a fluent speech pattern;
3. The use of approximately 400 diaphones (splitting of phrases at the centre of the phonemes and not at the transition).
Packages Used:

pyttsx3: It is a Python library for Text to Speech. It has many functions which will help the machine to communicate with us. It will help the machine to speak to us
PyPDF2: It will help to the text from the PDF. A Pure-Python library built as a PDF toolkit. It is capable of extracting document information, splitting documents page by page, merging documents page by page etc.

Both these modules need to be installed

pip install pyttsx3
pip install PyPDF2

Approach:

Import the PyPDF2 and pyttx3 modules.
Open the PDF file.
Use PdfFileReader() to read the PDF. We just have to give the path of the PDF as the argument.
Use the getPage() method to select the page to be read.
Extract the text from the page using extractText().
Instantiate a pyttx3 object.
Use the say() and runwait() methods to speak out the text.
