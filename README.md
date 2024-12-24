# Resume Customizer and Interview Preparation Agent

This project automates the customization of resumes and provides interview preparation tips tailored to specific job descriptions. Currently implemented as a Jupyter Notebook, the project dynamically analyzes your current resume and job description to create a personalized, optimized resume and actionable insights for interview preparation. Future updates will convert this project into a Streamlit app.

## Features

- **Resume Customization**: 
  - Upload your existing resume.
  - Input the job description for the desired role.
  - Generates a tailored resume emphasizing relevant skills, experiences, and keywords.

- **Interview Preparation**:
  - Offers a list of potential interview questions based on the job description.
  - Provides tips to answer behavioral and technical questions.

## Workflow

1. **Input**:
   - Current Resume (in TXT or PDF format).
   - Job Description (plain text or PDF).

2. **Processing**:
   - The system identifies key skills, qualifications, and requirements from the job description.
   - Matches them with your resume to highlight strengths and suggest improvements.

3. **Output**:
   - A modified resume aligned with the job description.
   - A detailed report with:
     - Suggested keywords and phrases.
     - Tips for structuring your resume.
     - Customized interview preparation tips.

## Technology Stack

- **Backend**:
  - Python
  - Natural Language Processing (NLP) using OpenAI's GPT-based models
  - LangChain for agentic workflows

- **Frontend** (Planned):
  - Streamlit for a user-friendly interface

- **Deployment**:
  - Dockerized for scalability
  - Compatible with cloud platforms (AWS, Azure, GCP)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/resume-customizer.git
   ```

2. Navigate to the project directory:
   ```bash
   cd resume-customizer
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook resume_customizer.ipynb
   ```

## Usage

1. Open the notebook in Jupyter and follow the step-by-step instructions.
2. Upload your current resume and job description as prompted.
3. Run the notebook cells to:
   - Generate the updated resume.
   - Review interview preparation tips.

## Examples

### Input
- **Resume**: Software Engineer with 3 years of experience in backend development.
- **Job Description**: Looking for a Full Stack Developer with experience in React.js, Node.js, and AWS.

### Output
- Modified Resume:
  - Emphasizes full-stack development projects.
  - Highlights React.js and Node.js skills.
  - Mentions AWS-related experience.
- Interview Tips:
  - Common questions about full-stack development.
  - Behavioral questions related to teamwork and leadership.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests for improvements.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements

- OpenAI for providing powerful NLP models.
- LangChain for enabling dynamic workflows.
- Jupyter for creating an interactive development environment.

