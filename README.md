# Student Success & Resource Management Simulation

### [ Live WebGL Demo 🥏](https://bilbanzania.github.io/Study-Abroad-Unity-Project_WebGL/)

A dynamic WebGL simulation built in Unity to model the impact of resource availability on student academic performance and behavior. This project was originally developed as part of a study abroad program at Waseda University (早稲田大学) in Tokyo, Japan.

## The Pitch

In any system, whether it's a university, a corporate campus, or a public service, the availability of key resources directly impacts user success and satisfaction. This simulation provides a visual model of this dynamic.

By observing autonomous AI agents, users can understand the tangible consequences of resource scarcity. It answers the question: **"What is the return on investment for improving our facilities?"** The model demonstrates how insufficient study space can lead not only to decreased academic success (lower GPA) but also to alternative, non-productive behaviors (students leaving to spend money elsewhere, in this case the arcade).

This tool can be used to justify infrastructure investment, optimize resource allocation, and visually communicate complex behavioral data to decision-makers.

## Simulation Mechanics

This is an **AI-driven simulation**. There are no direct controls over the agents; their actions are based on a set of rules and the state of the environment.

* **Primary Goal:** AI agents attempt to find available study rooms to increase their GPA.
* **Resource Scarcity:** The number of study rooms is limited. Agents may have to wait for a space to become available.
* **Behavioral Outcomes:**
    * **Success:** An agent finds a room and studies, causing their **GPA to increase**.
    * **Frustration:** An agent is forced to wait for a room, causing their **GPA to decrease** due to wasted time.
    * **Abandonment:** If no rooms are available after a certain time, the agent gives up, goes to an **arcade, and spends money**, representing a complete loss of productive time.

**Your role is to observe, adjust simulation parameters, and analyze the results.**
* **Use the scenario slider** to instantly change conditions from a "Good Case" (high resource availability) to a "Worst Case" (extreme resource scarcity) and observe the impact on agent behavior.
* Use the **[Mouse Buttons/Arrow Keys]** to move the camera and view the simulation from different perspectives.

## Development

This simulation was developed using **Unity 6.1**. The core technical challenge was programming the AI agents' decision-making logic to accurately model these behavioral outcomes. It serves as a practical application of simulation technology to solve real-world business and logistical problems.

---
*Developed by [Bilbanzania]*
