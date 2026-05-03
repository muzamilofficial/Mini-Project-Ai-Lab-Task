# Image and Video Caption Generator

A Flask-based web application that generates descriptive captions for uploaded images and videos. The application includes user authentication, file upload handling, image captioning with a pretrained BLIP model, and video captioning through frame extraction and caption aggregation.

## Features

- User signup and login with session-based authentication
- Secure dashboard access after authentication
- Image caption generation using Salesforce BLIP
- Video caption generation by extracting frames at regular intervals
- Support for common image and video file formats
- Simple Flask web interface with upload and caption display support
- Local JSON-based user storage for lightweight authentication

## How It Works

### Image Captioning
Uploaded images are processed with the `Salesforce/blip-image-captioning-base` model through Hugging Face Transformers. The image is opened with PIL, passed through the BLIP processor, and decoded into a natural-language caption.

### Video Captioning
Uploaded videos are read with OpenCV. Every nth frame is saved temporarily and passed to the image captioning pipeline. The final video description is created by combining captions from sampled frames.

### Authentication
The application uses email and password login with signup support. User credentials are stored in a local `users.json` file, and authenticated users are managed through Flask sessions.

## Tech Stack

- Python
- Flask
- Hugging Face Transformers
- PyTorch
- Pillow
- OpenCV

## Project Structure

```text
project-root/
├── app.py
├── image_caption.py
├── video_caption.py
├── utils.py
├── templates/
│   ├── login.html
│   ├── signup.html
│   └── dashboard.html
├── static/
│   └── uploads/
└── users.json
