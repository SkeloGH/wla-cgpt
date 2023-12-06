# TailorCV

TailorCV is a Python-based project that processes a user's CV and a job description, and generates a structured JSON output. This approach ensures that users receive only the essential, structured JSON data.

## Features

- Parses a user's CV and a job description.
- Generates a JSON output with the following schema:
    + basics: Basic information about the user.
    + work: An array of objects representing the user's work experience.
    + skills: An array of strings representing the user's skills.
    + education: An array of objects representing the user's education.
    + job: An object representing the details of the job description.
    + jobDescriptionAlignment: An object showing the alignment between the user's skills and the job description.

## Requirements

- Python 3.6 or higher
- An OpenAI API key

## Setup

1. Clone the repository:

```git clone https://github.com/SkeloGH/wla-cgpt.git```

2. Navigate to the project directory:

```cd capstone_project```

3. Install the required packages:
    
    ```pip install -r requirements.txt```

4. Create a .env file in the project root and add your OpenAI API key:

```OPENAI_API_KEY=YOUR_API_KEY```

## Usage
To use TailorCV, run the main.py script with Python:

```python main.py```

It will spin up a web server on port 5000. You can open the web app by navigating to http://localhost:5000 in your browser.
