# 🧠 Nudge: The Conscious Productivity Tracker.

**Nudge** is a minimal, cross-platform, "always-on-top" desktop application for obsessive productivity users who want to track their **real effort**, not just elapsed time.

---

## 🛑 The Problem

We often set aside a 2-hour block for "deep work" to get into "The Zone." But during that time, we get distracted. We check our phone, browse a non-work tab, get up for a snack, or get pulled into a conversation.

When we look back, our 2-hour "work" session only resulted in 25 minutes of *actual, focused progress*. Most productivity trackers either log total time or try (and fail) to automatically guess if you're "working," but they don't track your **intent**.

## ✅ The Solution: Conscious Accountability

Nudge helps you measure your **Real Productivity** by forcing you to be accountable.

Instead of automatic tracking, Nudge requires you to *consciously* press an **"Interrupt Work"** button when you get distracted. This activates a separate "Distracted" timer (while the "Total" timer keeps running). When you're ready to focus again, you press "Back to Work."

This simple, manual action provides a powerful psychological separation and gives you an honest, undeniable metric at the end of the day:

> **Real Productivity Time = Total Session Time - Total Distracted Time**

---

## ✨ Core Features

* **📂 Project-Based Tracking**: Organize your work into different projects.
* **⏱️ Total vs. Real Time**: Every project tracks three key lifetime metrics:
    * `Total Time` (Clock running)
    * `Total Distraction` (Time spent interrupted)
    * `REAL Time` (Total - Distraction)
* **🔔 Conscious Distraction Logging**: Manually log interruptions and categorize them (e.g., "Check Phone", "Other Distractions") to see what's really breaking your .
* **📜 Detailed Session Logs**: Review every individual work session for a project.
* **📌 Always-on-Top (Sticky) Mode**: A small, 500x500 (approx) window that stays visible on top of all other windows.
* **👥 Multi-User Support**: Simple, password-less user profiles to separate data if a computer is shared.
* **💡 "Don't Forget" Nudges**: A toggle-able list of reminders (e.g., "Drink water", "Put phone away") visible right in the timer interface.
* **🌍 i18n Support**: Full interface translation between **English** and **Spanish**.
* **💾 Import/Export**: Easily back up all your user data (projects, logs, settings) to a JSON file.

---

## 🛠️ Tech Stack

* **Language**: Python 3
* **GUI Framework**: PyQt6
* **Database**: SQLite 3 (Local, Server-less)

## 🗺️ Roadmap

- [ ] Design Database Schema
- [ ] Implement "Sticky" Timer Interface
- [ ] Build Project Management Logic
- [ ] Implement Pixel Art UI Theme

---
*This is a personal project built for conscious workflows.*
