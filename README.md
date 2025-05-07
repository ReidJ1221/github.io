
# HTML-Jordyn Reid Portfolio

The **Jordyn Reid's Portfolio** consists of a webpage with tabs that illustrate my background in terms of education, experience, skills, and includes my resume for viewing and downloading.

## 🌐 Website

Live site: [https://reidj1221.github.io](https://reidj1221.github.io)

## 📁 Project Structure

```
HTML-FGBC/
├── index.html          # Main homepage
├── about.html          # About Jordyn Reid
├── resume.html         # Includes vieweability and downloadability of my resume.
├── contact.html        # Contact form
├── projects.html       # Page that contains my projects and respective GitHub repos
├── style.css           # Main CSS styling
└── images/             # Images used in the site
```
## 🚀 Getting Started

You can clone the repo and open `index.html` in your browser:

```bash
git clone https://github.com/ReidJ1221/github.io.git
cd github.io
open index.html
```

## 🛠️ Requirements

- HTML5
- CSS3

## 🧩 How the Chatbot Works

The Dialogflow chatbot is embedded in my portfolio via the html code below:

```html
<script src="https://www.gstatic.com/dialogflow-console/fast/messenger/bootstrap.js?v=1"></script>

<df-messenger
  intent="WELCOME"
  chat-title="MyChatBot"
  agent-id="YOUR_AGENT_ID"
  language-code="en"
></df-messenger>
