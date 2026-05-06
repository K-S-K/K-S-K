## Hello, and welcome to my GitHub profile!

I am a software developer with 25 years of experience. The consistent pattern across those years: before any architecture was possible, there was a domain to understand — track circuits and axle physics before railway data analysis, transformer calibration factors before energy billing, reliability theory from economics literature before building a measurement methodology the software industry didn't have, wave behavior models before automated trading research, quaternion mathematics and attitude control theory before spacecraft simulation.

The software was never the first thing. Understanding the domain was.

Right now I am finishing a simulation of the Gaia telescope's Attitude and Orbit Control System at the Astronomisches Rechen-Institut, Heidelberg University — a research instrument the team uses to test ideas for the next-generation telescope mission.

---

## Recent work

### [Gaia telescope AOCS Software Digital Twin (2024–2026)](https://github.com/K-S-K/CV/blob/main/Articles/36_GaiaSDT/Article.md)

Scientists had developed ideas for improving attitude control for the next telescope generation but needed a complete simulation to test them. The existing partial implementations — Python and Java modules built independently by different researchers — had never run together. I learned the full control loop: scanning law, inertial rotation, disturbances, star tracker, Kalman filtering, micro propulsion. The hardest conceptual challenge: the controller never knows what it actually did — it fires the thrusters and watches whether the stars shift the way they were expected to. Getting the three-way separation between commanded torque, applied torque, and observable effect right was the foundation of the entire architecture.

![SDT](https://github.com/K-S-K/CV/blob/main/Articles/36_GaiaSDT/Images/Fig_01_SDT-UI-Q.png)

### [WissensNest — Local AI Assistant (2026)](https://github.com/K-S-K/CV/blob/main/Articles/37_LocalAI/Article.md)

A personal AI assistant running entirely locally on a MacBook Pro M3. The motivation was ownership, reproducibility, and the need to control the full prompt stack for research-adjacent work. Building it produced a conceptual insight I find more useful than "it's just statistics": an LLM is a *Chemical computer* — fast, associative, pattern-driven. The surrounding framework — project system, prompt architecture, tool integration — is the *Logical computer*. The two together may be more capable than either alone. That is still a hypothesis. Testing it is part of why the project continues.

![WissensNest](https://github.com/K-S-K/CV/blob/main/Articles/37_LocalAI/Images/Fig_05_UI_Buber.png)

### [FreeRTOS-based timer on RP2350 (2025)](https://github.com/K-S-K/Pico-Timer-2)

A hardware timer project: buttons, buzzer, 4×7-segment display, FreeRTOS task scheduling on the RP2350. The goal was hardware-level understanding — not to collect a credential, but to add embedded thinking to the software background I already have.

![Timer](https://github.com/K-S-K/Pico-Timer-2/blob/main/Doc/Pico2-timer-menu.gif)

---

## What I want to work on

Real problems where the domain is what matters — science, instrumentation, embedded systems, critical infrastructure. Places where correct answers depend on understanding the physics or the engineering, not just the requirements.

---

*Photography (with a real camera), traveling, and more microcontrollers — these happen in the time that remains.*

The **[full project gallery](https://github.com/K-S-K/CV/blob/main/README.md#project-gallery)** covers 25 years of work across all domains.
