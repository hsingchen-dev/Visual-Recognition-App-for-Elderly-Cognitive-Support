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
📱 Mobile App	Simple camera interface for elderly users — takes photos and displays AI responses.
💻 Local LLaMA Server	Runs on a nearby PC; processes received images, performs visual analysis, and generates text explanations using a fine-tuned LLaMA model.

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

   
