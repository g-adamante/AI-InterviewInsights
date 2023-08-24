# AI-InterviewInsights

This project provides an easy-to-use interface for generating concise reports from Google Meet recordings of customer interviews. By using this tool, you can automatically transcribe and summarize your recorded interviews without the need for manual efforts.

Features:

    Convert Google Meet MP4 recordings to MP3 audio files using FFmpeg (WebAssembly version).
    Automatic transcription of the audio using OpenAI's Whisper ASR model.
    Summarize the transcription using OpenAI's GPT-4.
    Entire process runs on the client side: zero data is shared with the server.

Prerequisites:

    API Token: To use the transcription and summary features, you need an OpenAI API token. If you don't have one, you can get it from the OpenAI website.

    Browser Compatibility: This tool uses WebAssembly, which requires a modern browser. Ensure you're using a recent version of Chrome, Firefox, Safari, or Edge.

Usage:

    Enter your OpenAI API token in the designated input field.
    Upload your Google Meet MP4 recording.
    Wait for the video to be processed. Checkmarks will appear as each task (conversion, transcription, summary) is completed.
    Once the processing is done, you can review the full transcript and the summarized report on the page.

Limitations:

    Because of the context-size, the recommended size for the video file is up to 30 minutes.
    Ensure the video file is in MP4 format.

Privacy:

All data processing, including transcription and summary generation, occurs on the client side. No data is sent to or stored on any server, ensuring the privacy of your recordings and transcripts.
Dependencies:

    FFmpeg (WebAssembly version): For MP4 to MP3 conversion.
    TailwindCSS: For styling.

Contribution:

Feel free to fork this repository, make changes, and submit pull requests. If you find any bugs or have feature requests, please open an issue in this repository.
License:

This project is open source, under the MIT License. Use it, modify it, and distribute it as you wish.
