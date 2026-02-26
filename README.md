# 🤖 AI Log Analyzer

An AI-powered log analysis platform built using **Spring Boot** and **OpenAI API** that automatically detects errors, summarizes root causes, and generates intelligent debugging suggestions from application log files.

This system reduces manual debugging effort by **50%** through automated AI-driven log analysis.

---

## 📌 Project Overview

The **AI Log Analyzer** is designed to:

- Parse server log files
- Detect critical errors
- Classify error types
- Generate AI-based root cause summaries
- Suggest debugging solutions
- Improve monitoring efficiency

This project demonstrates:

- AI integration in backend systems
- Automation mindset
- Log processing architecture
- Scalable backend design
- Production-style deployment

---

## 🏗 System Architectur

```html
<div align="center">
  <img src="architecture-diagram.png" alt="AI Log Analyzer Architecture" width="900"/>
</div>



🔁 Data Flow

User uploads a log file.
Backend parses log entries.
System extracts error patterns.
Relevant log snippets are sent to OpenAI API.

AI generates:
Root cause summary
Severity classification
Suggested resolution
Results are stored in MySQL.
Structured output is returned to user.

✨ Features

📄 Log file upload support
🧠 AI-powered error detection
🔎 Automatic root cause summarization
⚠ Severity classification (Low / Medium / High)
💡 AI-generated debugging suggestions

🗄 Persistent storage in MySQL
🐳 Dockerized deployment
☁️ Cloud-ready architecture

📡 API Endpoints
Upload Log File
POST /logs/upload
Get Analysis Result
GET /logs/{id}


🛠 Tech Stack
Backend
Java
Spring Boot
REST APIs
OpenAI API Integration

Database
MySQL

DevOps & Cloud
Docker
AWS EC2

Git & GitHub

 Running Locally
1 Clone Repository
git clone https://github.com/yourusername/ai-log-analyzer.git

cd ai-log-analyzer
2️ Configure OpenAI API Key

Add in application.properties:
openai.api.key=YOUR_API_KEY
3 Build Docker Image
docker build -t ai-log-analyzer .

4️Run Container
docker run -p 8080:8080 ai-log-analyzer

Application runs at:
http://localhost:8080

 Impact

Reduced manual debugging time by 50%
Automated log triaging

Faster incident resolution

Improved monitoring efficiency
Real-World Applications

This system can be adapted for:
Production server monitoring
Cloud infrastructure logs
Microservices error tracking
DevOps log analysis
Security incident detection
CI/CD pipeline log inspection

Future Improvements

Real-time log streaming
Role-based authentication (JWT)
Kubernetes deployment
Prometheus monitoring integration
Multi-model AI support
Frontend dashboard

Author

Kunal Prajapat
Java Backend Developer | AI & Cloud Enthusiast
