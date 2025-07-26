---
layout: post
title: "DailyWhispers MVP: Day 1–2 Reflections"
subtitle: "Building a quiet, mindful journaling app inside the Hardcore AI Builders Camp (硬核AI Builder 群)"
date: 2025-07-24
categories: indiecamp mvp
---

## What is DailyWhispers · 暮语晨风?

**DailyWhispers** is my first tiny web app, created during the Hardcore AI Builders Camp (**硬核AI Builder 群**).  
It may look very simple—just a single page where you can write morning intentions, evening gratitudes, and revisit your history—but it is a true **MVP (Minimum Viable Product)**.

Why?  
- **Minimum:** it has only the essential tabs—Morning, Evening, History.  
- **Viable:** you can actually use it; your entries are saved and persist in your browser.  
- **Product:** it already delivers the core experience of a *calm digital reflection space*.  

Like all MVPs, it’s just the **first room of a larger palace**—a base to learn from, improve, or rebuild later.  
And this week’s journey is about how I began sketching and building that first room.  

---

## Why DailyWhispers?

As part of the **硬核AI Builder 群**—a Hardcore AI Builders Camp where 14 of us co-create with guidance from two master mentors—I chose to start my journey with something soft and reflective.

**DailyWhispers** is a quiet journaling web app for setting gentle morning intentions and evening gratitudes. It may seem like the opposite of “hardcore AI,” but to me, it’s a way to explore how technology can create *calm spaces* rather than noise.

So I set a **7-day plan** for this MVP:
- Day 1: Plan the user flow & wireframe  
- Day 2: Build the simplest working version with **vanilla HTML/CSS/JS**  
- Day 3: Rebuild it in **Lovable (React)** to see the difference  
- Day 4–7: Iterate features, refine UI, and deploy

---

## Day 1: Drawing the Blueprint

I learned that **a clear wireframe with all the technical specs feels like a blueprint**—but not a flat one. It’s **3D or even multi-dimensional**, because it involves *time* (what happens when you click “Save” today vs. tomorrow) and *space* (how different sections like Morning, Evening, and History unfold dynamically).

Sitting down with just pen and paper, sketching the tabs and text fields, I felt a strange delight. It was like the **architectural drawing of a future room** where thoughts would live.

On the technical side, Day 1 was also about setting up the workspace like a builder arranging tools:
- I created a **GitHub repo**
- Installed **VSCode**
- Learned how **VSCode integrates with GitHub** so I can edit locally and push changes online
- Discovered the **Live Server** extension—like instantly previewing the walls of your new room while you’re still laying bricks

By the end of Day 1, the palace wasn’t built, but the *ground plan* was there.

---

## Day 2: Building the First Room

On Day 2, I translated the blueprint into the actual first version of the app. This was my first **single-page app (SPA)** in **vanilla HTML, CSS, and JS**—just the core web languages, no frameworks.

What amazed me:
- With just these three simple “languages,” the app was **alive**—I could type a note, click Save, and it would remember, even after refreshing or restarting.
- It felt like adding the first piece of furniture into an empty room and realizing it already changes the atmosphere.

The **biggest challenge** was when I tried to add a Chinese ink-brush background using an external image. On Safari it worked, but on Chrome it stubbornly showed *“image not found”*. I learned about **browser caching quirks**, DNS hosting, and why **pure CSS gradients** are sometimes more reliable for MVPs.

So I simplified. Instead of fighting the background, I chose a **soft gradient color**—like keeping the palace walls plain rice paper until I decide what paintings to hang.

By the end of Day 2, I had:
- A working web app with **Morning, Evening, History** tabs  
- Private local storage that persists even after closing the browser  
- A live deployment on **GitHub Pages**: [https://chai-studio.github.io/dailywhispers/](https://chai-studio.github.io/dailywhispers/)

---

## Reflections

What surprised me most was how **tangible** this process feels:

- Writing the **spec** was like **designing a space for thoughts**.
- Drawing the **wireframe** was like sketching the walls of a little palace.
- Coding with **vanilla HTML/CSS/JS** felt like manually laying the foundation stones—humble but satisfying.

Tomorrow, I’ll try **Lovable** to rebuild DailyWhispers in **React + Tailwind**—it’s like inviting a master builder with pre-made components to reorganize the same palace. I want to see how it compares: what’s easier, what’s heavier, and what’s worth learning for future, larger CHAI projects.

---

## Terms I Learned (Day 1–2)

- **Vanilla HTML/CSS/JS** → plain, no-framework web languages  
- **SPA (Single Page App)** → one page dynamically updating  
- **Framework vs Vanilla** → pre-made structure vs building barebones  
- **React** → a library that organizes UI into reusable components  
- **Tailwind CSS** → a styling shortcut library  
- **Jekyll** → a static site generator for blogs, not apps  
- **Cache Busting** → forcing browsers to load fresh code  
- **localStorage** → browser’s built-in private database  

---

## Live Link

👉 Try **DailyWhispers** here:  
[https://chai-studio.github.io/dailywhispers/](https://chai-studio.github.io/dailywhispers/)

🔒 *Your reflections stay private on your own browser.*
