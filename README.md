# 🧠 GenAI QE Tool

A comprehensive Quality Engineering assistant powered by Generative AI. This tool provides:

### 🔹 Features

- 🧪 **Test Case Generator**: Generate test cases from requirement text files using LLMs like OpenAI.
- 🔗 **API Tester**: UI interface to send API requests and view structured responses.
- 🧾 **Log Analyzer**: Automatically parse logs and highlight exceptions and error patterns.

### 🗂️ Project Structure

```
GenAI_QE_Tool/
│
├── test_case_generator/   # LLM-based test case generation logic
├── api_tester/            # Core API request/response handling
├── log_analyzer/          # Log file parsing and error highlighter
├── ui/                    # Streamlit or Flask UI files
├── utils/                 # Helper utilities
├── configs/               # Configuration files
├── data/
│   ├── requirements/      # Sample requirement files
│   └── logs/              # Sample log files
├── tests/                 # Unit and integration tests
├── docs/                  # Project documentation
└── README.md              # Project overview
```

---

### 🚀 Getting Started

```bash
# Clone the repo
git clone https://github.com/your-username/genai-qe-tool.git
cd genai-qe-tool

# Setup your virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run ui/app.py
```

### 📌 Requirements

- Python 3.8+
- OpenAI API key (for test case generation)
- Streamlit or Flask
