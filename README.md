# YouTube Video Transcription and Chunking

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.7%2B-brightgreen.svg)](https://www.python.org/downloads/)
[![Gradio](https://img.shields.io/badge/Gradio-3.0-brightgreen.svg)](https://www.gradio.app/)

A Python application that downloads audio from YouTube videos, transcribes it using the Whisper model, and chunks the transcription into manageable segments. The app provides a user-friendly interface powered by Gradio.

![Demo](demo.png)

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Download Audio**: Extract audio from YouTube videos.
- **Transcription**: Convert audio to text using Whisper.
- **Semantic Chunking**: Split the transcription into chunks based on duration.
- **User Interface**: Simple web-based UI to input video URL and view the transcription.

## Installation

### Prerequisites

- Python 3.7 or higher
- [ffmpeg](https://ffmpeg.org/download.html) installed and available in the system PATH

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/youtube-transcription.git
   cd youtube-transcription
