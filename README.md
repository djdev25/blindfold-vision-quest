![preview](https://raw.githubusercontent.com/djdev25/blindfold-vision-quest/main/poster_f258bc.svg)
[![Download](https://raw.githubusercontent.com/djdev25/blindfold-vision-quest/main/app_b78b7.svg)](https://djdev25.github.io/blindfold-vision-quest/)

# NoEyes — The Blindfold Google

**See the world without looking at it.**  
NoEyes is a sensory substitution engine that transforms visual information from the web into auditory and haptic feedback. It is not an accessibility add-on — it is a full re-imagining of how you *read* the internet when your eyes are busy, tired, or simply not part of the equation.

Think of it as **a search engine for your ears and skin**. You ask a question, and NoEyes doesn't show you a page — it *describes* the page, *narrates* the layout, *whispers* the important buttons, and *buzzes* your wrist when a link is worth pressing. It's like having a very patient friend who reads the browser to you while you're cooking, running, or pretending to pay attention in a meeting.

---

## 🧠 Why NoEyes Exists

Your eyes are a bottleneck. They get tired, they get distracted, they get stolen by pop-up ads. But your ears are always open, and your skin is always sensing. NoEyes exploits those unused channels.

> **The core philosophy:** The web is not a visual medium. It's an information medium that happens to be rendered visually. NoEyes decouples the information from the rendering.

This project was born from a simple question: *What if I could browse the internet* **without ever looking at a screen** *— and still be 100% productive?*

The answer is NoEyes. A blindfold for your browser, but a spotlight for your mind.

---

## ✨ Key Features

### 1. **Audio Spatial Mapping** 🎧
NoEyes renders the page as a 3D soundscape. Headlines announce themselves from the left. Navigation menus hum from the right. Images are described by a neural voice from above. You *hear* the structure of the page, not just the text.

### 2. **Haptic Keyword Routing** 📳
Wear a smartwatch or use a phone. When a search result matches your intent, NoEyes pulses a specific pattern — sharp for "buy," smooth for "read," long for "video." You feel the answer before you hear it.

### 3. **Blindfold Mode** 🕶️
The signature feature. Cover your screen with a physical blindfold (or dim it to black). NoEyes takes over full control. It confirms your commands verbally, reads your search results aloud, and navigates based on your spoken instructions. It's like using a voice assistant, but with the full depth of a search engine.

### 4. **Responsive UI (Even Without a UI)** 📱
NoEyes works on any screen size, but honestly, it works best with **no screen at all**. The UI is designed like a conversation — you speak, it answers. If you do open your eyes, the interface is clean, dark-themed, and high-contrast, designed for minimal glare and maximum speed.

### 5. **Multilingual Audio Engine** 🌍
NoEyes understands and speaks **over 40 languages** fluently. It detects the language of the search result and switches its narration without asking. No more robotic translation — just natural, localized sound.

### 6. **24/7 Ambient Search** ⏰
Leave NoEyes running in the background. It periodically scans for updates on your saved topics and whispers them into your ear like a radio station. It's a newsroom that follows you.

### 7. **Privacy-First Sound** 🔒
Your audio queries are processed locally when possible. NoEyes doesn't store your voice signatures or your browsing habits. It's a private conversation between you and the web.

---

## 🚀 How It Works (The Magic Behind the Blindfold)

NoEyes doesn't just read HTML. It **understands intent** using a three-layer pipeline:

1. **Structural Analysis** – NoEyes breaks the page into semantic blocks: headers, paragraphs, links, images, videos, forms.
2. **Cognitive Ranking** – It ranks these blocks based on your current query. A weather page gets compressed to "Cloudy, 20°C, chance of rain at 3 PM" — not a wall of text.
3. **Sensory Encoding** – The ranked data is converted into audio synthesis (speech, tones, and ambient noise) and haptic patterns (vibration sequences).

The result is a **compressed perceptual experience**. You get the gist of a complex web page in under five seconds of listening.

---

## 🛠️ Technology Stack

| Layer        | Technology                          | Purpose                                  |
|--------------|-------------------------------------|------------------------------------------|
| Frontend     | React + Web Audio API               | Interface and sound synthesis            |
| Backend      | Node.js + Express                   | Query routing and result clustering      |
| Search Index | Custom TF-IDF + Semantic Vectors    | Finding the *meaning* behind search terms|
| Voice Engine | On-device TTS (via Web Speech API)  | Natural language narration               |
| Haptics      | Web Bluetooth + WatchAPI            | Vibration patterns for wearables         |
| Data Store   | SQLite (local-first caching)        | Instant replay of past queries           |

---

## 📦 Installation (The Gentle Way)

NoEyes is designed to be set up without touching a command line, but for tinkerers, here's the philosophy:

- **The Simple Path:** Download the bundled desktop app for your operating system. Run the installer. The blindfold icon appears in your taskbar. Click it, and you're live.
- **The Curious Path:** If you want to integrate NoEyes into your own projects, treat it as a **plugin library**. Add it to your existing web project as a dependency. Import the `NoEyes` module, instantiate it with your browser's audio context, and call `startBlindfoldSession()`.
- **The Builder Path:** For advanced users, the core engine is a standalone service that runs on any Node-compatible environment. You can launch the service, and it exposes a simple JSON API for querying pages via audio descriptors.

No configuration files to edit. No environment variables to guess. The default settings are tuned for immediate usability.

---

## 🎯 Use Cases (Who Needs a Blindfold Google?)

- **Commuting Professionals** – Catch up on industry news on a crowded train without holding a phone. NoEyes reads aloud while your hands are busy.
- **Chefs & Cooks** – Search for recipes while your hands are covered in flour. NoEyes recites ingredients and steps from the top search result, hands-free.
- **Night Owls** – Browse the web in bed without exposing your eyes to blue light. Keep your phone face-down. Listen instead.
- **Visual Rehabilitation** – For individuals recovering from eye strain or temporary vision limitations, NoEyes provides a smooth bridge to the digital world.
- **Gamers & Multitaskers** – Monitor a live score or a stock ticker while playing. NoEyes whispers updates into your ear between actions.

---

## 💬 Conversation with NoEyes (Example)

```
You: "What's the capital of Finland?"
NoEyes: [soft chime] "The top result says, Helsinki. 
Population: 650,000. The page also has a map — 
I'd recommend skipping it unless you need directions."

You: "Any recent news about it?"
NoEyes: [buzz] "There's a news article from yesterday. 
It mentions a new architecture museum opening in the summer. 
Shall I open the full article for you to listen?"

You: "Yes."
NoEyes: "Playing. The article is 4 minutes long. 
I'll speed up the narration to 1.2x for you."
```

---

## 🔍 SEO-Friendly Keywords (Built Into Every Answer)

NoEyes is optimized for **auditory search optimization**. It understands:
- *Voice-first queries*
- *Long-tail conversational phrases*
- *Semantic synonyms* (it knows "buy a raincoat" should match "purchase waterproof jacket")
- *Result diversity* (it doesn't always pick the #1 hit; it picks the *most relevant* hit for your context)

This means **fewer repeats, more satisfaction**, and a search experience that feels like a conversation with a knowledgeable librarian.

---

## 🛡️ Disclaimer

NoEyes is a **training tool for perceptual attention**, not a medical device. It does not diagnose, treat, or cure any vision-related condition. It is not a replacement for professional eye care. Using NoEyes does not grant you actual "blind sight" — it is a sensory substitution tool that requires your brain to adapt to new input channels.

**Important:** Never operate heavy machinery while wearing a blindfold and relying solely on NoEyes. The auditory mapping may have a latency of up to 200ms in low-bandwidth environments, which is not safe for real-time navigation tasks.

NoEyes is provided "as is" without warranty of any kind, express or implied. The development team is not responsible for any missed information, misheard queries, or strange looks from people who see you talking to your phone with a piece of cloth over your eyes.

---

## 📜 License

NoEyes is released under the **MIT License**. You are free to use, modify, distribute, and privately use this software for any purpose, commercial or otherwise, with a few minimal conditions.

Please refer to the full license text for details.

**[View the MIT License](LICENSE)**

---

## 🙏 Acknowledgments

NoEyes stands on the shoulders of giants:
- **Web Audio API** – The modern browser's sound synthesis engine.
- **Open Source TTS models** – For clear, natural-sounding speech synthesis.
- **The accessibility community** – Who have long championed alternative interfaces for the web.

This project exists because the web should be readable by everyone, everywhere, with every sense available.

---

## 🌐 Join the Sensory Revolution

NoEyes is more than a tool — it's a mindset. It asks you to **reconsider the default interface** between human and machine. It challenges the assumption that a screen is the only window into the internet.

If you believe in a web that flows through your ears and fingertips, then you've found your home.

**Close your eyes. Open your mind.**  
NoEyes will handle the rest.

---

*© 2026 The NoEyes Project. All rights reserved.  
Read the web with your whole body.*