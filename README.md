# 📚 AI Language Library & Reader

**AI Language Library & Reader** is a modern web-based e-book reader designed for language learners. It transitions readers from textbooks to original literature by using **GPT-4o-mini** to provide deep linguistic context instead of simple word-to-word translations.

---

## 🌟 Key Features

* **Multi-Format Support:** Seamlessly read books in `.epub`, `.pdf`, and `.txt` formats.
* **Contextual AI Translation:** Highlight or click any word to receive a comprehensive breakdown powered by **GPT-4o-mini**.
* **Multilingual Interface:** Supports **Ukrainian (UA)**, **English (EN)**, and **Russian (RU)** for both the UI and AI output.
* **Advanced Word Analysis:** For every selected word, the AI provides:
    * **Direct Translation:** To your chosen native language.
    * **Target Definition:** A simplified definition in the target language to encourage immersive learning.
    * **Contextual Examples:** Three example sentences demonstrating the word in real-world usage.
* **Personal Library:** * Books are stored locally in your browser using **IndexedDB**.
    * Automatically tracks and saves your reading progress for every book.
* **Reading Comfort:** * **Themes:** Light, Dark, and Sepia modes.
    * **Typography:** Adjustable font sizes.
    * **Navigation:** Smooth progress slider and page-turn controls.

---

## 🚀 Getting Started

### Prerequisites
To use the AI features, you will need an **OpenAI API Key**:
1. Create an account at [platform.openai.com](https://platform.openai.com/).
2. Add a small balance to your account in the **Billing** section.
3. Generate a Secret Key in the **API Keys** section.

### Usage
1. Open the `reader.html` file in any modern web browser.
2. Enter your **OpenAI API Key** in the header input field (the status icon will turn **green 🟢**).
3. Upload your e-book file via the **"Add Book"** button.
4. Highlight any unfamiliar word to see the AI analysis.

---

## 💡 Why GPT-4o-mini?
This app is optimized for the `gpt-4o-mini` model, which offers:
* **Speed:** Near-instant responses (1-2 seconds).
* **Cost-Effectiveness:** Highly affordable for word-by-word analysis.
* **Context-Awareness:** Understands surrounding text to provide the most accurate meaning.

---

## 📱 Mobile Experience
The reader features a specialized mobile mode. On touch devices, a floating **AI Magic Sparkle button ✨** appears upon text selection to provide a seamless translation experience without interference from native system menus.

---

## 🛠 Tech Stack
* **Frontend:** HTML5, Tailwind CSS, FontAwesome.
* **Libraries:** `epub.js` (Epub rendering), `pdf.js` (PDF support), `jszip` (Archive handling).
* **Storage:** IndexedDB for local book and cache management.
* **API:** OpenAI Chat Completions (`gpt-4o-mini`).

---

## 🛡 Privacy First
Your privacy is guaranteed. Your **OpenAI API Key** and **books** are stored strictly in your browser's local storage (`localStorage` and `IndexedDB`). Data is only sent to OpenAI's servers for the specific words you choose to analyze.

## 💵 Donates
* EVM:
**0x46D7074095982a7635a2A069fe900738FEe443f1**
* SOL:
**G3Peo2KJuZEUkYE5e6Ly8WxizqJXCAZs9oJ5qhc8vDrx**

---
*Created for learners who want to master English by reading what they love.*
