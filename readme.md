# Smart README Generator

This project provides a tool for generating informative README.md files based on the contents of your project directory.  

## Description

This tool leverages the power of Google's Gemini AI model to analyze the files within your project and automatically create a well-structured README.md file. The generated README includes:

* **Project Title:** A descriptive title based on the project's content.
* **Description:** A summary of the project's purpose and functionality.
* **Installation Steps:** Instructions on how to set up the project environment and install any necessary dependencies.
* **Usage Instructions:** Guidance on how to use the project and its functionalities.
* **Dependencies:** A list of any libraries or packages required for the project to run.

## Installation

1. **Install Python:** Ensure that Python is installed on your system.
2. **Install Requirements:** Install the required libraries by running:
   ```bash
   pip install -r requirements.txt
   ```
3. **Obtain a Gemini API Key:** Visit the [Google AI Platform](https://cloud.google.com/generative-ai/docs/reference/rest) to acquire a Gemini API key. 
4. **Replace Placeholder:**  Locate the `cv.py` file and replace "YOUR_API_KEY_HERE" with your actual Gemini API key.

## Usage

1. **Run the Application:** Execute the `cv.py` file to start the application.
2. **Generate README:** The application will automatically generate a `README.md` file in the current directory, containing a structured summary of your project.

## Dependencies

* Google Generative AI (`google.generativeai`)
* Streamlit (`streamlit`)

## Notes

* The tool currently focuses on analyzing text-based files (e.g., `.txt`, `.py`, `.md`, `.js`, `.html`, etc.).
* The generated README might not include all possible information about your project.  You may need to manually add additional details or sections.

Thank you for using Smart README Generator! Have a great day!
