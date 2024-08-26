# Awesome-Mobile-Agent


## Base Model

- CogVLM: Visual Expert for Pretrained Language Models**
- MiniCPM
- LLaVA-NeXT
- LLaVA-OneVision: Easy Visual Task Transfer

## Framework

- Vision-Language Models as Decision-Making Agents
- **CogAgent: A Visual Language Model for GUI Agents**
- AppAgent: Multimodal Agents as Smartphone Users
- Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception
- **ScreenAI: A Vision-Language Model for UI and Infographics Understanding**
- TRAINING A VISION LANGUAGE MODEL AS SMARTPHONE ASSISTANT
- UFO: A UI-Focused Agent for Windows OS Interaction
- OS-Copilot: Towards Generalist Computer Agents with Self-Improvement
- AGENTOHANA: Designing a Unified Data and Training Pipeline for Effective Agent Learning

**Potential Directions**:

1. Develop a cross-attention mechanism for multimodal history in reinforcement learning (RL) to enhance the interaction between vision-language pairs, possibly by mimicking an autoregressive process or using visual SFT for multi-turn dialogue.
   
2. Create a vision encoder sensitive to mobile elements. Consider using click-through rates or text-guided attention to induce MAE (Masked Autoencoder) self-supervision for controlling components.
   
3. Build a complete pipeline focused on Mobile data. This is currently the most needed direction and could yield very stable results.

## Dataset

- Scaling Instructable Agents Across Many Simulated Worlds (2017)
- MiniWoB++ / Success Rate (2022)
- MoTIF: A Dataset for Interactive Vision-Language Navigation with Unknown Command Feasibility (2023)

These two datasets are similar in tasks but differ in data format—one involves cross-website tasks, and the other focuses on fixed website tasks.

- **MIND2WEB: Towards a Generalist Agent for the Web** (2023)
- WebArena: A Realistic Web Environment for Building Autonomous Agents (2023)
- **Android in the Wild: A Large-Scale Dataset for Android Device Control** (2024)

  - This AITW dataset is currently the highest quality, but there are several issues, including a lack of subtask analysis and explanation. It doesn't follow the format of visual SFT, though it could be improved.

- ANDROIDWORLD / Success Rate
- OSWORLD: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments / Success Rate
- SeeClick: Harnessing GUI Grounding for Advanced Visual GUI Agents (ACL2024)
- Screen Agent (ACL2024)
- OmniACT: A Dataset and Benchmark for Enabling Multimodal Generalist Autonomous Agents for Desktop and Web / Sequence score
- Ferret-UI: Grounded Mobile UI Understanding with Multimodal LLMs
- AutoUI: You Only Look at Screens: Multimodal Chain-of-Action Agents (ACL2024)
- GUI-WORLD: A Dataset for GUI-oriented Multimodal LLM-based Agents
- **DigiRL: Training In-The-Wild Device-Control Agents with Autonomous Reinforcement** (NIPS2024)
- TRAINING A VISION LANGUAGE MODEL AS SMARTPHONE ASSISTANT (ICLR 2024)
- **Octo-planner: On-device Language Model for Planner-Action Agents**
- **AppWorld: A Controllable World of Apps and People for Benchmarking Interactive Coding Agents** (ACL2024)
- **WebVoyager: Building an End-to-End Web Agent with Large Multimodal Models** (ACL2024)
- **Mobile-Bench: An Evaluation Benchmark for LLM-based Mobile Agents** (ACL2024)
- **Tuning Large Multimodal Models for Videos using Reinforcement Learning from AI Feedback** (ACL2024)
- **VisualWebArena: Evaluating Multimodal Agents on Realistic Visually Grounded Web Tasks** (ACL2024)
- **WebCanvas: Benchmarking Web Agents in Online Environments**
- **MobileAgentBench: An Efficient and User-Friendly Benchmark for Mobile LLM Agents**
- GUICourse: From General Vision Language Model to Versatile GUI Agent
- **CoCo-Agent: A Comprehensive Cognitive MLLM Agent for Smartphone GUI Automation**
