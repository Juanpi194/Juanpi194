# Hi there 👋

<!--
**Juanpi194/Juanpi194** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

💻 Aspiring software developer with a background in electronic engineering and currently studying at 42 Madrid.
I'm passionate about programming, problem-solving, and understanding how things work under the hood.

---
## 🚀 About me
- 🎓 Studied Electronic Engineering (Telecommunications) at UPM
- 📚 Currently studying at 42 Madrid
- 🧠 Strong technical mindset with a hands-on, self-taught approach
- ⚡ Interested in systems, backend development, and low-level programming

---
## 🛠️ Technologies

### Programming languages
[![My Skills](https://skillicons.dev/icons?i=c,cs,cpp,java,py,bash)](https://skillicons.dev)

### Tools
[![My Skills](https://skillicons.dev/icons?i=vscode,visualstudio,eclipse,godot,unity,github)](https://skillicons.dev)

### WIP
[![My Skills](https://skillicons.dev/icons?i=docker,rust,javascript)](https://skillicons.dev)

---
## 📌What I'm working on
- Improving my low-level programming skills (C/C++)
- Learning containerization with Docker
- Exploring Rust and modern systems programming
- Building practical projects to grow as a developer

---
## 🌱 Goals
To grow as a developer by working on meaningful projects and building solid, well-designed software.

---
## 📫 Contact
- [LinkedIn](https://www.linkedin.com/in/juan-pablo-vizca%C3%ADno-delgado-815b17351/?skipRedirect=true) 🐊
- Email: juanpiviz194@gmail.com

---
## 📌 42 Projects
<!-- TODO: Fill descriptions and not finished topics -->

### 🥥 Pacman ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
A **Pac-Man** arcade clone in Python — maze movement and collision, pellet and power-up logic, and ghost AI driving the classic *chase/scatter* behaviour. The **game logic was mine**; the sprites and visuals were by fellow 42 student *smarin-s*.

- 🎯 What I learned: how a game engine is structured — a **game loop** driving everything, with **managers** coordinating each part every frame.
- 🔧 Difficulty: hard

![Pacman](assets/Pacman.png)

### 📓 Libft ![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black)
A **from-scratch reimplementation** of a subset of the **C standard library** — string, memory, conversion and linked-list utilities (memcpy, strdup, atoi, strtrim, list helpers…) bundled into a **static library** (libft.a). The *foundational* 42 project: the personal **C toolbox** reused across some later projects.

- 🎯 What I learned: C syntaxis and memory management.
- 🔧 Difficulty: medium


### 🤖 RAG ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
Description...

- 🎯 What I learned: ...
- 🔧 Difficulty: hard


### 🎮 TAP ![C++](https://img.shields.io/badge/C%2B%2B-00599C?logo=cplusplus&logoColor=white)
A **multiplayer** C++ MUD — a **multithreaded TCP** server hosting a *shared world* (rooms, enemies, NPCs, quests, trading) over a **custom RFC-style line protocol**, played through interchangeable CLI and GUI clients.

- 🎯 What I learned: C++ bases, sockets and connections and structure designs.
- 🔧 Difficulty: hard

**🗺️ Map Design**

```mermaid
graph TD
    lobby["🏛️ Lobby<br/>spawn · 🎁"]:::spawn
    hub["📖 Narrator's Hub<br/>Apple · Iron Sword · Bronze Shield"]
    ench["✨ Enchanter"]:::svc
    merch["🛒 Merchant"]:::svc
    woods["🌲 Woods Gate"]
    fscout["📜 Forest Entrance"]:::quest
    goblin["🗡️ Goblin Clearing · 🎁"]:::enemy
    fshrine["⛩️ Forest Shrine"]
    mscout["📜 Mountain Pass"]:::quest
    ogre["🗡️ Ogre Crossing · 🎁"]:::enemy
    mshrine["⛩️ Mountain Shrine<br/>Steel Shield"]:::item
    kgate["🏰 Kingdom Gate"]
    frscout["📜 Frost Kingdom"]:::quest
    frwiz["🗡️ Frost Wizard"]:::enemy
    frshrine["⛩️ Frost Shrine<br/>Frost Sword"]:::item
    fiscout["📜 Fire Kingdom"]:::quest
    fiwiz["🗡️ Fire Wizard"]:::enemy
    fishrine["⛩️ Fire Shrine<br/>Flame Sword"]:::item
    bgate["🔒 Sealed Gate"]
    dragon["🐉 Dragon's Lair<br/>final boss"]:::boss

    lobby --> hub
    hub --- ench
    hub --- merch
    hub --> woods
    woods --> fscout --> goblin --> fshrine
    woods --> mscout --> ogre --> mshrine
    woods --> kgate
    kgate --> frscout --> frwiz --> frshrine
    kgate --> fiscout --> fiwiz --> fishrine
    kgate --> bgate --> dragon

    classDef spawn fill:#1f6feb,stroke:#0d419d,color:#fff
    classDef svc   fill:#8957e5,stroke:#6e40c9,color:#fff
    classDef enemy fill:#da3633,stroke:#b62324,color:#fff
    classDef boss  fill:#490202,stroke:#da3633,color:#fff
    classDef quest fill:#9e6a03,stroke:#7d5303,color:#fff
    classDef item  fill:#238636,stroke:#196c2e,color:#fff
```

**🖥️ GUI Example**

![ServerExample](assets/ServerExample.png)

---
## 🧠 Own Projects
Not yet...

## Languages

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Juanpi194&show_icons=true&locale=en&layout=compact&langs_count=10)](https://github.com/Juanpi194)

---
⭐ Always open to learning, collaborating, and new challenges
