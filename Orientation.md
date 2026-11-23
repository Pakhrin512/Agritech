# AI Foundation Training - Agritech Track
## Agricultural Agentic AI
### From Agricultural Understanding to an Integrated Intelligence System

---

## 1. What Is This Training About?

This training introduces students to the use of modern AI to understand and address real agricultural challenges. It connects agricultural understanding, data and intelligence, and the development of specialised AI agents.

### Three learning dimensions

1. **Agricultural understanding**
   - Understand how agricultural systems, production workflows, stakeholders and value chains operate.
2. **Data and intelligence**
   - Identify, prepare and analyse agricultural data; organise agricultural knowledge and use AI to interpret information.
3. **Agentic AI development**
   - Build specialised agents that retrieve information, use tools, coordinate tasks and support decisions.

Ten groups investigate ten agricultural intelligence themes. They contribute to a shared **Agricultural Data Foundation** and integrate their components into one Agricultural Agentic AI prototype.

---

## 2. Four Phases of the Programme

The programme moves from understanding a real situation to developing and evaluating an integrated prototype.

1. **Understand** — Explore agricultural systems, workflows, stakeholders and available data.
2. **Formulate** — Identify and structure agricultural problems.
3. **Build** — Develop analytical capabilities, knowledge retrieval and specialised agents.
4. **Transform** — Integrate capabilities into an AI-enabled workflow and evaluate the prototype.

**Central progression:** Understand the system → Formulate the problem → Work with evidence → Build intelligence.

---

## 3. Why Is This Important for IT Students?

This programme helps IT students move beyond developing isolated models or applications. It introduces the engineering of complete intelligence workflows that connect real-world needs, data, analytics, AI and software systems.

### Design complete intelligence workflows
Learn to design systems that connect data, analytical methods, AI capabilities and software components rather than building isolated models or apps.

### Develop domain understanding
Learn how to translate real-world needs into technical requirements. This skill is transferable to agriculture, healthcare, finance, retail, public services and other sectors.

### Understand that data is the foundation
The quality, relevance and limitations of data determine how useful an AI system can be. Students learn to inspect data, understand its origin and document uncertainty.

### Connect the complete AI workflow
Work across the end-to-end process: data preparation, analytics, knowledge retrieval, AI models, agents, APIs and system integration.

### Practise collaborative software engineering
Work through a shared repository with one central repository, ten group branches and forty individual member branches. Students practise commits, pull requests and reviews.

### Build responsibly
Use evidence, state uncertainty, label simulated data clearly and include human validation where needed.

---

## 4. What Will You Learn?

By the end of the programme, students should be able to demonstrate the following capabilities.

1. **Understand a system:** Describe agricultural workflows, identify stakeholders, information needs and decision gaps.
2. **Identify and prepare data:** Explore sources, inspect CSV/Excel files, and document data provenance and quality.
3. **Formulate problems using UDAAN U0:** Create an eight-element, structured and evidence-aware problem record.
4. **Perform analytics using UDAAN U1–U3:** Descriptive, diagnostic and predictive analysis.
5. **Work with LLMs and RAG:** Understand embeddings and vector search, work with local LLMs, build retrieval-augmented generation workflows and check answers against sources.
6. **Develop agents and workflows:** Use tool calling, an Agent Manager, Reviewer Agents and human-in-the-loop validation.
7. **Collaborate using GitHub:** Use branches, commits, pull requests, reviews and Markdown documentation.

---

## 5. Formulating Problems: UDAAN U0

UDAAN U0 provides an eight-element structure for documenting an agricultural problem before selecting or building a technical solution.

| Element | Guiding question |
|---|---|
| 1. Context | Where and under what conditions does the problem occur? |
| 2. Stakeholders | Who experiences, influences or addresses it? |
| 3. Expected Condition | What should happen? |
| 4. Observed Condition | What is actually happening? |
| 5. Gap and Significance | What is the difference, and why does it matter? |
| 6. Evidence and Uncertainty | What is known, assumed and unknown? |
| 7. Scope and Constraints | What are the boundaries and limitations? |
| 8. Formulated Problem | What exactly needs investigation? |

The purpose is to make the problem clear, bounded and evidence-aware before deciding whether analytics, machine learning, retrieval or agents are appropriate.

---

## 6. Analytics: UDAAN U1–U3

The analytics stages investigate a problem at three levels.

### U1 — Descriptive: What is happening?
- Data inspection and cleaning.
- Frequency analysis.
- Summary statistics.
- Tables and charts.

### U2 — Diagnostic: Why might it be happening?
- Group comparison.
- Correlation and regression.
- Significance analysis.
- Examination of confounding factors.

### U3 — Predictive: What might happen next?
- Defining features and targets.
- Preparing training and testing data.
- Forecasting.
- Establishing baselines.
- Evaluating predictive performance.

**Important limitation:** U3 depends on suitable historical data. If the available data cannot support prediction, students must document the limitation or use clearly labelled simulated data for demonstration. Unsupported predictions must never be presented as real findings.

---

## 7. LLMs, RAG and Specialised Agents

### 7.1 Knowledge retrieval with RAG

The programme introduces a retrieval-augmented generation workflow involving:
- Document processing.
- Text chunking.
- Embeddings.
- Vector search using tools such as FAISS and sentence-transformers.
- Frameworks such as LangChain or LlamaIndex.
- Local LLMs such as Gemma or Llama.
- Checking generated answers against source material.

RAG helps an AI system retrieve relevant information from a defined knowledge collection before generating a response. Generated answers should be checked against the retrieved sources.

### 7.2 Model versus agent

- **A model** performs a defined analytical or generative task.
- **An agent** selects tools, retrieves information and coordinates tasks to reach an objective.

### 7.3 Proposed agent workflow

```text
Farmer / User
      |
      v
Problem Understanding
      |
      v
Agent Manager
      |
      v
Specialised Agents
      |
      v
Solution Agent
      |
      v
Reviewer Agent
      |
      v
Human Review
      |
      v
Final Response
```

Not every request needs every agent. The Agent Manager selects the capabilities relevant to the request.

---

## 8. How the Training Works

The programme follows **Problem-Based Learning (PBL)** and the principle **Experience First, Theory Second**.

### Five-step learning cycle

1. **Experience** — Encounter a realistic scenario.
2. **Observe** — Identify the challenge and information gaps.
3. **Discover** — Learn the concepts, methods and tools needed.
4. **Practice** — Practise skills using examples and tools.
5. **Apply** — Use the skills in the group project.

### Time allocation

| Learning mode | Hours | Purpose |
|---|---:|---|
| Self-study | 40 | Guided learning, exploration, practice and project work |
| Workshops | 20 | Trainer-supported discussion, practical exercises and integration |
| **Total** | **60** | |

---

## 9. Ten Agricultural Intelligence Themes

Each group of four investigates one proposed theme. The themes are to be validated by each group.

| Group | Theme | Focus |
|---:|---|---|
| 01 | Crop Pest Intelligence | Pest identification, monitoring and damage assessment |
| 02 | Crop Disease Intelligence | Symptoms, severity and management knowledge |
| 03 | Smart Irrigation Intelligence | Soil moisture, rainfall, water needs and scheduling |
| 04 | Soil and Nutrient Intelligence | Soil properties, fertiliser and soil health |
| 05 | Agricultural Market Intelligence | Price monitoring, supply and demand, and selling |
| 06 | Dairy Production Intelligence | Milk yield, feeding, animal health and lactation |
| 07 | Livestock Health Intelligence | Identification, health records and veterinary advice |
| 08 | Agricultural Extension Intelligence | Farmer enquiries, expert referral and advisory support |
| 09 | Agricultural Supply Chain Intelligence | Harvest, grading, storage and logistics |
| 10 | Smart Greenhouse Intelligence | Temperature, humidity, ventilation and control |

---

## 10. The Nine Training Modules

The programme consists of nine modules with a total duration of 60 hours.

| Module | Duration | Topic |
|---|---:|---|
| M1 | 10 hours | Agricultural Understanding and Data Preparation |
| M2 | 6 hours | U0 — Agricultural Problem Formulation |
| M3 | 3 hours | Development Infrastructure and GitHub |
| M4 | 7 hours | U1 — Descriptive Analytics |
| M5 | 7 hours | U2 — Diagnostic Analytics |
| M6 | 6 hours | U3 — Predictive Analytics |
| M7 | 8 hours | RAG, Local LLM and Agent Basics |
| M8 | 7 hours | Multi-Agent Integration and U4 — Decision and Action |
| M9 | 6 hours | Capstone and Evaluation |
| **Total** | **60 hours** | |

---

## 11. The Final Project

The final outcome is **one integrated Agricultural Agentic AI prototype—not ten unrelated chatbots**.

### 11.1 What the integrated system brings together

- Shared Agricultural Data Foundation.
- Common geographical and environmental resources.
- Agricultural knowledge resources.
- Ten specialised intelligence components.
- Common interfaces and reusable tools.
- Agent Manager.
- Reviewer and human-validation workflow.
- A demonstrable and evaluated prototype.

### 11.2 How a request flows through the system

1. A user presents a question or need.
2. The Problem Understanding Agent interprets it.
3. The Agent Manager selects relevant capabilities.
4. Specialised agents use data, tools and knowledge.
5. The Solution Agent prepares a response.
6. The Reviewer Agent checks the response; human review is included when required.
7. The system provides a final response with evidence and limitations.

---

## 12. Deliverables and Assessment

Assessment measures understanding of agricultural workflows, not coding alone.

### Key deliverables

- System Understanding Document.
- Workflow Diagram.
- Stakeholder Map.
- Data Source Register.
- Data Inventory and Quality Notes.
- U0 Problem Formulation.
- Evidence and Uncertainty Register.
- Problem Bank entry.
- U1–U3 analytical reports.
- Knowledge Source Register and RAG Prototype.
- Agent Specifications and Architecture.
- U4 Decision Document.
- Integration Tests.
- Final Demonstration.
- Evaluation Report.
- Contribution Record.

---

## 13. Remember the Central Idea

This training is not about building a chatbot first and then looking for a problem.

It is about understanding a real problem first, identifying the evidence required, and then building the appropriate intelligence.

1. Understand the system.
2. Formulate the problem.
3. Work with evidence.
4. Build intelligence.
5. Coordinate agents.
6. Validate the result.

**Experience First. Theory Second. Application Throughout.**

---

*Source: Orientation_NAAMII.pptx — AI Foundation Training, Agritech Track.*
