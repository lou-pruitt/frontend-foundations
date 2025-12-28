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

- Build a clear mental model of files and folders
- Understand what file extensions mean
- Learn how browsers decide what to do with a file

**Outcome**

By the end of this step, you will be able to:

- Explain the difference between a file and a folder
- Explain what a file extension is and why it matters
- Describe, at a high level, how a browser turns files into a web page

No tools are required in this step.  
Nothing needs to be installed, created, or changed.

---

### A Calm Starting Point

Before we write anything for the web, we need to understand **what the web is actually made of**.

At a very basic level, the web is not mysterious.

It is built from:
- Files
- Stored in folders
- Read by programs called browsers

This step exists to make that feel concrete and understandable.

---

### Files and Folders: What They Really Are

A **folder** is a container.

It exists to:
- Hold files
- Group related things together
- Keep work organized

A **file** is a single item stored on your computer.

It may contain:
- Text
- Instructions
- Data
- Or a combination of these

An important distinction:

- A folder does not *do* anything by itself  
- A file contains the actual content or instructions

When we talk about a website, we are usually talking about **a folder full of files**.

---

### File Names and File Extensions

Most files have two parts to their name:

- The **name** (for humans)
- The **extension** (for programs)

Example:

`index.html`

- `index` → the name
- `.html` → the extension

The extension tells your computer and applications **how to interpret the file**.

This matters more than how the file looks or which icon it has.

---

### Common File Extensions You Will See

You do not need to memorize these.  
They are listed here to build familiarity.

- `.txt` — plain text
- `.html` — web page structure
- `.css` — visual styling rules
- `.js` — behavior and interaction
- `.png`, `.jpg` — images

For now, the most important idea is this:

> The same text, saved with a different extension, can be treated very differently.

---

### What a Browser Actually Does

A browser is a program whose job is to:

1. Open files
2. Read the instructions inside them
3. Display something on the screen

When a browser opens:
- a `.txt` file → it shows the text as-is
- an `.html` file → it interprets the text as instructions for a page

The browser is not guessing.
It is following rules based on file type.

---

### Where Websites Exist

A website can exist in two main places:

1. **On your own computer** (local files)
2. **On another computer** (a server on the internet)

Right now, we care only about the first case.

Working with local files means:
- Nothing is public
- Nothing can break the internet
- You can experiment safely

This is intentional.

---

### Checking Your Understanding

Without using tools, try to answer these in your own words:

1. What is the difference between a file and a folder?
2. Why does a file extension matter?
3. Why does a browser treat `.html` differently from `.txt`?

There are no perfect answers.
This step is about forming a mental model, not proving anything.

---

### Step Boundary

You now have the background needed to create your first real web file.

In the next step, we will:
- Create an actual HTML file
- Open it in a browser
- Confirm that changing a file changes what you see

Do not proceed until you are ready.
Nothing is expected to be committed yet.


---

## Step 3 — Your First HTML Page (Conceptual)

**Purpose**

- Understand what HTML is responsible for
- Learn what an HTML file represents conceptually
- Build a mental model of “structure” before writing anything

**Outcome**

By the end of this step, you will be able to:

- Explain what HTML is and what it is not
- Describe what an HTML page does for a browser
- Understand why structure comes before appearance or behavior

No files will be created in this part of the step.  
We are still preparing mentally.

---

### What HTML Is (At a High Level)

HTML stands for **HyperText Markup Language**.

Despite the name, you do not need to focus on:
- “Hyper”
- “Markup”
- Or “Language”

What matters is what HTML *does*.

HTML is used to **describe the structure and meaning of a page**.

It answers questions like:
- What is a heading?
- What is a paragraph?
- What is a list?
- What is a section of content?

HTML does **not** decide:
- Colors
- Fonts
- Layout
- Animations
- Interactions

Those come later.

---

### Structure Before Appearance

A helpful comparison:

Think of HTML like the **outline of a document**, not its design.

Before you choose:
- Fonts
- Colors
- Spacing

You need to know:
- What the content is
- How it is organized
- What role each piece plays

HTML exists to provide that structure.

---

### How Browsers Use HTML

When a browser opens an HTML file, it:

1. Reads the file from top to bottom
2. Interprets the structure described inside
3. Builds an internal representation of the page
4. Displays the result on screen

The browser is not looking for “code tricks.”

It is looking for **meaningful structure**.

---

### HTML Is Declarative, Not Instructional

This is an important idea.

HTML does not say:
- “Do this”
- “Calculate that”
- “Run this logic”

Instead, HTML says:
- “This is a heading”
- “This is a paragraph”
- “This is a section of content”

You are *describing* what things are, not commanding the browser step by step.

---

### Why This Matters for Beginners

Many beginners feel overwhelmed because they think:

> “I have to make the computer do things.”

With HTML, that is not true.

You are not controlling behavior yet.
You are labeling content so the browser can understand it.

This makes HTML a safe place to start.

---

### Checking Your Understanding

In your own words, try to answer:

1. What problem does HTML solve?
2. What kinds of decisions does HTML *not* make?
3. Why is structure important before styling or interaction?

Again, there are no perfect answers.
The goal is orientation, not precision.

---

### Step 3 Boundary (Important)

You now understand **what HTML is for**.

In the next part of this step, we will:
- Create your first HTML file
- Look at its structure
- Open it in a browser and observe what happens

That practical action will come **only after you confirm**.

Do not create any files yet.
Nothing should be committed at this stage.

## Step 3 — Your First HTML Page (Practical)

**Purpose**

- Create your first real HTML file
- Open it in a browser
- Confirm that changing a file changes what you see

**Outcome**

By the end of this step, you will have:

- An HTML file named `index.html`
- Opened that file in a browser
- Seen text appear on the screen because of your file

This is your first concrete artifact.
We will move slowly and verify each step.

---

### Creating Your First File

We are going to create a single file inside your project folder.

The file will be called:

`index.html`

This name is conventional and safe.
You do not need to understand *why* it is conventional yet.

---

### Step-by-Step: Create `index.html`

1. Make sure your **project folder is open** in Visual Studio Code.
2. In the file explorer (left side), look for your project folder name.
3. Right-click inside the folder area.
4. Choose **New File**.
5. Name the file exactly:

   `index.html`

Press **Enter** to confirm.

You should now see `index.html` listed in your project folder.

Nothing else should change.

---

### Adding Minimal Content

Open `index.html` by clicking on it.

Type the following **exactly**:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Page</title>
  </head>
  <body>
    <h1>Hello, world</h1>
  </body>
</html>


---

## Step 4 — Reading HTML as Structure, Not Code

**Purpose**

- Learn how to read HTML calmly and safely
- Understand HTML as structure and meaning, not “programming”
- Build confidence by recognizing familiar patterns

**Outcome**

By the end of this step, you will be able to:

- Look at an HTML file without feeling overwhelmed
- Identify the main sections of a basic HTML document
- Explain, at a high level, what each part is responsible for

No new files will be created in this step.  
We will work only with the file you already made.

---

### A Reassuring Reminder

You are not here to memorize HTML.

You are here to **recognize patterns**.

HTML is designed to be:
- Predictable
- Repetitive
- Readable by humans

If something looks unfamiliar, that does not mean you are behind.

---

### HTML Is Built from Elements

HTML is made up of **elements**.

Most elements follow a simple pattern:

```html
<tagname>content</tagname>

## Step 4 — Reading HTML as Structure, Not Code (Practical)

**Purpose**

- Practice reading HTML without fear
- Make small, safe text changes
- Confirm that structure stays intact when content changes

**Outcome**

By the end of this step, you will be able to:

- Change text in an HTML file confidently
- Recognize which parts of the file you are changing
- Trust that small changes are safe and reversible

We will not add new elements.
We will not reorganize the file.
We will work only with what already exists.

---

### Opening Your Existing File

Open `index.html` in Visual Studio Code.

You should see something similar to this:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Page</title>
  </head>
  <body>
    <h1>This is my first HTML page</h1>
  </body>
</html>


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
