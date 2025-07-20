# AI-Powered-Job-recommender
![mcpproject-ezgif com-video-to-gif-converter (1)](https://github.com/user-attachments/assets/110bfd8d-c76c-462f-90f7-a70ad55c92ee)


This project is an AI-powered job recommender system that analyzes your resume and provides personalized job recommendations from LinkedIn and Naukri. It also highlights skill gaps and suggests a future roadmap to improve your career prospects.

## Features

- Upload your resume (PDF) and extract key information.
- Summarize your skills, education, and experience using OpenAI.
- Identify missing skills, certifications, and experiences.
- Get a personalized career roadmap.
- Fetch job recommendations from LinkedIn and Naukri based on your profile.

## Project Structure

```
AI-Powered-Job-recommender/
├── app.py
├── mcp_server.py
├── src/
│   ├── job_api.py
│   └── helper.py
├── requirements.txt
├── .env.example
└── README.md
```
## Getting Started

### Prerequisites

- Python 3.12+
- [APIFY_API_TOKEN](https://apify.com/)
- [OpenAI API Key](https://platform.openai.com/)

### Installation

1. Clone the repository.
2. Install dependencies:
   ```sh
   pip install -r requirements.txt

3. Create a .env file with your API keys:
    ```sh
    OPENAI_API_KEY=your_openai_key
    APIFY_API_TOKEN=your_apify_token

Running the App

To start the Streamlit app:
```sh
    streamlit run app.py
```

To run the MCP server:
```sh
    python [mcp_server.py]
```
