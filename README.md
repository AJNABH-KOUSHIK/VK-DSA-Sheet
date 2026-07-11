<div align="center">

# 🧠 VK DSA Sheet

### *Master Patterns. Solve Problems. Level Up.*

> The **only** free, open-source DSA practice sheet that combines questions from **all major coding platforms** — organized by **patterns**, not just topics — with built-in progress tracking, revision management, and a personal knowledge base.

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-vk--dsa--sheet-blueviolet?style=for-the-badge)](https://vk-dsa-sheet-vz9q.vercel.app/)
[![Tech](https://img.shields.io/badge/Built_With-React_+_Firebase-orange?style=for-the-badge&logo=react)](https://vk-dsa-sheet-vz9q.vercel.app/)
[![Status](https://img.shields.io/badge/Status-Live_&_Active-brightgreen?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)]()

<br/>

<img src="https://github.com/user-attachments/assets/YOUR_SCREENSHOT_ID_HERE" alt="VK DSA Sheet Dashboard" width="90%" />

</div>

---

## 📌 The Problem

Every coding platform promotes **its own** problem set:

| Platform | What They Offer | What's Missing |
|----------|----------------|----------------|
| **LeetCode** | Huge question bank | No pattern-wise roadmap, no cross-platform tracking |
| **TakeUForward (TUF)** | Striver's SDE Sheet | Limited to their own curated list |
| **GeeksforGeeks** | Topic-wise problems | No unified progress tracking across platforms |
| **Codeforces** | Competitive problems | No structured DSA sheet |

### The Real Issue

- ❌ Students jump between 4-5 platforms with **no single place** to track everything
- ❌ Sheets exist, but they're just **lists** — no pattern-based learning
- ❌ No way to mark **revision status** separately from completion
- ❌ No personal **bookshelf**, **link storage**, or **notes** alongside practice
- ❌ No **calendar view** to visualize coding consistency
- ❌ No **difficulty-wise breakdown** (Easy / Medium / Hard) with progress

> **There is no completely free website that has LeetCode + GFG + TUF + Codeforces + Pattern Names + Progress Tracker all in one place.**

### 💡 Until now.

---

## 🎯 The Idea — How I Thought of This

I noticed something frustrating — **every creator, every platform promotes THEIR OWN sheet.**

But as a student, I wanted **ONE place** where I could:

- ✅ See **ALL patterns** (not just topics like "Arrays" — but actual patterns like *Sliding Window*, *Two Pointers*, *Kadane's Algorithm*, etc.)
- ✅ Get questions from **LeetCode, GFG, TUF, Codeforces** — ALL of them in one place
- ✅ Track what I've **COMPLETED** ✅
- ✅ Track what I need to **REVISE** 🔄
- ✅ Store my favourite **BOOKS** 📚
- ✅ Save important **LINKS** 🔗
- ✅ Write personal **NOTES** 📝
- ✅ See my practice on a **CALENDAR** 📅
- ✅ See **difficulty breakdown** — Easy, Medium, Hard
- ✅ Have all of this **PERSIST** with my login

> **No such website existed. So I built one.** 🚀

---

## 🔗 Try it out

👉 **[Click here to visit VK DSA Sheet](https://vk-dsa-sheet-vz9q.vercel.app/)**

---

## ✨ Features

### 🏠 Core DSA Sheet

- **16 Pattern Categories** — Arrays, Binary Search, Strings, Bit Manipulation, Linked List, Two Pointers, Sliding Window, Stacks & Queues, Greedy Algorithms, Heaps, Binary Trees, BST, Graphs, Tries, DP, and more
- **Sub-pattern Breakdown** — Each category is further divided into specific patterns (e.g., Arrays → Array Traversal, Rotate Array, Brute Force Subarray, Kadane's Algorithm, etc.)
- **Multi-Platform Questions** — Each pattern contains problems from:
  - 🟢 **LeetCode**
  - 🟠 **TakeUForward (Striver)**
  - 🟡 **GeeksforGeeks**
  - 🔵 **Codeforces**

### ✅ Progress Tracking System

- **Completion Tick** ✅ — Mark a question as done
- **Revision Tick** 🔄 — Separately mark questions for revision
- **Progress Bars** — Visual progress for each sub-pattern (e.g., `0/16`, `3/7`)
- **Circular Progress Ring** — Overall completion indicator (e.g., `0/65`)
- **Difficulty Counter** — Track how many Easy 🟢, Medium 🟡, Hard 🔴 you've solved
- **Beats Percentage** 👏 — See how you compare (e.g., "Beats 12.5%")

### 📅 Practice Calendar

- **GitHub-style Calendar** — See which days you practiced
- **Daily Streak Tracking** — Green dots on active days
- **Monthly View** — Navigate through months to see your history
- **Practice History** — Detailed log of questions solved per day

### 📚 Personal Knowledge Base (Sidebar)

| Feature | Description |
|---------|-------------|
| 🔍 **Search** | Quickly find any pattern or question |
| 📖 **Books** | Store your favourite DSA books + recommended books provided |
| 🔗 **Links** | Save important links (YouTube videos, articles, editorials) |
| 📝 **Notes** | Write personal notes for any topic or question |

### 🔐 User Authentication

- **Login / Sign Up** — Secure Firebase Authentication
- **Persistent Data** — Your progress, books, links, notes — everything saved to your account
- **Cross-Device Sync** — Login from anywhere, pick up where you left off

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) |
| **Backend / Database** | ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black) (Authentication + Firestore) |
| **Deployment** | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white) |
| **Version Control** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white) |

### Libraries & Tools Used

| Library/Tool | Purpose |
|-------------|---------|
| `React` | Component-based UI framework |
| `Firebase Auth` | User authentication (Login/Sign Up) |
| `Cloud Firestore` | Real-time database for storing user progress |
| `React Router` | Client-side routing and navigation |
| `CSS3 / Custom CSS` | Styling with dark theme and animations |
| `Vercel` | Production deployment and hosting |
| `Git & GitHub` | Version control and collaboration |

---


## 🏗️ Architecture & User Flow

Here's how the entire application works from the user's perspective:

<pre>
┌──────────────────────────────────────────────────────────────────────────────────────────────┐
│                                  🌐 USER FLOW                                               │
├──────────────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                              │
│  User Visits Website                                                                         │
│        │                                                                                     │
│        ▼                                                                                     │
│  Browse DSA Patterns (No Login Required)                                                     │
│        │                                                                                     │
│        ▼                                                                                     │
│  Login / Sign Up ─────────────► Firebase Authentication                                      │
│        │                                                                                     │
│        ▼                                                                                     │
│  ┌────────────────────────────────────────────────────────────────────────────────────────┐  │
│  │                              📊 DASHBOARD                                             │  │
│  ├────────────────────────────────────────────────────────────────────────────────────────┤  │
│  │                                                                                        │  │
│  │  ┌─────────────┐   ┌──────────────┐   ┌─────────────┐                                │  │
│  │  │ Total Solved│   │ Difficulty   │   │  Calendar   │                                │  │
│  │  │    0 / 450  │   │  Easy/Med/Hard│  │    View     │                                │  │
│  │  └─────────────┘   └──────────────┘   └─────────────┘                                │  │
│  │                                                                                        │  │
│  │  ┌──────────────────────────────────────────────────────────────────────────────────┐  │  │
│  │  │                      16 PATTERN CATEGORIES                                       │  │  │
│  │  ├──────────────────────────────────────────────────────────────────────────────────┤  │  │
│  │  │ Arrays            │ Binary Search │ Strings                                     │  │  │
│  │  │ Bit Manipulation  │ Linked List   │ Two Pointers                                │  │  │
│  │  │ Sliding Window    │ Stacks/Queues │ Greedy                                      │  │  │
│  │  │ Heaps             │ Binary Trees  │ BST                                         │  │  │
│  │  │ Graphs            │ Tries         │ Dynamic Programming                         │  │  │
│  │  └──────────────────────────────────────────────────────────────────────────────────┘  │  │
│  │                                                                                        │  │
│  │  Each Pattern                                                         │                │  │
│  │       │                                                               │                │  │
│  │       ▼                                                               │                │  │
│  │  Sub-Patterns                                                         │                │  │
│  │       │                                                               │                │  │
│  │       ▼                                                               │                │  │
│  │  Questions                                                            │                │  │
│  │       ├── LeetCode                                                    │                │  │
│  │       ├── GeeksforGeeks                                               │                │  │
│  │       ├── Take U Forward                                              │                │  │
│  │       └── Codeforces                                                  │                │  │
│  │                                                                                        │  │
│  │  ✅ Mark Complete                         🔄 Mark for Revision                        │  │
│  └────────────────────────────────────────────────────────────────────────────────────────┘  │
│        │                                                                                     │
│        ▼                                                                                     │
│  Progress Synced to Firebase (Real-Time)                                                     │
│                                                                                              │
│  ┌────────────────────────────── SIDEBAR ───────────────────────────────┐                    │
│  │                                                                      │                    │
│  │  🔍 Search                                                           │                    │
│  │  📚 Books (Recommended + User Favourites)                            │                    │
│  │  🔗 Links (Saved by User)                                            │                    │
│  │  📝 Notes (Personal Notes)                                           │                    │
│  │                                                                      │                    │
│  │  ───────────── Platform Quick Links ─────────────                    │                    │
│  │                                                                      │                    │
│  │        LC        TUF        GFG        CF                            │                    │
│  │                                                                      │                    │
│  └──────────────────────────────────────────────────────────────────────┘                    │
│                                                                                              │
└──────────────────────────────────────────────────────────────────────────────────────────────┘
</pre>


---
---

### 🔄 Flow Summary

**User Visits** → **Browses Patterns** → **Login/Sign Up** → **Selects Pattern** → **Solves Question** → **Marks ✅ Complete / 🔄 Revision** → **Progress Saved to Firebase** → **Views Calendar & Stats** → **Stores Books/Links/Notes** → **Continues from Any Device**

---

## 📸 Screenshots

### 🏠 Home — Dashboard View
> Pattern categories, total solved counter, difficulty breakdown, and calendar — all at a glance.

<img src="https://github.com/user-attachments/assets/YOUR_DASHBOARD_SCREENSHOT" alt="Dashboard" width="90%" />

### 📋 Pattern View — Sub-patterns with Progress
> Each pattern category expands into sub-patterns with individual progress tracking.

<img src="https://github.com/user-attachments/assets/YOUR_PATTERN_SCREENSHOT" alt="Pattern View" width="90%" />

### 📅 Calendar — Practice Streak
> Visualize your daily coding activity and maintain consistency.

<img src="https://github.com/user-attachments/assets/YOUR_CALENDAR_SCREENSHOT" alt="Calendar" width="90%" />

### 📚 Books & Resources
> Store recommended books and save your own favorites.

<img src="https://github.com/user-attachments/assets/YOUR_BOOKS_SCREENSHOT" alt="Books" width="90%" />

### 🔗 Links & 📝 Notes
> Your personal knowledge vault — save important links and write notes.

<img src="https://github.com/user-attachments/assets/YOUR_LINKS_NOTES_SCREENSHOT" alt="Links and Notes" width="90%" />

---

## 🗺️ DSA Patterns Covered

<table>
<tr>
<td>

| # | Pattern | Sub-patterns |
|---|---------|-------------|
| 1 | **Arrays** | Array Traversal, Rotate Array, Brute Force Subarray, Kadane's, Dutch National Flag |
| 2 | **Binary Search** | Standard BS, BS on Answers, BS on Rotated Arrays |
| 3 | **Strings** | String Matching, Palindromes, Anagrams |
| 4 | **Bit Manipulation** | XOR Tricks, Bit Masking, Power of Two |
| 5 | **Linked List** | Reversal, Fast & Slow Pointer, Merge |
| 6 | **Two Pointers** | Opposite Direction, Same Direction, Three Pointers |
| 7 | **Sliding Window** | Fixed Window, Variable Window, Shrinkable |
| 8 | **Stacks & Queues** | Monotonic Stack, Next Greater Element |

</td>
<td>

| # | Pattern | Sub-patterns |
|---|---------|-------------|
| 9 | **Greedy Algorithms** | Activity Selection, Fractional Knapsack |
| 10 | **Heaps** | Top-K Elements, Merge K Sorted, Median |
| 11 | **Binary Trees** | Traversals, Views, Diameter, LCA |
| 12 | **BST** | Search, Insert, Delete, Validate |
| 13 | **Graphs** | BFS, DFS, Dijkstra, Topological Sort |
| 14 | **Tries** | Insert, Search, Prefix Matching |
| 15 | **DP** | 1D DP, 2D DP, Knapsack, LIS, LCS |
| 16 | **More...** | Additional patterns added regularly |

</td>
</tr>
</table>

---

## 🤔 What Makes This Different?

<table>
<tr>
<th>Feature</th>
<th>LeetCode</th>
<th>TUF Sheet</th>
<th>GFG Sheet</th>
<th>NeetCode</th>
<th>✅ VK DSA Sheet</th>
</tr>
<tr>
<td><b>Pattern-wise Roadmap</b></td>
<td>❌</td>
<td>✅ (own only)</td>
<td>❌</td>
<td>✅ (own only)</td>
<td>✅</td>
</tr>
<tr>
<td><b>Multi-Platform Questions</b></td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>✅ LC + GFG + TUF + CF</td>
</tr>
<tr>
<td><b>Progress Tracking</b></td>
<td>✅ (premium)</td>
<td>✅</td>
<td>❌</td>
<td>✅</td>
<td>✅ (free)</td>
</tr>
<tr>
<td><b>Revision Tracking</b></td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>✅</td>
</tr>
<tr>
<td><b>Practice Calendar</b></td>
<td>✅</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>✅</td>
</tr>
<tr>
<td><b>Personal Notes</b></td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>✅</td>
</tr>
<tr>
<td><b>Book Shelf</b></td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>✅</td>
</tr>
<tr>
<td><b>Link Storage</b></td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>❌</td>
<td>✅</td>
</tr>
<tr>
<td><b>Difficulty Breakdown</b></td>
<td>✅</td>
<td>❌</td>
<td>❌</td>
<td>✅</td>
<td>✅</td>
</tr>
<tr>
<td><b>Completely Free</b></td>
<td>❌</td>
<td>✅</td>
<td>✅</td>
<td>❌</td>
<td>✅</td>
</tr>
</table>

---

## 🧩 Feature Breakdown

### 1️⃣ Pattern-Based Learning
> Instead of randomly solving questions, learn by **patterns** — the way interviewers actually think.

<pre>
📁 Arrays
   ├── 🔹 Array Traversal (16 questions)
   ├── 🔹 Rotate Array (7 questions)
   ├── 🔹 Brute Force Subarray (9 questions)
   ├── 🔹 Kadane's Algorithm (5 questions)
   └── 🔹 ... more sub-patterns
</pre>

### 2️⃣ Dual Tracking System
> **Complete** a question and **Revise** it — two separate tracks.

<pre>
Question: Two Sum
├── ✅ Completed: Yes (solved on July 5)
├── 🔄 Revised: No (needs revision)
└── 📊 Difficulty: Easy
</pre>

### 3️⃣ Smart Dashboard
> Everything you need at a glance.

<pre>
┌────────────────┬────────────────┬──────────────┐
│  Total Solved  │   Difficulty   │   Calendar   │
│    42 / 450    │  E: 20  M: 15  │  July 2026   │
│                │  H: 7          │  ● ● ●       │
│  Beats 12.5%   │                │  Streak: 5   │
└────────────────┴────────────────┴──────────────┘
</pre>

### 4️⃣ Personal Knowledge Vault
> Your coding journey companion — not just a problem list.

- 📚 **Books** — Recommended DSA books + add your own favourites
- 🔗 **Links** — Save YouTube videos, blog posts, editorials
- 📝 **Notes** — Write notes for any topic or problem

### 5️⃣ Practice History & Calendar
> Detailed log of every question you solved, when you solved it, and its difficulty. Visualize your consistency with a calendar view.

---

## 🎨 Design Philosophy

- 🌙 **Dark Theme** — Easy on the eyes during late-night coding sessions
- 🎨 **Purple & Cyan Gradient** — Modern, aesthetic, developer-friendly
- 📱 **Responsive** — Works on desktop, tablet, and mobile
- ⚡ **Fast** — Optimized React components with efficient state management
- 🔥 **Real-time** — Firebase ensures instant sync across devices

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** (v16 or above)
- **npm** or **yarn**
- A **Firebase** project (for authentication and database)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/vk-dsa-sheet.git

# 2. Navigate to the project directory
cd vk-dsa-sheet

# 3. Install dependencies
npm install

# 4. Create a .env file with your Firebase config
cp .env.example .env
