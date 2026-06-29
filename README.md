# Simple ACE-Step 1.5 Turbo Colab

This is a Google Colab notebook that runs a simple AI song generator using ComfyUI and ACE-Step 1.5 Turbo.

The notebook installs ComfyUI, downloads the required ACE-Step model files, starts ComfyUI in the background, and opens a simple Gradio web interface for generating songs.

## How to Use

1. Open `Simple_ACE_Step_Colab.ipynb` in Google Colab.
2. In Colab, click **Runtime → Change runtime type**.
3. Set **Hardware accelerator** to **T4 GPU**.
4. Run the cells from top to bottom.
5. If Colab asks you to restart the runtime after installing packages, do **not** restart. Close the popup and continue.
6. When the final cell shows a public Gradio link, open that link in a new tab.

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
