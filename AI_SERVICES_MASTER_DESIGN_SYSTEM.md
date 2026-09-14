# WEBCONVOY AI SERVICES: MASTER DESIGN SYSTEM & 6-PAGE GENERATION PROMPTS

---

## 0. MASTER DESIGN SYSTEM FOR ALL 6 AI SERVICE PAGES

### 0.1 Core Philosophy: WebConvoy Natural Extension (Zero AI-Slop)
The AI service pages must feel like an organic, high-end extension of WebConvoy’s core website—**not** a separate sci-fi “AI-themed” landing page. 

**Strict Visual Guardrails**:
- ❌ **ABSOLUTELY NO**: Giant glowing brains, humanoid robots, floating holographic dashboards, cyberpunk neural-network grids, or 3D AI robot faces.
- ✔️ **STRICTLY USE**: Real software interfaces, clean technical architectures, system workflow diagrams, editorial typography, and enterprise business process maps.

### 0.2 Global Color Architecture
We adhere to the strict **70% Dark / 20% White / 10% Blue** ratio:

| Role | Hex Code | Purpose & Context |
| :--- | :--- | :--- |
| **Primary Background** | `#050607` | Deep near-black, foundational canvas (70% dominance) |
| **Secondary Dark Surface** | `#0A0D12` | Elevated section background, alternate dark bands |
| **Card Surface** | `#0D1118` | Interactive cards, bento blocks, technical panels |
| **Dark Borders** | `#202630` | 1px subtle crisp borders on cards and dividers |
| **Primary Blue** | `#126BFF` | Core accent (10% limit): primary CTAs, active states, key nodes |
| **Electric Blue** | `#2D8CFF` | Hover states, pill badges, subtle active borders |
| **Blue Glow** | `rgba(18, 107, 255, 0.22)` | Restrained ambient backlighting, glowing buttons |
| **Primary Dark Text** | `#F5F7FA` | Off-white high-contrast text on dark surfaces |
| **Secondary Dark Text** | `#9BA4B2` | Muted descriptions, metadata, technical labels |
| **Crisp White Section BG** | `#F7F8FA` | Editorial contrast sections (20% visual balance) |
| **Dark Text on White** | `#101318` | Confident typography on white background sections |
| **White Section Borders** | `#E2E8F0` | Light hairline borders on white cards |

> **Accent Rule**: Blue is an accent, **not** the entire page canvas. Never bathe entire sections in blue gradients.

### 0.3 Typography System
- **Headings (H1, H2, H3)**: `Geist`, `Inter Tight`, or `Montserrat` (tight letter-spacing `-0.02em` to `-0.03em`, confident, modern grotesk).
- **Body & Subtitles**: `Inter` (15px–17px, line-height 1.65, comfortable reading).
- **Technical Badges & Eyebrows**: `JetBrains Mono` or `Inter` (11px–12px, Uppercase, letter-spacing `+0.12em` to `+0.18em`, e.g., `AI CONSULTING / 01`).

### 0.4 Card & Component Geometry
- **Border Radius**: `12px` to `18px` maximum (no bubbly rounded corners).
- **Borders**: 1px solid `#202630` (dark) or `#E2E8F0` (light).
- **Shadows**: Restrained, deep inset or soft ambient drop shadows (`0 12px 32px rgba(0,0,0,0.4)`).
- **Glassmorphism**: Minimal and restrained (only applied to the sticky navigation bar and subtle status badges).

### 0.5 Navigation & Header Standard (Locked & Invariant)
Every AI page inherits the exact WebConvoy global navbar:
- **Left**: `NEW LOGO- wc.png` (WebConvoy official brand logo).
- **Center Nav**: Services, Industries, Portfolio, Insights.
- **Right Action Group**:
  - Pulsing AI Pill Button (`AI ✦` with restrained electric blue aura).
  - Primary Contact CTA (`☎ Contact Us` / `Book a Discovery Call`).
- **Styling**: Sticky header, `#08090C` with 85% alpha backdrop-blur (20px), 1px `#202630` border.

### 0.6 Dominant Visual Idea Matrix

| Page | Service Name | Dominant Visual Idea (No Slop) |
| :---: | :--- | :--- |
| **01** | **AI Consulting** | **Strategic Planning Workspace**: Business process mapping, friction-to-value nodes, ROI matrix, and readiness scoreboards. |
| **02** | **AI Development** | **Real Product UI & Layered Architecture**: Live SaaS cockpit, RAG pipeline, model layer, and PoC-to-Production timeline. |
| **03** | **AI Automation** | **Workflow & Operations Pipeline**: Trigger-to-action routing, Before/After split operational diagrams, and Document Intelligence UI. |
| **04** | **AI Agent Development** | **Autonomous Agent Orchestration**: Central supervisor agent directing tools (Browser, CRM, API, SQL) + Perceive-Reason-Plan-Act engine. |
| **05** | **AI Compiler Engineering** | **Systems & Inference Architecture**: Graph lowering, quantization, Triton/TensorRT execution engine, hardware dispatch to GPU/NPU. |
| **06** | **AI Integration** | **Enterprise Connected Ecosystem**: Central AI layer unifying legacy databases, CRM, ERP, and event buses into real-time business apps. |

---

## 1. MASTER PROMPT PREFIX
> **Instructions**: Prepend this master prefix to **every single generation prompt** (Midjourney v6, Flux.1 Pro, DALL-E 3, or front-end LLM generators) to enforce WebConvoy's brand consistency:

```text
[MASTER SYSTEM PREFIX - WEBCONVOY 2026]:
Create a premium 2026 WebConvoy website page, not an AI-generated concept-art website. Follow the existing WebConvoy brand: near-black #050607, off-white #F7F8FA, primary blue #126BFF, electric blue #2D8CFF, subtle dark borders #202630, white #F5F7FA typography, restrained blue glow. Use a sophisticated editorial SaaS/technology-agency layout with strong typography, precise 12-column grid, generous negative space, thin borders, asymmetric compositions, real product interfaces, technical diagrams, photography used sparingly, and carefully art-directed UI. Avoid humanoid robots, giant brains, glowing neural networks, holographic floating cards, excessive glassmorphism, generic 3D AI objects, excessive gradients, cyberpunk aesthetics, cliché futuristic imagery, and random decorative elements. Every visual must communicate the actual service being offered. The result should look like a real high-end WebConvoy website designed by a senior product designer, not an AI-generated landing-page template.
```

---

## 2. DETAILED SPECIFICATION & GENERATION PROMPTS FOR THE 6 PAGES

---

### PAGE 01 — AI CONSULTING (`ai-consulting.html`)

#### Core Positioning
*"Turn AI possibilities into a clear plan. Know where AI fits. Know what to build."*  
Answers the foundational enterprise question: *Where should AI actually be deployed for maximum economic impact, and what should never be automated?*

#### Detailed Section Breakdown
1. **01 — Hero (Dark `#050607` - 50/50 Split)**:
   - *Left*: Eyebrow badge `AI CONSULTING / 01`. Headline: *"Know where AI fits. Know what to build."* Body: *"We help businesses identify high-value AI opportunities, define the right architecture, and build a practical roadmap from PoC experimentation to mission-critical production."* CTAs: `Talk to an AI Strategist →` (Primary Blue) + `Explore Our Framework` (Ghost Border).
   - *Right Visual*: Strategic AI planning workspace UI. Real dark canvas showing business capability mapping, friction nodes, model cost-benefit projections, and milestone roadmap timelines.
2. **02 — The AI Decision Problem (White `#F7F8FA`)**:
   - Headline: *"AI isn't the problem. Knowing where to start is."*
   - 4 friction columns:
     - 1. *Too Many Possibilities* (Paralysis by infinite AI hype).
     - 2. *Unclear ROI* (High model tokens with unmeasured value).
     - 3. *Disconnected Data* (Fragmented enterprise silos).
     - 4. *No Production Roadmap* (Stuck in perpetual lab prototypes).
   - Connecting thin blue spine leading to: *"A focused, mathematically grounded AI strategy."*
3. **03 — AI Opportunity Discovery (Dark `#050607`)**:
   - Left: `01 / DISCOVER` — *"Find the work worth automating."*
   - Right: Clean vertical strategy board: `BUSINESS PROCESS ↓ FRICTION POINT ↓ AI CAPABILITY MATCH ↓ TANGIBLE ROI`.
4. **04 — Our Consulting Framework (Dark `#0A0D12`)**:
   - 5 Interactive horizontal expanding cards: `01. Discover` → `02. Prioritize` → `03. Architect` → `04. Validate` → `05. Roadmap`.
5. **05 — AI Readiness Score (White `#F7F8FA`)**:
   - Diagnostic enterprise readiness interface. 6 audit dimensions with numeric radar scores:
     - `DATA READINESS` (Cleanliness, governance, vectorization suitability).
     - `PEOPLE & ADOPTION` (Internal skillset, workflow friction).
     - `INFRASTRUCTURE` (GPU availability, VPC compliance).
     - `USE CASES` (High-impact vs vanity experiments).
     - `SECURITY & PRIVACY` (PII protection, SOC2/HIPAA compliance).
     - `OPERATIONS` (Observability, evaluation loops).
6. **06 — What We Help You Decide (Dark `#050607`)**:
   - 6 Editorial rows with micro-metrics:
     - *Should we build custom or buy SaaS?*
     - *Which models (Open-source Llama/Mistral vs Closed GPT/Claude) fit our margin?*
     - *What data infrastructure must precede modeling?*
     - *Where can autonomous agents safely operate?*
     - *What deterministic workflows should never use probabilistic LLMs?*
     - *How do we reach enterprise SLA production?*
7. **07 — Final CTA & Scoping Form (Dark Navy `#050607`)**:
   - *"Don't start with AI. Start with the right problem."*
   - Scoping form with math captcha (`2 * 12 = 24`) and direct strategist booking.

#### Complete Generation Prompt (Image & UI Mockup)
```text
[MASTER SYSTEM PREFIX - WEBCONVOY 2026]
PAGE FOCUS: AI CONSULTING & STRATEGY.
Create a complete high-fidelity desktop web page design for WebConvoy's AI Consulting service. The aesthetic is clean, technical, and executive-level editorial. 

HERO SECTION (50/50 Layout):
- Left column: Dark #050607 background with crisp #F5F7FA typography. Monospace small tag "AI CONSULTING / 01" with a subtle electric blue bullet. Large confident headline: "Know where AI fits. Know what to build." Restrained secondary subtext in #9BA4B2 explaining enterprise roadmap and feasibility analysis. Solid primary blue #126BFF button "Talk to an AI Strategist →" and ghost border button "Explore Our Framework".
- Right column: High-resolution dark enterprise strategy dashboard UI mockup. Showing a node-based opportunity mapping canvas with real business workflow blocks ("Customer Onboarding", "Risk Underwriting", "Claims Processing"), friction severity heatmaps, ROI feasibility indicators (e.g. "64% cycle time reduction"), and a phased implementation Gantt roadmap. NO floating holographic brain or blue cyberspace grids. Crisp 1px #202630 borders, clean data tables, and subtle blue active highlights.

SECTION 2 - THE DECISION PROBLEM (Contrast Crisp White #F7F8FA):
- Minimalist editorial layout with dark #101318 heading: "AI isn't the problem. Knowing where to start is." Four distinct cards with subtle gray borders representing enterprise roadblocks: Too Many Possibilities, Unclear ROI, Disconnected Data, and No Production Roadmap. Below them, a thin electric blue pathway connects the cards to a summary badge: "A Focused AI Strategy".

SECTION 3 & 4 - DISCOVERY & 5-STAGE FRAMEWORK (Dark #050607):
- Editorial 2-column discovery diagram showing Business Process to Value conversion.
- Horizontal card slider for the 5-phase consulting methodology: Discover, Prioritize, Architect, Validate, Roadmap with hover elevation and technical deliverables listed.

SECTION 5 - AI READINESS DIAGNOSTIC (Crisp White #F7F8FA):
- Professional enterprise assessment interface showing 6 evaluation gauges: Data, People, Infrastructure, Use Cases, Security, and Operations, with clean percentage scores and benchmark metrics.

SECTION 6 & 7 - STRATEGIC DECISION MATRIX & DARK CTA:
- 6 clean editorial accordion rows answering Build vs Buy, Model Selection, and SLA guarantees.
- Final conversion banner on dark #050607 with headline "Don't start with AI. Start with the right problem." and high-conversion scoping consultation form.
```

---

### PAGE 02 — AI DEVELOPMENT (`ai-development.html`)

#### Core Positioning
*"From AI idea to production-ready product."*  
WebConvoy’s core software engineering page: Full-stack LLM engineering, fine-tuning, RAG pipelines, and enterprise-grade AI software development.

#### Detailed Section Breakdown
1. **01 — Hero (Dark `#050607` - Product Interface Visual Anchor)**:
   - *Headline*: *"From AI idea to production-ready product."*
   - *Subtext*: *"We design, engineer, and scale custom AI applications, custom-tuned models, and robust RAG architectures that run seamlessly inside your enterprise ecosystem."*
   - *Hero Visual*: Real split-view AI product cockpit. Left pane: live SaaS customer portal with structured generative output, citations, and confidence badges. Right pane: the underlying live technical architecture layers (`Application Layer → Model Router → RAG Vector Engine → Cache & DB → REST/GraphQL API`).
2. **02 — What We Build (Dark `#0A0D12`)**:
   - 4-Column bento grid with technical telemetry:
     - 1. *Generative AI & Copilots* (Domain-specific drafting, coding, and workflow assistants).
     - 2. *LLM Applications* (Fine-tuned open-source & proprietary foundation model integrations).
     - 3. *Autonomous AI Applications* (Multi-step deterministic & probabilistic software).
     - 4. *AI-Powered SaaS Products* (End-to-end multi-tenant commercial platforms).
3. **03 — The AI Application Stack (White `#F7F8FA`)**:
   - Visual layered architecture diagram:
     - `ENTERPRISE PRODUCT & UI`
     - `↓ AI INTERFACE & PROMPT ORCHESTRATION (LangChain / LlamaIndex)`
     - `↓ MODEL ROUTING & GUARDRAILS (NeMo Guardrails, Semantic Cache)`
     - `↓ RAG KNOWLEDGE ENGINE (Milvus, Pinecone, Hybrid Search)`
     - `↓ DATA RETRIEVAL & VECTOR PIPELINE`
     - `↓ CLOUD & COMPUTE INFRASTRUCTURE (AWS, Azure, GCP, vLLM)`
4. **04 — Development Capabilities (Dark `#050607`)**:
   - Interactive technical matrix: Custom Model Fine-Tuning (LoRA/QLoRA), Retrieval-Augmented Generation (RAG), Conversational Voice/Chat AI, Multimodal Vision Systems, Predictive Intelligence Engines, and Real-Time Copilots.
5. **05 — Prototype → Production Lifecycle (Dark `#0A0D12`)**:
   - Phased pipeline: `01. Idea → 02. Feasibility PoC → 03. Core Build → 04. Eval & Red-Teaming → 05. Deploy → 06. Scale & Monitor`.
6. **06 — Real Products / Engineering Showcase (White `#F7F8FA`)**:
   - 3 Real case studies with architectural problem-solution-outcome metrics:
     - Case A: Enterprise Financial RAG System (99.2% accuracy, sub-800ms latency).
     - Case B: Autonomous Code Analysis Copilot (45% dev cycle acceleration).
     - Case C: Multi-Modal Medical Imaging Intake (HIPAA-compliant, 60% faster triage).
7. **07 — Engineering Stack & Model Partners (Dark `#050607`)**:
   - Logos & tool badges: PyTorch, HuggingFace, OpenAI, Anthropic Claude, Google Gemini, Meta Llama, vLLM, LangChain, PostgreSQL pgvector, Docker, Kubernetes.
8. **08 — Final CTA**: *"Let's build something intelligent."*

#### Complete Generation Prompt (Image & UI Mockup)
```text
[MASTER SYSTEM PREFIX - WEBCONVOY 2026]
PAGE FOCUS: AI SOFTWARE DEVELOPMENT & ENGINEERING.
Create a modern, ultra-clean editorial engineering web page for WebConvoy's AI Development service.

HERO SECTION (Engineering Product Focus):
- Dark #050607 background with electric blue accents #126BFF. Monospace label "AI DEVELOPMENT / 02".
- Headline: "From AI idea to production-ready product." Subtext focused on production SLAs, deterministic evaluation, and scalable architecture.
- Visual: An authentic, pixel-perfect split interface showing a modern AI product in production. The left half shows an intelligent SaaS dashboard with markdown streaming, document citations, latency indicators (412ms), and confidence scoring (99.4%). The right half shows an inspectable systems diagram with layered tiers: Product UI, Prompt Pipeline, Model Gateway, Vector Index, and GPU Inference Engine. Crisp 1px borders, subtle data meters, monospaced code snippets. ZERO robots, zero glowing crystal spheres, zero humanoid cyborgs.

SECTION 2 & 3 - WHAT WE BUILD & THE APPLICATION STACK:
- Dark #0A0D12 4-column bento grid detailing Generative AI, LLM Applications, Autonomous Workflows, and Custom AI SaaS.
- Crisp White #F7F8FA section featuring a clean, enterprise-grade diagram of the full AI application stack from frontend interface down to GPU compute cluster with subtle blue routing arrows.

SECTION 4 & 5 - CAPABILITIES & PRODUCTION LIFECYCLE (Dark #050607):
- Vertical interactive capabilities list with technical specs (LoRA fine-tuning, Hybrid RAG, Semantic Caching).
- Horizontal timeline illustrating the 6-stage transition from Idea to Scale with real engineering milestones (Eval metrics, Red-teaming, CI/CD pipeline).

SECTION 6 & 7 - CASE STUDIES & TECH STACK:
- White #F7F8FA section with 3 real software case study cards displaying architecture diagrams, Problem, Built Solution, and Verifiable Outcome metrics.
- Dark partner grid showcasing real engineering frameworks: PyTorch, OpenAI, Anthropic, Gemini, Llama 3, vLLM, Pinecone, AWS.
- Minimal dark CTA banner: "Let's build something intelligent." with project scoping form.
```

---

### PAGE 03 — AI AUTOMATION (`ai-automation.html`)

#### Core Positioning
*"Turn repetitive work into intelligent workflows."*  
Visual language: Operations, automation logic, data routing, trigger-action engines. No sci-fi faces.

#### Detailed Section Breakdown
1. **01 — Hero (Dark `#050607` - Business Operations Pipeline Visual)**:
   - *Headline*: *"Turn repetitive work into intelligent workflows."*
   - *Subtext*: *"Eliminate operational bottlenecks. We automate complex multi-step enterprise tasks by combining cognitive AI decisioning with existing software systems."*
   - *Hero Visual*: A clean, interactive enterprise workflow pipeline:
     `INCOMING EMAIL / TICKET → AI CLASSIFICATION → POLICY & RISK DECISION → BRANCHING ACTION [CRM Update / ERP Transaction / Escalate to Human]`.
2. **02 — The Work: Before vs After AI (White `#F7F8FA` - Split Screen)**:
   - *Before (Left - Red/Neutral Muted)*: Manual data entry, copy-pasting across tabs, slow email approvals, static spreadsheets, human fatigue errors.
   - *After (Right - WebConvoy Blue `#126BFF`)*: Instant detection, semantic understanding, policy-aware decisioning, automated execution, and real-time audit logging.
3. **03 — Automation Opportunities by Department (Dark `#0A0D12`)**:
   - 8 Interactive functional tabs with live workflow previews:
     - 1. *Finance & Accounting* (Invoice matching, reconciliation, fraud audit).
     - 2. *Customer Operations* (Tier-1 resolution, sentiment routing, automated refund processing).
     - 3. *Legal & Compliance* (Contract clause extraction, NDA triage, compliance gap detection).
     - 4. *Human Resources* (Resume parsing, candidate screening, employee onboarding flows).
     - 5. *Supply Chain & Logistics* (Bill of lading extraction, dispatch re-routing, supplier PO matching).
     - 6. *Sales Operations* (Inbound lead enrichment, CRM hygiene, meeting intelligence).
     - 7. *IT & Security* (Log anomaly remediation, password reset triage, access provisioning).
     - 8. *Data & Analytics* (Automated KPI report generation, trend anomaly alerts).
4. **04 — The Automation Engine (Dark `#050607`)**:
   - 6-Step architectural cycle: `TRIGGER → UNDERSTAND → DECIDE → EXECUTE → VERIFY → CONTINUOUS LEARN`.
5. **05 — Document Intelligence Suite (White `#F7F8FA`)**:
   - Realistic document extraction UI showing real business documents (Invoices, Master Services Agreements, Medical Claims) with AI bounding boxes extracting Key-Value pairs: `Vendor Name`, `Total Amount`, `Due Date`, `Tax ID`, and `Confidence: 99.8%`.
6. **06 — Human-in-the-Loop (HITL) Governance (Dark `#0A0D12`)**:
   - Crucial trust section showing AI handling high-volume 95% repetitive tasks, automatically flagging edge cases to human managers with explainable audit logs.
7. **07 — Quantified Automation Outcomes (Dark `#050607`)**:
   - 3 Enterprise transformation metrics:
     - *84% reduction in invoice processing cycle time.*
     - *99.1% extraction accuracy across unstructured PDFs.*
     - *$340,000 annual labor savings reallocated to strategic growth.*
8. **08 — Final CTA**: *"Give your team fewer things to do manually."*

#### Complete Generation Prompt (Image & UI Mockup)
```text
[MASTER SYSTEM PREFIX - WEBCONVOY 2026]
PAGE FOCUS: ENTERPRISE AI AUTOMATION & INTELLIGENT WORKFLOWS.
Design a sleek, modern, operations-focused website page for WebConvoy's AI Automation service.

HERO SECTION (Workflow & Operations Visual):
- Dark #050607 background with crisp white typography and electric blue accents. Monospace badge "AI AUTOMATION / 03".
- Headline: "Turn repetitive work into intelligent workflows." Subtext about enterprise operational efficiency.
- Hero Visual: A clean, technical workflow automation canvas. Shows an enterprise trigger node ("Inbound Customer Claim") feeding into an "AI Semantic Classification" node, routing through a "Policy Decision Matrix", and branching into three live endpoints: "SAP ERP Ledger Entry", "Salesforce CRM Update", and "Exception Flagged to Manager". The design resembles modern workflow tools (like Zapier, Temporal, or Retool) reimagined with an ultra-premium dark editorial aesthetic. Sharp borders, subtle green status dots, and crisp directional connecting paths.

SECTION 2 - BEFORE VS AFTER (Crisp White #F7F8FA):
- High-contrast split-screen section. Left column "Before AI" shows painful manual processes (tedious spreadsheet entries, email chains, delay badges). Right column "After AI" shows streamlined automated execution (instant triage, sub-second API sync, verified audit trails) with clean blue accents.

SECTION 3 & 4 - DEPARTMENTAL AUTOMATION & ENGINE ARCHITECTURE (Dark #0A0D12 & #050607):
- Departmental matrix for Finance, Customer Ops, Legal, Supply Chain, and HR.
- Technical diagram of the 6-stage execution engine: Trigger, Understand, Decide, Execute, Verify, Learn.

SECTION 5 - DOCUMENT INTELLIGENCE SHOWCASE (Crisp White #F7F8FA):
- Realistic UI showing automated extraction on commercial invoices and legal agreements. Highlights parsed bounding boxes, clean JSON schema output, and extraction confidence indicators (99.8%).

SECTION 6 & 7 - HUMAN-IN-THE-LOOP & ROI IMPACT:
- Serious governance diagram illustrating Human-in-the-loop oversight for high-risk decisions.
- 3 Large quantified outcome metric cards. Dark CTA banner: "Give your team fewer things to do manually."
```

---

### PAGE 04 — AI AGENT DEVELOPMENT (`ai-agents.html`)

#### Core Positioning
*"Build AI that doesn't just answer. It acts."*  
Visual language: Agent orchestration, tool use, perceive-reason-plan-act loop, multi-agent coordination. No humanoid robots.

#### Detailed Section Breakdown
1. **01 — Hero (Dark `#050607` - Agent Orchestrator Visual Anchor)**:
   - *Headline*: *"Build AI that doesn't just answer."* Second line in Electric Blue `#2D8CFF`: *"It acts."*
   - *Subtext*: *"Move beyond passive conversational chatbots. We build autonomous, tool-using AI agents that research, plan, execute multi-step workflows, and interact directly with your software tools."*
   - *Hero Visual*: Center node `AUTONOMOUS AGENT CORE` connected through live API telemetry lines to 7 external capabilities: `[Web Browser Engine]`, `[Enterprise CRM]`, `[PostgreSQL DB]`, `[Email & Slack]`, `[REST APIs]`, `[Vector Memory]`, and `[Human Supervisor]`.
2. **02 — What Makes an Agent? (White `#F7F8FA`)**:
   - The 4 Cognitive Pillars (clean circular system):
     - 1. *PERCEIVE*: Ingest unstructured text, UI clicks, API events, and multimodal data.
     - 2. *REASON*: Break down broad business goals into sequenced sub-tasks using ReAct / Tree-of-Thought prompting.
     - 3. *PLAN*: Dynamically adjust execution paths based on environmental errors and validation feedback.
     - 4. *ACT*: Execute tool calls, trigger database writes, run code, and communicate across external systems.
3. **03 — Autonomous Agent Types (Dark `#0A0D12`)**:
   - 6 Interactive agent profile cards with real capability workflows:
     - 1. *Research & Intelligence Agent* (Gathers web sources, verifies facts, compiles reports).
     - 2. *Sales & SDR Agent* (Prospect research, personalized email drafting, CRM syncing).
     - 3. *Support Resolution Agent* (Runs diagnostic scripts, resolves tickets, issues refunds).
     - 4. *Operations & Logistics Agent* (Monitors inventory, adjusts re-order points, coordinates vendors).
     - 5. *Data Analysis Agent* (Writes and executes SQL queries, visualizes charts, surfaces insights).
     - 6. *Browser Automation Agent* (Navigates web apps, logs into legacy portals, fills complex forms).
4. **04 — Single Agent → Multi-Agent Orchestration (Dark `#050607`)**:
   - Clean hierarchical tree diagram:
     ```text
                       SUPERVISOR AGENT
                     /        |        \
            RESEARCH AGENT  CODER AGENT  QA & AUDIT AGENT
                  |           |              |
              Web Data    Repository     Test Suite
     ```
5. **05 — How Agents Work: The Execution Loop (White `#F7F8FA`)**:
   - Horizontal linear lifecycle: `Goal Ingestion → Decomposition → Tool Selection → Sandboxed Execution → Self-Correction & Verification → Final Output`.
6. **06 — Agentic Memory & State Management (Dark `#0A0D12`)**:
   - Technical architecture showing:
     - *Short-Term Memory*: In-context conversation state & scratchpad.
     - *Long-Term Memory*: Vector database retrieval of past experiences & user preferences.
     - *Episodic Memory*: Historical tool execution logs and error recovery patterns.
7. **07 — Enterprise Safety, Guardrails & Human Control (White `#F7F8FA`)**:
   - Serious enterprise compliance section: Granular API permissions, budget token caps, deterministic guardrails, human approval for financial transactions, and immutable audit logs.
8. **08 — Final CTA**: *"Give your software the ability to act."*

#### Complete Generation Prompt (Image & UI Mockup)
```text
[MASTER SYSTEM PREFIX - WEBCONVOY 2026]
PAGE FOCUS: AUTONOMOUS AI AGENT DEVELOPMENT & MULTI-AGENT SYSTEMS.
Design a cutting-edge, technical desktop page for WebConvoy's AI Agent Development service.

HERO SECTION (Agent Orchestration Visual):
- Dark #050607 canvas with high-contrast typography. Monospace eyebrow "AI AGENT DEVELOPMENT / 04".
- Dramatic headline: "Build AI that doesn't just answer." with second line highlighted in electric blue #2D8CFF: "It acts."
- Hero Visual: A centralized AI Agent Orchestration diagram. At the center is a sleek dark processing node "Autonomous Agent Core" with a live status indicator. Surrounding it are 6 interconnected capability modules rendered as clean dark cards with 1px #202630 borders: "Headless Browser Automation", "Internal Database (SQL)", "Enterprise CRM (Salesforce)", "Email & Messaging API", "Vector Memory Engine", and "Human Supervisor Loop". Fine electric blue data transmission lines link the core to each tool with live latency tags (e.g., "GET /api/v2 200 OK"). NO 3D robot faces, cyborg hands, or glowing blue brains.

SECTION 2 - WHAT MAKES AN AGENT? (Crisp White #F7F8FA):
- Minimalist circular cognitive cycle diagram featuring four core stages: Perceive, Reason, Plan, and Act, with clear architectural annotations.

SECTION 3 & 4 - AGENT ROLES & MULTI-AGENT ORCHESTRATION (Dark #0A0D12 & #050607):
- 6 Grid cards for specialized enterprise agents: Research, Sales SDR, Customer Support, Operations, Data Analysis, and Browser Automation.
- Multi-agent hierarchical flowchart showing a "Supervisor Agent" delegating tasks to sub-agents (Research, Code, QA) with feedback loops.

SECTION 5 & 6 - EXECUTION PIPELINE & MEMORY ARCHITECTURE:
- Crisp white section showing the ReAct self-correction loop.
- Dark technical diagram breaking down Short-Term Context, Long-Term Vector Memory, and Tool Execution State.

SECTION 7 & 8 - ENTERPRISE SAFETY & CTA (Crisp White #F7F8FA & Dark #050607):
- Enterprise security layout emphasizing Permission Boundaries, Human Approval Gates, and Cryptographic Audit Logs.
- Dark CTA banner: "Give your software the ability to act."
```

---

### PAGE 05 — AI COMPILER ENGINEERING (`ai-compiler.html`)

#### Core Positioning
*"Make AI models run smarter, faster. Hardware-aware inference optimization."*  
Visual language: Systems engineering, compiler passes, memory hierarchy, GPU/NPU kernels, latency reduction. Deeply technical, no consumer AI clichés.

#### Detailed Section Breakdown
1. **01 — Hero (Dark `#050607` - Technical Systems Architecture)**:
   - *Eyebrow*: `AI COMPILER ENGINEERING / 05`.
   - *Headline*: *"Make AI models run smarter, faster."*
   - *Subtext*: *"Bridge the gap between deep learning frameworks and high-performance silicon. We optimize, quantize, and compile neural models for peak throughput, lowest latency, and minimal compute cost."*
   - *Hero Visual*: Deep technical compiler architecture pipeline:
     `PYTORCH / ONNX MODEL → INTERMEDIATE REPRESENTATION (IR) GRAPH → GRAPH REWRITING & FUSION → HARDWARE CODEGEN → LOW-LEVEL KERNELS (CUDA/Triton) → ACCELERATED SILICON [NVIDIA H100 / Apple M-Series / Qualcomm NPU]`.
2. **02 — The Inference Bottleneck (White `#F7F8FA`)**:
   - 3 Quantified bottleneck challenges and how compiler engineering solves them:
     - 1. *Latency Spikes* (Eliminate kernel launch overhead through operator fusion).
     - 2. *Memory Bandwidth Saturation* (Overcome KV-cache bottlenecks via FlashAttention and paging).
     - 3. *Unsustainable Cloud Compute Costs* (4x higher throughput per GPU instance with FP8/INT4 quantization).
3. **03 — The Model Compilation Pipeline (Dark `#0A0D12`)**:
   - 6-Stage horizontal systems pipeline:
     `01. Model Input → 02. Graph Lowering → 03. Target-Independent Optimization → 04. Custom Kernel Gen → 05. Target Runtime Execution → 06. Hardware Acceleration`.
4. **04 — Core Optimization Techniques (Dark `#050607`)**:
   - 6 Deep engineering cards:
     - *Graph Optimization & Fusion* (Fusing Conv+BatchNorm+ReLU into single kernel passes).
     - *Precision Quantization* (AWQ, GPTQ, SmoothQuant to 8-bit and 4-bit with zero accuracy drop).
     - *Custom Kernel Engineering* (Hand-crafted CUDA & OpenAI Triton kernels for custom attention).
     - *Memory & Cache Optimization* (PagedAttention, chunked prefill, weight streaming).
     - *Continuous Batching & Speculative Decoding* (vLLM and TensorRT-LLM throughput multipliers).
     - *Heterogeneous Hardware Targeting* (Deploying to GPU, CPU, Apple Silicon, and Edge NPUs).
5. **05 — Model → Heterogeneous Hardware Dispatch (White `#F7F8FA`)**:
   - Clean architectural diagram showing one trained foundation model branching through an optimization compiler layer into diverse targets: Data Center GPUs (NVIDIA H100/A100), Edge Silicon (Jetson), Consumer Chips (Apple M4), and Mobile NPUs (Snapdragon NPU).
6. **06 — Quantified Performance Benchmark Placeholders (Dark `#050607`)**:
   - Clean dark benchmark visual comparing standard PyTorch eager mode vs WebConvoy compiled runtime:
     - *Latency*: `↓ 68% Lower TTFT (Time to First Token)`.
     - *Throughput*: `↑ 3.8x Higher Tokens/Second/GPU`.
     - *Memory Footprint*: `↓ 55% Reduced VRAM Usage`.
     - *Compute Infrastructure Cost*: `↓ 60% Reduced Monthly Cloud Spend`.
7. **07 — Low-Level Engineering Stack (Dark `#0A0D12`)**:
   - Technologies: NVIDIA TensorRT, CUDA, Triton, PyTorch 2.0 TorchDynamo, TVM, MLIR, ONNX Runtime, OpenXLA, vLLM, DeepSpeed.
8. **08 — Final CTA**: *"Your model is only as fast as the system running it."*

#### Complete Generation Prompt (Image & UI Mockup)
```text
[MASTER SYSTEM PREFIX - WEBCONVOY 2026]
PAGE FOCUS: AI COMPILER ENGINEERING, INFERENCE OPTIMIZATION & SYSTEMS INFRASTRUCTURE.
Create a deeply technical, systems-engineering web page design for WebConvoy's AI Compiler Engineering service.

HERO SECTION (Systems Architecture Visual):
- Dark #050607 background with subtle technical grid lines. Monospace label "AI COMPILER ENGINEERING / 05".
- Bold, technical headline: "Make AI models run smarter, faster." Subtext regarding lower-level kernel compilation and reduced GPU inference cost.
- Hero Visual: A low-level technical compiler systems diagram. Displays the transformation of a neural network: starting from an unoptimized computational graph (PyTorch/ONNX), passing through Graph Lowering, Node Fusion (fusing Attention, LayerNorm, and MatMul), down into custom OpenAI Triton / CUDA kernels, and deploying onto labeled silicon targets (NVIDIA H100, AMD MI300, Apple Silicon). Features monospaced IR code snippets, memory layout diagrams, and clean vector arrows. NO consumer AI slop, no glowing heads, no cyberpunk cityscapes.

SECTION 2 - THE INFERENCE BOTTLENECK (Crisp White #F7F8FA):
- High-contrast white editorial section detailing the three critical barriers to enterprise scale: Memory Bandwidth Saturation, TTFT Latency Spikes, and Exponential GPU Cloud Costs, accompanied by technical resolution metrics.

SECTION 3 & 4 - COMPILATION PIPELINE & OPTIMIZATION TECHNIQUES (Dark #0A0D12 & #050607):
- Horizontal 6-stage compiler pipeline from Graph Ingestion to Silicon Execution.
- 6 Deep technical capability cards: Graph Rewriting, AWQ/GPTQ Quantization, Custom Triton Kernels, PagedAttention Memory, Speculative Decoding, and Hardware Target Specialization.

SECTION 5 & 6 - HETEROGENEOUS DISPATCH & BENCHMARK METRICS:
- Clean white architectural diagram illustrating single-model multi-silicon deployment (Cloud GPU, Edge, NPU).
- Dark benchmark dashboard with comparison bar charts showing 3.8x Throughput Gains and 68% Latency Reductions against baseline PyTorch.
- Dark partner grid: CUDA, TensorRT, Triton, MLIR, TVM, vLLM, ONNX.
- Minimal technical CTA banner: "Your model is only as fast as the system running it."
```

---

### PAGE 06 — AI INTEGRATION (`ai-integration.html`)

#### Core Positioning
*"Put intelligence into the systems you already use."*  
Visual language: Connected enterprise ecosystem, middleware, APIs, data buses, ERP/CRM orchestration.

#### Detailed Section Breakdown
1. **01 — Hero (Dark `#050607` - Enterprise Architecture Visual)**:
   - *Eyebrow*: `AI INTEGRATION / 06`.
   - *Headline*: *"Put intelligence into the systems you already use."*
   - *Subtext*: *"You don't need to rebuild your enterprise software stack to benefit from AI. We engineer secure, real-time integration layers that connect modern AI models directly into your existing CRMs, ERPs, databases, and internal platforms."*
   - *Hero Visual*: Real enterprise architecture schematic:
     ```text
                                CENTRAL AI ORCHESTRATION LAYER
                                  /            |            \
                           API GATEWAYS    EVENT BUSES    DATA CONNECTORS
                              /                |                \
                     SALESFORCE CRM      SAP / NETSUITE ERP    SNOWFLAKE / POSTGRES
                            ↓                  ↓                      ↓
                     Sales Copilot      Automated Ledger       Predictive Forecasts
     ```
2. **02 — AI Doesn't Have to Replace Your Stack (White `#F7F8FA`)**:
   - Headline: *"Your existing software already works. We make it smarter."*
   - Architecture contrast showing existing enterprise software (Salesforce, SAP, Zendesk, Oracle, Snowflake) gaining cognitive superpowers via non-disruptive API middleware.
3. **03 — What We Connect (Dark `#0A0D12`)**:
   - 6 Enterprise integration cards:
     - 1. *AI + CRM Integration* (Salesforce, HubSpot, Microsoft Dynamics).
     - 2. *AI + ERP Systems* (SAP, NetSuite, Oracle, Workday).
     - 3. *AI + Modern SaaS* (Slack, Notion, Jira, Zendesk, Google Workspace).
     - 4. *AI + Core Databases & Warehouses* (Snowflake, BigQuery, Databricks, PostgreSQL).
     - 5. *AI + Custom APIs & Microservices* (REST, GraphQL, gRPC, Webhooks).
     - 6. *AI + Legacy On-Premises Systems* (Mainframe DBs, AS400, proprietary legacy ERPs).
4. **04 — Integration Architecture Blueprint (Dark `#050607`)**:
   - High-fidelity architecture visual showing the 3-tier integration topology:
     - *Client & Experience Tier*: Existing software UI.
     - *AI Middleware Tier*: Authentication, Rate Limiting, Semantic Router, Context Injection, Audit Logger.
     - *Model & Storage Tier*: Foundation LLMs, Vector Databases, Data Warehouses.
5. **05 — Legacy → AI Bridge (White `#F7F8FA`)**:
   - Detailed visual flow showing how slow, brittle legacy enterprise platforms are modernized without risky rewrites:
     `Legacy Database → CDC (Change Data Capture) → Vector Transformation → AI Semantic Layer → Modern Intelligent API`.
6. **06 — Security, Governance & Isolation (Dark `#0A0D12`)**:
   - Enterprise security pillars: Zero-retention data policies, role-based access control (RBAC), end-to-end encryption, VPC deployment, SOC2 Type II and HIPAA compliance.
7. **07 — Integration Delivery Timeline (Dark `#050607`)**:
   - 4-Week rapid integration model:
     - *Week 1: Architecture & Data Audit*.
     - *Week 2: Connector Build & Semantic Mapping*.
     - *Week 3: Model Pipeline & Validation*.
     - *Week 4: Staging Deployment & Employee Training*.
8. **08 — Final CTA**: *"Your systems already have the data. Let's give them intelligence."*

#### Complete Generation Prompt (Image & UI Mockup)
```text
[MASTER SYSTEM PREFIX - WEBCONVOY 2026]
PAGE FOCUS: ENTERPRISE AI INTEGRATION, CONNECTED ECOSYSTEMS & API ARCHITECTURE.
Design a sophisticated enterprise technology page for WebConvoy's AI Integration service.

HERO SECTION (Connected Ecosystem Architecture):
- Dark #050607 background with crisp #F5F7FA typography and #126BFF electric blue accents. Monospace label "AI INTEGRATION / 06".
- Headline: "Put intelligence into the systems you already use." Subtext explaining non-disruptive AI layer implementation across existing enterprise applications.
- Hero Visual: A clean, high-end enterprise architecture diagram. Displays an overarching "WebConvoy AI Orchestration Layer" bridging seamlessly into existing corporate systems: Salesforce CRM, SAP ERP, Snowflake Data Warehouse, and Zendesk Support. Shows bidirectional data streams with status pills ("Real-time Sync", "Encrypted TLS 1.3", "Zero Model Retention"). Styled like a technical whitepaper diagram with 1px dark borders, subtle glowing interconnection nodes, and modern vector iconography. NO robotic arms, floating neon wireframes, or humanoid avatars.

SECTION 2 - STACK COEXISTENCE (Crisp White #F7F8FA):
- Editorial layout with bold header: "Your existing software already works. We make it smarter." Illustrates standard corporate software receiving an intelligent enhancement layer without requiring rip-and-replace overhauls.

SECTION 3 & 4 - WHAT WE CONNECT & ARCHITECTURAL BLUEPRINT (Dark #0A0D12 & #050607):
- 6-Card enterprise integration matrix: CRM, ERP, Modern SaaS, Databases, APIs, and Legacy On-Premises Systems.
- Detailed 3-tier integration topology diagram highlighting the API gateway, semantic caching, vector retriever, and model privacy isolation layer.

SECTION 5 & 6 - LEGACY MODERNIZATION & ENTERPRISE SECURITY:
- Clean white section detailing the "Legacy to AI Bridge" utilizing Change Data Capture (CDC).
- Dark security panel highlighting SOC2, HIPAA, RBAC, and Zero-Data-Retention guarantees.

SECTION 7 & 8 - 4-WEEK ROLLOUT & FINAL CTA:
- Phased 4-week delivery roadmap from Audit to Production.
- High-impact dark CTA banner: "Your systems already have the data. Let's give them intelligence." with project scoping form.
```

---

## 3. SUMMARY MATRIX OF THE 6 LOCKED PAGES

| Page File | Page Title | Core Message | Hero Visual | Dominant Palette |
| :--- | :--- | :--- | :--- | :--- |
| `ai-consulting.html` | AI Consulting | Know where AI fits. Know what to build. | Strategic AI Planning Workspace | 70% Dark / 20% White / 10% Blue |
| `ai-development.html` | AI Development | From AI idea to production-ready product. | Production Product UI + Layered Stack | 70% Dark / 20% White / 10% Blue |
| `ai-automation.html` | AI Automation | Turn repetitive work into intelligent workflows. | Operations Pipeline & Trigger Engine | 70% Dark / 20% White / 10% Blue |
| `ai-agents.html` | AI Agent Development | Build AI that doesn't just answer. It acts. | Autonomous Agent Orchestration Hub | 70% Dark / 20% White / 10% Blue |
| `ai-compiler.html` | AI Compiler Engineering | Make AI models run smarter, faster. | Systems Architecture & Low-Level Silicon | 70% Dark / 20% White / 10% Blue |
| `ai-integration.html` | AI Integration | Put intelligence into the systems you already use. | Enterprise Ecosystem & Connected Stack | 70% Dark / 20% White / 10% Blue |

---

## 4. HOW TO USE THESE PROMPTS
1. **For Image / Visual Generation (Midjourney, Flux, DALL-E)**:
   - Always copy the `[MASTER SYSTEM PREFIX - WEBCONVOY 2026]` first.
   - Paste the specific page's `Complete Generation Prompt`.
2. **For Frontend HTML/CSS Code Generation**:
   - Use the exact section IDs and color tokens defined in Section 0.2 (`#050607`, `#0A0D12`, `#0D1118`, `#126BFF`, `#F7F8FA`).
   - Preserve the exact `<nav class="main-navbar-sticky">` and corporate footer from `ai.html`.
   - Maintain the alternating rhythm of dark and crisp white sections.
   - Include the validated math security captcha (`2 * 12 = 24`) on every contact/scoping form.
