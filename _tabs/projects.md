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

### 📈 Cryptocurrency Cross-Sectional Momentum Strategy
**Winter 2026 | Python, Pandas, NumPy, Matplotlib**

Developed and backtested a statistical arbitrage strategy on 9 liquid cryptocurrencies (BTC, ETH, BNB, XRP, ADA, SOL, DOGE, AVAX, DOT) over a 6-year period (2020-2026), achieving strong risk-adjusted returns with proper transaction cost modeling.

**Key Achievements:**
- Backtested 20-day cross-sectional momentum strategy achieving 1.39 Sharpe ratio (gross), 0.71 Sharpe net of 20 bps transaction costs over 2,226 trading days
- Discovered structural regime break in 2023: cross-sectional dispersion collapsed 38% (3.20% → 1.98%), causing momentum Sharpe to degrade from 1.04 to 0.23
- Implemented production-grade backtesting methodology: lookahead bias prevention (shift+1), dynamic eligibility enforcement, winsorized returns to handle extreme volatility
- Conducted comprehensive transaction cost sensitivity analysis (5-40 bps), finding momentum remains profitable up to 35-40 bps breakeven cost
- Validated market neutrality through rolling 60-day beta analysis (centered at zero), confirming returns driven by cross-sectional alpha rather than directional exposure
- Tested 1-day mean-reversion strategy: found catastrophically unprofitable (Sharpe -3.88 at 20 bps) due to 128% daily turnover vs 29% for momentum

**Tech Stack:** Python, Pandas, NumPy, Matplotlib, Seaborn, Binance API, Statistical Backtesting, Time-Series Analysis

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