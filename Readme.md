# 🤖 LLM-Powered Robot Agent

This repository is the initial scaffold for a **Python-based project** focused on building a modular, test-driven system around LLM-powered robot agents.

At this stage, the project structure and contribution workflow are being set up.  
Detailed design decisions and features will be documented as the project evolves.

---

## 📌 Current Status

- Repository scaffolding complete
- Testing framework in place (`pytest`)
- Contribution guidelines defined
- Ready for external contributors

⚠️ **Note:**  
The core architecture and functionality are still under discussion.  
Please avoid making assumptions about final APIs unless explicitly documented.

---

## 🗂 Repository Structure

```
llm-powered-robot-agent/
│
├── functions/        # Core functions (implementation lives here)
├── tests/            # Pytest-based tests
├── docs/             # Documentation (to be expanded)
├── scripts/          # Utility scripts
│
├── requirements.txt
├── README.md
├── CONTRIBUTING.md
└── pytest.ini
```

---

## 🛠 Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/ERS-IIITJ/llm-powered-robot-agent.git
cd llm-powered-robot-agent
```

### 2️⃣ Create and activate a virtual environment
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

---

## 🧪 Running Tests

Run all tests from the project root:

```bash
pytest
```

Run a specific test file:

```bash
pytest tests/test_example.py
```

🚫 Do not run tests directly using `python test_file.py`.

---

## 🤝 Contributing

Contributions are welcome.

Please read **[CONTRIBUTING.md](docs/CONTRIBUTING.md)** before opening an issue or pull request.

Key rules:
- All functions must include tests
- Use `pytest`
- Follow Conventional Commits
- Keep pull requests focused

---

## 📜 License

License information will be added later.

---

## 📎 Notes

This README is intentionally minimal.  
More detailed documentation will be added once the project direction is finalized.