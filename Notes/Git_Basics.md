# Git Basics
# Git Fundamentals

**Author:** Mayuresh Tripathi

**Repository:** linux-labs

---

# What is Git?

Git is a **Distributed Version Control System (DVCS)** that tracks changes made to files over time. It enables developers to save different versions of a project, restore previous versions, collaborate efficiently, and maintain the complete history of a project.

---

# Simple Definition

Git is software that records every change made to a project so developers can save versions, restore previous work, and collaborate safely.

---

# Non-Technical Explanation

Imagine several people are writing a book.

Git is like a **register** that records:

- What changed
- Who changed it
- When it changed
- Which version is the latest

If someone makes a mistake, you can always return to an older version of the book.

---

# What is Version Control?

Version Control is a system that records changes made to files over time so that previous versions can be restored whenever required.

---

# Why is Git Used?

Git is used to:

- Track project history
- Save different versions
- Restore previous versions
- Collaborate with multiple developers
- Prevent loss of work
- Manage software projects efficiently

---

# Why Do Companies Use Git?

Companies use Git because it allows multiple developers to work on the same project while maintaining complete project history and preventing conflicts.

Without Git:

- Nobody knows who changed the code.
- Previous versions cannot be restored easily.
- Collaboration becomes difficult.
- Bugs are difficult to trace.
- Accidental deletions may cause permanent loss.

---

# What is a Repository?

A Repository (Repo) is a project folder that is tracked by Git.

Example:

linux-labs/

README.md

Notes/

Projects/

Daily-Labs/

Screenshots/

---

# What is a Commit?

A Commit is a **saved snapshot** of a project stored in the local Git repository.

Each commit records:

- What changed
- Who made the change
- When it was changed
- A message describing the change

---

# Why is a Commit Called a Snapshot?

A commit captures the complete state of a project at a particular point in time.

Developers can return to any previous snapshot whenever required.

---

# What Information Does a Commit Store?

A commit stores:

- Project state
- File changes
- Author information
- Date and time
- Commit message

---

# Commit vs Push

## Commit

- Saves changes locally
- Stored on your computer
- Does not require internet

Think of it as pressing **Save** on your laptop.

---

## Push

- Uploads committed changes to GitHub
- Requires internet
- Creates an online backup

Think of it as uploading your saved work to the cloud.

---

# Difference Between Git and GitHub

## Git

- Software
- Installed on your computer
- Tracks project history
- Works offline
- Creates commits

## GitHub

- Cloud platform
- Stores Git repositories
- Enables collaboration
- Requires internet
- Hosts your project online

---

# Git Works Offline

One of Git's biggest advantages is that it works completely offline.

Without internet you can:

- Create repositories
- Edit files
- Commit changes
- View history
- Create branches

Internet is only required when communicating with GitHub.

---

# Golden Rule

**Commit Early.**

**Push Regularly.**

This minimizes the risk of losing work.

---

# Git Workflow

Create File

↓

Modify File

↓

Git Tracks Changes

↓

Commit (Save Locally)

↓

Push (Upload to GitHub)

---

# Real-Life Analogy

Imagine writing a book.

Git is like a register that records:

- Every page edited
- Every editor
- Every version
- Every date

GitHub is like a secure online library where both the book and the register are stored safely for everyone to access.

---

# Benefits of Git

- Maintains complete project history
- Easy collaboration
- Easy rollback
- Prevents accidental data loss
- Tracks every modification
- Industry standard for software development

---

# Important Interview Questions

## Q1. What is Git?

Git is a Distributed Version Control System that tracks changes in files over time. It allows developers to save versions, restore previous versions, collaborate efficiently, and maintain complete project history.

---

## Q2. What is Version Control?

Version Control is a system that records changes made to files over time, allowing developers to restore previous versions whenever required.

---

## Q3. What is a Repository?

A Repository is a project folder that is tracked by Git.

---

## Q4. What is a Commit?

A commit is a saved snapshot of the project stored in the local Git repository.

---

## Q5. Why is a Commit called a Snapshot?

Because it captures the complete state of a project at a particular point in time.

---

## Q6. Difference between Commit and Push?

Commit:

- Saves locally.
- Does not require internet.

Push:

- Uploads commits to GitHub.
- Requires internet.

---

## Q7. Difference between Git and GitHub?

Git is software that tracks project history.

GitHub is a cloud platform that stores Git repositories and enables collaboration.

---

## Q8. Can Git work without internet?

Yes.

Git works completely offline.

---

## Q9. Can GitHub work without internet?

No.

GitHub is an online platform and requires internet connectivity.

---

## Q10. What happens if your laptop crashes before you push?

If the commits were never pushed to GitHub, the latest work cannot be recovered from GitHub because it only stores the commits that have been pushed.

---

# Interview Answer (Technical)

Git is a Distributed Version Control System (DVCS) that tracks changes in files, maintains project history, enables collaboration among developers, and allows easy restoration of previous versions.

---

# Interview Answer (Non-Technical)

Imagine several people are writing a book.

Git is like a register that records every change made to the book—what changed, who changed it, and when it changed.

GitHub is like a secure online library where both the book and the register are stored safely, allowing everyone to collaborate without losing previous versions.

---

# Key Terminologies

| Term | Meaning |
|------|---------|
| Git | Distributed Version Control System |
| Repository | Project folder tracked by Git |
| Commit | Saved snapshot |
| Push | Upload commits to GitHub |
| Version Control | Tracking file changes over time |
| Local Repository | Repository stored on your computer |
| Remote Repository | Repository stored on GitHub |

---

# Quick Revision

Git = Software

GitHub = Cloud Platform

Repository = Project Folder

Commit = Local Snapshot

Push = Upload to GitHub

Version Control = History of Changes

---

# Mentor's Tip

Understanding **why** Git exists is more important than memorizing Git commands.

Once the concepts are clear, the commands become easy to learn and remember.
