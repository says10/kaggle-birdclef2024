# BirdCLEF 2024 - Bird Audio to Mel Spectrogram Conversion

This project processes bird audio recordings into **Mel spectrograms** for the **BirdCLEF 2024** competition.  
The generated spectrograms can be used for training machine learning models to classify bird species based on their calls and songs.

## Project Status

✅ Audio preprocessing complete.  
🚀 Mel spectrograms successfully generated and ready for model training or further analysis.

## Features

- Load and preprocess raw bird audio recordings
- Convert audio clips into Mel spectrogram images
- Save spectrograms as `.png` or use them directly in model pipelines
- Handle variable audio lengths and sampling rates
- Batch processing for large datasets

## Tech Stack

- Programming Language: Python
- Audio Processing: Librosa
- Visualization: Matplotlib
- Data Handling: NumPy, Pandas
- (Optional) Deep Learning Frameworks: PyTorch / TensorFlow

## Getting Started

### Prerequisites

- Python 3.8+
- Install the required packages:

```bash
pip install librosa matplotlib numpy pandas
