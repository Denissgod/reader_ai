# reader_ai
An AI-powered web e-book reader designed for language learners. Features instant GPT-4o-mini translations, English definitions, and contextual example sentences in various tenses for effective vocabulary building.
# 📚 AI Language Learning Reader

An intelligent web-based e-book reader designed to help language learners transition to reading original literature. Instead of simple word-to-word translation, this tool leverages Artificial Intelligence to provide deep linguistic context.

## 🌟 Key Features

* **Multi-Format Support:** Read your favorite books in `.epub`, `.pdf`, or `.txt` formats.
* **Contextual AI Translation:** Click any word to receive a comprehensive breakdown powered by **GPT-4o-mini**.
* **Advanced Word Analysis:** For every word, the AI provides:
    * Direct translation to your native language.
    * A simplified English definition (ideal for immersive learning).
    * Three example sentences in different grammatical tenses (Simple, Continuous, Perfect).
* **Privacy First:** Your **OpenAI API Key** is stored locally in your browser's `localStorage`. It is never sent to any third-party server except OpenAI.
* **Reading Comfort:** Clean UI with dark mode support, adjustable font sizes, and mobile-friendly navigation.

## 🚀 Getting Started

### Prerequisites
To use the AI features, you will need an **OpenAI API Key**.
1. Create an account at [platform.openai.com](https://platform.openai.com/).
2. Add a small balance to your account (e.g., $5) in the **Billing** section.
3. Generate a Secret Key in the **API Keys** section.

### Usage
1. Open the [Live Demo](YOUR_GITHUB_PAGES_LINK_HERE) or download `reader.html` and open it in your browser.
2. Enter your API Key in the header input field.
3. Upload your e-book file.
4. Click on any unfamiliar word to see the magic happen!

## 💡 Why GPT-4o-mini?
This app is optimized for the `gpt-4o-mini` model, which is:
* **Fast:** Responses appear in 1-2 seconds.
* **Cost-Effective:** Approximately $1 per 10,000+ words translated (enough for dozens of books).
* **Context-Aware:** Unlike standard dictionaries, the AI understands the surrounding text to give the most accurate meaning.

## 🛠 Tech Stack
* **Frontend:** HTML5, Tailwind CSS, JavaScript (Vanilla).
* **Libraries:** `epub.js` (Epub rendering), `pdf.js` (PDF support), `jszip` (Archive handling).
* **API:** OpenAI Chat Completions.

---
*Created for learners who want to master English by reading what they love.*
