# HAN Supply Chain Simulation
An interactive Supply Chain Management simulation developed using **Python**, **Streamlit**, and **Pandas** for HAN University of Applied Sciences.

The application allows students to experience real-world supply chain decision-making by managing Purchasing, Operations, Sales, and Supply Chain departments while balancing profitability, service level, sustainability, inventory, lead time, and risk.

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

---

## Key Enhancement: Strategy Memory & Reflective Learning

One of the main improvements introduced in this version is the **Strategy Memory System**.

### Previous Version

```text
Quarter 2 Decision
       ↓
Immediate KPI Change
       ↓
End
```

Decisions only affected the current quarter and students immediately saw the KPI result.

### Enhanced Version

```text
Quarter 2 Supplier Decision
       ↓
Stored in Strategy Memory
       ↓
Student Records Rationale
       ↓
Quarter 3 Port Strike Event
       ↓
Disruption Modified by Previous Choice
       ↓
Previous Rationale Displayed
       ↓
Reflection and Learning
```

### Educational Impact

This enhancement encourages students to:

* Justify their decisions rather than guess
* Reflect on previous choices
* Understand long-term supply chain consequences
* Connect decisions across multiple quarters
* Develop critical thinking and decision-making skills

For example, a supplier strategy selected in Quarter 2 can influence the outcome of a disruption event in Quarter 3, demonstrating how supply chain decisions affect future resilience and performance.
---

## Technologies Used

* Python
* Streamlit
* Pandas

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

### Dynamic Supply Chain Events

The simulation includes realistic business scenarios such as:
* Rotterdam Port Strike
* Demand Surge
* Sustainability Pressure
* Tariff Shock
* Market Volatility
* CEO Challenge

These events require students to adapt their strategies and respond to changing business conditions.

###Financial Analysis
Generate and review:

* Income Statements
* Balance Sheets
* Quarterly Performance Reports
* KPI Trend Analysis

### Instructor Mode
Special instructor controls allow:

* Locking and unlocking game sections
* Managing classroom activities
* Triggering global disruption events
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
* Integrated Business Decision-Making
* Strategic Thinking
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
## Author
**Isheeta **
---
## License

This project is licensed under the MIT License.
