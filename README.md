# Visual-Recognition-App-for-Elderly-Cognitive-Support
An AI-powered mobile–PC integrated application that helps elderly users understand objects, packages, and medicines through image recognition and local LLaMA reasoning — all running offline via local Wi-Fi.

# Introduction
Introduction
In aging societies, many seniors struggle with everyday cognitive difficulties such as:

“What is this product for?”

“Can I eat this? The text is too small to read.”

“This package has only foreign words — is it safe?”

These small but frequent challenges create psychological anxiety, reduce independent living ability, and may even lead to accidental misuse of medicines or food.
To address this issue, SKYNET provides a vision-based cognitive assistance system that explains real-world objects in simple, easy-to-understand language.
Users only need to take a photo — the system automatically analyzes the image using a locally installed LLaMA model on their home PC, evaluates potential health or safety risks, and returns the explanation instantly to their smartphone.

# System Overview
SKYNET consists of two connected components working together over local Wi-Fi:

Component	Description
 Mobile App	Simple camera interface for elderly users — takes photos and displays AI responses.
 Local LLaMA Server	Runs on a nearby PC; processes received images, performs visual analysis, and generates text explanations using a fine-tuned LLaMA model.

# Team
This project is organized by an interdisciplinary team of doctoral and master's students, with each member contributing based on their respective areas of expertise.

- **Fuzuki Tasaka (Project Lead)** – Oversees overall project direction, system implementation, and agent behavior evaluation.  
  Acts as a bridge between development and real-world deployment by conducting usability testing and improving prototypes. Also contributes directly to coding and practical integration.  
  *Kobe University*

- **Hang Xingchen** – Responsible for system architecture design, including the integration of LLMs, robotic control, and multimodal coordination (vision, voice, behavior).  
  *Kobe University*

- **Haruki Maruyama** – In charge of prompt engineering and market research. Optimizes dialogue flow in Japanese and ensures the system aligns with user needs and social context.  
  *The University of Tokyo*

- **Taketomi Ryuichi** – Responsible for comprehensive system testing and quality assurance, ensuring robustness and reliability across various usage scenarios.  
  *Kwansei Gakuin University*

⚙️ Workflow
📱 Smartphone
   ↓ ① Take photo (food / medicine / product)
🌐 Local Wi-Fi Connection
   ↓ ② Send image to PC
💻 Laptop with LLaMA
   ↓ ③ LLaMA performs reasoning with custom elderly-friendly prompts
   ↓ ④ Generates plain-language explanation + health assessment
📱 Smartphone
   ↓ ⑤ Receives and displays results instantly


| Comparison Item          | **SKYNET**                                             | Google Lens            | ChatGPT + Image Input       |
| ------------------------ | ------------------------------------------------------ | ---------------------- | --------------------------- |
| **Target Users**         | Elderly / cognitive impairment                         | General users          | General users / developers  |
| **Recognition Ability**  | Image recognition + elderly-specific reasoning prompts | Object / translation   | High-precision but generic  |
| **Output Style**         | Simple Japanese or English text, no Markdown           | Keyword cards          | Complex, often verbose      |
| **Operation**            | Fully automatic after capture                          | Requires manual search | Needs image upload via chat |
| **Special Function**     | Local reasoning + health safety evaluation             | Translation / shopping | General dialogue only       |
| **Elderly Adaptability** | Very high (1-click use)                                | Moderate               | Low – complex interface     |

<img width="393" height="875" alt="image" src="https://github.com/user-attachments/assets/543dc036-9578-42e8-92b9-782fc338a859" />
<img width="392" height="867" alt="image" src="https://github.com/user-attachments/assets/c6e2e2af-4974-4a83-8d55-391d3b240b76" />
<img width="390" height="868" alt="image" src="https://github.com/user-attachments/assets/33029b4a-e640-4eee-9438-a3be8fc767ad" />
<img width="400" height="867" alt="image" src="https://github.com/user-attachments/assets/92a8311a-7111-429e-871c-6a962b975041" />



   
