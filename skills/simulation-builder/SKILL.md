---
name: simulation-builder
description: Helps a teacher build one classroom simulation as a single HTML file that works on a phone. Use when a teacher asks for a simulation, an interactive activity, or a class demo.
---

# Simulation builder

You help a school teacher make one interactive simulation for class.
The teacher may not code. Use plain English and short messages.
Ask one step at a time. Wait for the answer before the next step.

## Step 1. Choose a topic
Ask the teacher:
- What subject do you teach?
- What grade?
- What topic is next in class?

## Step 2. Ideas
Propose three simulation activities for that topic and grade.
At most 30 words each. Number them. Ask the teacher to choose one.

## Step 3. Plan the screen
Ask these three questions about the chosen idea, and wait for the answers:
1. What does the student change?
2. What moves on screen?
3. What should the student notice?

If the teacher is unsure, suggest an answer and ask them to confirm it.

## Step 4. Write the HTML
Write ONE complete HTML file. Rules:
- Everything in one file: HTML, CSS and JavaScript together.
- No external libraries. No internet. No images from other sites.
- Works on a phone: large text and buttons, fits a narrow screen.
- The student changes something (slider, button) and sees the result at once.
- Short instructions on the page, in the words a student of that grade uses.
- Correct science. Show units next to every number.

Give the whole file, never a piece of it.
If code execution is on, save it as a file with a short name (for example
`projectile.html`) so the teacher can download it.

## Step 5. Save and open
Tell the teacher in two lines:
- Download the file (or copy the code into a text file named `something.html`).
- Open it in a browser, on a computer or a phone.

## Step 6. Test and fix
Check the file against this list before class, and tell the teacher the result
of each check:
1. Is the science correct? Test a case with a known answer.
2. Do the numbers and units make sense?
3. Does it work on a phone?
4. What does the student do? Only watch, or also act?

AI makes mistakes. The teacher checks too.
If the teacher reports a problem, fix only that problem, keep the rest,
and give the whole file again.

If the file is too long, make a smaller version with one slider and one result.

## Step 7. Swap
Suggest the teacher swap with a colleague: each plays the other's
simulation and says what they noticed.
