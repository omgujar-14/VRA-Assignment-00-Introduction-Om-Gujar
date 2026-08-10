# Assignment 00 — Student Answer Sheet

## Student Information

| Field | Student Response |
|---|---|
| Full name | `[Om Purushottam Gujar]` |
| GitHub username | `[omgujar-14]` |
| Class/college | `[Shankarlal Khandelwal college Akola , BCA 3rd Year  ]` |
| Submission date | `[10/08/2026]` |

---

## Section A — Industrial Automation Fundamentals (15 marks)

### Q1. What is industrial automation? Explain it in 3–5 sentences. (5 marks)

`[Industrial automation means using machines, control systems, and software to perform industrial work with less human effort. It helps control and monitor machines automatically during the production process. Automation makes work faster, more accurate, and safer. It is commonly used in factories for manufacturing, packaging, assembly, and quality checking. ]`

### Q2. State any four reasons industries use automation. (4 marks)

1. `[To increase production – Machines can work faster and for longer hours.]`
2. `[To reduce human effort – Automation reduces the need for doing repetitive work manually.]`
3. `[To improve quality – Machines can perform tasks with better accuracy and consistency.]`
4. `[To improve safety – Automation can handle dangerous tasks and reduce the risk of accidents.]`

### Q3. Give three examples of processes that can be automated using PLC and SCADA. (3 marks)

1. `[Water treatment system – Controls water pumps, tanks, and water levels automatically.]`
2. `[Conveyor belt system – Controls the movement of materials from one place to another.]`
3. `[Industrial temperature control – Monitors and controls the temperature of machines or production processes.]`

### Q4. Complete the automation sequence. (3 marks)

```
Input  →  PLC → Output  → SCADA
```

Explain the meaning of each stage:

`[1. Input – Sensors or switches collect information from the machine or process, such as temperature, level, or pressure.
2. PLC – The PLC receives the input, checks the programmed logic, and decides what action should be taken.
3. Output – Based on the PLC decision, output devices such as motors, pumps, valves, or lights perform the required action.
4. SCADA – SCADA monitors the whole process and shows the machine status and important data on a computer screen for the operator.
]`

---

## Section B — PLC Fundamentals and Working (25 marks)

### Q5. Expand PLC and explain why it is called an industrial computer. (5 marks)

`[
PLC stands for Programmable Logic Controller. It is an industrial device used to control machines and automatic processes. It is called an **industrial computer** because it can receive input from sensors, process the information using a program, and control output devices like motors, pumps, and valves. PLCs are specially designed to work in harsh industrial environments and can operate continuously with high reliability.
]`

### Q6. Classify each device as a PLC input or PLC output. (5 marks)

| Device | Input or Output? |
|---|---|
| Push button | `[Input]` |
| Proximity sensor | `[Input]` |
| Motor contactor | `[Output]` |
| Indicator lamp | `[Output]` |
| Temperature sensor | `[Input]` |

### Q7. Write the three main PLC working steps in the correct order. (6 marks)

1. `[ Input Scan – The PLC reads the signals coming from input devices such as sensors and switches.]`
2. `[Program Scan – The PLC processes the inputs according to the program stored in its memory.]`
3. `[Output Scan – The PLC sends signals to output devices such as motors, lamps, and valves.]`

### Q8. What is a PLC scan cycle? Why must it repeat continuously? (5 marks)

`[
A PLC scan cycle is the process in which a PLC reads the input signals, executes the programmed logic, and updates the output devices. This process happens in a fixed sequence: **Input Scan → Program Scan → Output Scan**. The scan cycle repeats continuously so that the PLC can monitor changes in the machine and respond quickly. Continuous scanning helps the machine work automatically and safely.
]`

### Q9. Identify the PLC section responsible for each function. (4 marks)

| Function | PLC Section |
|---|---|
| Executes the user program | `[CPU]` |
| Stores the program and data | `[MEMORY]` |
| Reads field-device signals | `[INPUT MODULE]` |
| Controls external devices | `[OUTPUT MODULE]` |

---

## Section C — SCADA Fundamentals (20 marks)

### Q10. Expand SCADA and explain its purpose. (5 marks)

`[
SCADA stands for Supervisory Control and Data Acquisition. It is a system used to **monitor and control industrial processes** from a central computer. SCADA collects data from PLCs, sensors, and other devices and displays it on a screen for the operator. It helps operators easily check machine status, detect problems, and control the process when needed.
]`

### Q11. State five important functions of a SCADA system. (5 marks)

1. `[Monitoring – It shows the current status of machines and processes.]`
2. `[Data Collection – It collects information from PLCs, sensors, and other devices.]`
3. `[Control – It allows the operator to control machines and processes.]`
4. `[Alarm Management – It gives alerts when a problem or abnormal condition occurs.]`
5. `[Data Storage – It stores process data for future analysis and reporting.]`

### Q12. Why is SCADA described as the “eyes” of an automation system? (4 marks)

`[
SCADA is called the **“eyes” of an automation system** because it allows the operator to see what is happening in the industrial process. It collects information from PLCs and sensors and displays it on a computer screen. The operator can easily monitor machine status, temperature, pressure, levels, and other important values. It also shows alarms when something goes wrong.
]`

### Q13. Name four industries or services where SCADA can be used. (4 marks)

1. `[Water Treatment Plants – To monitor water levels, pumps, and treatment processes.]`
2. `[Power Plants – To monitor and control power generation and distribution.]`
3. `[Oil and Gas Industry – To monitor pipelines, pressure, and flow.]`
4. `[Manufacturing Industries – To monitor and control machines and production processes.]`

### Q14. What is the difference between monitoring and controlling? (2 marks)

`[ Monitoring– It means watching and checking the status of a machine or process.
Controlling – It means **taking action or giving commands** to change or operate a machine or process.
Example: SCADA monitors the temperature, while PLC controls the heater to maintain the required temperature.
]`

---

## Section D — PLC, HMI and SCADA Relationship (15 marks)

### Q15. Complete the comparison table. (9 marks)

| System | Main purpose | Typical user/location | Example task |
|---|---|---|---|
| PLC | `[Controls machines and processes]` | `[Factory / Control Panel]` | `[Starting and stopping a motor]` |
| HMI | `[Displays information and allows operator control]` | `[Operator Station / Machine Panel]` | `[Setting motor speed or checking status]` |
| SCADA | `[Monitors and controls processes from a central system]` | `[Control Room]` | `[Monitoring water level and showing alarms]` |

### Q16. Explain how information travels from a field sensor to a SCADA screen. (6 marks)

`[1) Sensor detects the condition – The field sensor measures something like temperature, pressure, level, or flow.
2) Signal is sent to PLC – The sensor sends its electrical signal to the PLC input module.
3) PLC processes the signal – The PLC reads the signal and processes it according to its program.
4) Data is sent to SCADA – The PLC sends the processed data to the SCADA system through a communication network.
5) SCADA receives the data – SCADA collects and processes the information received from the PLC.
6) Data is displayed – The information is shown on the SCADA screen so the operator can monitor the process.]`

---

## Section E — Industrial Application Challenge (15 marks)

### Scenario: Automatic Water Tank

A tank must fill automatically. A low-level sensor detects when water is low, and a high-level sensor detects when the tank is full. A pump supplies water. The operator should see the tank and pump status on a monitoring screen.

### Q17. Identify the PLC inputs and output. (3 marks)

- Inputs: `[Push button, proximity sensor, temperature sensor.]`
- Output: `[ Motor, indicator lamp, valve.]`

### Q18. Write the required control behaviour in plain language. (4 marks)

`[1. When the Start button is pressed, the **motor should start**.
2. When the Stop button is pressed, the **motor should stop**.
3. If the sensor detects an object, the system should perform the required action.
4. The indicator lamp should show the current status of the machine.
]`

### Q19. State four items that should be visible on the SCADA/HMI screen. (4 marks)

1. `[Machine Status – Shows whether the machine is ON or OFF.]`
2. `[Process Values – Shows values such as temperature, pressure, level, or speed.]`
3. `[Alarms – Shows warnings when a fault or abnormal condition occurs.]`
4. `[Control Buttons – Allows the operator to start, stop, or control the machine.]`

### Q20. Suggest one alarm and one value/event that should be recorded. (4 marks)

- Alarm: `[High-temperature alarm when the machine temperature goes above the safe limit.]`
- Recorded value/event: `[ Record the temperature value and time whenever the alarm occurs.]`

---

## Submission Checklist

- [x] I entered my student information.
- [x] I answered Questions 1–20.
- [x] I used my own words.
- [x] I checked spellings and technical terms.
- [x] I completed `student-work/reflection.md`.
- [x] I made at least three meaningful commits.
- [x] I checked the Actions result.
- [x] I submitted my repository link to Prof. Dattaraj Vidyasagar.
