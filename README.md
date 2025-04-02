:

🎙️ TranscriptionWithWhisperAI
A simple Python script that uses OpenAI's Whisper to transcribe audio files into .txt text files using a user-friendly file picker interface.

📦 Features
GUI-based audio file selection

Transcribes audio to text using Whisper

Saves the result in the same folder as the input file

FFmpeg dependency check with helpful error handling

🛠️ Requirements
Python 3.8+

OpenAI Whisper

FFmpeg

Tkinter (usually preinstalled with Python)

🧩 Installation
1. Install FFmpeg
Whisper uses FFmpeg to process audio. Follow these steps to install it on Windows:

➤ Download FFmpeg
Visit: https://ffmpeg.org/download.html

Click the Windows logo under "Get packages & executable files"

Download the ffmpeg-git-full.7z build

➤ Extract FFmpeg
Use 7-Zip or another extraction tool

Extract to a folder like: C:\ffmpeg

➤ Add FFmpeg to PATH
Open the Start Menu → search "Environment Variables"

Click "Edit the system environment variables"

In System Properties, click "Environment Variables…"

Under System Variables, select Path → click Edit

Click New → add:

makefile
Copy
Edit
C:\ffmpeg\bin
Click OK on all dialogs

➤ Verify Installation
Open Command Prompt and run:

bash
Copy
Edit
ffmpeg -version
You should see version info printed to the terminal.

2. Install Whisper
➤ Install Python
Make sure Python 3.8+ is installed:
https://www.python.org/downloads/

➤ Install Whisper via pip
bash
Copy
Edit
pip install git+https://github.com/openai/whisper.git
🚀 Usage
Run the script:

bash
Copy
Edit
python whisper_gui_transcribe.py
A file picker will appear. Select your audio file (.wav, .mp3, .m4a, etc.)

The script will transcribe it and save a .txt file in the same folder.

💡 Example
Input File	Output File
Intro.wav	Intro.txt
Interview.m4a	Interview.txt
📌 Notes
If FFmpeg is not detected, the script will show a popup with installation instructions.

Supported audio formats depend on your FFmpeg build (.mp3, .wav, .m4a, .webm, .flac, etc.)

🧠 License
This project uses the MIT License.

