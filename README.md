README.md
English → German Shadowing App (Text/PDF → MP3 + Text)

Version: Dec 2025
Platform: Streamlit (Python 3.13+)
Purpose: PDF ya text input se English → German translation + TTS MP3 generation for shadowing practice.

Features

Input Options:

Paste English text directly

Upload PDF containing English sentences

Translation & Audio:

Automatic English → German translation (via deep-translator)

TTS audio in:

English (optional)

German (optional slow speed)

15-second real pause added between sentences for shadowing

Output:

Playable MP3 audio inside Streamlit

Download buttons:

Shadowing MP3

Translated German text

Full translated text visible in expandable text area

Caching:

Translation and audio generation cached for faster performance

Installation

Clone or download the repository

Create virtual environment (recommended)

python -m venv venv


Activate virtual environment

Windows: venv\Scripts\activate

Mac/Linux: source venv/bin/activate

Install dependencies

pip install -r requirements.txt


requirements.txt example:

streamlit==1.25.0
PyPDF2==3.1.0
gTTS==2.3.2
deep-translator==1.11.1

Usage

Run the app:

streamlit run app.py


Open browser → http://localhost:8501

Choose input method:

Paste Text: Paste your English sentences

Upload PDF: Upload a PDF with English sentences

Configure options:

English first: Play English TTS before German

German slow: Slow German speech for better shadowing

Click:

Text → German MP3 + Text Banao (if text pasted)

PDF → German MP3 + Text Banao (if PDF uploaded)

Output:

Listen to MP3 inside app

Download MP3 + translated text

Notes

Works fully offline after dependencies installed

Uses Google Translate API via deep-translator

Maximum efficiency with caching

15-second pause included for shadowing practice

Troubleshooting

ModuleNotFoundError

pip install -r requirements.txt


Slow translation or TTS issues

Make sure your internet connection is active

Avoid extremely long PDFs (>500 pages) in one go

MP3 not playing

Check browser audio support

Try smaller text chunks for testing

License

Free to use for personal learning and shadowing practice

Attribution appreciated
