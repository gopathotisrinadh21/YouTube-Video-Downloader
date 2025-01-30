# YouTube Video Downloader

## Overview
This is a simple YouTube Video Downloader built using Flask for the backend and HTML, CSS for the frontend. The application allows users to enter a YouTube video URL and download the video in various available formats.

## Features
- Download YouTube videos in multiple resolutions.
- Simple and user-friendly UI.
- Fast and efficient processing.
- Error handling for invalid URLs.

## Tech Stack
- **Backend**: Flask (Python)
- **Frontend**: HTML, CSS
- **Libraries Used**:
  - `pytube` (for downloading YouTube videos)
  - `flask` (for creating the web server)

## Installation

### Prerequisites
Make sure you have Python installed. You can download it from [python.org](https://www.python.org/).

### Steps to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/youtube-video-downloader.git
   cd youtube-video-downloader
   ```
2. Create a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the Flask app:
   ```sh
   python app.py
   ```
5. Open your browser and go to `http://127.0.0.1:5000/` to use the application.

## Project Structure
```
/ youtube-video-downloader
│── /static
│   ├── style.css
│── /templates
│   ├── index.html
│── app.py
│── requirements.txt
│── README.md
```

## Usage
1. Open the application in your browser.
2. Paste the YouTube video URL in the input field.
3. Select the desired video quality.
4. Click the "Download" button to get the video.

## License
This project is licensed under the MIT License.

## Contact
For any queries, contact: [srinadhgopathoti@gmail.com]

