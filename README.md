# ATS Resume Expert

ATS Resume Expert is a Streamlit application that helps you evaluate how well your resume matches a job description. It uses Google Generative AI to analyze the content of your resume and provide feedback on its alignment with the job requirements.

## Features

- Upload your resume in PDF format.
- Input the job description.
- Get a professional evaluation of your resume.
- Receive a percentage match score indicating how well your resume fits the job description.
- Identify missing keywords and get final thoughts on your resume.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/vishnukhare/ats_check.git
    cd ats_resume_expert
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Set up your Google API key:
    - Create a [.env](http://_vscodecontentref_/1) file in the root directory.
    - Add your Google API key to the [.env](http://_vscodecontentref_/2) file:
        ```env
        GOOGLE_API_KEY="your_google_api_key"
        ```

4. Download and set up Poppler for PDF conversion:
    - Download Poppler from [Poppler for Windows](http://blog.alivate.com.au/poppler-windows/).
    - Extract the files and note the path to the `bin` directory.

## Usage

1. Run the Streamlit application:
    ```sh
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.

3. Enter the job description in the provided text area.

4. Upload your resume in PDF format.

5. Click on "Tell Me About the Resume" to get a professional evaluation.

6. Click on "Percentage match" to get a percentage match score and feedback on missing keywords.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [Google Generative AI](https://cloud.google.com/ai-platform)
- [pdf2image](https://github.com/Belval/pdf2image)
- [python-dotenv](https://github.com/theskumar/python-dotenv)
- [Pillow](https://python-pillow.org/)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Contact

For any questions or inquiries, please contact [kahrevishnu2@gmail.com](mailto:kahrevishnu2@gmail.com).
