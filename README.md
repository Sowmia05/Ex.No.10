# Ex.No.10
Content Creation (Reports, Articles, Case Studies, etc.) Using Prompt Patterns

## Date:10/09/2026
## Reg. No.212223050052

## Aim:
To demonstrate how various prompting techniques (query decomposition, decision-making, semantic filtering, etc.) can be employed to create content such as reports, articles, case studies, or creative works like comic books, using ChatGPT or similar models. The objective is to highlight how different prompt structures affect the content's quality, coherence, and structure.

Absolutely. I’ll use the **attached experiment as the format/sample** and adapt it to **your EEE domain and your final-year project: “Speed Control of Induction Motor Using Cloud.”** I’ll keep the same academic structure, prompt-pattern demonstration, two content-generation scenarios, iterations, evaluation, ethics, deliverables, and conclusion.

The sample demonstrates the experiment using an engineering project and two content types—case study and article. 

# EXPERIMENT NO. 10

## Prompt Patterns for Engineering Content Generation

### Date:10/09/2026

### Reg. No.:212223050052

# Aim

To demonstrate how various prompting techniques such as **query decomposition, decision-making, answer engineering, fact-check listing, tail generation, menu actions, and semantic filtering** can be employed to generate engineering content using ChatGPT or similar AI models.

The objective is to study how different prompt structures improve the **quality, coherence, technical accuracy, organization, and presentation** of content related to an engineering project.

---

# Engineering Domain Selected

**Electrical and Electronics Engineering (EEE)**

---

# Selected Project

## Speed Control of Induction Motor Using Cloud

The proposed system integrates an **induction motor, Variable Frequency Drive (VFD), Programmable Logic Controller (PLC), HMI, sensors, Arduino UNO-Q gateway, and cloud platform** to enable remote speed control and real-time monitoring.

The system allows the motor speed to be controlled through cloud-based commands while monitoring parameters such as **speed, voltage, current, and power**. The system aims to improve operational efficiency, remote accessibility, fault monitoring, and reliability through an Industry 4.0-oriented approach.

---

# Problem Statement

Traditional induction motor speed-control systems are often operated locally using manual controls or conventional control panels. Such systems provide limited remote accessibility and real-time visibility of motor operating conditions.

The absence of cloud connectivity makes it difficult to monitor motor parameters remotely, record operating data, and identify abnormal conditions at an early stage. Unexpected faults can result in downtime, maintenance requirements, and reduced operational efficiency.

Therefore, there is a need for a **smart cloud-connected motor control system** that integrates PLC, VFD, HMI, sensors, and cloud technology to provide **remote speed control, real-time monitoring, data logging, and early fault indication**.

This experiment uses structured prompting techniques to generate two types of engineering content related to the proposed system:

1. **Case Study** – describing the implementation and working of the cloud-based induction motor control system.
2. **Educational Article** – explaining cloud-based motor control and its role in Industry 4.0.

---

# Selected Content Generation Scenarios

Two scenarios are selected from the given list:

1. **Case Study** – *“Cloud-Based Speed Control of an Induction Motor: A Case Study”*
2. **Educational Article** – *“Cloud-Based Induction Motor Control: Moving Towards Industry 4.0”*

---

# Prompt Patterns Used and How They Were Applied

| Prompt Pattern          | Application in This Experiment                                                                                                                                 |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Query Decomposition** | The broad topic was divided into smaller parts such as motor control, VFD operation, PLC control, sensor monitoring, cloud communication, and fault detection. |
| **Decision Making**     | The model was asked to select the most suitable presentation approach, such as technology-first or application-first, for the case study.                      |
| **Answer Engineering**  | Detailed instructions were provided regarding headings, word limits, technical depth, tables, and target audience.                                             |
| **Fact Check List**     | The model was instructed to identify technical facts before generating the final content to reduce unsupported claims.                                         |
| **Tail Generation**     | Additional sections such as lessons learned, benefits, limitations, and future scope were generated after the initial content.                                 |
| **Menu Actions**        | Multiple possible article approaches were provided, and the model selected the most appropriate one for engineering students.                                  |
| **Semantic Filter**     | The generated content was refined to use a clear, professional, technically accurate, and easy-to-understand engineering tone.                                 |

---

# Prompt Design and Iteration

# Content 1: Case Study

## “Cloud-Based Speed Control of an Induction Motor: A Case Study”

### Basic Prompt – First Draft

```text
Write a short case study about a system that controls the
speed of an induction motor using cloud technology.
```

### Sample Output – First Draft

> A cloud-based system was developed to control the speed of an induction motor remotely. The system uses a motor, VFD, PLC, sensors, and cloud platform. The motor speed and other parameters can be monitored remotely. The system helps improve motor control and monitoring.

### Observation

The output is simple and understandable, but it is **generic** and does not provide sufficient information about the system architecture, communication flow, monitoring parameters, or practical applications.

---

# Refined Prompt – Query Decomposition + Fact Check List

```text
Before writing, list the key technical facts that can be safely
included based only on the following project description:

Project:
Speed Control of Induction Motor Using Cloud.

System:
Three-phase induction motor, VFD, PLC, HMI, sensors,
Arduino UNO-Q gateway and cloud dashboard.

Functions:
Remote motor speed control, real-time monitoring of speed,
voltage, current and power, data logging and fault indication.

Then write a 300-word case study covering:

1. Background
2. Problem
3. System architecture
4. Working principle
5. Monitoring and control
6. Benefits
7. Challenges

Do not invent numerical performance results that are not provided.
```

### Sample Output – Refined Draft

**Fact List:**

1. Three-phase induction motor is used.
2. VFD controls the motor speed.
3. PLC provides control commands to the VFD.
4. Sensors monitor motor parameters.
5. HMI provides local monitoring and control.
6. Arduino UNO-Q acts as a gateway to the cloud.
7. Cloud enables remote speed control and monitoring.
8. Speed, voltage, current and power can be monitored.
9. Data logging and fault indication are included.

**Case Study:**

The proposed system addresses the limitations of conventional local induction motor control by integrating industrial control components with cloud technology. A three-phase induction motor is connected to a VFD, which regulates the motor speed according to commands generated by the PLC.

Sensors collect operating parameters such as speed, voltage, current, and power. The HMI provides a local interface for monitoring and control. An Arduino UNO-Q gateway connects the control system with the cloud platform, allowing operating information to be transmitted to a remote dashboard.

The cloud platform provides remote speed-setting capability, real-time monitoring, and data logging. Fault conditions can also be identified and communicated to improve system supervision.

### Observation

The **Fact Check List** and **Query Decomposition** produced a more technically structured response while reducing unsupported technical claims.

---

# Advanced / Final Prompt – Decision Making + Answer Engineering + Tail Generation

```text
Two possible narrative approaches are available for the case study:

(a) Technology-first – explain the PLC, VFD, sensors, gateway and
cloud architecture first.

(b) Application-first – begin with the limitations of conventional
motor control and then introduce the proposed cloud-based solution.

Choose the approach that is most suitable for an engineering
audience and briefly justify your choice.

Then write a 400–500 word case study using the following structure:

1. Background
2. Existing Problem
3. Proposed System
4. System Architecture
5. Working Principle
6. Monitoring and Control
7. Benefits and Impact
8. Challenges
9. Lessons Learned
10. Future Scope

Use a professional engineering tone.
Include a table summarizing the conventional system versus
the proposed cloud-based system.

Do not invent experimental values or performance results.
```

### Sample Output – Final Version

**Chosen Approach: Application-first**

The application-first approach is selected because it first establishes the limitations of conventional motor control and then explains how the proposed cloud-based architecture addresses those limitations.

### 1. Background

Induction motors are widely used in industrial applications because of their robustness, reliability, and relatively simple construction. However, conventional speed-control systems generally depend on local operation and provide limited access to motor operating data.

### 2. Existing Problem

Manual or localized control makes remote supervision difficult. Operators may not have continuous visibility of motor speed, voltage, current, and power. This can delay the identification of abnormal operating conditions and increase maintenance requirements.

### 3. Proposed System

The proposed system introduces cloud connectivity into induction motor control. A VFD is used to control motor speed, while a PLC generates the required control commands. Sensors acquire important operating parameters, and an HMI provides local monitoring.

### 4. System Architecture

The basic architecture consists of:

**Three-Phase Induction Motor → VFD → PLC Control**

with sensors connected for parameter monitoring. The control system communicates with the **Arduino UNO-Q gateway**, which transfers relevant information to the cloud platform.

### 5. Working Principle

The operator provides a desired motor speed through the cloud interface. The command is transferred through the gateway and control system to the PLC. The PLC generates the appropriate command for the VFD, which regulates the motor speed.

At the same time, sensors collect motor operating parameters. These values are transmitted to the cloud dashboard, allowing remote monitoring and data logging.

### 6. Monitoring and Control

The system provides monitoring of:

| Parameter    | Purpose                                |
| ------------ | -------------------------------------- |
| Motor Speed  | Monitor operating speed                |
| Voltage      | Observe electrical operating condition |
| Current      | Monitor motor loading                  |
| Power        | Observe power consumption              |
| Fault Status | Identify abnormal conditions           |

### 7. Benefits and Impact

| Conventional Control         | Proposed Cloud-Based Control   |
| ---------------------------- | ------------------------------ |
| Mainly local operation       | Remote monitoring and control  |
| Limited data visibility      | Real-time parameter monitoring |
| Manual observation           | Cloud-based supervision        |
| Limited data storage         | Data logging                   |
| Delayed fault identification | Early fault indication         |
| Limited accessibility        | Remote accessibility           |

### 8. Challenges

The major challenges include reliable communication between industrial devices and the cloud, maintaining data integrity, ensuring communication security, and handling network interruptions.

### 9. Lessons Learned

The project demonstrates that combining conventional industrial automation components such as **PLC and VFD** with cloud technology can extend motor-control capabilities beyond the local control panel.

### 10. Future Scope

The system can be further developed by incorporating advanced fault diagnosis, predictive maintenance, energy-efficiency analysis, mobile monitoring, secure industrial communication, and intelligent analytics.

### Observation

The final prompt produced a more **structured, technically focused, and application-oriented case study**. Decision Making improved the narrative flow, while Answer Engineering controlled the structure and Tail Generation added meaningful lessons and future scope.

---

# Content 2: Educational Article

## “Cloud-Based Induction Motor Control: Moving Towards Industry 4.0”

### Basic Prompt – First Draft

```text
Write an article about cloud-based control of induction motors.
```

### Sample Output – First Draft

> Cloud technology can be used to monitor and control induction motors remotely. Sensors collect motor information and send it to the cloud. Operators can monitor motor performance and control the motor remotely. This technology can improve industrial automation and efficiency.

### Observation

The output provides a basic explanation but is **short, generic, and lacks a clear connection between PLC, VFD, HMI, and cloud technology**.

---

# Refined Prompt – Menu Actions + Semantic Filter

```text
Choose the most suitable approach for an educational article
intended for undergraduate EEE students:

1. Highly technical explanation of PLC-VFD-cloud communication
2. Application-oriented explanation using an induction motor
3. Industrial management and business-oriented explanation

Select one approach and explain why.

Then write a 350-word educational article about cloud-based
induction motor speed control.

Use an optimistic but balanced tone.
Explain technical terms such as VFD, PLC and cloud monitoring
briefly when they are first introduced.
Avoid unnecessary jargon.
Include both advantages and limitations.
```

### Sample Output – Refined Draft

**Chosen Approach: Application-oriented explanation**

The application-oriented approach is selected because undergraduate students can understand the importance of cloud-based motor control more easily when the technology is connected to a practical induction motor application.

Induction motors are an essential part of modern industrial systems. They are used in pumps, fans, conveyors, compressors, and many other applications. Traditionally, their operation is controlled locally through electrical and industrial control systems.

A **Variable Frequency Drive (VFD)** can regulate induction motor speed by controlling the frequency and voltage supplied to the motor. A **Programmable Logic Controller (PLC)** can generate control commands and coordinate the motor-control process.

Cloud technology adds another level of capability. Sensors can collect motor operating parameters such as speed, voltage, current, and power. These values can be transferred through a gateway to a cloud dashboard where operators can remotely monitor the motor.

The major advantage is improved visibility. Instead of depending entirely on local observation, operators can access motor information remotely. Data logging also allows operating conditions to be reviewed over time.

However, cloud-based control also introduces challenges. Network reliability, communication security, data integrity, and system response must be considered before implementing such systems in real industrial environments.

---

# Final Version – Semantic Filter Iteration

### Advanced Prompt

```text
Rewrite the previous article using the following semantic filter:

- Make the opening relatable to an industrial application.
- Maintain technical accuracy.
- Use simple language suitable for undergraduate EEE students.
- Keep the article professional but engaging.
- Explain PLC, VFD and cloud monitoring briefly.
- Connect the explanation to the proposed induction motor project.
- Do not introduce unsupported numerical performance claims.
- End with future possibilities for Industry 4.0.
```

### Sample Output – Final Version

Imagine an industrial motor operating a pump or conveyor for several hours a day. Traditionally, an operator may need to remain near the control panel to adjust the motor and observe its operating condition. But what if the same information could be viewed remotely?

This is where **cloud-based induction motor control** becomes useful.

Induction motors are widely used in industrial applications, but conventional systems often provide limited remote accessibility and operating-data visibility. Integrating industrial automation with cloud technology can help overcome these limitations.

In a cloud-based motor-control system, a **Variable Frequency Drive (VFD)** is used to regulate the speed of the induction motor. A **Programmable Logic Controller (PLC)** manages the control commands and communicates with the VFD. Sensors can continuously collect parameters such as motor speed, voltage, current, and power.

An **HMI** provides a local interface for monitoring and control, while a gateway can connect the industrial control system to a cloud platform. Through the cloud dashboard, an operator can remotely provide a speed command and monitor the motor's operating condition.

The major benefit is improved visibility. Instead of depending only on local observation, operating information can be accessed remotely and recorded for future analysis. Fault indications can also help operators identify abnormal conditions earlier.

However, cloud-based control is not without challenges. Reliable communication, cybersecurity, data integrity, and network availability are important considerations in industrial applications.

The integration of **PLC, VFD, HMI, sensors, gateway, and cloud technology** represents an important step toward Industry 4.0. Future systems can extend this approach using predictive maintenance, intelligent fault diagnosis, energy monitoring, and advanced analytics.

### Observation

The Semantic Filter improved the article by making it **more engaging and easier to understand while maintaining its technical meaning**. The Menu Actions technique helped select the appropriate audience-oriented approach.

---

# AI Output Evaluation

| Content    | Version | Coherence | Creativity | Accuracy  | Tone & Style            | Overall    |
| ---------- | ------- | --------- | ---------- | --------- | ----------------------- | ---------- |
| Case Study | Basic   | Fair      | Low        | Fair      | Generic                 | **5.5/10** |
| Case Study | Refined | Good      | Moderate   | Good      | Professional            | **7.8/10** |
| Case Study | Final   | Excellent | Good       | Excellent | Professional, technical | **9.2/10** |
| Article    | Basic   | Fair      | Low        | Good      | Generic                 | **5.2/10** |
| Article    | Refined | Good      | Good       | Good      | Educational             | **7.8/10** |
| Article    | Final   | Excellent | High       | Excellent | Clear, engaging         | **9.0/10** |

### Evaluation Summary

The experiment shows that basic prompts generally produce short and generic responses. **Query Decomposition** and **Fact Check Lists** significantly improved structure and technical grounding.

**Decision Making** helped select an appropriate narrative approach, while **Answer Engineering** improved organization and readability. **Menu Actions** helped select the most suitable content style, and **Semantic Filtering** improved tone and audience suitability.

**Tail Generation** was useful for extending the content with lessons learned and future scope.

---

# Ethical Considerations

* **Technical Accuracy:** AI-generated technical information must be checked before being used in academic or industrial applications.
* **Avoiding Fabricated Results:** Numerical performance values, efficiency improvements, or experimental results should not be generated unless they are supported by actual experiments.
* **Human Supervision:** Cloud-based motor control should not be presented as completely autonomous without appropriate human supervision and safety mechanisms.
* **Cybersecurity:** Connecting industrial control systems to the cloud introduces cybersecurity considerations that must be addressed.
* **Data Privacy and Security:** Motor operating data transmitted to cloud platforms should be appropriately protected.
* **Responsible AI Usage:** AI-generated reports and articles should be reviewed by the student or engineer before submission or publication.

---

# Final Presentation Outline

1. **Title Slide** – Prompt Patterns for Engineering Content Generation
2. **Engineering Domain** – Electrical and Electronics Engineering
3. **Project Overview** – Speed Control of Induction Motor Using Cloud
4. **Problem Statement**
5. **Prompt Patterns Demonstrated**
6. **Case Study – Basic to Final Prompt**
7. **Case Study – Output Evaluation**
8. **Educational Article – Basic to Final Prompt**
9. **Educational Article – Output Evaluation**
10. **Comparison of Prompt Techniques**
11. **Ethical Considerations**
12. **Conclusion and Future Scope**

---

# Deliverables

1. **First Draft** – Basic case study and educational article generated using simple prompts.
2. **Refined Content** – Improved content generated using query decomposition, fact checking, menu actions, and semantic filtering.
3. **Multiple Versions** – Basic, refined, and advanced versions demonstrating the effect of different prompting techniques.
4. **Final Version** – Polished case study and educational article with improved structure, clarity, technical accuracy, and audience suitability.
5. **Prompt Repository** – Collection of basic, refined, and final prompts used during the experiment.

---

# Conclusion

By applying structured prompting techniques such as **Query Decomposition, Decision Making, Answer Engineering, Fact Check Listing, Tail Generation, Menu Actions, and Semantic Filtering**, high-quality engineering content was generated for the project **“Speed Control of Induction Motor Using Cloud.”**

The experiment demonstrated that structured prompts provide better control over the **organization, technical accuracy, coherence, creativity, and tone** of AI-generated content. The case study became more technically structured through fact checking and decomposition, while the educational article became more engaging through menu selection and semantic filtering.

Therefore, effective prompt engineering can help engineering students generate **reports, case studies, technical articles, presentations, and other academic content** more efficiently. However, AI-generated technical content must always be reviewed for accuracy, unsupported claims, safety, and ethical considerations before final use.
