### Hi there š

I manly work with React, ES6 and Python3, from top to bottom...

<!--
**bacchilu/bacchilu** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
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
    contact=ContactInfo(email="bacchilu@gmail.com", phone="+39 347 4846411"),
    position=[Position.SW_ENGINEER, Position.SW_ARCHITECT],
    github="https://github.com/bacchilu",
    skills=["Python3", "ReactJS"],
)
```
