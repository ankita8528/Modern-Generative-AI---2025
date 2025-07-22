# Generative AI — Basics

Before diving into the building blocks of Generative AI, it's important to establish a strong foundation — especially for those who are new to the field or coming from a Machine Learning background.

This document covers the key concepts you need to understand before jumping into advanced topics like Prompt Engineering, RAG, Agents, and Fine-Tuning.

---

### What is Generative AI?
A system that can generate new data based on training sample (similar as the input/independent features in Machine Learning). Generative models can generate image, text, audio, video, etc. data as output.
#### Key Types:
- **Generative Image Models** – Generate realistic or artistic images.
- **Generative Language Models (LLMs)** – Generate coherent and contextual text.

---

### What is LLM?
LLM stands for Large Language Model (Generative Language Model) that generates text/image/audio/video. Examples of LLMs - ChatGPT, Google Gemini, Meta Llama, DeepSeek, Claude etc.
Similar to a Machine Learning models like linear regression, xgboost,etc., we need to train an LLM too and for that we need to provide a huge amount of training data. After the LLM gets trained on the data we can ask the LLM to generate any kind of text/image/audio/video, and the "ask" thing is nothing but "Prompt".

---

### What is Prompt?

In the world of LLMs, a **Prompt** is the input or instruction you provide to guide the model’s response.
> Think of it as "asking the model a question" — and how well you ask determines how good the answer will be.
Here's an example of how important is prompt and how it can change a model's (LLM's) output.
> Prompt1 - What is generative ai?
> ChatGPT's response - Generative AI (Generative Artificial Intelligence) refers to a class of AI models designed to generate new content — such as text, images, audio, video, or code — that mimics human creativity. These models learn patterns from existing data and use that knowledge to produce original outputs.

🔍 In Simple Terms:
Generative AI can create things, not just analyze or classify them.
It answers prompts like:

“Write me a poem.”

“Generate a photo of a sunset in Tokyo.”

“Create a voiceover in Morgan Freeman's style.”

🧠 How It Works:
Generative AI models are typically based on:

Large Language Models (LLMs) like GPT, which generate human-like text.

Diffusion Models (e.g., used in DALL·E, Midjourney) for image generation.

Transformers, a neural network architecture that revolutionized generative tasks.

They are trained on huge datasets from books, code, images, internet content, etc.

📌 Popular Applications:
Type	Example Tools	What It Creates
Text	ChatGPT, Claude, Gemini	Emails, articles, stories, code
Image	DALL·E, Midjourney, Stable Diffusion	Art, designs, product images
Audio	ElevenLabs, Voicemod	Synthetic voices, music
Video	Sora (OpenAI), Runway	Short films, animations
Code	GitHub Copilot	Auto-generated code

💡 Use Cases:
Content creation (blogs, marketing)

Customer service chatbots

Virtual assistants

Game design

Personalized education

Drug discovery

Simulation and prototyping

⚠️ Risks & Challenges:
Misinformation (deepfakes, fake news)

Copyright concerns

Bias in generated content

Ethical use and accountability

Let me know if you'd like a visual, code-level explanation, or specific examples in any domain (e.g., healthcare, marketing, gaming).
Prompting is the first and most fundamental building block in working with Generative AI — and leads us into the topic of **Prompt Engineering**, which we’ll cover next.
> Prompt2 - Explain what is generative ai in a layman's language in less than 100 words.
> ChatGPT's response - Generative AI is a type of technology that can create new things like text, images, music, or videos—just like humans do. It learns from large amounts of existing data (like books, pictures, or conversations) and then uses that knowledge to make something new. For example, you can ask it to write a story, draw a picture, or answer questions, and it will generate a response that feels natural and creative.
> There is a noticable difference between the reponses of both the prompt, although I have asked the same question in both the prompts with few modifications. This is how any LLM is heavily dependent on the way the prompt is written. Prompting could lead to better performance of the model as well as can also degrade its behavior. And this is the reason why prompt engineering is called the heart of Generative AI.


So, now that we have read the basic required things, we can proceed with the first building block of Generative AI - Prompt Engineering.
