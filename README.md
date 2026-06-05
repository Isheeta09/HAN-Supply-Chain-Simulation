# HAN Supply Chain Simulation
An interactive Supply Chain Management simulation developed using **Python**, **Streamlit**, **Pandas**, and AI-supported reflective learning components for HAN University of Applied Sciences. The application allows students to experience real-world supply chain decision-making by managing Purchasing, Operations, Sales, and Supply Chain departments while balancing profitability, service level, sustainability, inventory, lead time, and risk.
---

## Project Objective
The goal of this project is to provide students with a hands-on learning environment where they can explore the impact of supply chain decisions on overall business performance.

Players must:
* Select supplier strategies
* Manage inventory levels
* Respond to demand fluctuations
* Handle supply chain disruptions
* Improve sustainability performance
* Balance cost, service, and risk
* Evaluate long-term strategic consequences

---
## Key Enhancement: Strategy Memory & Adaptive Learning
One of the major improvements introduced in this version is the implementation of a **Strategy Memory System** combined with **Adaptive Learning Feedback**.

### Previous Version
```text
Quarter Decision
       ↓
Immediate KPI Change
       ↓
End of Round
```

Decisions affected only the current quarter and students immediately observed KPI changes without long-term consequences.

### Enhanced Version
```text
Quarter Decision
       ↓
Decision Stored
       ↓
Student Provides Rationale
       ↓
Future Event Occurs
       ↓
Event Impact Adjusted
       ↓
AI Reflection & Feedback
       ↓
Learning Outcome
```
### Educational Impact

This enhancement encourages students to:
* Justify their decisions before confirming them
* Reflect on previous strategic choices
* Understand long-term supply chain consequences
* Connect decisions across multiple quarters
* Develop critical thinking and managerial reasoning skills
* Learn the importance of resilience and risk management

---
## Dynamic Event-Based Learning
The simulation now includes linked decision-making across quarters.

### Example: Purchasing → Rotterdam Strike
Students must choose among:

* Low-cost overseas supplier
* Reliable European supplier
* Diversified supplier portfolio

These decisions are stored and later influence disruption outcomes.

Example:

```text
Quarter 2 Supplier Strategy
       ↓
Stored in Strategy Memory
       ↓
Quarter 3 Rotterdam Strike
       ↓
Different Risk, Cost and Lead Time Outcomes
```

Possible outcomes:
| Supplier Strategy           | Lead Time Impact | Risk Impact |
| --------------------------- | ---------------- | ----------- |
| Single Overseas Supplier    | High             | High        |
| Diversified Suppliers       | Moderate         | Moderate    |
| Resilient Regional Supplier | Low              | Low         |

This creates a realistic cause-and-effect relationship between strategic decisions and future supply chain resilience.

---
## AI-Supported Reflective Learning
An AI Learning Coach framework has been integrated into the simulation.

The AI component is designed to:
* Interpret student decisions
* Connect outcomes to supply chain theory
* Explain why results occurred
* Encourage reflection and critical thinking
* Support experiential learning

Example reflection topics include:
* Supplier diversification
* Supply chain resilience
* Risk mitigation
* Inventory strategies
* Demand management
* Sustainability trade-offs

This transforms the simulation from a KPI-focused game into a guided learning environment.

---
## Technologies Used

* Python
* Streamlit
* Pandas
* OpenAI API (AI Learning Coach Framework)

---
## Features

### Interactive Dashboard
Monitor key business metrics in real time:

* Efficiency Score
* Revenue
* Net Profit
* Inventory Value
* Service Level
* ESG Score
* Lead Time
* Supply Chain Risk

### Department-Based Decision Making
Students make decisions across:
* Purchasing
* Operations
* Sales
* Supply Chain

Each department contributes to overall company performance.

### Strategy Memory System
* Decision rationale capture
* Decision history tracking
* Cross-quarter decision persistence
* Long-term consequence modelling

### Dynamic Supply Chain Events
The simulation includes realistic business scenarios such as:

* Rotterdam Port Strike
* Demand Surge
* Sustainability Pressure
* Tariff Shock
* Market Volatility
* CEO Challenge

Events dynamically interact with previous strategic decisions.

### Financial Analysis
Generate and review:

* Income Statements
* Balance Sheets
* Quarterly Performance Reports
* KPI Trend Analysis

### Instructor Mode
Special instructor controls allow:

* Locking and unlocking game sections
* Managing classroom activities
* Triggering disruption events
* Monitoring student progress
* Running decision and review rounds

---
## Learning Outcomes

This simulation helps students develop practical knowledge in:
* Supply Chain Management
* Supplier Selection
* Inventory Planning
* Demand Forecasting
* Risk Management
* Sustainability (ESG)
* Supply Chain Resilience
* Integrated Business Decision-Making
* Strategic Thinking
* Reflective Learning

---
## Installation

### Clone the Repository

```bash
git clone https://github.com/Isheeta09/HAN-Supply-Chain-Simulation.git
cd HAN-Supply-Chain-Simulation
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

---

## Author
**Isheeta**
---

## License
This project is licensed under the MIT License.
