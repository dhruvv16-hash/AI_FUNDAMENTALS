# 🧠 AI Fundamentals & Masterclass: Hands-On Learning Lab

Welcome to the **AI Fundamentals & Masterclass** repository! This workspace is designed as a complete, self-paced learning path to master modern Artificial Intelligence concepts—from APIs and text embeddings to Retrieval-Augmented Generation (RAG) and autonomous AI Agents.

This repository uniquely pairs **interactive visual web guides** with **practical hands-on coding notebooks** to ensure a deep, multi-dimensional understanding of AI engineering.

---

## 📂 Repository Contents

The workspace is organized into two main parts:

### 1. 🎨 The Interactive Visual Guides (Root Directory)
Directly in the root folder, you will find two rich, interactive web pages built to simplify complex concepts:
*   **[Visual Study Guide (ai_masterclass_visual_guide.html)](file:///e:/DHRUV_BACKUP/AI/ai_masterclass_visual_guide.html)**: A beautifully designed visual dashboard covering the theory of LLMs, Embeddings, RAG, Prompt Engineering, and Agentic loops with animated diagrams, sticky notes, and clean comparisons.
*   **[Interactive Coding Lab (ai_coding_lab.html)](file:///e:/DHRUV_BACKUP/AI/ai_coding_lab.html)**: An interactive guide mapped directly to the codebase. It provides a detailed, line-by-line breakdown of every crucial code cell, showing exactly how the APIs and frameworks function under the hood.

> [!TIP]
> To view these guides, simply open [ai_masterclass_visual_guide.html](file:///e:/DHRUV_BACKUP/AI/ai_masterclass_visual_guide.html) or [ai_coding_lab.html](file:///e:/DHRUV_BACKUP/AI/ai_coding_lab.html) directly in any web browser (Chrome, Safari, Edge, or Firefox).

### 2. 💻 The Hands-On Codebase (`/AI_Fundamentals_Data_Domain-main`)
A full hands-on project folder containing structured Jupyter notebooks, dependencies, and datasets.

*   **Chapter 1: Large Language Models (LLMs)**
    *   `1_API_Calls.ipynb`: Call LLM providers (OpenAI SDK, Google Gemini SDK) programmatically.
    *   `2_Embeddings.ipynb`: Generate text embeddings (1536-dimensional vectors) and calculate semantic similarity.
*   **Chapter 2: Retrieval-Augmented Generation (RAG)**
    *   `1_RAG.ipynb`: Build a complete RAG search and question-answering pipeline using ChromaDB.
    *   `NovaS.pdf`: Sample document used for knowledge retrieval.
*   **Chapter 3: Prompt Engineering**
    *   `Prompting_Types.ipynb`: Walkthrough of zero-shot, few-shot, and Chain-of-Thought (CoT) patterns.
    *   `prompt_call.ipynb`: Implementation examples of templates and system prompt structures.
*   **Chapter 4: Building AI Agents**
    *   `1_Tool_Binding.ipynb`: Bind custom functions and web tools (DuckDuckGo, Wikipedia) to LLMs.
    *   `2_ReAct_Agent.ipynb`: Implement an autonomous agent using the ReAct (Reasoning + Acting) loop.
    *   `3_Structured_Output.ipynb`: Enforce and extract validated Pydantic models from model outputs.
    *   `4_prompt_templates.ipynb`: Advanced prompt setups for agent orchestration.
    *   `5.1_RAG_Semantic.ipynb` & `5.2_RAG_Agent.ipynb`: Advanced semantic retrieval and RAG-capable agents.
    *   `6_Agent_Memory.ipynb`: Add conversation history and memory buffers for stateful agents.

---

## 🛠️ Project Structure

```text
AI/
├── ai_masterclass_visual_guide.html  # Interactive visual theory dashboard
├── ai_coding_lab.html                # Interactive code line-by-line explanation
└── AI_Fundamentals_Data_Domain-main/ # Hands-on codebase directory
    ├── CH-1_LLMs/                    # Chapter 1 Notebooks (APIs, Embeddings)
    ├── CH-2_RAG/                     # Chapter 2 Notebooks (ChromaDB, PDF extraction)
    ├── CH-3_Prompt_Engineering/      # Chapter 3 Notebooks (Few-shot, CoT)
    ├── CH-4_Agent/                   # Chapter 4 Notebooks (ReAct, Tools, Memory)
    ├── requirements.txt              # Project Python packages
    ├── pyproject.toml / uv.lock      # Package manager configurations
    └── README.md                     # Codebase-specific README
```

---

## 🚀 Getting Started with the Code

To run the Python notebooks locally on your machine, follow these steps:

### 1. Navigate to the Code Folder
Open your terminal or command prompt and change directory to the codebase folder:
```bash
cd AI_Fundamentals_Data_Domain-main
```

### 2. Set Up a Virtual Environment
Create a clean virtual environment and activate it:
```bash
# Create the environment
python -m venv .venv

# Activate it (Windows)
.venv\Scripts\activate

# Activate it (macOS/Linux)
source .venv/bin/activate
```

### 3. Install Dependencies
Install all the required libraries (including LangChain, OpenAI, Google GenAI, and ChromaDB):
```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables
Create a file named `.env` in the `AI_Fundamentals_Data_Domain-main` folder and add your API keys:
```env
OPENAI_API_KEY=your-openai-api-key
GEMINI_API_KEY=your-gemini-api-key
```

### 5. Start Jupyter Notebook
Launch Jupyter to start editing and running the code cells:
```bash
jupyter notebook
```

---

## 🎓 Learning Path Recommendation
For the best learning experience, we recommend:
1.  **Read the Concept**: Open [ai_masterclass_visual_guide.html](file:///e:/DHRUV_BACKUP/AI/ai_masterclass_visual_guide.html) in your browser and study the chapter's conceptual layout.
2.  **Open the Notebook**: Go to the corresponding Jupyter notebook in `/AI_Fundamentals_Data_Domain-main` and execute the cells.
3.  **Inspect the Logic**: Use [ai_coding_lab.html](file:///e:/DHRUV_BACKUP/AI/ai_coding_lab.html) as you run code cells to read deep line-by-line explanations of how complex functions and configurations work.
