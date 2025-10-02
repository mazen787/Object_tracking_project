# Object Tracking Application

This application tracks moving objects in a video using OpenCV and Streamlit. It uses the MOG2 background subtractor to detect moving objects and draws a green rectangle around them.

## Features

- Upload video files (`.mp4`, `.avi`, `.mov`, `.wmv`)
- Detect and highlight moving objects in real-time
- Simple web interface powered by Streamlit

## Requirements

See [`requirments.txt`](requirments.txt) for dependencies:

- streamlit
- opencv-python-headless
- numpy

## Installation

1. Clone the repository.
2. Install dependencies:

    ```sh
    pip install -r requirments.txt
    ```

## Usage

Run the Streamlit app:

```sh
streamlit run app.py
```

Then, open the provided local URL in your browser and upload a video to start tracking objects.

## File Structure

- [`app.py`](app.py): Main application code.
- [`requirments.txt`](requirments.txt): Python dependencies.
- [`.gitattributes`](.gitattributes): Git configuration.

## License

This project is for educational purposes.