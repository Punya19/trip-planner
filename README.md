
🧳 [AI Trip Planner](screencapture-localhost-8504-2026-01-19-01_14_06.png)

An AI-powered trip planning application that helps users generate personalized travel itineraries based on preferences such as destination, duration, and interests. The app uses multiple AI agents to plan trips efficiently and presents results through a simple web interface.

🚀 Features

Generates complete travel itineraries using AI agents

Plans trips based on user inputs like destination and travel days

Uses multiple agents for task planning and coordination

Interactive and easy-to-use web interface

Fast local AI inference without external API dependency

🛠️ Tech Stack

Python – Core application logic

AutoGen – Multi-agent orchestration

Ollama – Local LLM inference

Streamlit – Web-based user interface

⚙️ How It Works

User enters trip details through the Streamlit UI

AutoGen agents collaborate to plan travel routes and activities

Ollama runs the language model locally to generate responses

The final trip itinerary is displayed in real time

trip-planner/
│── agents/            # AI agents for planning
│── main.py            # Application entry point
│── requirements.txt   # Project dependencies
│── .env               # Environment variables
│── README.md          # Project documentation

# Create virtual environment
python -m venv venv
venv\Scripts\activate   # Windows

# Install dependencies
pip install -r requirements.txt

# Start Ollama
ollama serve

# Run the app
streamlit run main.py

🎯 Use Case

This project demonstrates how multi-agent AI systems can be used to solve real-world problems like travel planning, showcasing skills in AI integration, backend logic, and UI development.

📌 Future Enhancements

Budget-based trip planning

Hotel and transport recommendations

Map-based visualization

Deployment to cloud platforms


