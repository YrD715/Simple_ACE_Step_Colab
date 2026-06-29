# Simple ACE-Step 1.5 Turbo Colab

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YrD715/Simple_ACE_Step_Colab/blob/main/Simple_ACE_Step_Colab.ipynb)

A Google Colab notebook that runs ACE-Step 1.5 Turbo through a hidden ComfyUI backend and opens a simple Gradio song-making interface.

## Start Here

Click the **Open in Colab** button above.

Before running the notebook, choose:

**Runtime → Change runtime type → T4 GPU**

If Colab asks you to restart the runtime after installing packages, do **not** restart. Close the popup and continue.

## First Test

Use a short duration first, such as 10 or 15 seconds. After that works, try longer songs.

## Important Notes

This does not run permanently. Google Colab sessions are temporary, and the Gradio link only works while the notebook is running.

The notebook does not include model weights. Required model files are downloaded from Hugging Face at runtime.

Free Colab GPUs are limited and may be slow or unavailable depending on Google’s current limits.

## Third-Party Components

This project uses:

* ComfyUI
* ACE-Step-ComfyUI
* ACE-Step 1.5 ComfyUI model files
* Gradio

See `NOTICE.md` for third-party notices.
