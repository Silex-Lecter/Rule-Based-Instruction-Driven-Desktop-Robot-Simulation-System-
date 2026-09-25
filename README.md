# Rule-Based-Instruction-Driven-Desktop-Robot-Simulation-System-
# Overview
This project realizes an embodied AI closed-loop system demonstrating the process of "Language — Planning — Action — Feedback".

Instead of training heavy Large Language Models (LLMs), the system employs keyword matching and rule parsing to interpret multi-step Chinese natural language instructions. The parsed commands are converted into structured task pipelines, which are then executed by a desktop pusher robot with simplified kinematics in a PyBullet simulation environment.
