# CS-340--Client-Server-Development

**Writing Maintainable, Readable, and Adaptable Programs**

When I build something, I try to make sure the code is easy to understand, easy to update, and not tied together in a way that makes future changes painful. That was the whole point of creating the CRUD Python module in Project One. By keeping all the database operations in one place, the dashboard in Project Two stayed clean and focused on the user interface instead of database logic.

Working this way had a lot of advantages. I didn’t have to rewrite queries every time I added a new widget. If something needed to change in how the database was accessed, I only had to update one file. It made the dashboard more stable and way easier to troubleshoot. This CRUD module is something I could reuse in future projects too—anything that needs to talk to MongoDB could plug into it with minimal changes.

Overall, separating responsibilities and keeping things modular helped me write code that’s easier to maintain and expand later on.

**Approaching Problems as a Computer Scientist**
My approach to this project was to break everything down into smaller steps and tackle the foundation first. Grazioso Salvare needed a working database and a dashboard that pulled meaningful information from it, so I started by making sure the data layer was in good standings. Once the CRUD module was reliable, building the dashboard on top of it felt more straightforward.

Compared to earlier courses, this project required more real‑world thinking. Instead of following a strict checklist, I had to interpret what the client wanted, figure out how the pieces should fit together, and make design decisions that would hold up as the project grew. I leaned on strategies like modular design, testing as I went, and keeping the code flexible enough to handle changes.

Going forward, I’d probably use the same approach for future database projects: start with a clear data model, build reusable components, and make sure each part works independently before connecting everything together. It keeps the project organized and makes it easier to meet client needs without starting from scratch every time.

**What Computer Scientists Do — and Why It Matters**
Computer scientists solve problems by building tools that make work easier, faster, and more accurate. In this project, the dashboard I created helped Grazioso Salvare quickly analyze animal data and make decisions without digging through records manually. It gives them a clearer picture of which animals qualify for training and how resources should be allocated.

This kind of work matters because it directly supports the organization’s mission. When a company can access reliable data instantly, it improves efficiency and helps them focus on what they do best. For Grazioso Salvare, that meant spending more time helping animals and less time sorting through information. Projects like this show how technology can make a real difference in how a company operates.
