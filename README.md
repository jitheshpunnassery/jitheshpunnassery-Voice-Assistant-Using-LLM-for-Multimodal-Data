## Voice Assistant Using LLM for Multimodal Data

This project implements a Voice Assistant powered by Large Language Models (LLMs) that handles multimodal data, including images and audio. The assistant is designed to analyze images, transcribe speech, generate natural language descriptions, and respond with synthesized speech. The system supports a wide range of use cases, including medical image analysis, report interpretation, and general image descriptions.

## Key Features

**Multimodal Interaction**: Users can interact using both voice and images.
**Image Analysis**: Capable of analyzing photographs, paintings, medical images, and reports.
**Medical Image Processing**: For medical images, it can identify symptoms, suggest possible diagnoses, and provide remedies.
**Speech-to-Text**: Converts spoken input into text using OpenAI Whisper.
**Text-to-Speech**: Converts textual output into speech using Google Text-to-Speech (gTTS).
**Seamless Integration**: Uses Gradio for easy interaction and a web-based interface.

## Project Structure

**Image Analysis**: Describes an image or identifies medical issues when provided with medical imagery.
**Speech-to-Text**: Transcribes voice input using OpenAI’s Whisper model.
**Text-to-Speech**: Generates audio responses with gTTS.
**User Interface**: Built with Gradio to allow users to upload images and use voice inputs easily.

## Core Technologies

**Transformers**: Uses the Hugging Face Transformers library to load and run LLaVA (Large Language and Vision Assistant) models.
**BitsAndBytes**: Provides model quantization for efficient inference on low-memory devices.
**Whisper**: For accurate speech recognition (transcription).
**gTTS (Google Text-to-Speech)**: Converts text output into spoken audio.
**Gradio**: Simplifies the creation of the user interface for multimodal interactions.
