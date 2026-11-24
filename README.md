
# Exp No. 1: Developing an AI Agent with PEAS Description

**Name:** POPURI SAHITHYA  
**Register Number:** 212225240106

---

## AIM

To identify the PEAS description for the given AI problem and develop an AI agent using Python.

## THEORY

### Medicine Prescribing Agent

The Medicine Prescribing Agent is designed to monitor patients in a two-room hospital environment. The user enters the temperatures of the patients in Room A and Room B.

For this experiment, a temperature greater than **98.5°F** is considered unhealthy, while a temperature of **98.5°F or below** is considered healthy.

The agent starts in a random room and checks the patient's condition using the entered temperature. If an unhealthy patient is detected, the agent performs a simulated treatment and updates the patient's status to healthy.

After checking and treating the patient in one room, the agent moves to the other room to check the patient's condition. The agent's performance increases for every treatment and decreases for every movement between rooms.

The process continues until both rooms have been visited and all patients are marked healthy.


---

## PEAS DESCRIPTION

| Agent Type | Performance Measure | Environment | Actuators | Sensors |
|---|---|---|---|---|
| Medicine Prescribing Agent | Treating unhealthy patients and accounting for agent movement | Two hospital rooms (Room A and Room B), patients | Movement and simulated treatment | Patient temperature and agent location |

---

## DESIGN STEPS

### STEP 1: Identifying the Input

- Temperature of the patient in Room A.
- Temperature of the patient in Room B.
- Current location of the agent.

### STEP 2: Identifying the Output

- Identify whether the patient is healthy or unhealthy.
- Perform simulated treatment if the patient is unhealthy.
- Move the agent between Room A and Room B.
- Display the patient's updated condition and agent performance.

### STEP 3: Developing the PEAS Description

The PEAS description is developed by identifying the following four components:

- **Performance Measure:** Treating unhealthy patients and accounting for movement.
- **Environment:** Two hospital rooms containing patients.
- **Actuators:** Movement and simulated treatment.
- **Sensors:** Patient temperature and agent location.

### STEP 4: Implementing the AI Agent

The AI agent is implemented using Python. It starts in a random room, checks the patient's temperature, identifies the patient's condition, and performs simulated treatment when required. It then moves to the other room and repeats the process.

### STEP 5: Measuring the Performance Parameters

The agent's performance is calculated based on the following conditions:

- For every simulated treatment, the performance is incremented by **10**.
- For every movement between rooms, the performance is decremented by **1**.
- The process ends when both rooms have been visited and both patients are marked healthy.

---

## OUTPUT
<img width="456" height="396" alt="image" src="https://github.com/user-attachments/assets/245bbf58-96f4-488f-98c4-a57ff9dfd1b0" />

## RESULT

Thus, the PEAS description for the Medicine Prescribing Agent was identified, and the AI agent was implemented successfully using Python in a two-room hospital environment.
