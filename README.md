# Resume Builder and Interview Preparation Tool

This project provides a comprehensive tool for tailoring resumes and preparing for interviews. Leveraging OpenAI's GPT models and additional tools, the application customizes resumes to match job postings and generates interview preparation materials based on the tailored resume and job requirements.

## Features

- **Tailored Resume Builder**: Customize your resume to align with the job description and requirements.
- **Interview Preparation**: Generate interview questions and talking points based on the tailored resume and job description.
- **Streamlit Web Application**: A user-friendly interface for inputting job details and uploading resumes.
- **Jupyter Notebook**: A step-by-step implementation walkthrough in `resume-builder.ipynb`.

---

## Getting Started

### Prerequisites

- **Python 3.7 or later**
- Required Python packages (listed in `requirements.txt`):
  - `streamlit`
  - `crewai`
  - `python-dotenv`
  - `pandas`
  - `numpy`
  - And other dependencies required by these packages.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/billy-enrizky/Resume-builder.git
    cd Resume-builder
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up the `.env` file:

    Create a `.env` file in the project directory and add the following keys:

    ```env
    SERPER_API_KEY=your-serper-api-key
    OPENAI_API_KEY=your-openai-api-key
    ```

4. (Optional) Review the Jupyter Notebook:

    Open `resume-builder.ipynb` to walk through the implementation step-by-step or debug any issues.

    For a rendered HTML version of the notebook, visit the [GitHub Website Page](https://billy-enrizky.github.io/Resume-builder/).

---

## Usage

1. Run the Streamlit application:

    ```bash
    streamlit run app.py
    ```

2. Open the web application in your browser.

3. Provide the required details:
    - Job posting URL
    - GitHub profile URL
    - A brief personal write-up

4. Upload your resume in Markdown (`.md`) format.

5. Click **Generate Tailored Resume and Interview Prep**. Once the process is complete, download the tailored resume and interview preparation files.

---

## File Overview

- `app.py`: The Streamlit web application for the resume builder.
- `resume-builder.ipynb`: A Jupyter Notebook walkthrough of the implementation.
- `.env`: Contains the `SERPER_API_KEY` and `OPENAI_API_KEY` (not included in the repo for security).
- `requirements.txt`: List of dependencies for the project.
- [GitHub Website Page](https://billy-enrizky.github.io/Resume-builder/): A rendered HTML page of the Jupyter Notebook.

---

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repository and create a pull request.

---

## License

This project is licensed under the MIT License. See `LICENSE` for more details.

---

## Links

- **GitHub Repository**: [Resume Builder](https://github.com/billy-enrizky/Resume-builder)
- **GitHub Website Page**: [Jupyter Notebook HTML Walkthrough](https://billy-enrizky.github.io/Resume-builder/)
