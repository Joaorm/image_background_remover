# Image Background Remover

This is a simple Streamlit app that removes the background from an uploaded image using the `rembg` library. The app allows users to upload images, processes them, and lets users download the image with the background removed.

## Features

- Upload an image (`png`, `jpg`, `jpeg`) with a maximum size of 5MB.
- View the original image and the processed image side by side.
- Download the image with the background removed.
- Built using Streamlit for the front-end and `rembg` for background removal.

## Demo

1. Upload your image.
2. Watch as the background is removed.
3. Download the modified image from the sidebar.

## Installation

1. Clone this repository:

```bash
git clone https://github.com/your-repo/streamlit-background-remover.git
cd streamlit-background-remover
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Running the App
To run the Streamlit app locally, use the following command:
```bash
streamlit run bg_remove.py
```

Once the app is running, open your browser and navigate to the local URL provided by Streamlit, typically http://localhost:8501.

How It Works
	1.	The user uploads an image via the sidebar.
	2.	The app uses the rembg library to remove the background.
	3.	The original and processed images are displayed side by side.
	4.	The user can download the processed image with the background removed in PNG format.

Credits
- rembg library for background removal.
- Original code based on Tyler Simons’ BackgroundRemoval.

License

This project is licensed under the MIT License.
