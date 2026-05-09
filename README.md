# media-metadata-tool

Automation tool for collecting and processing publicly available media metadata from YouTube and Instagram using Python, Selenium, and Flask.

## Features

* Extracts metadata from YouTube videos and Shorts, including views, likes, comments, and related engagement data.
* Retrieves publicly available Instagram post and reel information such as captions, profile details, likes, and comments.
* Supports both command-line and browser-based interaction.
* Provides structured metadata processing through a lightweight Flask interface.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/media-metadata-tool.git
cd media-metadata-tool
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

The CLI allows users to retrieve supported YouTube and Instagram metadata by providing valid public URLs.

### Browser Version

Start the Flask application:

```bash
python api.py
```

The application will run locally at:

```bash
http://127.0.0.1:5000/
```

Users can submit supported YouTube or Instagram links through the web interface to retrieve metadata.

## Notes

* The tool processes only publicly accessible data.
* No private or restricted platform information is accessed.
* Intended for educational and development purposes.
