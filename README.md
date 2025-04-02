# TranscriptionWithWhsiperAI
Python script to take an audio file and transcribe it to a txt file

1. Download and Install FFmpeg
Whisper requires FFmpeg for audio processing. Here's how to install it:

Download FFmpeg:

Visit the official FFmpeg download page: https://www.ffmpeg.org/download.html?utm_source=chatgpt.com

Under "Get packages & executable files," click on the Windows logo.

You'll be directed to a page with Windows builds. Download the "ffmpeg-git-full.7z" version.

Extract FFmpeg:

Use a tool like 7-Zip to extract the downloaded .7z file.

Choose a destination like C:\ffmpeg.

Add FFmpeg to System PATH:

Open the Start Menu and search for "Environment Variables."

Click on "Edit the system environment variables."

In the System Properties window, click on "Environment Variables."

Under "System Variables," find and select the Path variable, then click "Edit."

Click "New" and add the path to the bin folder inside your FFmpeg directory, e.g., C:\ffmpeg\bin.

Click "OK" to save the changes.

Verify FFmpeg Installation:

Open Command Prompt and type ffmpeg -version.

If installed correctly, you'll see version information displayed.

2. Install Whisper
Whisper is OpenAI's speech recognition model. To install it:

Install Python:

Ensure you have Python 3.8 or higher installed. You can download it from the official Python website.

Install Whisper:

Open Command Prompt and run: pip install git+https://github.com/openai/whisper.git

Finally, use the Python script to run the program and transcribe your auido files.
