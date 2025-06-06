🚗 Auto Expert
Auto Expert is an intelligent Python-powered diagnostic tool designed to help vehicle owners and mechanics quickly identify and understand vehicle issues based on user-described symptoms. Leveraging cutting-edge AI technologies, it delivers accurate, structured, and easy-to-understand vehicle problem diagnoses, possible causes, and actionable maintenance recommendations.

✨ Key Features
🩺 Symptom-Based Diagnosis: Users input vehicle details and observed symptoms, and Auto Expert analyzes these to suggest potential problems.

📋 Structured Output: The AI generates clear, organized results including a diagnosis summary, detailed causes, practical repair tips, and preventive maintenance advice.

🖥️ Interactive Interface: Built with Streamlit, offering a seamless and user-friendly web app experience accessible from any device.

🤖 AI-Driven Insights: Utilizes Google Generative AI models to provide intelligent, context-aware responses, ensuring recommendations are relevant and up-to-date.

🔒 Secure Configuration: Environment variables such as API keys are managed securely using dotenv to maintain confidentiality and ease deployment.

🛠️ Technologies Used
🐍 Python: Core programming language powering the entire application, chosen for its flexibility and strong AI ecosystem.

🚀 Streamlit: A rapid web app framework that simplifies building interactive user interfaces for data-driven applications.

🔗 LangChain: An advanced framework to orchestrate complex AI prompt workflows, manage context, and handle multi-step reasoning.

🧠 Google Generative AI: State-of-the-art AI models used for natural language understanding and generation, delivering expert-level vehicle diagnostics.

🔑 dotenv: Manages environment variables securely, helping to keep sensitive credentials safe and facilitating easy configuration across environments.

⚙️ Backend Architecture
The backend integrates Google Generative AI via the LangChain framework, which structures and manages the AI prompt interactions. When a user submits vehicle information and symptoms through the Streamlit interface, this input is sent to the AI model, which then:

🔍 Analyzes Symptoms: Identifies relevant vehicle systems and components potentially affected.

📝 Generates Diagnosis: Produces a prioritized list of probable issues in a structured format.

🛠️ Lists Causes: Provides detailed explanations of possible root causes for each identified problem.

🧰 Recommends Solutions: Suggests practical repair steps, troubleshooting tips, and preventive maintenance.

💻 Delivers Results: Outputs are rendered interactively on the Streamlit frontend for immediate user feedback.

This architecture ensures a responsive, intelligent, and scalable vehicle diagnostic experience, making automotive troubleshooting accessible to both professionals and everyday users.

