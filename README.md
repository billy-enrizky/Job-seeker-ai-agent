# Resume Customization and Interview Preparation Tool

## Overview
This project leverages a **multi-agent AI system** to assist users in tailoring their resumes and preparing for job interviews. By using advanced tools and AI agents, it ensures your resume highlights your most relevant skills and experiences, perfectly aligning with the job posting requirements.

### Key Features:
- **Multi-Agent AI System**: 
  - Four specialized agents collaborate to perform tasks: 
    1. **Job Researcher**: Extracts key information from job postings.
    2. **Personal Profiler**: Creates a comprehensive personal profile.
    3. **Resume Strategist**: Tailors your resume to match job requirements.
    4. **Interview Preparer**: Prepares interview questions and talking points.
- **Integrated Tools**:
  - **SerperDevTool**: Enables advanced web search capabilities.
  - **ScrapeWebsiteTool**: Extracts key details from job postings.
  - **FileReadTool** and **MDXSearchTool**: Analyze and enhance resume content.
- **Streamlit UI**: User-friendly interface for input, processing, and downloading customized outputs.
- **Output**:
  - A tailored resume in Markdown format.
  - Interview preparation materials including potential questions and key talking points.

## Installation and Setup

### Prerequisites
- Python 3.8 or later.
- Streamlit and the required Python packages.

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/billy-enrizky/Resume-builder.git
   cd Resume-builder
   ```
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Set up the `.env` file with your API keys:
   ```plaintext
   SERPER_API_KEY=your_serper_api_key
   OPENAI_API_KEY=your_openai_api_key
   ```

### Run the App
Start the Streamlit application:
```bash
streamlit run app.py
```
The application will launch in your default browser.

## Files in the Repository
- **`app.py`**: The main application script.
- **`resume-builder.ipynb`**: A Jupyter Notebook to walk through the AI pipeline interactively.
- **GitHub Pages**: View the HTML-rendered notebook at [Resume Builder GitHub Page](https://billy-enrizky.github.io/Resume-builder/).

## Usage Guide
1. Provide the following inputs:
   - Job posting URL.
   - GitHub profile URL.
   - A brief personal write-up.
2. Upload your resume in Markdown format (`.md`).
3. Click "Generate Tailored Resume and Interview Prep."
4. Download the tailored resume and interview preparation files once generated.

## Multi-Agent AI System
This project utilizes **Crew AI**, a framework that coordinates multiple agents to accomplish complex tasks. Here's how it works:
- **Task Coordination**: Each agent specializes in a specific domain, ensuring detailed and efficient execution.
- **Collaborative Process**: Agents share intermediate outputs to refine the final results.

### Agent Breakdown:
1. **Tech Job Researcher**:
   - Analyzes job postings to identify critical requirements.
2. **Personal Profiler for Engineers**:
   - Builds a detailed personal and professional profile from provided inputs.
3. **Resume Strategist for Engineers**:
   - Adjusts and enhances resumes to emphasize the most relevant qualifications.
4. **Engineering Interview Preparer**:
   - Crafts a comprehensive interview preparation guide.

## Debugging and Process Walkthrough
If you encounter issues or want to explore the process in detail:
1. Use the **`resume-builder.ipynb`** notebook for a step-by-step guide.
2. Visit the [GitHub Pages walkthrough](https://billy-enrizky.github.io/Resume-builder/) for a visual guide and debugging assistance.

## Repository Links
- **GitHub Repository**: [Resume-builder](https://github.com/billy-enrizky/Resume-builder)
- **GitHub Pages**: [HTML Walkthrough](https://billy-enrizky.github.io/Resume-builder/)

---

Feel free to contribute or raise issues on the GitHub repository!
