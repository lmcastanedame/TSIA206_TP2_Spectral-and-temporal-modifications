# Spectral and Temporal Modifications (TSIA206)

This project is part of the TSIA206 course and involves applying various spectral and temporal modifications to audio signals. The aim is to explore how altering the frequency spectrum and time-domain properties of audio signals can affect their characteristics, using techniques such as time-stretching, pitch-shifting, and filtering.

## Project Description

The project focuses on processing audio signals to modify their spectral (frequency) and temporal (time-domain) properties. Techniques such as time-stretching, pitch-shifting, and spectral filtering are implemented to analyze how changes in these domains impact the perception and characteristics of audio signals. The project serves as an introduction to advanced audio processing concepts.

## Project Structure

The repository contains the following key files and directories:

- **main.py**: The main script for applying spectral and temporal modifications to audio signals.
- **audio_samples/**: A directory containing audio files used for testing the signal processing techniques.
- **modifications.py**: A module implementing the algorithms for spectral and temporal modifications.
- **notebooks/**: Jupyter notebooks for experimenting with the different modifications and visualizing the results.
- **requirements.txt**: A file listing the required dependencies to run the project.
- **README.md**: This file, providing an overview of the project.

## How to Use

### Prerequisites

- Python 3.x
- Libraries: NumPy, SciPy, librosa, Matplotlib

Install the necessary dependencies with:

```bash
pip install -r requirements.txt
```

### Running the Project

To apply spectral and temporal modifications to an audio signal, follow these steps:

1. Select an audio file from the `audio_samples/` directory.
2. Run the main script to process the audio with the desired modifications:

    ```bash
    python main.py
    ```

3. The output will be the modified audio files saved in the `output/` directory, along with visual representations of the original and modified audio signals.

### Key Steps in the Process

1. **Load Audio Signal**: Load the audio file from the `audio_samples/` directory.
2. **Apply Modifications**: Use techniques such as time-stretching, pitch-shifting, or spectral filtering to modify the audio signal.
3. **Visualize Results**: Plot the waveforms and spectrograms of the original and modified audio to analyze the changes in both the time and frequency domains.
4. **Output**: The modified audio files are saved for playback and further analysis.

## Purpose

The purpose of this project is to demonstrate how spectral and temporal modifications can alter the characteristics of audio signals. These techniques are widely used in audio processing tasks such as music production, speech synthesis, and sound design.

## Technologies

- **Language**: Python
- **Libraries**: NumPy, SciPy, librosa, Matplotlib
- **Tools**: Jupyter Notebooks for visualization and experimentation
