# Handwritten OCR + Translation

Takes photos of handwritten text and converts them to typed text. For non-English scripts, translates to English.

## What it does right now

- English handwriting → clean typed English
- Kannada handwriting → English translation

More languages coming later. Each script needs its own OCR model.

## Built with

- TrOCR for handwriting recognition
- IndicTrans2/NLLB for translation
- PyTorch and Hugging Face
- Gradio for the web interface
- Training on Google Colab

## How to use

Not ready yet. Check back soon.

## Project layout

- `data/` - datasets and preprocessing
- `notebooks/` - experiments and prototyping
- `src/` - main code
- `app/` - web UI
- `models/` - saved model weights
- `configs/` - training settings

## Status

Currently building the first version.

# Dataset Documentation

## English Handwriting

**Source:** IAM Handwriting Database  
**Status:** Not yet downloaded  
**Notes:** Standard benchmark for English handwriting recognition

## Kannada Handwriting

**Source:** IIIT-HWS Kannada or Kaggle Kannada MNIST  
**Status:** Not yet downloaded  
**Notes:** Will evaluate both sources and choose based on quality

## Download Instructions

Coming soon after dataset selection is finalized.

## Data Organization

- `raw/` - Original downloaded datasets
- `processed/` - Cleaned and preprocessed data ready for training