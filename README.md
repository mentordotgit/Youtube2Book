# YouTube Playlist to Book

YTplaylist2Book is a Python script that converts a YouTube playlist into a PDF document. It downloads the videos, extracts their transcripts, and includes them in the PDF along with the video titles and descriptions.

## Demo

Playlist: [LangChain How to and guides by Sam Witteveen](https://www.youtube.com/watch?v=J_0qvRt4LNk&list=PL8motc6AQftk1Bs42EW45kwYbyJ4jOdiZ)
Pdf book: [LangChain How to and guides.pdf](https://github.com/mshojaei77/Youtube2Book/blob/main/LangChain%20How%20to%20and%20guides.pdf)

## Features

- Access videos from a YouTube playlist
- Extracts transcripts from each video
- Creates a PDF document with the playlist's information
- Includes video thumbnails in the PDF
- Logs progress and errors for easy troubleshooting

## Prerequisites

- Python  3.x installed on your machine
- Required Python libraries: `pytube`, `youtube_transcript_api`, `fpdf`, and `requests`

## Installation

To install the required Python libraries, run the following command:

```bash
pip install pytube youtube_transcript_api fpdf requests
```

## Usage

1. Run the script from the command line:

```bash
python YTplaylist2Book.py
```

2. When prompted, enter the URL of the YouTube playlist you want to convert to a PDF.

3. The script will extract their transcripts, and create a PDF document with the playlist's information.

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- The `pytube` library for simplifying YouTube video info.
- The `youtube_transcript_api` library for fetching video transcripts.
- The `fpdf` library for creating PDF documents.
- The `requests` library for downloading thumbnails.
