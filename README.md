# 🎮 Blizzard 2025 Gold Standard Curriculum  
*A Modern Career Development Framework for Game Engine & Systems Programmers*  

A modern, milestone-driven reading list for aspiring game engine and systems programmers.  
This curriculum modernizes the classic **Blizzard Software Engineering Reading List** for 2025, focusing on **Modern C++**, **game architecture patterns**, and **professional engineering habits**.  

---

## 📖 Origins & Philosophy  

This curriculum is a modern homage to the original **Blizzard Software Engineering Reading List** curated by *Jay Baxter* circa 2009.  
That list was legendary for its rigorous approach to crafting well-rounded, professional C++ engineers within a game development context.  

Our goal with this 2025 edition is to **honor the spirit and intent** of Baxter’s original vision —  
**deep C++ mastery, software engineering fundamentals, and professional craftsmanship** —  
while radically updating its contents for the contemporary era.  

---

## 🚀 What's New in the 2025 Edition?  

The original list was a product of its time, focused on **C++98** and the tools of that era.  
To work effectively in 2025, the list required a significant evolution:  

| Original Focus (2009) | Modernized Focus (2025) |
|-----------------------|--------------------------|
| **C++98 / "C with Classes"** | **Modern C++ (C++17/20):** RAII, smart pointers, move semantics, lambdas |
| **General Software Engineering** | **Game-Engine Specialization:** Data-Oriented Design, ECS, engine architecture, multiplayer |
| **Theoretical Foundations** | **Applied Practice:** Projects integrated at every tier |
| **Individual Contribution** | **Technical Leadership:** Modern senior IC skills (*The Staff Engineer’s Path*) |

This list is our attempt to answer the question:  
**“What would a Jay Baxter–style curriculum look like if it were created today?”**  

It is a **living document.** We will continue to update it as our industry evolves.  

---

## 🌍 Core Curriculum  

The **core tiers** form the foundation of this curriculum.  
Every aspiring engineer should progress through these stages, regardless of specialization.  

---

### **Tier 1: Associate Developer (0–2 Years)**  
**Goal:** Build strong programming fundamentals and fluency in Modern C++.  

- **Programming: Principles and Practice Using C++ (2nd Ed.)** — *Bjarne Stroustrup*  
- **A Tour of C++ (3rd Ed., C++20)** — *Bjarne Stroustrup*  
- **The Pragmatic Programmer (20th Anniversary Edition)** — *Andrew Hunt & David Thomas*  
- **The Mythical Man-Month** — *Frederick P. Brooks Jr.*  

📌 **Project:** Build small **2D games** using **SDL2** or **Raylib**.  

---

### **Tier 2: Mid-Level Developer (2–5 Years)**  
**Goal:** Master C++ idioms, design patterns, and game engine architecture.  

- **Effective Modern C++** — *Scott Meyers*  
- **Professional C++ (5th Ed.)** — *Marc Gregoire*  
- **Game Programming Patterns** — *Robert Nystrom*  
- **Design Patterns: Elements of Reusable Object-Oriented Software (GoF)** — *Gamma, Helm, Johnson, Vlissides*  
- **Game Engine Architecture (4th Edition)** — *Jason Gregory*  
- **Refactoring (2nd Edition)** — *Martin Fowler*  

📌 **Project:** Implement a basic **engine subsystem** (e.g., renderer, physics, or resource loader).  

---

### **Tier 3: Senior Developer (5+ Years)**  
**Goal:** Design and optimize complex systems, lead technical direction, and think strategically.  

- **C++ Concurrency in Action (2nd Ed.)** — *Anthony Williams*  
- **Data-Oriented Design** — *Richard Fabian*  
- **Clean Architecture** — *Robert C. Martin*  
- **Working Effectively with Legacy Code** — *Michael Feathers*  
- **The Staff Engineer’s Path** — *Tanya Reilly*  
- **Peopleware** — *Tom DeMarco & Timothy Lister*  

📌 **Project:** Develop a **multiplayer prototype** with optimized systems (networking, concurrency, and DOD).  

---

## ⚡ Optional Specialization Tracks  

(Choose after Tier 2 to focus your career path.)  

### 🔹 Graphics & Rendering  
- *Foundations of Game Engine Development Vol. 2: Rendering* — *Eric Lengyel*  
- *Real-Time Rendering (4th Edition)* — *Tomas Akenine-Möller et al.*  
- *Vulkan Programming Guide* — *Graham Sellers*  
  OR  
  *Introduction to 3D Game Programming with DirectX 12* — *Frank Luna*  

### 🔹 Online & Distributed Systems  
- *Designing Data-Intensive Applications* — *Martin Kleppmann*  
- *Production-Ready Microservices* — *Susan J. Fowler*  
- *(Advanced)* *Site Reliability Engineering* — *Betsy Beyer et al.*  

### 🔹 Production & DevOps  
- *The DevOps Handbook* — *Gene Kim et al.*  
- *Infrastructure as Code* — *Kief Morris*  
- *(Advanced)* *Continuous Delivery* — *Jez Humble & David Farley*  

**Practical Tools to Learn:**  
- **Perforce Helix Core** → branching, streams, handling large binaries  
- **Git LFS** → versioning large assets in Git  
- **Docker / Kubernetes** → containerization and orchestration  
- **CI/CD Platforms** (e.g., Jenkins, GitLab CI, TeamCity)  

---

## 📝 Note on Improvements  

This list stays **as close as possible** to Jay Baxter’s 2009 vision —  
structured tiers, deep C++ focus, and professional engineering mindset.  

We added a few **pluses** based on **advice from real AAA developers**:  

- ✅ **SDL2 or Raylib projects** → force deeper low-level understanding.  
- ✅ **Effective Modern C++ & Professional C++** → reflect post-C++11 language revolutions.  
- ✅ **Game Engine Architecture** → provides the “big picture” every AAA developer needs.  
- ✅ **Data-Oriented Design** → essential for modern, high-performance engines.  
- ✅ **The Staff Engineer’s Path** → guidance for senior IC leadership, reflecting today’s AAA studio expectations.  

These additions ensure the curriculum **produces developers ready for real AAA game studios in 2025**.  

---

## 📜 License  

Shared under the **MIT License**.  
Use, adapt, and expand it for your own learning journey.  



# 📚 Blizzard Software Engineering Reading  
by **Jay Baxter (circa 2009)**  

---

## 🎮 Associate Developer  

> *"This list is for people who want to become Associate Software Engineers at Blizzard.  
> An associate should have skills at the level indicated by these books. Note that this is almost completely focused on C++ programming.  
> This list is incomplete. I need a book on how to become a professional. I've listed several books that give examples of professional behavior, but not one on the actual training."*  

- **Programming: Principles and Practice Using C++** — *Bjarne Stroustrup*  
  > Beginner-to-intermediate. A deep dive into programming using C++.  

- **C++ Primer Plus (5th Edition)** — *Stephen Prata*  
  > Easier to read than Stroustrup, lighthearted tone.  

- **C++ Projects: Programming with Text-Based Games** — *Michael Dawson*  
  > Practical, project-based learning with simple games.  

- **Beginning Game Programming** — *Michael Morrison*  
- **Beginning Game Programming** — *Jonathan S. Harbour*  
  > Two distinct books. Great project-based introductions with source code.  

- **The Mythical Man-Month (Anniversary Edition, 2nd Ed.)** — *Frederick P. Brooks Jr.*  
  > Classic essays on software engineering.  

- **Joel on Software** — *Joel Spolsky*  
  > Essays on software development and culture.  

- **Programming Pearls (2nd Edition)** — *Jon Louis Bentley* *(Optional)*  
  > Insightful problems and solutions in programming.  

---

## ⚔️ Mid-Level Developer  

> *"This list is for people who want to become Mid-level Software Engineers at Blizzard.  
> A mid-level engineer should have skills at the level indicated by these books.  
> It’s about a year of reading — several hours a day, every day. The order is intentional."*  

- **The Pragmatic Programmer: From Journeyman to Master** — *Andrew Hunt*  
- **Object-Oriented Programming in C++** — *Nicolai M. Josuttis*  
- **Thinking in C++ Vol. 1 & Vol. 2** — *Bruce Eckel*  
- **Head First Design Patterns** — *Eric Freeman*  
- **User Interface Design for Programmers** — *Joel Spolsky*  
- **Debugging: The 9 Indispensable Rules** — *David J. Agans*  
- **Code Reading: The Open Source Perspective** — *Diomidis Spinellis*  
- **TCP/IP Sockets in C (2nd Edition)** — *Michael J. Donahoo* *(Optional)*  

---

## 🏆 Senior Developer  

> *"This list is for people who want to become a Senior Software Engineer.  
> A senior should have all the skills from Associate + Mid-level lists.  
> This is a 3-year reading list, designed for depth, theory, and practice."*  

- **Head First Software Development** — *Dan Pilone*  
- **The Practice of Programming** — *Brian W. Kernighan*  
- **Agile Software Development: Principles, Patterns, and Practices** — *Robert C. Martin*  
- **Clean Code: A Handbook of Agile Software Craftsmanship** — *Robert C. Martin*  
- **C++ Gotchas** — *Stephen C. Dewhurst*  
- **Design Patterns Explained (2nd Edition)** — *Alan Shalloway*  
- **TCP/IP Illustrated, Vol. 1: The Protocols** — *W. Richard Stevens*  
- **Refactoring: Improving the Design of Existing Code** — *Kent Beck*  
- **Secure Coding in C and C++** — *Robert C. Seacord*  
- **The Software Development Edge** — *Joe Marasco*  
- **The Passionate Programmer** — *Chad Fowler*  
- **Facts and Fallacies of Software Engineering** — *Robert L. Glass*  
- **Beautiful Code** — *Elliote Harold (ed.)*  
- **C++ Templates: The Complete Guide** — *David Vandevoorde*  
- **The C++ Standard Library: A Tutorial and Reference** — *Nicolai M. Josuttis*  
- **Herb Schildt's C++ Programming Cookbook** — *Herbert Schildt*  
- **Algorithms in a Nutshell** — *Gary Pollice*  
- **Coders at Work** — *Peter Seibel*  

---

## 📝 Notes  

- This original 2009 list was designed as a **career roadmap** for C++ and systems programmers.  
- It focuses heavily on **C++ expertise, professional craftsmanship, debugging, networking, and patterns**.  
- Later adaptations (like the **Blizzard 2025 Gold Standard Curriculum**) modernize this framework with **C++17/20, Data-Oriented Design, concurrency, and live-service backend knowledge**.  

---

📌 This is preserved here as a **historical artifact** and a foundation for modern updates.  
