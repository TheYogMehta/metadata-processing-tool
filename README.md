# yt-ig-scraper

Automation tool for collecting and processing publicly available media metadata from YouTube and Instagram using Python, Selenium, and Flask.

## Features

* Extracts metadata from YouTube videos and Shorts, including views, likes, comments, and related information.
* Retrieves publicly available Instagram post and reel data such as captions, engagement metrics, and profile information.
* Supports both command-line and browser-based interaction.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/yt-ig-scraper.git
cd yt-ig-scraper
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

### CLI Version

Run the command-line interface:

```bash
python main.py
```

The CLI allows users to fetch metadata by providing supported YouTube or Instagram URLs.

### Browser Version

Start the Flask application:

```bash
python api.py
```

The application will run locally at:

```bash
http://127.0.0.1:5000/
```

Users can submit supported YouTube or Instagram links through the browser interface to retrieve metadata.

## Notes

* The tool processes only publicly accessible data.
* No private or restricted platform information is accessed.
