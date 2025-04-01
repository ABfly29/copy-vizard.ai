# AI-Powered Short Video Clip Extractor (Inspired by Vizard.ai)

## Overview
This project automates the extraction of impactful short clips from a full-length video, mimicking the functionality of Vizard.ai. It uses AI-driven speech analysis to identify the most engaging moments and exports them in a **9:16 vertical format** with **preserved audio**.

## Features
- Extracts **5 short clips** (~10-12 seconds each) from the main video.
- Ensures **dialogues are not cut off** mid-sentence.
- Rescales video to **9:16** aspect ratio while maintaining quality.
- **Preserves audio** for seamless short-form content creation.
- Fully **automated** pipeline with minimal user input.

## How It Works
1. **Video Processing**  
   - The input video is loaded and converted to an appropriate format.
   - Audio is extracted and analyzed for speech patterns.

2. **AI-Based Clip Selection**  
   - Speech recognition identifies the most **impactful** segments.
   - The script ensures that clips do not cut off dialogues abruptly.
   - Selected clips are **around 10-12 seconds**, but flexible if needed.

3. **Video Cropping & Export**  
   - Clips are **resized** to a vertical **9:16 ratio**.
   - Final clips are **exported** in a high-quality format.

## Dependencies
Make sure you have the following Python libraries installed:
```bash
pip install moviepy pydub openai-whisper ffmpeg
