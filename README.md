# Background Remover
This project provides a web application for removing backgrounds from images using various Python libraries including rembg, Pillow, streamlit, numba, and numpy. The application allows users to upload an image and receive the same image with the background removed.

## Features
- Background Removal: Automatically removes the background from the uploaded image.
- Web Interface: User-friendly web interface for uploading images and viewing results.
- Fast Processing: Utilizes efficient libraries to ensure quick background removal.

## Libraries
- rembg: A tool to remove the background from images.
- Pillow: A Python Imaging Library (PIL) that adds image processing capabilities.
- streamlit: A framework for creating web apps with Python.
- numba: A Just-in-Time compiler to optimize numerical functions for performance.
- numpy: A fundamental package for numerical computation in Python.

## Installation
To run this project locally, follow these steps:

- Clone the repository:
```bash
git clone https://github.com/jatinkumarverma/background-remover.git
cd background-remover
```

- Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

- Install the required libraries:

```bash
pip install rembg Pillow streamlit numba numpy
```

- Usage
Run the Streamlit application:

```bash
streamlit run app.py
```

- Upload an image:

Open the local server URL provided by Streamlit, upload an image, and the application will display the image with the background removed.


## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
