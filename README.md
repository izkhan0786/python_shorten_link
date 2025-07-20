# Flask URL Shortener

A simple Flask app that shortens long URLs and redirects them using a short code. No database is used — it stores data in memory and resets on every restart. Mobile-friendly with Bootstrap.

## How to Run

Clone the repo, install Flask, and run the app:

```bash
git clone https://github.com/your-username/flask-url-shortener.git
cd flask-url-shortener
source .venv/bin/activate  #for vitual environment activate
pip install -r requirements.txt
python app.py
Then open http://127.0.0.1:5000 in your browser.
