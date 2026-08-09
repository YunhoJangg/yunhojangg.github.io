---
layout: default
---
## 장윤호 (Jang Yunho, 張允豪) | 💮 KNU CSE 25

### 📚 Education
- **2024. 03. - 2025. 01.**  |  **충북대학교 전자정보대학 컴퓨터공학과**
- **2025. 03. -**  |  **경북대학교 IT대학 컴퓨터학부 글로벌SW융합전공**

### 💻 Tech Stack
- **Languages**: C, Java, Python, Dart
- **Mobile / Frontend**: Flutter
- **Tools**: Git, GitHub

### 📂 Projects
- **2024. 11. - 2024. 12.**  |  **Code Ground (https://github.com/IngyoKim/Code_Ground)** - **UI / UX 디자인 총괄**
- **2025. 11.**  |  **찍먹 (Jjikmuk) (https://github.com/jungminmobile/Iwantfirst)** - **UI / UX 디자인 담당**

### 📬 Contact
* **Instagram**  |  @u_know1104
* **E-Mail** | yunho2066@knu.ac.kr
---
# 최근 글

{% for post in site.posts limit:10 %}
## [{{ post.title }}]({{ post.url | relative_url }})

{{ post.date | date: "%Y-%m-%d" }}

{{ post.excerpt }}

{% endfor %}
