# 🌟 AI Content Generator

AI Content Generator is a Flask-based web application that uses OpenAI's GPT models to generate **daily viral content, captions, quotes, and ideas** in both **English + Hindi**.  
Perfect for Instagram Reels, YouTube Shorts, and Social Media Creators. 🚀

---

## ✨ Features
- Generate **English + Hindi viral captions & quotes**.
- Simple and clean **web UI**.
- Built using **Flask + OpenAI API**.
- Secure API key management with `.env`.

---

## 📂 Project Structure

```
ai-content-generator/
│
├── app.py               # Main Flask application
├── requirements.txt     # Python dependencies
├── templates/
│   └── index.html       # Main HTML page
├── static/
│   ├── style.css        # CSS for UI
│   └── script.js        # (Optional) JS for UI features
├── .env                 # Environment variables (not committed)
└── README.md            # Project documentation
```
- **app.py**: Handles routes, OpenAI API interaction, and rendering the UI.
- **templates/**: Jinja2 HTML templates for web pages.
- **static/**: CSS/JS assets for styling and interactivity.
- **.env**: Store your OpenAI API key here as `OPENAI_API_KEY=...` (never share this!).

---

## 🚀 Getting Started

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/ai-content-generator.git
    cd ai-content-generator
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up environment variables:**
    - Create a `.env` file in the root directory.
    - Add your OpenAI API key:
      ```
      OPENAI_API_KEY=your_openai_api_key_here
      ```

4. **Run the application:**
    ```bash
    python app.py
    ```
    > The app will start on [http://localhost:5000](http://localhost:5000)

---

## 📝 Usage

- Enter your content idea or theme in the input box.
- Choose **English**, **Hindi**, or **Both** for content language.
- Click **Generate** to get viral captions, quotes, or short content ideas.
- Copy and use them in your reels, shorts, or posts!

---

## 🔐 Security

- Your OpenAI API key is loaded securely from a `.env` file.
- **Never** commit your `.env` or API keys to version control.

---

## 🙌 Credits

Built with [Flask](https://flask.palletsprojects.com/) and [OpenAI GPT](https://platform.openai.com/docs/).

---

## 📜 License

MIT License
