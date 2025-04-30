# AI Resume Manager

An intelligent system for managing and customizing your CV/resume using AI. The system helps you maintain a database of experiences and automatically suggests relevant modifications based on job descriptions.

## Project Structure

```
project/
├── templates/
│   └── cv_template.tex         # Your main LaTeX CV template
├── resumes/
│   ├── base/                   # Your main, uncustomized CV
│   ├── versions/               # Customized versions for specific jobs
│   └── archive/               # Old or unused versions
├── data/
│   └── experiences.db         # Experience database
├── src/                       # Source code
├── tests/
└── requirements.txt
```

## Setup Instructions

1. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Install LaTeX (if not already installed):
   - Windows: Install MiKTeX (https://miktex.org/)
   - macOS: Install MacTeX (https://www.tug.org/mactex/)
   - Linux: `sudo apt-get install texlive-full`

3. Customize the CV template:
   - Edit `templates/cv_template.tex` with your information
   - Compile to test: `pdflatex templates/cv_template.tex`

4. Initialize the experience database:
   - Run the database setup script (coming soon)
   - Add your experiences using the CLI tool (coming soon)

## Usage

### Managing Your CV

1. Store your base CV in `resumes/base/`
2. Create customized versions in `resumes/versions/`
3. Move old versions to `resumes/archive/`

### Adding Experiences

Coming soon: Instructions for adding experiences to the database.

### Customizing for Job Applications

Coming soon: Instructions for using the AI agent to customize your CV.

## Development

- Source code will be in the `src/` directory
- Tests will be in the `tests/` directory
- Database schema and migrations will be in `data/`

## Requirements

- Python 3.9+
- LaTeX distribution
- Required Python packages listed in `requirements.txt` 