# Rosie Chatbot

**Rosie** is a cute, sassy, and bold chatbot powered by OpenAI's GPT-3.5. Rosie is designed to interact with users in a fun and engaging way, providing witty, intelligent, and playful responses.

---

## 💡 Features

- **Engaging Conversations**: Chat with Rosie, a bold, sassy AI chatbot.
- **OpenAI-powered**: Built using OpenAI’s **GPT-3.5** API to generate intelligent and human-like responses.
- **Playful Personality**: Rosie’s personality is full of confidence, and she adds a touch of fun to each conversation.

---

## 🛠️ Requirements

To run **Rosie**, make sure you have:

- Python 3.7 or higher
- An OpenAI API key (which can be obtained from [OpenAI's platform](https://platform.openai.com/account/api-keys))

---

## 🚀 Setup Instructions

### 1. Clone the Repository

First, clone the repository to your local machine using the following command:

```bash
git clone https://github.com/YOUR-USERNAME/rosie-chatbot.git


2. **Install Dependencies**
Navigate to the project directory and install the required dependencies using pip:

bash
Copy
Edit
cd rosie-chatbot
pip install -r requirements.txt
If you don't have a requirements.txt file, manually install these dependencies:

bash
Copy
Edit
pip install openai python-dotenv streamlit


3.** Add Your OpenAI API Key**
To keep your API key secure:

Create a .env file in the root directory of your project.

Add your OpenAI API key to the .env file:

env
Copy
Edit
OPENAI_API_KEY=your-api-key-here
Make sure NOT to share this key publicly, and do not push the .env file to GitHub. It's added to .gitignore by default.

4.** Run the Chatbot Locally**
To run Rosie locally on your machine, use Streamlit:

bash
Copy
Edit
streamlit run app.py
This will open a browser window where you can chat with Rosie.

