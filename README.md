http://127.0.0.1:5000/

![image](https://github.com/user-attachments/assets/f3ec2af9-6633-48c9-9774-78d5d0e65999)


Simple AI Chatbot using Flask & OpenRouter
This is a lightweight, browser-based AI chatbot built using Flask, HTML, CSS, and JavaScript. It leverages the OpenRouter API to respond intelligently to user queries in real time.

🚀 Features
Interactive chat UI with message history

Asynchronous communication with OpenRouter API

Typing indicator for a better user experience

Responsive and clean UI design using pure HTML/CSS

Auto-launches in the browser on start

📦 Tech Stack
Backend: Flask (Python)

Frontend: HTML, CSS, JavaScript (Vanilla)

API: OpenRouter (LLM backend)

Threading: Used to auto-open browser after server start

📷 Preview

<sup>(Replace with actual screenshot)</sup>

Setup Instructions
1. Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/flask-chatbot.git
cd flask-chatbot
2. Create a virtual environment and activate it
bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install the dependencies
bash
Copy
Edit
pip install flask requests
4. Add your OpenRouter API Key
Replace the API key in this section of the code in app.py:

python
Copy
Edit
"Authorization": "Bearer YOUR_API_KEY_HERE",
You can get your API key from OpenRouter.ai.

🧪 Run the Project
bash
Copy
Edit
python app.py
This will:

Start the Flask server on http://127.0.0.1:5000

Automatically open the chatbot in your default browser

📁 Project Structure
bash
Copy
Edit
.
├── app.py                # Main Flask app
├── README.md             # Project documentation
No templates/ or static/ folders required — the HTML is rendered directly from a Python string.

⚠️ Notes
This project is intended for local use only. If you deploy it publicly, ensure to secure the API key and add rate-limiting.

Add error handling and input validation if extending the project.

For production, consider using gunicorn or waitress instead of Flask's built-in server.
