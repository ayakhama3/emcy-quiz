# 🛡️ EMCY Quiz — "Test your digital level"

🇬🇧 English | [🇫🇷 Français](README.fr.md)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

An interactive web quiz that helps young people measure their **cybersecurity awareness**, created for **EMCY — Cyberconfidence Space Youth**. Content is in French.

## ✨ Features

- **10 scenario-based questions** on everyday digital risks: strong passwords, phishing, social-network privacy, cyberbullying and more.
- **Instant feedback**: each answer comes with a short explanation.
- **Live score** and a final profile: *Cyber Smart*, *At risk* or *Vulnerable*, with tips to improve.
- **Share your result** through the native Web Share API.
- **Dark / light theme** toggle and an animated "cyberpunk" background.
- **Zero dependencies**: plain HTML, CSS and JavaScript.

## 📁 Structure

```
emcy-quiz/
├── index.html   # Pages: home, quiz, results
├── style.css    # Themes and animations
└── script.js    # Questions, scoring and result logic
```

## 🚀 Run locally

No build step required.

```bash
git clone https://github.com/ayakhama3/emcy-quiz.git
cd emcy-quiz

# Option 1: open index.html in your browser
# Option 2: serve it locally
python -m http.server 8000     # then visit http://localhost:8000
```

## 🔭 Ideas for improvement

- Move the questions to a JSON file to make them easier to edit
- Add an English version of the quiz
- Add more questions and randomize their order

## 👩‍💻 Author

**Aya Khama** — Data Science & AI engineering student (EMSI)
[LinkedIn](https://www.linkedin.com/in/aya-khama-160752387/) · [GitHub](https://github.com/ayakhama3)
