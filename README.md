# YouTube Transcript Summarizer

## Overview

YouTube Transcript Summarizer is a web application designed to simplify the process of understanding lengthy YouTube videos. By utilizing the power of natural language processing (NLP), this tool fetches video transcripts and generates concise, accurate summaries. The project is built using Flask for the backend, and leverages the YouTube APIs, NLTK, and SpaCy libraries for effective transcript summarization.

## Features

- **YouTube API Integration**: Fetches transcripts of YouTube videos based on the provided URL.
- **NLP-Driven Summarization**: Utilizes NLTK and SpaCy to generate concise summaries of the video transcripts.
- **Optimized Accuracy**: Focuses on delivering high-quality, accurate summaries that capture the essence of the video content.
- **User-Friendly Interface**: A clean and simple UI designed for ease of use.

## Technologies Used

- **Backend**: Flask
- **Frontend**: HTML, CSS, JavaScript
- **APIs**: YouTube Data API
- **NLP Libraries**: NLTK, SpaCy

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/parth968/YouTube-Transcript-Summarizer.git
   cd YouTube-Transcript-Summarizer
   ```

2. **Set up a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up YouTube Data API:**
   - Obtain an API key from the [Google Developer Console](https://console.developers.google.com/).
   - Replace `YOUR_API_KEY` in the code with your actual API key.

5. **Run the application:**
   ```bash
   flask run
   ```

6. **Access the application:**
   Open your browser and go to `http://127.0.0.1:5000`.

## Usage

1. Enter the URL of the YouTube video you want to summarize.
2. Click on the "Summarize" button.
3. The application will fetch the transcript, process it using NLP, and display a summarized version.

## Project Structure

```
YouTube-Transcript-Summarizer/
├── static/
│   ├── css/
│   └── js/
├── templates/
│   └── index.html
├── app.py
├── requirements.txt
└── README.md
```

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [YouTube Data API](https://developers.google.com/youtube/v3)
- [NLTK](https://www.nltk.org/)
- [SpaCy](https://spacy.io/)
