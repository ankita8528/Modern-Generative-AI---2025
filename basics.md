# Generative AI — Basic Introduction

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

##  What is a Prompt?
In the world of LLMs (Large Language Models), a **Prompt** is the input or instruction you provide to guide the model’s response.

Think of it as **"asking the model a question"** — and how well you ask determines how good the answer will be.


### Why Prompts Matter and is the Heart of Generative AI?
A small change in your prompt can significantly affect the model's output.

### 🔁 Example:

#### 👉 Prompt 1:
**What is Generative AI?**

**ChatGPT's Response:**
> Generative AI (Generative Artificial Intelligence) refers to a class of AI models designed to generate new content — such as text, images, audio, video, or code — that mimics human creativity. These models learn patterns from existing data and use that knowledge to produce original outputs.

 > 🔍 In Simple Terms:
 > Generative AI can create things, not just analyze or classify them.
 > It answers prompts like:
 
 > “Write me a poem.”

 > “Generate a photo of a sunset in Tokyo.”

 > “Create a voiceover in Morgan Freeman's style.”
 
 > 🧠 How It Works:
 > Generative AI models are typically based on:

 > Large Language Models (LLMs) like GPT, which generate human-like text.

 > Diffusion Models (e.g., used in DALL·E, Midjourney) for image generation.

 > Transformers, a neural network architecture that revolutionized generative tasks.

 > They are trained on huge datasets from books, code, images, internet content, etc.

> ## 📌 Popular Applications:

> | Type  | Example Tools                          | What It Creates                     |
> |-------|----------------------------------------|--------------------------------------|
> | Text  | ChatGPT, Claude, Gemini                | Emails, articles, stories, code     |
> | Image | DALL·E, Midjourney, Stable Diffusion   | Art, designs, product images        |
> | Audio | ElevenLabs, Voicemod                   | Synthetic voices, music             |
> | Video | Sora (OpenAI), Runway                  | Short films, animations             |
> | Code  | GitHub Copilot                         | Auto-generated code                 |

 
 > 💡 Use Cases:
 > Content creation (blogs, marketing)

 > Customer service chatbots

 > Virtual assistants

 > Game design

 > Personalized education

> Drug discovery

> Simulation and prototyping

> ⚠️ Risks & Challenges:
> Misinformation (deepfakes, fake news)

> Copyright concerns

> Bias in generated content

> Ethical use and accountability
#### 👉 Prompt 2:
**Explain what is generative AI in a layman's language in less than 100 words.**

**ChatGPT's Response:**
> Generative AI is a type of technology that can create new things like text, images, music, or videos—just like humans do. It learns from large amounts of existing data (like books, pictures, or conversations) and then uses that knowledge to make something new. For example, you can ask it to write a story, draw a picture, or answer questions, and it will generate a response that feels natural and creative.

🧠 Notice how both prompts asked the same question—but the way the prompt was written changed the style, tone, and depth of the answer.

That’s the power of **prompting**.

A good prompt improves model performance. A bad prompt can misguide it.

And that’s exactly why **Prompt Engineering** is considered the **heart of GenAI**.

> ⚠️ NOTE: Even with the same prompt, different outputs can occur depending on the model version, temperature, and other parameters (these terms will be covered in the later blogs).

🚀 Now that you’ve understood the basics, let’s move forward to the next building block of Generative AI — **Prompt Engineering**.
