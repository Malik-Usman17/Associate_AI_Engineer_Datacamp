<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Associate%20AI%20Engineer&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=for%20Developers%20%E2%80%A2%20DataCamp%20Career%20Track&descAlignY=58&descSize=18" alt="Associate AI Engineer for Developers banner" width="100%"/>

<a href="https://github.com/othneildrew/Best-README-Template"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=36BCF7&center=true&vCenter=true&width=640&lines=Building+AI+apps+with+the+OpenAI+API;Embeddings+%2B+Vector+Search+with+Pinecone;Agents+and+Chains+with+LangChain;Shipping+production-ready+AI+systems" alt="Typing animation"/></a>

<br/>

![Track](https://img.shields.io/badge/DataCamp-Career%20Track-03EF62?style=for-the-badge&logo=datacamp&logoColor=white)
![Courses](https://img.shields.io/badge/Courses-10-1f6feb?style=for-the-badge)
![Projects](https://img.shields.io/badge/Guided%20Projects-2-8957e5?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-Required-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Progress-f0883e?style=for-the-badge)

**A public log of my learning path from developer to AI engineer.**
Notes, code, and projects for every course in the track.

[Track Page](https://www.datacamp.com/tracks/associate-ai-engineer-for-developers) ·
[Roadmap](#-roadmap) ·
[Course Tracker](#-course-tracker) ·
[Projects](#-projects) ·
[Tech Stack](#-tech-stack)

</div>

---

## 📊 Progress

<!-- UPDATE: change the numbers in the badge URL and the bar below after each course -->

![Progress](https://img.shields.io/badge/Progress-1%2F10%20courses-blue?style=flat-square&logo=target)

```text
[██░░░░░░░░░░░░░░░░░░░]   10%   (1 / 10 courses)
```

> **How to update:** change `0%2F10` in the badge URL to `N%2F10`, then fill the text bar (each `█` = 5%).

---

## 🧭 Roadmap

```mermaid
flowchart LR
    A["1. OpenAI API"] --> B["2. Prompt Engineering"]
    B --> C["3. Hugging Face"]
    C --> D["4. LLMOps Concepts"]
    D --> E["5. Embeddings"]
    E --> F["6. Pinecone"]
    F --> G["7. SE Principles in Python"]
    G --> H["8. LangChain"]
    H --> I["9. Responses API"]
    I --> J["10. MCP"]
    J --> K(["🚀 Capstone Projects"])

    style A fill:#1f6feb,color:#fff,stroke:none
    style B fill:#1f6feb,color:#fff,stroke:none
    style C fill:#8957e5,color:#fff,stroke:none
    style D fill:#8957e5,color:#fff,stroke:none
    style E fill:#238636,color:#fff,stroke:none
    style F fill:#238636,color:#fff,stroke:none
    style G fill:#bf8700,color:#fff,stroke:none
    style H fill:#da3633,color:#fff,stroke:none
    style I fill:#da3633,color:#fff,stroke:none
    style J fill:#da3633,color:#fff,stroke:none
    style K fill:#f0883e,color:#fff,stroke:none
```

| Phase | Focus | Courses |
|:--|:--|:--|
| 🔵 **Foundations** | Call LLM APIs and write effective prompts | 1–2 |
| 🟣 **Open Models & Ops** | Use open-source models, understand LLM production | 3–4 |
| 🟢 **Retrieval** | Embed text, search with a vector database | 5–6 |
| 🟡 **Engineering** | Write modular, testable Python | 7 |
| 🔴 **Orchestration** | Chains, agents, newer APIs, tool access | 8–10 |

---

## ✅ Course Tracker

Tick the boxes as you finish. Expand each course for notes and code links.

- [✅] **1. Working with the OpenAI API**
- [ ] **2. Prompt Engineering with the OpenAI API**
- [ ] **Guided Project 1**
- [ ] **3. Working with Hugging Face**
- [ ] **4. LLMOps Concepts**
- [ ] **5. Introduction to Embeddings with the OpenAI API**
- [ ] **6. Vector Databases with Pinecone**
- [ ] **Guided Project 2**
- [ ] **7. Software Engineering Principles in Python**
- [ ] **8. Developing LLM Applications with LangChain**
- [ ] **9. Working with the OpenAI Responses API**
- [ ] **10. Introduction to Model Context Protocol (MCP)**


<br/>

<details>
<summary><b>🔵 1 · Working with the OpenAI API</b> &nbsp;·&nbsp; <code>Foundations</code></summary>

<br/>

**Goal:** Build AI-powered applications with the OpenAI API, the functionality behind tools like ChatGPT.

| | |
|:--|:--|
| **Status** | ⬜ Not started |
| **Date completed** | 15-October-2026 |
| **Code** | [`/01-openai-api`](./01-openai-api) |

**Key takeaways**
- _Add what you learned_
- _Add what you learned_

**Snippet**
```python
from openai import OpenAI

client = OpenAI()
response = client.chat.completions.create(
    model="gpt-4o-mini",
    messages=[{"role": "user", "content": "Explain embeddings in one sentence."}],
)
print(response.choices[0].message.content)
```

</details>

<details>
<summary><b>🔵 2 · Prompt Engineering with the OpenAI API</b> &nbsp;·&nbsp; <code>Foundations</code></summary>

<br/>

**Goal:** Apply prompt engineering principles and best practices to GPT models through the API.

| | |
|:--|:--|
| **Status** | ⬜ Not started |
| **Date completed** | — |
| **Code** | [`/02-prompt-engineering`](./02-prompt-engineering) |

**Key takeaways**
- _Add what you learned_

</details>

<details>
<summary><b>🟣 3 · Working with Hugging Face</b> &nbsp;·&nbsp; <code>Open Models</code></summary>

<br/>

**Goal:** Navigate the Hugging Face Hub, run models and pipelines, and work with datasets.

| | |
|:--|:--|
| **Status** | ⬜ Not started |
| **Date completed** | — |
| **Code** | [`/03-hugging-face`](./03-hugging-face) |

**Key takeaways**
- _Add what you learned_

**Snippet**
```python
from transformers import pipeline

generator = pipeline("text-generation", model="gpt2")
print(generator("AI engineering is", max_new_tokens=30)[0]["generated_text"])
```

</details>

<details>
<summary><b>🟣 4 · LLMOps Concepts</b> &nbsp;·&nbsp; <code>Operations</code></summary>

<br/>

**Goal:** Understand the practices for developing, deploying, and maintaining LLM systems in production.

| | |
|:--|:--|
| **Status** | ⬜ Not started |
| **Date completed** | — |
| **Notes** | [`/04-llmops`](./04-llmops) |

**Key takeaways**
- _Add what you learned_

</details>

<details>
<summary><b>🟢 5 · Introduction to Embeddings with the OpenAI API</b> &nbsp;·&nbsp; <code>Retrieval</code></summary>

<br/>

**Goal:** Use OpenAI's embedding model to build semantic search and recommendation engines.

| | |
|:--|:--|
| **Status** | ⬜ Not started |
| **Date completed** | — |
| **Code** | [`/05-embeddings`](./05-embeddings) |

**Key takeaways**
- _Add what you learned_

**Snippet**
```python
from openai import OpenAI

client = OpenAI()
emb = client.embeddings.create(
    model="text-embedding-3-small",
    input="semantic search with embeddings",
)
print(len(emb.data[0].embedding))
```

</details>

<details>
<summary><b>🟢 6 · Vector Databases with Pinecone</b> &nbsp;·&nbsp; <code>Retrieval</code></summary>

<br/>

**Goal:** Store, index, and query embeddings with the Pinecone vector database.

| | |
|:--|:--|
| **Status** | ⬜ Not started |
| **Date completed** | — |
| **Code** | [`/06-pinecone`](./06-pinecone) |

**Key takeaways**
- _Add what you learned_

</details>

<details>
<summary><b>🟡 7 · Software Engineering Principles in Python</b> &nbsp;·&nbsp; <code>Engineering</code></summary>

<br/>

**Goal:** Write modular, documented, and testable Python for production AI code.

| | |
|:--|:--|
| **Status** | ⬜ Not started |
| **Date completed** | — |
| **Code** | [`/07-se-principles`](./07-se-principles) |

**Key takeaways**
- _Add what you learned_

</details>

<details>
<summary><b>🔴 8 · Developing LLM Applications with LangChain</b> &nbsp;·&nbsp; <code>Orchestration</code></summary>

<br/>

**Goal:** Build applications with LLMs, prompts, chains, and agents in LangChain.

| | |
|:--|:--|
| **Status** | ⬜ Not started |
| **Date completed** | — |
| **Code** | [`/08-langchain`](./08-langchain) |

**Key takeaways**
- _Add what you learned_

</details>

<details>
<summary><b>🔴 9 · Working with the OpenAI Responses API</b> &nbsp;·&nbsp; <code>Orchestration</code></summary>

<br/>

**Goal:** Build interactive, reliable AI applications with the newer OpenAI Responses API.

| | |
|:--|:--|
| **Status** | ⬜ Not started |
| **Date completed** | — |
| **Code** | [`/09-responses-api`](./09-responses-api) |

**Key takeaways**
- _Add what you learned_

</details>

<details>
<summary><b>🔴 10 · Introduction to Model Context Protocol (MCP)</b> &nbsp;·&nbsp; <code>Orchestration</code></summary>

<br/>

**Goal:** Connect models to external tools and data through MCP.

| | |
|:--|:--|
| **Status** | ⬜ Not started |
| **Date completed** | — |
| **Code** | [`/10-mcp`](./10-mcp) |

**Key takeaways**
- _Add what you learned_

</details>

---

## 🚀 Projects

| # | Project | Stack | Status | Link |
|:-:|:--|:--|:-:|:-:|
| 1 | _Guided project 1_ | _OpenAI · Python_ | ⬜ | [`/projects/project-1`](./projects/project-1) |
| 2 | _Guided project 2_ | _LangChain · Pinecone_ | ⬜ | [`/projects/project-2`](./projects/project-2) |
| ⭐ | _Own capstone: RAG app with semantic search_ | _Embeddings · Pinecone · LangChain_ | ⬜ | [`/projects/capstone`](./projects/capstone) |

---

## 🛠 Tech Stack

<div align="center">

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Model%20Context%20Protocol-0f2027?style=for-the-badge)

</div>

---

## 🎯 Skills Gained

<details open>
<summary><b>Click to collapse</b></summary>

<br/>

| Skill | Course(s) | Confidence |
|:--|:--|:--|
| Call LLM APIs and handle responses | 1, 9 | ⭐☆☆☆☆ |
| Design prompts programmatically | 2 | ⭐☆☆☆☆ |
| Run and evaluate open-source models | 3 | ⭐☆☆☆☆ |
| Explain LLMOps in production | 4 | ⭐☆☆☆☆ |
| Build semantic search with embeddings | 5, 6 | ⭐☆☆☆☆ |
| Write modular, testable Python | 7 | ⭐☆☆☆☆ |
| Build chains and agents | 8 | ⭐☆☆☆☆ |
| Connect models to tools through MCP | 10 | ⭐☆☆☆☆ |

</details>

---

## 🗂 Repository Structure

```text
.
├── 01-openai-api/
├── 02-prompt-engineering/
├── 03-hugging-face/
├── 04-llmops/
├── 05-embeddings/
├── 06-pinecone/
├── 07-se-principles/
├── 08-langchain/
├── 09-responses-api/
├── 10-mcp/
├── projects/
│   ├── project-1/
│   ├── project-2/
│   └── capstone/
└── README.md
```

---

## ⚙️ Quick Start

```bash
# 1. Clone
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

# 2. Create environment
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install openai transformers langchain pinecone python-dotenv

# 4. Add API keys
cp .env.example .env             # then set OPENAI_API_KEY and PINECONE_API_KEY
```

> ⚠️ Never commit `.env`. Add it to `.gitignore`.

---

## 🗓 Learning Log

| Date | Course | Hours | Notes |
|:--|:--|:-:|:--|
| _YYYY-MM-DD_ | _Course name_ | _1.5_ | _What you built or learned_ |

---

## 🔗 Resources

- [Track page on DataCamp](https://www.datacamp.com/tracks/associate-ai-engineer-for-developers)
- [OpenAI API docs](https://platform.openai.com/docs)
- [Hugging Face docs](https://huggingface.co/docs)
- [LangChain docs](https://python.langchain.com)
- [Pinecone docs](https://docs.pinecone.io)
- [Model Context Protocol](https://modelcontextprotocol.io)

---

<div align="center">

**Built while learning. Updated after every course.**

<sub>Course content © DataCamp. This repository contains only my own notes and code.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=100&section=footer" width="100%" alt="footer"/>

</div>
