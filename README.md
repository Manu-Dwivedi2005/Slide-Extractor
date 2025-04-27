# Slide Extractor Project

## Description

This project is a Python-based tool designed to extract slides from YouTube videos. It downloads the video, processes it frame by frame, identifies potential slides based on visual and textual differences, and saves them as image files.  It also has the capability to generate a PDF from the extracted slides.

## Features

* Extracts slides from YouTube videos.
* Uses a combination of visual similarity and Optical Character Recognition (OCR) to identify slides.
* Saves extracted slides as PNG image files.
* Generates a PDF file from the extracted slides.
* Provides a simple graphical user interface (GUI) for ease of use.

## Requirements

The following Python libraries are required to run this project.  They are listed in the `requirements.txt` file.

* opencv-python
* pytesseract
* Pillow
* yt-dlp
* scikit-image
* tk
* reportlab

## Installation

### 1.  Python Installation

Ensure you have Python 3.6 or later installed on your system. You can check your Python version by running:

```bash
python --version
```
If Python is not installed, download and install it from the official Python website (https://www.python.org/downloads/).2.  Project SetupDownload the project files: Download the main.py, slide_extractor.py, and requirements.txt files and save them in the same directory (e.g., a folder named SLIDE_EXTRACTOR).Create a virtual environment (Recommended):It is highly recommended to create a virtual environment for this project to manage dependencies and avoid conflicts with other Python projects.Open your command prompt (on Windows) or terminal (on macOS and Linux).Navigate to the directory where you saved the project files. For example:cd Desktop\SLIDE_EXTRACTOR
Create a virtual environment:python -m venv venv
Activate the virtual environment:On Windows:venv\Scripts\activate
On macOS and Linux:source venv/bin/activate
(Your command prompt/terminal should now show (venv) at the beginning, indicating that the virtual environment is active.)Install dependencies:pip install -r requirements.txt
3. Global Installation (Not Recommended)If you choose not to use a virtual environment, you can install the dependencies globally.

* Open your command prompt (on Windows) or terminal (on macOS and Linux).
* Navigate to the directory where you saved the project files.
* Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
**Warning:** Global installation can lead to dependency conflicts with other Python projects. It's strongly recommended to use a virtual environment.
3.  Running the ApplicationEnsure your virtual environment is activated (if you created one).Navigate to the project directory in your command prompt or terminal.Run the main script:python main.py
UsageRun the application as described in the "Running the Application" section.The "YouTube Slide Extractor" window will appear.Enter the URL of the YouTube video you want to process.Adjust the "Frame Interval (Seconds)" and "Similarity Threshold (0.0 to 1.0)" if needed.Click the "Extract Slides" button. The extracted slides will be saved as PNG images in the slides directory.Once the extraction is complete, click the "Generate PDF" button to create a PDF file from the extracted slides.  You will be prompted to choose a location and filename for the PDF.Important Information Regarding Global PackagesListing Globally Installed Packages:To see a list of all packages installed in your global Python environment (outside of any virtual environment), you can use the following command:pip freeze
Uninstalling Packages Globally:If you need to uninstall a package from your global Python environment, use the following command:pip uninstall <package-name>
Replace <package-name> with the name of the package you want to remove (e.g., pip uninstall opencv-python).  Use this with caution, as uninstalling packages globally can affect other Python projects on your system.  It is a best practice to manage dependencies within virtual environments.Directory StructureSLIDE_EXTRACTOR/
├── main.
```

3. Running the Application
Ensure your virtual environment is activated (if you created one).

Navigate to the project directory in your command prompt or terminal.

Run the main script:
 ```bash  
python main.py
```
Usage
Run the application as described in the "Running the Application" section.

The "YouTube Slide Extractor" window will appear.

Enter the URL of the YouTube video you want to process.

Adjust the "Frame Interval (Seconds)" and "Similarity Threshold (0.0 to 1.0)" if needed.

Click the "Extract Slides" button. The extracted slides will be saved as PNG images in the slides directory.

Once the extraction is complete, click the "Generate PDF" button to create a PDF file from the extracted slides.  You will be prompted to choose a location and filename for the PDF.

Important Information Regarding Global Packages
Listing Globally Installed Packages:

To see a list of all packages installed in your global Python environment (outside of any virtual environment), you can use the following command:
```bash
pip freeze
```
Uninstalling Packages Globally:

If you need to uninstall a package from your global Python environment, use the following command:
```bash
pip uninstall <package-name>
```
Replace <package-name> with the name of the package you want to remove (e.g., pip uninstall opencv-python).  Use this with caution, as uninstalling packages globally can affect other Python projects on your system.  It is a best practice to manage dependencies within virtual environments.
```bash
Directory Structure
SLIDE_EXTRACTOR/
├── main.
