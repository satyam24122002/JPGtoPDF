
# Image to PDF Converter

A simple desktop application built using Python that allows users to convert multiple images into a single PDF document.

## Features

- Select multiple images (JPG, JPEG, PNG).
- Display selected image filenames.
- Convert multiple images into a single PDF.
- Maintain image proportions while fitting images to PDF pages.
- Choose a custom PDF filename and save location.
- User-friendly graphical interface using Tkinter.
- Error and success notifications.

## Technologies Used

- Python
- Tkinter
- Pillow
- ReportLab

## Project Structure

JPGtoPDF/
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore

## Installation

### 1. Clone the repository

git clone https://github.com/satyam24122002/JPGtoPDF.git

### 2. Open the project directory

cd JPGtoPDF

### 3. Install dependencies

python -m pip install -r requirements.txt

### 4. Run the application

python app.py

## Requirements

- Python 3.10 or later
- Windows, macOS, or Linux
- Required Python libraries listed in requirements.txt

Note: Tkinter must be available in your Python installation.

## How to Use

1. Run app.py.
2. Click the Select Images button.
3. Choose one or more images.
4. Enter your desired PDF filename.
5. Click Convert to PDF.
6. Select the destination to save your PDF.

## Author

Satyam Gupta

## License

This project is licensed under the MIT License.
