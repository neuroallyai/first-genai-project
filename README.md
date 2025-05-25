# NeuroAlly.AI
---
[![NeuroAlly.AI Project](https://img.shields.io/badge/NeuroAlly.AI-Project%20Roadmap-2856f7)](https://neuroally.ai/)
[![Python 3.10](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)](https://www.python.org/downloads/release/python-310/)
[![Launch Jupyter Notebook](https://img.shields.io/badge/Launch-Jupyter%20Notebook-orange?logo=jupyter)](https://mybinder.org/v2/gh/neuroallyai/first-genai-project/HEAD?labpath=notebooks%2F)
[![Anaconda](https://img.shields.io/badge/Anaconda-Environment-44A833?logo=anaconda)](https://anaconda.org/)
[![VSCode Recommended](https://img.shields.io/badge/VSCode-Recommended-blueviolet.svg)](https://code.visualstudio.com/)
---
[![Cookiecutter](https://img.shields.io/badge/built%20with-Cookiecutter-ff69b4.svg)](https://github.com/cookiecutter/cookiecutter)
[![License](https://img.shields.io/badge/License-MIT%2FApache--2.0%2FNone-yellow.svg)](https://opensource.org/licenses/)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit)
---
[![OpenAI API](https://img.shields.io/badge/OpenAI-API-10a37f?logo=openai)](https://platform.openai.com/docs/api-reference)
[![Gemini API](https://img.shields.io/badge/Gemini-API-4285F4?logo=google)](https://ai.google.dev/gemini-api/docs)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Poetry](https://img.shields.io/badge/Poetry-Package%20Management-60A5FA?logo=poetry&logoColor=white)](https://python-poetry.org/)
[![LangChain Enabled](https://img.shields.io/badge/LangChain-Enabled-blueviolet)](https://www.langchain.com/)
[![Docker Ready](https://img.shields.io/badge/Docker-Ready-2496ED?logo=docker&logoColor=white)](https://www.docker.com/)

---
# First Generative AI Project

*A minimal GPT-4.1 starter repo for secure, rapid GenAI prototyping.*

---

## Table of Contents

* [Overview](#overview)
* [Getting Started](#getting-started)
* [Tech Stack](#tech-stack)
* [Mission Alignment](#mission-alignment)
* [Learning Roadmap](#learning-roadmap)
* [Usage](#usage)
* [Example Output](#example-output)
* [Next Steps / Roadmap](#next-steps--roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Acknowledgments](#acknowledgments)
* [Contact](#contact)

---

## Overview

This Python application uses OpenAI’s **GPT-4.1** API to send prompts securely with environment-variable handling (`.env`).
It serves as a **modular, secure, and deploy-ready** foundation for building advanced Generative AI tools.

Built with a focus on:

* 🧠 Automating knowledge workflows
* 👥 Supporting veterans and inclusive services
* 🧰 Experimenting with GenAI pipelines such as **LangChain**, **n8n**, and **Vertex AI**

---

## Getting Started

### Prerequisites

* **Python 3.13** — [Download](https://www.python.org/downloads/)
* **OpenAI API key** — [Sign up](https://platform.openai.com/signup)

### Installation

```bash
# Clone the repository
git clone https://github.com/neuroallyai/first-genai-project.git
cd first-genai-project

# Install dependencies
pip install -r requirements.txt   # see requirements.txt for exact versions

# Set up environment variables
cp .env.example .env
# Edit .env to add your OpenAI API key securely
```

---

## Tech Stack

| Tool / Library       | Version    | Purpose                       |
| -------------------- | ---------- | ----------------------------- |
| `python`             | **3.13**   | Core language                 |
| `openai`             | **1.13.3** | GPT-4.1 API client            |
| `python-dotenv`      | **1.0.1**  | Secure key management         |
| `Anaconda Navigator` | Latest     | Environment & package manager |
| `VS Code`            | Latest     | IDE/Editor                    |
| `git`, `GitHub`      | —          | Version control & CI          |

See **[requirements.txt](requirements.txt)** for the full, pinned dependency list.

---

## Mission Alignment

This project is part of **NeuroAlly.AI** — an AI-first advocacy initiative promoting digital inclusion for disabled veterans and neurodivergent individuals.

---

## Learning Roadmap

This repository is directly mapped to the [NeuroAlly.AI GenAI Learning Roadmap](#), which defines the technical, ethical, and advocacy-focused skill progression behind each project.

> 🚦 **Every code release is milestone-driven, following this public learning journey — see the [attached roadmap file](./GenAI%20Learning%20Roadmap%20-%20v1.csv) for context and transparency.**

* Each feature and commit aligns with a specific learning or portfolio objective
* The project evolves as practical skills from the roadmap are mastered

---

## Usage

Run the script by providing a prompt to GPT-4.1:

```bash
python main.py --prompt "Hello, GPT-4.1!"
```

---

## Example Output

```bash
GPT-4.1 → Hello! How can I help you today?
```

---

## Next Steps / Roadmap

* [ ] **\[#12]** Add a Command-Line Interface (CLI) — **Q3 2025**
* [ ] **\[#22]** Dockerize the app — **Q4 2025**
* [ ] **\[#34]** Integrate with **LangChain** (RAG) — **Q1 2026**
* [ ] **\[#45]** Publish on **HuggingFace / Replicate** — **Q1 2026**

> 📈 *Next planned milestones are directly traceable in the learning roadmap CSV and in GitHub Issues.*

---

## Contributing

Contributions are welcome!
Please read **[CONTRIBUTING.md](CONTRIBUTING.md)** and adhere to our
**[CODE\_OF\_CONDUCT.md](CODE_OF_CONDUCT.md)**.

---

## License

This project is licensed under the MIT License — see the LICENSE file for details.

---

## Acknowledgments

* OpenAI for GPT-4.1
* DeepLearning.AI & Coursera for foundational GenAI courses
* Google Cloud Skills Boost & DataCamp for up-skilling resources
* The veterans and neurodivergent communities inspiring NeuroAlly.AI

---

## Contact

* Website » [NeuroAlly.AI](https://neuroally.ai)
* LinkedIn » [linkedin.com/in/jamiescottcraik](https://linkedin.com/in/jamiescottcraik)
* Email » [creator@fndveteran.uk](mailto:creator@fndveteran.uk)

---

### 🛤️ *Project Progress = Roadmap-Driven Learning*

Every commit = one more step in the [NeuroAlly.AI GenAI Learning Roadmap](./GenAI%20Learning%20Roadmap%20-%20v1.csv).
