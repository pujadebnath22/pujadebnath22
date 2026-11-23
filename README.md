from pathlib import Path

content = """<div align="center">

# Hi 👋, I'm Puja Debnath

### Computer Science and Design Student
**Software Development · Artificial Intelligence · UI/UX Design**

Building useful software and exploring the intersection of technology, AI, and design.

[![GitHub](https://img.shields.io/badge/GitHub-pujadebnath22-181717?style=for-the-badge&logo=github)](https://github.com/pujadebnath22)
[![DevPilot](https://img.shields.io/badge/Featured_Project-DevPilot-6C63FF?style=for-the-badge)](https://github.com/pujadebnath22/DevPilot)

</div>

---

## 👩‍💻 About Me

- 🎓 Computer Science and Design student
- 🔭 Building **[DevPilot](https://github.com/pujadebnath22/DevPilot)**, an AI-powered codebase assistant
- 🌱 Exploring backend development, AI integration, and UI/UX design
- 💡 Interested in problem-solving and creating user-friendly digital experiences

## 🧰 Skills & Technologies

| Area | Technologies |
|---|---|
| **Languages** | Java, Python, JavaScript, SQL |
| **Backend** | Spring Boot, REST APIs |
| **Frontend** | Next.js, HTML, CSS |
| **Databases** | PostgreSQL, MySQL, pgvector |
| **AI** | Gemini, Retrieval-Augmented Generation (RAG) |
| **Design** | Figma, UI/UX Design, Prototyping |
| **Tools** | Git, GitHub, Docker, VS Code |

## 🚀 Featured Project

### [DevPilot](https://github.com/pujadebnath22/DevPilot)

An AI-powered codebase assistant that uses **RAG and Gemini** to help developers understand and explore code through natural-language conversations.

**Tech stack:** Java · Spring Boot · Next.js · Gemini · PostgreSQL · pgvector

[View the DevPilot repository →](https://github.com/pujadebnath22/DevPilot)

## 📈 GitHub Stats

<div align="center">

[![GitHub Stats](https://github-readme-stats.vercel.app/api?username=pujadebnath22&show_icons=true&hide_border=true&rank_icon=github)](https://github.com/pujadebnath22)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=pujadebnath22&layout=compact&hide_border=true)](https://github.com/pujadebnath22)

</div>

## 🤝 Connect With Me

- **GitHub:** [@pujadebnath22](https://github.com/pujadebnath22)
- **LinkedIn:** Add your LinkedIn profile URL
- **Email:** Add your professional email address

---

<div align="center">

*Building at the intersection of technology, AI, and design.* 🚀

</div>
"""

path = Path("/mnt/data/README.md")
path.write_text(content, encoding="utf-8")
print(f"Created corrected Markdown README: {path}")
