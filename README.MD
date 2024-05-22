---

# LangChain Google GenAI Integration

This project demonstrates the integration of LangChain with Google Generative AI using the `langchain-google-genai` package. It uses the Gemini 1.5 Flash model for language generation tasks, specifically for translating text into Japanese.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7 or higher
- Pip (Python package installer)
- Google Cloud Platform (GCP) API key with access to Generative AI

## Installation

1. **Clone the repository** (if applicable):

   ```sh
   git clone <repository_url>
   cd <repository_directory>
   ```

2. **Install the required packages**:

   ```sh
   pip install langchain
   pip install --upgrade --quiet langchain-google-genai
   ```

3. **Set up environment variables**:
   - Create a `.env` file in the project root directory and add your GCP API key:
     ```env
     GCP_API_KEY=your_gcp_api_key
     LANGCHAIN_API_KEY=your_langchain_api_key
     ```

## Example Output

Running the script should print the Japanese translation of "Hi!".

## Troubleshooting

- Ensure that your GCP API key is valid and has the necessary permissions for accessing the Generative AI models.
- Verify that the environment variables are correctly set by printing them or using debugging tools.
- Check the installation of the required Python packages and their versions.

## Acknowledgements

- [LangChain](https://github.com/hwchase17/langchain)
- [Google Generative AI](https://cloud.google.com/generative-ai)

---
