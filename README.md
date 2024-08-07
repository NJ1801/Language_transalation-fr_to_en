# Text Translation and Analysis

## Overview

This Streamlit application provides a comprehensive analysis of text files, including tokenization, language detection, and statistical analysis. Additionally, it offers translation capabilities from French to English using the MarianMT model.

## Features

- **File Upload**: Upload text files (.txt format) for analysis.
- **Text Display**: View the content of the uploaded file.
- **Tokenization**: Tokenize the text into words and sentences.
- **Language Detection**: Detect the language of the text.
- **Statistical Analysis**: Calculate the number of lines, words, and characters in the text.
- **Translation**: Translate the text from French to English.

## Setup Instructions

### Prerequisites

Ensure you have the following installed:

- Python 3.7+
- pip

### Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/your-username/text-translation-analysis.git
    cd text-translation-analysis
    ```

2. **Create a virtual environment** (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required packages**:

    ```bash
    pip install -r requirements.txt
    ```

    Make sure `requirements.txt` contains the following dependencies:

    ```txt
    streamlit
    nltk
    langdetect
    transformers
    torch
    ```

4. **Download NLTK resources**:

    ```python
    import nltk
    nltk.download('punkt')
    ```

## Usage

1. **Run the Streamlit app**:

    ```bash
    streamlit run app.py
    ```

2. **Upload a text file**: Use the sidebar to upload your text file (.txt format).

3. **View analysis**: The app will display the content of the file, tokenized words and sentences, detected language, and various statistical analyses.

4. **Translate text**: The app will translate the text from French to English.

## File Structure

- `app.py`: Main application file containing the Streamlit code.
- `README.md`: This README file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Feel free to open issues or submit pull requests for any improvements or bug fixes.

## Contact

For any questions or inquiries, please contact [njnagaraj007@gmail.com].
