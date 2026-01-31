# Comic Stories Generator - Ramayana

A Jupyter notebook that generates comic-style stories from the Ramayana epic using AI image generation models.

## Overview

This notebook uses Stable Diffusion models to create visual comic panels depicting scenes from the Ramayana. It's designed to run on Google Colab with GPU acceleration.

## Requirements

- GPU runtime (T4 or better recommended)
- Google Colab account
- Hugging Face account (for model access)

## How to Use with Google Colab

### Method 1: Direct Upload

1. Go to [Google Colab](https://colab.research.google.com/)
2. Click **File** → **Upload notebook**
3. Select `Ramayana_Comic_Story.ipynb` from your local machine
4. Click **Runtime** → **Change runtime type**
5. Select **T4 GPU** as hardware accelerator
6. Click **Save**
7. Run cells sequentially from top to bottom

### Method 2: Open from GitHub

1. Go to [Google Colab](https://colab.research.google.com/)
2. Click **File** → **Open notebook**
3. Select **GitHub** tab
4. Enter: `manojaiconf26/comic_stories`
5. Select `Ramayana_Comic_Story.ipynb`
6. Enable GPU: **Runtime** → **Change runtime type** → **T4 GPU**

## Running the Notebook

1. **Enable GPU**: Runtime → Change runtime type → T4 GPU → Save
2. **Run cells in order**: Click the play button on each cell or use Runtime → Run all
3. **Wait for model downloads**: First run takes 5-10 minutes to download Stable Diffusion models
4. **View generated images**: Comic panels will display inline as they're generated

## What the Notebook Does

- Installs required dependencies (diffusers, transformers, torch)
- Loads Stable Diffusion models from Hugging Face
- Generates comic-style images based on Ramayana story prompts
- Creates visual panels depicting key scenes from the epic
- Displays generated images directly in the notebook

## Troubleshooting

- **Out of memory error**: Restart runtime and ensure T4 GPU is selected
- **Slow generation**: Verify GPU is enabled in Runtime settings
- **Model download fails**: Check internet connection and try again

## Notes

- GPU runtime is required for reasonable generation times
- Generated images are saved in Colab's temporary storage
- Session data is lost when runtime disconnects
