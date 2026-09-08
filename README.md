# 🎓 College Admission Agent — RAG-Based AI Assistant

> 💡 **Smart Guidance. Faster Decisions. Brighter Futures.**

## 🌟 About the Project

**College Admission Agent** is an intelligent, AI-powered chatbot designed to make the college admission journey **simpler, faster, and more accessible** for students.

🤖 It provides instant answers to common admission-related questions such as:

* 🎯 **Eligibility Criteria**
* 📚 **Available Courses & Programs**
* 💰 **Fee Structure**
* 📄 **Required Documents**
* 📅 **Important Dates & Deadlines**
* 🎓 **Scholarships & Financial Assistance**
* ❓ **Frequently Asked Questions**
* 📝 **Application & Admission Process**

🔍 The system uses **Retrieval-Augmented Generation (RAG)** to retrieve relevant information from trusted admission documents before generating a response.

🧠 **IBM Granite**, powered through **IBM watsonx.ai**, transforms the retrieved information into clear, natural-language answers that are easy for students to understand.

---

## 🚀 Key Features

| ✨ Feature                     | 📝 Description                                          |
| ----------------------------- | ------------------------------------------------------- |
| 🤖 **AI Admission Assistant** | Provides conversational admission guidance              |
| 🔍 **RAG-Based Search**       | Retrieves relevant information from admission documents |
| 🧠 **IBM Granite**            | Generates intelligent, natural-language responses       |
| 🎓 **Course Information**     | Helps students explore available programs               |
| ✅ **Eligibility Checker**     | Provides course eligibility information                 |
| 💰 **Fee Information**        | Answers questions about tuition and other fees          |
| 📄 **Document Guidance**      | Lists documents required for admission                  |
| 📅 **Deadline Information**   | Provides important admission dates                      |
| 🏆 **Scholarship Support**    | Provides scholarship-related information                |
| 💬 **Interactive Chat**       | Allows students to ask questions naturally              |

---

## 🛠️ Technologies Used

### ☁️ IBM Technologies

* 🧠 **IBM Granite**
* 🔗 **IBM watsonx.ai**
* ☁️ **IBM Cloud**

### 💻 Development Technologies

* 🐍 **Python**
* 🌐 **Flask**
* 🎨 **HTML**
* 💅 **CSS**
* ⚡ **JavaScript**

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/mahendrajoshwa-eng/AI-Powered-College-Admission-Agent.git
cd college-admission-agent
```

## 2️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

### 🪟 Windows

```bash
venv\Scripts\activate
```

### 🐧 Linux / 🍎 macOS

```bash
source venv/bin/activate
```

## 3️⃣ Install Dependencies

```bash
pip install -r backend/requirements.txt
```

## 4️⃣ ▶️ Run the Application

```bash
python backend/app.py
```

🌐 Once the server starts, open:

```text
http://localhost:5000
```

🎉 **Your College Admission Agent is ready to use!**

---

# 🔐 IBM watsonx.ai Configuration

Create a `.env` file in the **project root directory**:

```env
IBM_CLOUD_API_KEY=your_ibm_cloud_api_key
WATSONX_PROJECT_ID=your_watsonx_project_id
WATSONX_URL=https://us-south.ml.cloud.ibm.com
GRANITE_MODEL_ID=ibm/granite-4-h-small
```

🔑 Replace the placeholder values with your own **IBM Cloud** and **watsonx.ai** credentials.

---

# 📚 Add Admission Knowledge

Place your admission-related documents inside:

```text
data/admission_documents/
```

📂 Example:

```text
data/
└── admission_documents/
    ├── courses.txt
    ├── eligibility.txt
    ├── fees.txt
    ├── scholarships.txt
    ├── admission_process.txt
    ├── important_dates.txt
    └── required_documents.txt
```

🔍 The **RAG pipeline** retrieves relevant information from these documents before generating the final response.

---

# 🔒 Security

⚠️ **Never expose your IBM credentials!**

🚫 Do **not** upload your `.env` file or IBM API key to GitHub.

Add this to `.gitignore`:

```text
.env
venv/
__pycache__/
```

---

# 🧠 How It Works

```text
👨‍🎓 Student
      ↓
💬 Ask a Question
      ↓
🤖 College Admission Agent
      ↓
🔍 RAG Retrieval
      ↓
📚 Admission Knowledge Base
      ↓
🧠 IBM Granite
      ↓
✨ Intelligent Response
      ↓
👨‍🎓 Student
```

---

## 🌈 Project Vision

> 🎓 **Making college admissions easier, smarter, and more student-friendly — one question at a time.**

### 💙 Built with

**🧠 IBM Granite + 🔍 RAG + ☁️ IBM Cloud + 🤖 AI**

⭐ **College Admission Agent — Your Guide to a Brighter Future!**
