# 🎮 A/B Testing Interaction Mechanics: Impact on Memory & Cognitive Load

> **A Data-Driven UX Research & Engineering Project** analyzing the efficiency, cognitive load, and memory retention of two video game interaction mechanics: *Drag-and-Drop* vs. *Point-and-Click*.

## 📌 Project Overview
This repository contains the analytical dashboard for my Bachelor of Engineering (B.Eng.) thesis. The goal of the study was to determine how different physical interaction mechanics affect a player's short-term memory and subjective workload. 

To test this, I developed a custom 2D Escape Room game using the Godot Engine. The game was deployed in two distinct versions: one fully controlled via Drag-and-Drop, and the other via Point-and-Click. Gameplay telemetry and survey data from 30 participants were collected and visualized in Power BI.

The results confirmed the **Enactment Effect** in digital environments: active motor engagement (Drag-and-Drop) significantly improves memory retention while simultaneously lowering the mental effort required to play.

## 💡 Key Findings
* **🧠 Better Memory Retention:** The Drag-and-Drop group achieved an average memory test score of **68.00%**, significantly outperforming the Point-and-Click group (**47.33%**).
* **⏱️ Higher Efficiency (Interaction Cost):** Point-and-Click proved to be significantly less efficient. Players using this method took an average of **16.1 minutes** and **517 clicks** to finish, whereas the Drag-and-Drop group completed the same game in just **10.0 minutes** using **305 clicks**.
* **⚖️ The Workload Trade-off (NASA-TLX):** While Drag-and-Drop required a slight increase in physical effort (2.27 vs. 1.80 on a 10-point scale), it drastically reduced mental demand (**5.60 vs. 7.60**). This proves Drag-and-Drop is a more intuitive and cognitively optimal choice.
* **⏳ Time vs. Memory:** Correlation analysis (Pearson's r = -0.14) proved that total playtime has no significant impact on memory retention; the interaction method is the deciding factor.

---
## 📊 Dashboard Previews & Report Structure

The Power BI report is divided into 4 analytical sections.

### 1. Participant Demographics & Overview
An overview of the test group, detailing participant age distribution, gaming frequency, and their assignment to the respective A/B testing groups.
![Overview & Memory Scores](https://github.com/user-attachments/assets/cdc3aac8-1ea3-4ceb-bdbe-ee3cc3a504ac)

### 2. Memory Performance Results
The core A/B test findings regarding short-term memory retention, clearly demonstrating the impact of the assigned interaction mechanic on the users' ability to remember elements.
![Interaction Cost Analysis](https://github.com/user-attachments/assets/1c1f896a-16b8-44ff-9753-700eed19534b)

### 3. Gameplay Telemetry & Interaction Cost
Objective behavioral data collected during the experiment. This section analyzes time spent on tasks, total mouse clicks, and total mouse distance, highlighting the physical efficiency of each mechanic.
![NASA-TLX Workload Profile](https://github.com/user-attachments/assets/878e739b-48b1-4c78-b8a8-54a4509f975c)

### 4. Subjective Workload (NASA-TLX)
A detailed breakdown of the subjective workload experienced by participants using the NASA-TLX framework, showcasing the crucial trade-off between mental and physical demand.
![Gameplay Screenshots](https://github.com/user-attachments/assets/445316dc-8923-4e94-bc6f-7d5186825862)

---

## 🔬 Methodology & Data
* **Testing Method:** A/B Testing (Between-subjects design with 15 users per group).
* **Objective Metrics:** Task completion time, total clicks, mouse distance (px), memory test scores.
* **Subjective Metrics:** Modified NASA-TLX for evaluating mental demand, physical demand, time pressure, performance, effort, and frustration.

## 🛠️ Tools & Technologies Used
* **Power BI:** Data visualization, DAX measures, and UI/UX dashboard design.
* **Godot Engine (GDScript):** Development of the 2D logic game and the custom telemetry logging system.
* **Data Processing:** Power Query (cleaning and shaping raw gameplay `.tres` logs and Google Forms survey results).

---
*Feel free to download the `.pbix` file from this repository to interact with the dashboard directly!*
