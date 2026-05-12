# Merge Conflict Practice Task

## Goal

Learn how merge conflicts happen and how to resolve them.

---

## Instructions

1. Fork the repo
2. Create a new branch
3. Edit this file
4. Change ONLY your assigned section below
5. Commit and open a Pull Request

---

## Section A (User 1 edits this)

My favorite programming language is JavaScript.
I want to learn Git because it helps teams work together.
I am excited to contribute to open source.

---

## Section B (User 2 edits this)

My favorite programming language is Python.
I am learning backend engineering.
I want to build scalable systems like Kronos.

---

## What will happen

If two people edit this file at the same time:
- Git will not know which version to keep
- A merge conflict will occur
- You will need to manually fix it

---

## Your Task

When a conflict happens:

1. Open the file in your editor
2. Look for conflict markers:

```
<<<<<<< HEAD
=======
>>>>>>> branch-name
```

3. Decide what to keep
4. Remove the markers
5. Commit the resolved file

---

## Expected Outcome

A clean file that contains both contributions without conflict markers.