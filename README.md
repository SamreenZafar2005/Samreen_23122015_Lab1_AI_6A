# Samreen_23122015_Lab1_AI_6A

## Intelligent Agents Assignment

### AI Patient Follow-Up and Care Management Agent

**Student Name:** Samreen Zafar
**Roll Number:** 23122015  **Section:** A  **Semester:** 6

---

## Project Overview

This repository contains my submission for the Intelligent Agents assignment, focused on
the design and evaluation of an **AI Patient Follow-Up and Care Management Agent**.

The agent is designed around a common real-world healthcare problem: patients may forget
their follow-up appointments, required tests, or medication schedules after receiving
treatment. This project models an intelligent agent that monitors a patient's care plan and
provides timely reminders and follow-up support to help patients stay on track with their
treatment.

The assignment report covers four parts — problem identification, problem formulation
(with a graphical environment diagram), evaluation using the PEAS framework, and
classification of the agent's environmental properties.

As a small practical example, I also implemented a rule-based Travel Agent in Python to
demonstrate conditional decision-making using if / elif / else logic.

---

## Repository Contents

| File | Description |
|---|---|
| `AI_Patient_FollowUp_Agent_Assignment.pdf` | Complete Intelligent Agents assignment report |
| `Samreen_Lab1_TravelAgent.ipynb` | Google Colab notebook containing the rule-based Travel Agent example |
| `README.md` | Project documentation and overview |

---

## Basic Travel Agent Example

As a small practical example, I created a simple rule-based Travel Agent.

The agent checks the passenger's selected seat class and calculates the final ticket price
accordingly.

- If the seat class is **Business**, a fixed surcharge is added to the base fare.
- If the seat class is **Economy Plus**, a smaller surcharge is added.
- Otherwise (**Economy**), the base fare applies with no surcharge.

### Python Code

```python
seat_class = "Business"
base_fare = 12000
passenger = "Ahmed"

if seat_class == "Business":
    surcharge = 8000
elif seat_class == "Economy Plus":
    surcharge = 3000
else:
    surcharge = 0

final_price = base_fare + surcharge
print(f"{passenger} booked {seat_class} class. Final ticket price: PKR {final_price}")
```

---

## Key Concepts Applied

- **PEAS Framework** — Performance measure, Environment, Actuators, Sensors
- **Environment Properties** — Partially Observable, Stochastic, Sequential, Dynamic,
  Discrete, Multi-Agent
- **Conditional Decision Making** — if / elif / else logic, as shown in the Travel Agent
  example above
