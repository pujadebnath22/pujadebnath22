from pathlib import Path

content = """# Hi 👋, I'm Puja Debnath

### Computer Science and Design Student | Software Development • AI • UI/UX

I'm a Computer Science and Design student interested in building useful software, exploring AI-powered applications, and creating user-friendly digital experiences.

- 🔭 Currently building **DevPilot**, an AI-powered codebase assistant
- 🌱 Exploring Java, Spring Boot, AI integration, and UI/UX design
- 💻 Interested in Data Structures & Algorithms and software engineering
- 🎨 Enjoy combining technology with thoughtful user experiences

---

## 🛠️ Skills & Technologies

- **Languages:** Java, Python, JavaScript, SQL
- **Backend:** Spring Boot, REST APIs
- **Frontend:** Next.js, HTML, CSS
- **Database:** PostgreSQL, pgvector, MySQL
- **AI:** Gemini, Retrieval-Augmented Generation (RAG)
- **Design:** Figma, UI/UX Design, Prototyping
- **Tools:** Git, GitHub, Docker, VS Code

---

## 🚀 Featured Project

### [DevPilot](https://github.com/pujadebnath22/DevPilot)

An AI-powered codebase assistant that uses **RAG and Gemini** to help developers understand and explore code through natural-language conversations.

**Tech Stack:** Java · Spring Boot · Next.js · Gemini · PostgreSQL · pgvector

[View Repository →](https://github.com/pujadebnath22/DevPilot)

---

## 🤝 Connect With Me

- 💻 GitHub: [pujadebnath22](https://github.com/pujadebnath22)
- 💼 LinkedIn: Add your LinkedIn profile URL
- 📧 Email: Add your professional email

---

*Building at the intersection of technology, AI, and design.* 🚀
"""

path = Path("/mnt/data/README.md")
path.write_text(content, encoding="utf-8")
print(f"Created {path}")
