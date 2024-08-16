# Image and Text to Video Generation

## Workflow

There are two options for generating videos:

1. **Image to Video**: Users can upload an image, and a video will be generated based on the content of the image.
2. **Text to Video**: Users can input text, and a video will be generated based on the provided text.

## Output Structure

- **Upload Image**: Users can upload an image through the application interface.
- **Input Text**: Users can type text directly into the application.
- **Final Video**: The generated video will be displayed to the user.

## Installation Guide

To set up and run the application, follow these steps:

1. **Create a Virtual Environment**:  
   Create a new virtual environment using the `venv` package:
   ```bash
   python -m venv env_for_video_generation
2. **Activate the environment**:
    ```bash
    env_for_video_generation\Scripts\activate
3. **Install packages**:
    ```bash
    python -r requirements.txt
4. **run main file**:
    ```bash
    python run main.py