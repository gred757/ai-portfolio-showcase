# 🎙️ Multi-Modal AI Solutions: TTS/STT Toolkit

## Overview

This project is a flexible, high-performance service designed to handle complex voice-to-text (STT) and text-to-voice (TTS) tasks. The primary goal was to create a unified system that balances the privacy of local processing with the high quality of cloud-based services.

## Key Features

- Hybrid Model Support: Integration with Silero for fully offline, private local synthesis and Microsoft Edge TTS for high-fidelity cloud output.

- Voice Cloning: Implementation of voice cloning capabilities for personalized TTS.

- Batch Processing: Ability to process multiple large text corpora simultaneously.

- User Interface: A custom Gradio GUI, making sophisticated AI models accessible to non-technical users.

## Technical Architecture

- Input Layer: Gradio-based web interface for file uploads (text) and parameter tuning (pitch, rate, voice selection).

- Processing Core: - Audio normalization and transcription using local models.

- TTS: Logic-based routing between local (Silero) and cloud (Edge) engines.

- Output Layer: Real-time audio playback and batch file export.

## Tech Stack
- Language: Python

- GUI: Gradio

- Models: Silero (Local), Edge TTS (Cloud)

- Libraries: Librosa (Audio analysis), SoundFile, Pydantic (Data validation).

## Project Screenshots
(Тут ти можеш завантажити скріншот свого Gradio інтерфейсу)
