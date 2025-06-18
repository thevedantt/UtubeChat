# 🎥 YouTube Video Chat Assistant 

This Python project lets you enter a YouTube video link, extract its details and description using `yt_dlp`, and then interact with an AI chatbot powered by Google's Gemini Flash 2.0. You can ask questions about the video based on its description.

## ✅ Features

- Accepts YouTube video links
- Displays title, views, duration, rating, and description
- Uses Google's Gemini AI (via API key) to chat about the video content
- Interactive question-answering loop
- Gracefully handles invalid links or unavailable videos

## 🚀 How to Run

1. Install dependencies:

```bash
pip install yt-dlp google-generativeai
```

2. Run the script:

```bash
python your_script_name.py
```

3. Input a YouTube video link when prompted.

4. Ask questions about the video. Type `exit` to quit.

## 🔐 Note

Replace the Gemini API key in the script with your own to enable AI responses.
