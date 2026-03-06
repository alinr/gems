# CORPUSRANK: Messy Middle & GEO Prompt Suite

A collection of system instructions and frameworks designed to bridge the gap between **Google’s "Messy Middle" consumer journey** and **Generative Engine Optimization (GEO)**.

This repository provides a complete workflow for SEOs, GEOs, Strategists, and Marketing Managers to dominate AI Overviews (AIO), ChatGPT, Gemini, Perplexity, Grok, ... and Search results by leveraging behavioral heuristics (BH) and E-E-A-T principles.

---

## Core Methodology: The Messy Middle

These prompts are built on the framework of the **Messy Middle**, the complex space between a "Trigger" and a "Purchase" where consumers **Explore** and **Evaluate**. Each prompt is engineered to address specific **Behavioral Heuristics (BH)**:

- **BH1: Category Heuristics** (Simplifying complex choices)
- **BH2: Social Proof** (Recommendations and reviews)
- **BH3: Authority Bias** (Expertise and trust)
- **BH4: Scarcity Bias** (Limited availability)
- **BH5: Power of Now** (Immediate solutions)
- **BH6: Power of Free** (Incentives and bonuses)

---

## Included Frameworks

### 1. Phase-Specific Analysis (The Full Funnel)

- **`mm-exposure.md`**: Analyzes passive touchpoints and priming before a trigger occurs.
- **`mm-trigger.md`**: Identifies the emotional impulses and "Zero Moment of Truth" questions.
- **`mm-exploration.md`**: Maps how users expand their knowledge and discover category options.
- **`mm-evaluation.md`**: Decodes comparison logic and risk-reduction queries.
- **`mm-purchase.md`**: Focuses on eliminating final transactional hurdles (shipping, trust, price).
- **`mm-experience.md`**: Drives post-purchase loyalty and troubleshooting.

### 2. Strategy & Architecture

- **`CORPUSRANK_TopicCluster.md`**: A strategic advisor for Pillar/Cluster content architecture. Links the "Messy Middle" to measurable business results.
- **`CORPUSRANK_Schema.md`**: A JSON-LD generator that creates semantically rich, linked data graphs (Organization, WebSite, WebPage, Breadcrumb) to help AI "understand" your entity relationships.

### 3. Trust & Authority

- **`EEAT.md`**: An architect for Experience, Expertise, Authoritativeness, and Trust. Designed to make your content the primary source cited by AI models.
- **`mm-context.md`**: Generates a high-level "Executive Overview" for any product or service category.

---

## ⚡ How to Use

Each file is a **System Instruction**. To use them:

1. **Copy the content** of the desired `.md` file.
2. **Paste it** as the "System Instruction" or "Custom Instruction" in your LLM (ChatGPT, Claude, Gemini).
3. **Follow the "YOUR START" prompt**: The AI will ask you for specific inputs (e.g., `category`, `URL`, or `language`).
4. **Execute the Workflow**: The AI will perform live searches and provide structured, strategic output.

---

## The "AI Memory Score"

A feature of this suite is the **AI Memory Score (1-5)**:

- **1/5 (Tool-Required):** The AI must use a live search (e.g., current prices, news).
- **5/5 (Pure Memory):** The AI knows this from its training data (evergreen knowledge).
- _Strategy:_ We optimize for both—dominating "Memory" with clarity and "Tool Use" with up-to-date authority.

---

## Repository Structure

```text
├── Analysis-Phases/
│   ├── mm-exposure.md
│   ├── mm-trigger.md
│   ├── mm-exploration.md
│   ├── mm-evaluation.md
│   ├── mm-purchase.md
│   └── mm-experience.md
├── Content-Strategy/
│   ├── CORPUSRANK_TopicCluster.md
│   └── EEAT.md
├── Technical/
│   └── CORPUSRANK_Schema.md
└── General/
    └── mm-context.md

```

---

## Contributing

If you have refinements for the behavioral heuristic triggers or new GEO strategies, feel free to open a Pull Request.

---

## **Disclaimer:** These prompts are designed for professional marketing use. They require an LLM with web-browsing capabilities (e.g., ChatGPT Plus, Gemini Paid Tier, Claude with Analysis) to function as intended.
