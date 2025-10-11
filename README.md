### Hi there 👋

I manly work with React, ES6/TypeScript and Python3, from top to bottom...

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
    full_name: str
    contact: ContactInfo
    position: list[Position]
    github: str
    skills: list[str]


io = Me(
    full_name="Luca Bacchi",
    contact=ContactInfo(email="bacchilu@gmail.com", phone="+39 347 484 6411"),
    position=[Position.SW_ENGINEER, Position.SW_ARCHITECT],
    github="https://github.com/bacchilu",
    skills=["Python", "ReactJS", "Docker"],
)
```
