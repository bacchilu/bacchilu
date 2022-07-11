### Hi there 👋

I manly work with React, ES6 and Python3, from top to bottom...

<!--
**bacchilu/bacchilu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

```python3
from dataclasses import dataclass
from enum import Enum


class Position(Enum):
    SW_ENGINEER = "Software Engineer"
    SW_ARCHITECT = "Software Architect"


@dataclass
class ContactInfo:
    email: str
    phone: str


@dataclass
class Me:
    full_name: str = "Luca Bacchi"
    contact: ContactInfo = ContactInfo(email="bacchilu@gmail.com", phone="+39 347 4846411")
    position: Position = Position.SW_ENGINEER
    github: str = "https://github.com/bacchilu"
    skills: list[str] = ["Python3", "ReactJS"]
```
