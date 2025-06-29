---

### 🚀 Introduction

Intimidated by the command line? Don’t worry—you’re in good company. Hollywood has trained us to think that developers are black-screen wizards, hammering out green text at light speed to hack into satellites while chugging energy drinks. Reality? Much simpler (and far less dramatic).

That mysterious black window with a blinking cursor is called the <span id="command-line">command line interface (CLI)</span>. It lets you interact with your computer by typing commands, directly telling it what to do—no buttons, no mouse clicks, just pure power at your fingertips.

Why learn this? Because as a developer, this is your launchpad. Want to start projects, navigate files, or use Git like a boss? The command line is your best friend. It might feel alien at first, but trust me—it becomes second nature faster than you think.

---

### 🧭 Lesson Overview

By the end of this lesson, you'll confidently:

* Explain what the command line is and why it matters.
* Open the terminal on your computer.
* Navigate directories and view files using CLI commands.
* Create, rename, and delete files and folders like a pro.
* Open projects in a code editor directly from the terminal.

---

### ⚙️ Open the Terminal

Let’s get your terminal fired up:

* **Linux**: Press <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>T</kbd> or search for "Terminal".
* **macOS**: Open Spotlight (<kbd>Cmd</kbd> + <kbd>Space</kbd>), search "Terminal", and hit <kbd>Enter</kbd>.

You'll see a blinking cursor. That’s the prompt—it’s listening. Try typing:

```bash
whoami
```

Hit <kbd>Enter</kbd>. Boom—your username appears. You're in.

> ⚠️ Tip: When tutorials show `$ whoami`, it means “type `whoami` in your terminal.” Don’t include the \`\$”.

---

### 🧠 Why This Matters Now

You’ll be installing tools, writing code, and pushing to GitHub—all from the terminal. Learning this now saves you *months* of frustration later. And in real-world dev jobs? You'll live here.

---

### ✨ Use the CLI Like a Lazy Genius

Let’s embrace the golden rule of programmers: **“If it can be automated, it will be.”**

#### 📋 Copy & Paste in Terminal

It works differently:

* **Linux**: <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>C</kbd> to copy, <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>V</kbd> to paste.
* **macOS**: Just like usual: <kbd>Cmd</kbd> + <kbd>C</kbd> and <kbd>Cmd</kbd> + <kbd>V</kbd>.

#### 🔄 Tab Completion = No More Typos

Don’t type long folder names. Let the terminal autocomplete for you.

```bash
cd Doc[Tab]O[Tab]f[Tab]j[Tab]cal[Tab]
```

Saves time. Avoids errors. Makes you look cool.

#### 🚀 Open Projects Instantly

Once VS Code is installed:

```bash
code .
```

Opens the current folder in VS Code. Magic.

---

### 💻 Opening VS Code from Terminal

* **Linux**: It’s already in your PATH. Use `code folder-name/`
* **macOS**: Open VSCode, then <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> → Type “Shell Command” → Select `Install 'code' command in PATH`. Done.

---

### 🧪 Assignment: Level Up

#### Step 1: Practice CLI Basics

1. Open terminal.
2. Run these:

```bash
cd ~
mkdir test
cd test
touch test.txt
code test.txt
cd ..
rm -r test
```

Congratulations. You're now dangerous.

#### Step 2: Visit [The Unix Shell course](https://swcarpentry.github.io/shell-novice/)

Complete:

* [Download Files](https://swcarpentry.github.io/shell-novice/#download-files)
* [Introducing the Shell](https://swcarpentry.github.io/shell-novice/01-intro.html)
* [Navigating Files and Directories](https://swcarpentry.github.io/shell-novice/02-filedir.html)
* [Working With Files and Directories](https://swcarpentry.github.io/shell-novice/03-create.html)

#### Step 3: Build a Project Skeleton

```bash
mkdir my_website
cd my_website
touch index.html style.css
mkdir images
```

---

### 💡 Bonus Tips

> 🔐 **Entering Passwords in Terminal?**
> You won’t see stars, dots, or anything at all. That’s normal. It’s a security feature. Just type and hit enter.

> 🧭 **Where will `cd` take you?**
> `cd` with no arguments → Home directory (`~`)
> `cd ..` → Go up one directory level

---

### 🧠 Knowledge Check

Reflect on:

* What does the command line let you do?
* How do you navigate, view, create, and delete files?
* What’s the difference between `cd`, `pwd`, and `ls`?
* How do you open VSCode from CLI?

---

### 📚 Additional Resources

* [Learn Enough Command Line to Be Dangerous](https://www.learnenough.com/command-line-tutorial)
* [Command Line Flashcards](https://flashcards.github.io/command_line/introduction.html)

---

