<!--
Copilot Context — Read Only

This repository is a beginner-first, documentation-driven learning project.

Constraints:
- Content must be sequential. Do not suggest skipping steps or reordering sections.
- Assume the reader has zero prior coding experience.
- Favor clarity, reassurance, and explanation over completeness or efficiency.
- Avoid frameworks, build tools, abstractions, or advanced patterns.
- Avoid jargon unless it is introduced and explained gently.
- Do not optimize for speed, performance, or “best practices” beyond fundamentals.
- Treat AI as a mentor that explains concepts, not an authority or code generator.

Intent:
This workbook teaches how to learn front-end development calmly and safely.
Any suggestion that increases cognitive load, assumes prior knowledge, or
prioritizes output over understanding is out of scope.

This comment exists to guide AI assistance only. It is not learner-facing.
-->

# Frontend Foundations — Workbook

Welcome to **Frontend Foundations**.

This workbook is a **sequential, beginner-first guide** to learning front-end web
development from zero experience. It is designed to be followed **in order**.

We assume no prior knowledge. Every concept, tool, and decision is introduced
intentionally and explained clearly.

If something feels confusing, that is normal. We will revisit ideas multiple
times as your understanding grows.

---

## How to Use This Workbook

- Follow the steps **in order**
- Do not skip ahead
- Take your time
- Ask questions
- Verify what you see in the browser
- Modify examples and observe what changes

This workbook uses AI tools (such as ChatGPT) as **mentors**, not authorities.
You are encouraged to question, test, and reflect at every step.

---

## Step 0 — What We Are Building and Why

We know that learning something new can feel uncertain, especially when it comes to technology. That’s why we created this workbook — to give you a gentle, step-by-step introduction to how websites are made and how the web works.

Our goal is to help you understand the basics of building for the web, starting from the very beginning. We believe that everyone deserves a clear and welcoming path, no matter their background or experience.

As you move through these pages, you’ll find that we focus on understanding, not memorization or speed. We want you to feel safe, supported, and confident as you discover how the web is built. Together, we’ll explore the basics, one step at a time, always making sure you know not just what to do, but why it matters.

**Purpose**

- Understand what front-end web development is
- Understand what a website actually is
- Set expectations for the learning journey

**Outcome**

- You know what problems front-end developers solve
- You understand what this workbook will and will not cover

---

### What a Website Is (at a High Level)

Before we begin installing tools or creating files, it is important to clarify what we mean by a *website*.

At its most basic level, a website is **a collection of files** that a computer program called a *browser* (such as Chrome or Safari) knows how to read and display.

These files describe:
- What content exists, such as text or images
- How that content is arranged
- How it should look
- How it may respond to interaction

When you visit a website, your browser:
1. Receives these files
2. Interprets the instructions inside them
3. Displays the result on your screen

Nothing more mysterious is happening.

A website is not:
- A single page
- A single language
- A single program running by itself

Instead, it is a cooperation between:
- Files written by people
- Rules understood by browsers
- Actions taken by users, such as clicking, scrolling, and typing

Front-end development focuses on the part of this system that lives **inside the browser** — the part the user sees, touches, and experiences directly.

As you continue through this workbook, you will learn how different kinds of files work together to form a website. For now, it is enough to remember this:

> A website is a set of instructions that tells a browser what to show and how to behave.

You will soon begin writing those instructions yourself — slowly, intentionally, and with full understanding of each step.

In the next step, we will prepare a simple environment so you can begin working with these ideas directly.



---

## Step 1 — Your Tools and Your Environment

**Purpose**

- Understand what development tools are
- Install and open Visual Studio Code
- Learn what a project folder represents

**Outcome**

- VS Code installed
- A project folder created
- The folder opened correctly in the editor

---

Before we write anything for the web, we need a place to work.

In this step, we will set up a simple, calm environment where you can create files, make changes, and see results. Nothing here is complicated, and nothing here is permanent. These tools exist to support learning, not to test you.

We will move slowly and explain what each thing is and why it matters.

---

### What We Mean by “Tools”

In web development, a *tool* is simply something that helps you write and organize instructions for the computer.

At this stage, you only need two things:

- A place to store your project files
- A program to edit text files safely

That’s it.

You are not setting up anything advanced.  
You are not configuring a system.  
You are just preparing a workspace.

---

### Your Project Folder

A **project folder** is just a normal folder on your computer.

It exists to:
- Hold your files in one place
- Keep related work together
- Make it easier for tools to understand your project later

You can think of it as a container.  
Everything related to this project will live inside it.

In the next steps, this folder will begin to contain files that describe a website. For now, it is simply an empty home waiting to be used.

---

### Your Code Editor

A **code editor** is a program designed for editing plain text files.

We will use **Visual Studio Code** (often called *VS Code*) because it is:
- Free
- Widely used
- Beginner-friendly
- Available on all major operating systems

A code editor is not special because it writes code for you.  
It is special because it helps you see and organize what you write.

At this stage, you do not need to understand:
- Menus
- Extensions
- Settings
- Shortcuts

You only need to be able to:
- Open the editor
- Open your project folder
- Create and save files

We will learn everything else gradually.

---

### Installing Visual Studio Code

In this section, you will install a program called **Visual Studio Code**.  
This is the editor we will use to view and edit files throughout the workbook.

Take your time. Nothing here is fragile.

---

#### If You Are Using Windows

1. Open a web browser you already use (such as Edge or Chrome).
2. Go to the Visual Studio Code website:  
   https://code.visualstudio.com
3. Click the button labeled **Download for Windows**.
4. Once the download finishes, open the installer.
5. Follow the on-screen instructions and accept the default options.
6. When installation completes, open **Visual Studio Code**.

You should see a window open with a welcome screen.  
If you do, installation was successful.

---

#### If You Are Using macOS

1. Open a web browser you already use (such as Safari or Chrome).
2. Go to the Visual Studio Code website:  
   https://code.visualstudio.com
3. Click the button labeled **Download for Mac**.
4. Once the download finishes, open the downloaded file.
5. Drag **Visual Studio Code** into your **Applications** folder.
6. Open **Visual Studio Code** from Applications.

You should see a window open with a welcome screen.  
If you do, installation was successful.

---

#### If You Are Using Linux

If you are using Linux, you likely already know how software is installed on your system.

You may install Visual Studio Code using the method recommended by your distribution (for example, through your package manager or software center).

Once installed, open Visual Studio Code and continue with the next section.

---

### Creating Your Project Folder

Next, create a folder on your computer where this project will live.

You may name this folder something simple, such as:

- `frontend-foundations`
- `web-learning`
- or any name you prefer

The location does not matter.  
Your desktop or documents folder is fine.

This folder will hold all of your files for this workbook.

---

### Opening Your Project Folder in Visual Studio Code

1. Open **Visual Studio Code**.
2. Look for an option that says **Open Folder**.
3. Select the project folder you just created.
4. Confirm your choice.

You should now see the folder name appear in the editor.

At this point:
- Visual Studio Code is installed
- Your project folder exists
- The folder is open in the editor

You are ready to continue.

In the next step, we will look closely at files, folders, and how the web understands them.


---

## Step 2 — Files, Folders, and How the Web Sees Them

**Purpose**

- Understand files vs folders
- Understand file extensions
- Learn how browsers load files

**Outcome**

- You know what an HTML file is
- You know where files live and why naming matters

---

## Step 3 — Your First HTML Page

**Purpose**

- Learn what HTML does
- Write a minimal HTML document
- Understand page structure

**Outcome**

- A working HTML page
- You can open it in a browser and see it render

---

## Step 4 — Reading HTML as Structure, Not Code

**Purpose**

- Learn to read HTML calmly
- Understand semantic elements
- Recognize patterns instead of memorizing tags

**Outcome**

- You can explain what each section of your HTML does
- You can change text without breaking the page

---

## Step 5 — Introducing CSS: Making Things Visible and Readable

**Purpose**

- Understand what CSS does
- Connect CSS to HTML
- Apply simple visual changes

**Outcome**

- Text is styled
- Spacing and layout are improved
- You understand separation of concerns

---

## Step 6 — Layout and Flow

**Purpose**

- Understand how elements are positioned
- Learn basic layout concepts
- Avoid common beginner layout confusion

**Outcome**

- A simple, readable layout
- Fewer “why is this over here?” moments

---

## Step 7 — Introducing JavaScript: Behavior and Interaction

**Purpose**

- Understand what JavaScript is responsible for
- Learn how JavaScript interacts with HTML
- Respond to user actions

**Outcome**

- A button that does something
- You understand events at a high level

---

## Step 8 — The DOM: Understanding What JavaScript Is Touching

**Purpose**

- Introduce the Document Object Model (DOM)
- Understand how the page is represented internally
- Learn safe, simple DOM manipulation

**Outcome**

- You can connect JavaScript to real elements
- You can change the page without reloading

---

## Step 9 — Mistakes, Errors, and Debugging Calmly

**Purpose**

- Normalize errors
- Learn how to read error messages
- Learn how to debug without panic

**Outcome**

- You can fix simple mistakes
- Errors feel informative, not scary

---

## Step 10 — Saving Your Work with Git

**Purpose**

- Understand what version control is
- Learn why developers use Git
- Save progress safely

**Outcome**

- Git initialized
- Changes committed intentionally

---

## Step 11 — Sharing Your Work with GitHub

**Purpose**

- Understand what GitHub is
- Publish your work publicly
- Learn what “remote” means

**Outcome**

- A GitHub repository
- Your project visible online

---

## Step 12 — From Learner to Contributor

**Purpose**

- Understand how learning continues
- Learn how to ask better questions
- See how beginners become contributors

**Outcome**

- You know how to keep learning
- You understand how to participate in open-source safely

---

## Closing

You are not expected to understand everything immediately.

Learning front-end development is not about memorization.
It is about **recognition, repetition, and confidence**.

If you reached this point, you have already done something difficult:
you stayed.
