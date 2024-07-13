BOOK FINDER
Welcome to Book Finder, a chatbot designed to provide laptop recommendations based on your budget and requirements. You can access the webapp here.
Features
Personalized Recommendations: Get information and choose books according to requirments.
Dynamic Filtering: Adjust your preferences to receive the most suitable recommendations.
Getting Started
Prerequisites
Python 3.12
Create and activate a Python virtual environment:
Install the required dependencies:
pip install -r requirements.txt
Set the environment variable GOOGLE_API_KEY with your own Gemini API key which you can get for free from here:
Windows:
$env:GOOGLE_API_KEY = "your_gemini_api_key"
Linux:
export GOOGLE_API_KEY="your_gemini_api_key"
Usage
python bookstore.py
Interact with the chatbot to receive book recommendations based on price, genre,etc.
Project Structure
bookstore.py: The main file.
requirements.txt: List of Python libraries required to run the app.
vectorstore: Directory containing vector database (FAISS).


