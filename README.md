# Invisibility Cloak

A computer vision project that creates an "invisibility cloak" effect using a webcam. The project captures a background image and replaces areas of a specific color in the video feed with the background, creating the illusion of invisibility. Built with OpenCV and NumPy.

## Project Status

The project is currently in the development phase. Future updates may include:

- Improved color detection for more accurate invisibility effects.
- Enhanced user interface for easier interaction.
- Support for additional color ranges and customization.

## Project Screen Shot(s)

Screenshots coming soon.

## Installation and Setup Instructions

Clone down this repository. You will need Python and OpenCV installed on your machine.

### Installation:
bash
pip install opencv-python numpy

### To Start the Application:
bash
python main.py


### To View the Output:

The application will open a window displaying the invisibility effect in real-time. Press 'q' to exit.

## Reflection

This project was developed as a fun exploration into computer vision techniques. The goal was to create a simple yet intriguing effect using OpenCV, a library I had not extensively used before.

One of the biggest challenges was fine-tuning the color detection to ensure the invisibility effect worked smoothly across different lighting conditions. I experimented with various HSV color ranges and morphological operations to achieve the desired result.

I chose OpenCV and NumPy for this project because they are powerful tools for image processing and manipulation. OpenCV's extensive documentation and community support made it easier to overcome challenges and learn new techniques.

## Design Thinking Process

As a software developer, I approached this project with a design thinking mindset:

1. **Empathize**: Understanding the user's desire for a seamless and magical invisibility effect.
2. **Define**: Clearly defining the problem of accurately detecting and replacing specific colors in a video feed.
3. **Ideate**: Brainstorming different approaches to color detection and background replacement.
4. **Prototype**: Rapidly developing a working prototype using OpenCV to test various techniques.
5. **Test**: Iteratively testing and refining the color detection and invisibility effect based on user feedback and observations.

This process allowed me to create a project that not only meets the initial goals but also provides a foundation for future enhancements. By focusing on user experience and iterative improvement, I demonstrated my ability to develop effective and innovative software solutions.