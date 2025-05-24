DonutMSV Project Documentation

Overview

DonutMSV is a forward-thinking initiative focusing on open and semi-private AI infrastructure, intelligent tools, and terminal-based environments. Rooted in a passion for artificial intelligence, privacy, and custom operating systems, the DonutMSV ecosystem offers a collection of AI models, systems, and utilities aimed at developers, creators, and tech enthusiasts seeking independence from mainstream platforms.


---

Project Philosophy

DonutMSV believes in:

AI democratization: Making smart assistants and models accessible.

Privacy-first design: User data is kept local and encrypted.

Hybrid distribution: Some models are open-source; some are private for commercial use.

Creativity & Customization: Offering tools that are flexible and developer-friendly.



---

Key Components

1. Donut AI Models (Donut-O Series)

Custom AI models with various capabilities built using LLaMA, Gemma, and other architectures. These include:

donut-o1

Parameters: 1B

Task: Basic conversation

Availability: Public testing


donut-o2-mini

Parameters: 7B

Task: Chat + Light reasoning

Runtime: Local via Ollama

Availability: Free local runtime (not open-sourced model weights)


donut-o2

Parameters: 27B

Task: Conversational + image analysis + basic coding

Availability: Commercial


donut-o2.1

Parameters: 27B+

Subtypes: o2.1-gaming, o2.1-school

Advanced versions specialized in gaming inference and code generation


donut-o2.5

Parameters: 40b

Subtypes: o2.5-coding 70b


donut-o3-mini

Parameters: 70B

Task: Crypto trading AI, economic models

Availability: Hosted


donut-o3

Parameters: 100B+

Task: Image generation, deep reasoning, API extensions

Availability: In development



---

2. DonutOA Models

These models are powered by OpenAI and used in a more structured system under Donut’s branding with custom system prompts and role design.

donut-oa-gpt3.5

donut-oa-gpt4-mini

donut-oa-gpt4


These models are used in web chat, terminal bots, and assistant systems with attribution to OpenAI.


---

3. Donut Terminal (donut$)

A custom-built terminal interface that mimics classic Unix shells with added support for AI assistance, script automation, and Donut package management:

Install custom packages via:

donut o vim for Ubuntu packages

o donut ohack for Donut-native tools


Special directories like /donutOS/ to simulate a root environment

Integrated AI helpers



---

4. DonutOS (In Progress)

A lightweight OS powered by Ubuntu + Hyperland, targeting performance, modularity, and AI integration. It will:

Use donut$ as the primary terminal

Be developer-first

Support embedded AI tools



---

5. DonutAPI

A REST API built using Express.js and connected to local LLMs via Ollama.

Token system for usage management

Chat history persistence via JSON

Fully local or proxy-based hosting

Example endpoint: POST /chat with username and message



---

Security & Ethics

Models like donut-o2-mini encrypt local files and do not log IPs.

Commercial models are not publicly distributed to prevent abuse.

DonutMSV proudly mentions source tech such as OpenAI, LLaMA, and Ollama to respect licensing and credits.



---

Future Goals

Build an education-focused AI (o-school)

Develop a secure downloader and file-sharing app (donut-file-transformer)

Release a simplified AI playground for non-developers

Launch community features for bot developers and open collaboration



---

Final Note

DonutMSV is more than a toolset—it's a vision for the future of personal, ethical, and private AI. This document evolves as projects expand. For contributions or discussions, stay tuned for the upcoming GitHub repository.

Created by: Unknownmsv / DonutMSV

