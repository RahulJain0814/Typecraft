# ⌨️ Typecraft

### Modern Typing Practice & Performance Analysis Web App

**Typecraft** is an interactive web-based typing practice application designed to help users improve their **typing speed, accuracy, consistency, and error awareness** through timed practice sessions and detailed performance analysis.

Users can practice with built-in text, paste their own content, or upload documents/images from which readable text can be extracted for typing practice.

---

## ✨ Features

* 🎯 **Typing Practice** — Practice typing with interactive passages.
* 📄 **Custom Content** — Paste your own text or upload supported files.
* 🤖 **AI-Assisted Text Extraction** — Extract readable text from uploaded PDFs and images using the Anthropic API.
* 📚 **Passage Selection** — Uploaded content is divided into individual passages that can be selected for practice.
* ⚙️ **Multiple Typing Modes**

  * Raw Text
  * Words Only
  * Words + Numbers
  * Words + Punctuation
  * Words + Numbers + Punctuation
  * Commas & Periods Focus
* ⏱️ **Timed Sessions** — Practice through different time-based sessions.
* ⚡ **Quick Practice** — Generate random practice rounds with Easy, Medium, and Hard difficulty levels.
* 📊 **Real-Time Statistics**

  * Words Per Minute (WPM)
  * Accuracy
  * Words Typed
  * Errors
  * Characters Typed
* 🎨 **Character-Level Feedback** — Characters are visually identified as correct, incorrect, or pending while typing.
* 🔄 **Automatic Passage Progression** — Move through selected passages during a session.
* 📈 **Detailed Results** — Analyze your performance after completing a session.
* 🔤 **Mistake Analysis** — Identify frequently missed characters and view their accuracy.
* ⌨️ **Keyboard Shortcuts**

  * `Tab` — Skip to the next passage
  * `Esc` — Restart the current session

---

## 🛠️ Tech Stack

| Technology        | Purpose                                        |
| ----------------- | ---------------------------------------------- |
| **HTML5**         | Application structure                          |
| **CSS3**          | Styling, layout, and responsive interface      |
| **JavaScript**    | Application logic and typing engine            |
| **SVG**           | Interface icons and visual elements            |
| **Google Fonts**  | Typography                                     |
| **Anthropic API** | Text extraction from uploaded documents/images |

---

## 🔄 How Typecraft Works

```text
        ┌─────────────────────┐
        │      User Input     │
        └──────────┬──────────┘
                   │
        ┌──────────▼──────────┐
        │ Paste Text / Upload │
        │   PDF / Image / TXT │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │ Text Extraction     │
        │ & Processing        │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │ Passage Generation  │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │ Select Practice     │
        │      Mode           │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │ Typing Session      │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │ Real-Time Metrics   │
        │ WPM / Accuracy /    │
        │ Errors / Characters │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │ Performance Report  │
        └─────────────────────┘
```

---

## 📊 Performance Analysis

After completing a typing session, Typecraft provides a detailed performance summary including:

* **Words Per Minute (WPM)**
* **Typing Accuracy**
* **Total Words**
* **Total Errors**
* **Total Characters**
* **Practice Time**
* **Typing Mode**
* **Most Frequently Missed Characters**
* **Per-Character Accuracy**

This allows users to understand not only their typing speed but also the areas where they make the most mistakes.

---

## 📁 Supported Content

Typecraft is designed to work with different types of practice material, including:

* `.txt`
* `.pdf`
* `.png`
* `.jpg`
* `.webp`

Uploaded content can be processed into practice passages so users can type material that is relevant to them.

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/typecraft.git
```

### 2. Open the project

Navigate to the project directory:

```bash
cd typecraft
```

### 3. Run the application

Open the HTML file in a modern web browser.

For the best development experience, you can also use a local development server such as VS Code Live Server.

---

## 🔑 API Configuration

Typecraft uses the **Anthropic API** for AI-assisted text extraction from uploaded documents and images.

If your version of the project requires an API key, configure it according to your implementation.

> ⚠️ **Important:** Never upload or commit your private API key to GitHub.

Do not place real API keys directly inside publicly accessible frontend JavaScript.

---

## 🎮 Quick Practice

Typecraft also provides a **Quick Practice** mode for users who want to start typing immediately without uploading their own material.

Users can select different difficulty levels:

* 🟢 Easy
* 🟡 Medium
* 🔴 Hard

The application generates a practice round and calculates performance metrics in real time.

---

## 🎯 Project Goals

The main goals of Typecraft are to:

* Improve typing speed
* Increase typing accuracy
* Help users identify recurring typing mistakes
* Provide customizable typing material
* Make typing practice more interactive
* Provide meaningful performance feedback

---

## 🔮 Future Improvements

Possible future improvements include:

* User accounts and personalized profiles
* Persistent typing history
* Performance charts and progress tracking
* Leaderboards
* More typing languages
* Additional typing exercises
* Cloud-based progress synchronization
* Advanced analytics
* Personalized practice recommendations
* Improved document processing

---

## 💡 What I Learned

Building Typecraft involved working with:

* DOM manipulation
* JavaScript event handling
* Real-time application state
* Typing-speed calculations
* Character-level validation
* File handling in the browser
* API integration
* Dynamic UI updates
* Responsive web design
* Performance analysis and data visualization concepts

---

## 📸 Screenshots

Add screenshots of the application here:

```text
screenshots/
├── home.png
├── practice.png
├── quick-practice.png
└── results.png
```

Example:

```markdown
![Typecraft Home](screenshots/home.png)

![Typing Practice](screenshots/practice.png)

![Performance Results](screenshots/results.png)
```

---

## 👨‍💻 Author

**Rahul Jain**

Built as a web development project to explore interactive JavaScript applications, API integration, and real-time performance tracking.

---

## ⭐ Support

If you find the project useful, consider giving the repository a ⭐ on GitHub.
