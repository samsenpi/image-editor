# Image Editor with Streamlit and Pillow 🎨

## Introduction 🚀

This is a simple image editor built using Python with the Streamlit and Pillow libraries. The purpose of this project is to provide a user-friendly interface for cropping, resizing, rotating, and applying filters to images. Users can upload their images, perform various edits, and download the final output.

## Features ✨

- **Upload Image**: Users can upload their images using the provided upload button.
- **Crop**: Crop the image by selecting a region of interest.
- **Resize**: Change the dimensions of the image.
- **Rotate**: Rotate the image by a specified angle.
- **Filter**: Apply various filters to enhance or modify the image.
- **Download**: Download the edited image after making the desired changes.

## Prerequisites 📋

Make sure you have Python installed on your machine. You can install the required libraries using the following command:

```bash
pip install streamlit pillow
```

## How to Run ▶️

1. Clone the repository:

```bash
git clone https://github.com/samsenpi/image-editor.git
cd image-editor
```

2. Run the Streamlit app:

```bash
streamlit run app.py
```

3. Open your web browser and go to `http://localhost:8501` to access the Image Editor.

## Usage 🎬

1. Click on the "Upload Image" button to select and upload your image.
2. Use the sliders and input fields to adjust the cropping, resizing, rotation, and filter options.
3. Click on the "Apply" button to see the preview of the edited image.
4. Once satisfied with the edits, click on the "Download" button to save the final image.

## Libraries Used 📚

- **Streamlit**: For creating the web application.
- **Pillow**: For image processing and manipulation.
