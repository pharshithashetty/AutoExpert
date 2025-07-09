
# 🚗 Auto Expert – AI-Powered Vehicle Diagnosis

**Auto Expert** is an intelligent AI-powered tool that helps vehicle owners and mechanics quickly diagnose car problems based on described symptoms. With advanced reasoning and natural language understanding, it delivers expert-level insights, practical repair guidance, and preventive care suggestions — all in a simple, user-friendly web app.

---

## 🌟 Key Features

* **🩺 Symptom-Based Diagnosis**
  Describe your vehicle’s symptoms in plain language — Auto Expert interprets and identifies potential issues.

* **📋 Organized, Actionable Reports**
  Get a detailed diagnosis summary with:

  * Likely causes
  * Troubleshooting and repair tips
  * Preventive maintenance advice

* **🖥️ User-Friendly Web App**
  Built with **Streamlit**, the interface works seamlessly on desktop and mobile — no technical knowledge required.

* **🤖 AI-Driven Insights**
  Powered by **Google Generative AI** and managed through **LangChain** for deep, context-aware reasoning.

* **🔐 Secure Configuration**
  Environment variables like API keys are handled using **dotenv**, keeping your credentials safe.

---

## 🧰 Tech Stack

* **Python** – Core application logic
* **Streamlit** – Web app framework
* **Google Generative AI** – Natural language processing and reasoning
* **LangChain** – AI workflow orchestration
* **dotenv** – Environment variable management

---

## ⚙️ How It Works

1. **Input**: Users enter vehicle information and describe symptoms.
2. **AI Reasoning**: LangChain routes input to Google Generative AI to analyze and infer possible issues.
3. **Diagnosis**: Auto Expert returns a prioritized list of potential problems, their causes, and solutions.
4. **Display**: Results are shown in an interactive web interface for immediate action.

---

## 📦 Installation & Setup

Follow these steps to set up Auto Expert locally:

1. **Clone the Repository**
   Open a terminal and run:

   ```
   git clone https://github.com/pharshithashetty/auto-expert.git
   cd auto-expert
   ```

2. **Install Dependencies**
   Make sure you have Python installed, then run:

   ```
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables**
   Create a `.env` file in the root directory and add your API key:

   ```
   GOOGLE_API_KEY=your_api_key_here
   ```

4. **Run the Application**
   Start the web app with:

   ```
   streamlit run app.py
   ```

5. **Open in Browser**
   Streamlit will open the app automatically, or you can visit `http://localhost:8501`.

---

## ✅ Use Cases

* **Mechanics** needing fast second opinions
* **Vehicle owners** diagnosing issues before service visits
* **DIY repairers** seeking troubleshooting guidance
* **Fleet managers** monitoring and maintaining multiple vehicles

---

## 📄 License

This project is licensed under the **MIT License**. See the `LICENSE` file for full details.

---

## 🙌 Contributing

We welcome contributions!
If you’d like to add features, improve the AI prompts, or enhance the interface — please open an issue or pull request.

---

## 📬 Contact

Questions or collaboration inquiries?
📧 **[pharshithashetty@gmail.com](mailto:pharshithashetty@gmail.com)**
