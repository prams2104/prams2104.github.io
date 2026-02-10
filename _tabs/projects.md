---
layout: page
icon: fas fa-laptop-code
order: 1
title: Projects
---

<div style="text-align: center; margin-bottom: 2rem;">
  <h1>Engineering Projects</h1>
  <p style="color: #666; font-size: 1.1rem;">
    AI systems, robotics, and full-stack applications bridging theory and real-world impact
  </p>
</div>

---

## Featured Projects

### 📈 Cryptocurrency Cross-Sectional Momentum Research
**Winter 2026 | Python, Pandas, NumPy, Matplotlib**

Rigorous research project evaluating cross-sectional momentum and reversal strategies on **25 liquid cryptocurrencies** over 6+ years (2020–2026) using an institutional-style **train / validation / out-of-sample** framework, alpha regression, and realistic transaction costs.

**Key Findings & Achievements:**
- Built market-neutral long/short portfolios with proper execution timing (shift+1), dynamic eligibility, and winsorized returns to avoid look-ahead bias and outliers
- Showed that a 20-day momentum strategy with strong in-sample alpha **completely fails** in validation and out-of-sample once a 2023 regime break (≈38% collapse in cross-sectional dispersion) is accounted for
- Demonstrated that a 1-day reversal strategy delivers **highly significant alpha** out-of-sample (t-stat > 4) but is **unimplementable** in practice due to ~138% daily turnover and cost drag
- Ran full alpha regression vs BTC to separate true cross-sectional alpha from market exposure, and validated market neutrality via rolling beta analysis
- Performed transaction cost sweeps (5–40 bps) and period-by-period analysis to show how seemingly good strategies break once costs and regime changes are incorporated

**Tech Stack:** Python, Pandas, NumPy, Matplotlib, Seaborn, Binance API, statistical backtesting, alpha regression, time-series analysis

[View on GitHub](https://github.com/prams2104/crypto-momentum-backtest)

### 🎨 Figma Mini – Real-Time Collaborative Design Board
**Winter 2026 | React, TypeScript, Node.js, Socket.IO**

Built a lightweight collaborative canvas application enabling multiple users to simultaneously create and edit shapes with instant synchronization, live cursor tracking, and version history.

**Key Achievements:**
- Architected full-stack real-time system with WebSocket communication for <100ms synchronization across distributed clients
- Implemented event-driven backend broadcasting drawing events and cursor positions to all connected users
- Developed local version history with undo/redo functionality while maintaining shared canvas state synchronization
- Optimized HTML5 Canvas rendering for smooth concurrent editing without flickering or performance degradation

**Tech Stack:** React, TypeScript, Node.js, Express, Socket.IO, HTML5 Canvas API, Vite

[View on GitHub](https://github.com/prams2104/figma-mini) | [Watch Demo](https://youtu.be/QWXNByalFuE)

### 🤖 OpsPilot – AI-Powered Operations Reconciliation System
**Winter 2026 | Python, FastAPI, SQLAlchemy, Claude API**

Designed and built a full-stack reconciliation system to automate trade/ledger validation, detecting mismatches and missing entries with intelligent analysis.

**Key Achievements:**
- Implemented RESTful APIs with comprehensive CRUD operations and automated reconciliation engine
- Dual validation strategies: exact matching and statistical anomaly detection
- Integrated Anthropic Claude API for natural language issue explanations with graceful fallback to rule-based analysis
- Architected extensible validation framework supporting multiple data sources and business rules

**Tech Stack:** Python, FastAPI, SQLAlchemy, SQLite, Claude API, JavaScript, REST APIs

[View on GitHub](https://github.com/prams2104/opspilot)

---

### 🚗 Sim-to-Real Robot Navigation with RL & Digital Twins
**Winter 2025 | Unreal Engine, Python, C++, Reinforcement Learning**

Led a 5-member team developing autonomous navigation for a PiCar using reinforcement learning models trained in simulation.

**Key Achievements:**
- Built a photorealistic PiCar replica in Unreal Engine for training RL models
- Trained and fine-tuned models using Stable-Baselines3 and AMD Schola
- Achieved reliable sim-to-real transfer for real-world autonomous navigation
- Collaborated with AMD engineers through weekly technical consultations
- Delivered graded presentations to faculty and peers on complex ML concepts

**Tech Stack:** Unreal Engine, Python, C++, Stable-Baselines3, AMD Schola

---

### 📈 AI Marketing Optimization for Small Businesses
**Spring 2025 | GPT-3.5, Python, NLP**

Built a lightweight AI pipeline generating high-conversion, platform-specific marketing content for SMEs across Instagram, LinkedIn, TikTok, and Etsy.

**Key Achievements:**
- Combined structured prompting, few-shot learning, and human-aligned ranking
- **67% improvement** in CTA clarity and perfect platform-fit across 12 evaluation prompts
- Outperformed Jasper.ai-style baselines without full model retraining
- Achieved near-zero loss through quality-weighted fine-tuning

**Tech Stack:** Python, GPT-3.5 API, NLP, Few-Shot Learning

---

## Project Categories

Browse by domain:

**🧠 Machine Learning & AI**
- Reinforcement Learning for robotics
- NLP and content generation
- Anomaly detection systems

**🔧 Systems & Infrastructure**
- Full-stack web applications
- Database design and optimization
- API development and integration

**🤖 Robotics & Embedded Systems**
- Sim-to-real transfer learning
- Autonomous navigation
- Digital twin development

**💼 Business Applications**
- Operations automation
- Marketing optimization
- Financial reconciliation systems

---

## In Progress & Coming Soon

**🔬 Computer Architecture Projects**
- Processor design and optimization
- Memory hierarchy analysis
- Hardware acceleration studies

**⚡ Control Systems**
- PID controller implementations
- Automation frameworks
- Real-time system design

**📊 Data Analysis**
- Signal processing applications
- ML model deployment
- Performance optimization

---

## How I Approach Projects

Each project follows a structured methodology:

1. **Problem Definition** - Understanding the real-world challenge
2. **Research & Design** - Exploring solutions and architecting systems
3. **Implementation** - Writing clean, maintainable code
4. **Testing & Validation** - Ensuring reliability and performance
5. **Documentation** - Creating clear technical documentation
6. **Iteration** - Continuous improvement based on feedback

---

## Collaborate With Me

Working on something interesting? Looking for a team member? I'm always open to collaboration on:
- AI/ML applications and research
- Robotics and autonomous systems
- Full-stack development projects
- Strategy and consulting challenges

**Let's build something together:**  
📧 [prameshsinghavi02@gmail.com](mailto:prameshsinghavi02@gmail.com)  
💻 [GitHub](https://github.com/prams2104)

---