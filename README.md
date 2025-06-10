# Video-Captioning
Project Title:
Automatic Video Captioning and Summarization using LLMs and VLMs

Project Description:
This project implements an end-to-end system that automatically generates natural language descriptions for videos by leveraging Vision-Language Models (VLMs) and Large Language Models (LLMs). The system takes a Google Drive video link as input, downloads the video, extracts key frames, and uses a pre-trained BLIP model to generate captions for each frame. These captions are then aggregated and summarized into a coherent textual description using GPT-4 (optional). The final output is a concise and human-like summary of the video content, enabling efficient content indexing, accessibility, and understanding of video material.


Key Features:
Accepts video input from Google Drive.

Extracts representative frames using OpenCV.

Generates high-quality image captions using the BLIP model.

Optionally summarizes captions using GPT-4 to produce a narrative description.

Easy-to-use and modular Python implementation.
