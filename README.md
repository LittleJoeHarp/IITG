
---

# Book Finder

Welcome to Book Finder, a chatbot designed to provide personalized book recommendations based on your budget and requirements. You can access the web app [here](#).

## Features
- **Personalized Recommendations:** Get information and choose books according to your requirements.
- **Dynamic Filtering:** Adjust your preferences to receive the most suitable recommendations.

## Getting Started

### Prerequisites
- Python 3.12

### Installation

1. **Create and activate a Python virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

2. **Install the required dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Set the environment variable `GOOGLE_API_KEY` with your own Gemini API key:**

   You can get your free Gemini API key from [here](#).

   - **Windows:**

     ```powershell
     $env:GOOGLE_API_KEY = "your_gemini_api_key"
     ```

   - **Linux:**

     ```bash
     export GOOGLE_API_KEY="your_gemini_api_key"
     ```

### Usage

To start the application, run:

```bash
python bookstore.py
```

Interact with the chatbot to receive book recommendations based on price, genre, and other preferences.

## Project Structure
- **`bookstore.py`**: The main file for running the application.
- **`requirements.txt`**: List of Python libraries required to run the app.
- **`vectorstore/`**: Directory containing the vector database (FAISS).

---


