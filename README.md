# MarkdownViewer: An Interactive Web-Based Markdown Editor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

`MarkdownViewer` has evolved into a powerful and interactive web-based Markdown editor, providing a seamless experience for writing, previewing, loading, and saving Markdown files.

## Key Features

-   **Real-time Preview:** See your Markdown rendered into HTML instantly as you type.
-   **In-Browser File I/O:** Load existing Markdown files and save your edits directly from the web interface.
-   **Enhanced Code Snippet Viewing:** Code blocks are beautifully highlighted with Pygments-compatible syntax highlighting.
-   **User-Friendly Interface:** A clean and intuitive design with improved user feedback for operations.
-   **Automatic README.md Load:** Automatically loads the project's `README.md` upon startup for immediate context.

## Project Structure

```
MarkdownViewer/
├── templates/
│   └── index.html
├── viewer.py
├── requirements.txt
├── README.md
└── ... (other project files like test.md, commit_message.txt)
```

-   **`viewer.py`**: The core Flask application that serves the web interface, handles Markdown conversion, and manages file loading/saving.
-   **`templates/index.html`**: The HTML, CSS, and JavaScript for the interactive editor interface.
-   **`requirements.txt`**: Lists all Python dependencies required for the project.

## Installation

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/MemaroX/MarkdownViewer.git
    cd MarkdownViewer
    ```

2.  **Install Python Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    This will install Flask, Markdown, Pygments, and other necessary packages.

## Usage

To launch the interactive Markdown editor, simply run the `viewer.py` script:

```bash
python viewer.py
```

Once the server starts (typically on `http://127.0.0.1:8000/`), open your web browser and navigate to the displayed address. The editor will automatically load the `README.md` file. You can then type Markdown, load other files using their full path, and save your work.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.