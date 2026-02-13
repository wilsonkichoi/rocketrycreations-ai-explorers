# 🎮 Module 3: Coding with Your Voice (Vibe Coding)

You don't need to know "code" to build an app. You just need to describe the "vibe."

---

## 🎯 Learning Objectives

By the end of this module, you will be able to:
- [ ] Build a working game without writing code yourself
- [ ] Debug problems by describing them clearly
- [ ] Explain what variables, loops, and functions do
- [ ] Iterate on a project to add new features

---

## 💼 Why This Matters

| Career | How They Use This Skill |
|--------|------------------------|
| **Product Manager** | Prototyping app ideas quickly without waiting for developers |
| **Entrepreneur** | Building MVPs (minimum viable products) to test business ideas |
| **Software Developer** | Using AI to speed up coding and handle boilerplate |
| **Data Analyst** | Creating quick tools and visualizations |

*"No-code" and "low-code" tools are the fastest-growing segment in tech. Vibe Coding takes this even further.*

---

## 🔑 Key Concept: What is Vibe Coding?

**Vibe Coding** = Describing what you want your program to *feel* like and *do*, then letting AI write the actual code.

| Traditional Coding | Vibe Coding |
|-------------------|-------------|
| Learn syntax first | Describe in plain English |
| Write code line by line | AI generates the code |
| Fix errors by reading code | Fix errors by describing the problem |
| Years to master | Start building today |

### The Vibe Coding Process

1. **Describe** what you want
2. **Generate** the code with AI
3. **Test** if it works
4. **Iterate** by describing changes
5. **Repeat** until it's right

---

## 🛠️ Tools for Today

| Tool | What It Does | Access |
|------|--------------|--------|
| **Google Gemini** | Generates code from descriptions | [gemini.google.com](https://gemini.google.com) |
| **Gemini Canvas** | Runs and displays your game instantly | Built into Gemini |

**What is Canvas?** Canvas is Gemini's built-in preview feature that lets you see and interact with code instantly - no need to save files or use external editors!

---

## 🏗️ Activity A: Arcade Architect - Build Your First Game

### Step 1: Open Google Gemini

1. Go to **[gemini.google.com](https://gemini.google.com)**
2. Start a new conversation

### Step 2: The Magic Prompt

Copy and paste this prompt to create your first game:

```
Create a simple Space Invaders style game using HTML, CSS, and JavaScript.

Requirements:
- A player spaceship at the bottom that moves left/right with arrow keys
- Enemies that move across the screen and slowly descend
- The player can shoot bullets with the spacebar
- When bullets hit enemies, the enemies disappear
- Display a score counter
- Game over when enemies reach the bottom

Show me the game in Canvas so I can play it directly.
```

### Step 3: Play in Gemini Canvas

1. **Look for the Canvas panel** on the right side of Gemini
2. Your game should appear and be **playable immediately!**
3. **Click inside the Canvas** to activate it
4. **Play your game:**
   - Use **Arrow Keys** to move left/right
   - Use **Spacebar** to shoot

### Step 4: Test and Take Notes

While playing, think about:
- Does the spaceship move smoothly?
- Do bullets fire correctly?
- Is the game too easy or too hard?
- What would make it more fun?

**Write down 1-2 things you want to change** - we'll iterate on these next!

### ✓ Checkpoint

- [ ] Did your game load and run?
- [ ] Can you move and shoot?
- [ ] What's one thing you want to change?

---

## 🐛 Activity A.5: Debug Buddy Protocol

**When things break, don't panic! Try this with a partner:**

### Step 1: Find a Debug Buddy
Pair up with a classmate

### Step 2: Describe the Problem
Use this template:

```
My game has a problem:
- What I expected: _______________
- What actually happens: _______________
- When does it happen: _______________

Please fix it and show the updated game in Canvas.
```

### Step 3: Buddy Asks Questions
- Is the Canvas panel showing?
- Did you click inside Canvas to activate it?
- What exactly isn't working?

### Step 4: Ask Gemini to Fix It
The Canvas will update automatically!

**Why this matters:** Professional developers spend 50% of their time debugging. Learning to describe problems clearly is a crucial skill!

### Common Issues Reference

| What's Happening | What to Tell Gemini |
|-----------------|---------------------|
| Canvas is blank | "The Canvas isn't showing anything. Can you fix the game?" |
| Player won't move | "The spaceship doesn't respond to arrow keys" |
| Bullets don't shoot | "Pressing spacebar doesn't create bullets" |
| Enemies don't die | "Bullets pass through enemies without destroying them" |
| Score doesn't update | "The score stays at 0 even when I hit enemies" |
| Game is too fast/slow | "The game runs too fast, please slow it down" |

---

## 🔄 Activity B: Iteration - Making It Better

Now the fun part - improving your game through conversation!

**How Canvas Makes This Easy:**
- Just type what you want to change
- Canvas updates instantly with your changes
- No need to copy/paste or save files
- You can keep building on the same game!

### The Iteration Challenge

Try at least 3 of these improvements (copy & paste into the same conversation):

**Speed & Difficulty:**
```
Make the enemies move faster
```

```
Add more rows of enemies
```

```
Make the enemies shoot back at the player
```

**Visual Improvements:**
```
Change the player ship to be green and the enemies to be red
```

```
Add a starry background that slowly moves
```

```
Make explosions appear when enemies are destroyed
```

**Gameplay Features:**
```
Add 3 lives for the player
```

```
Add levels - when all enemies are destroyed, spawn a new harder wave
```

```
Add a high score that saves between games
```

```
Add power-ups that randomly fall from destroyed enemies
```

### Iteration Tracker

| Change Requested | Did It Work? | Notes |
|-----------------|--------------|-------|
| 1. | Yes / No | |
| 2. | Yes / No | |
| 3. | Yes / No | |
| 4. | Yes / No | |

**Tip:** If something breaks, just tell Gemini: "That broke the game, please undo that change."

---

## 🧠 Understanding What You Built

Even without knowing code, you can understand the logic of your game:

### Game Logic Breakdown

```
GAME LOOP (runs 60 times per second):
├── CHECK player input (arrow keys, spacebar)
├── MOVE player based on input
├── MOVE enemies in their pattern
├── MOVE bullets upward
├── CHECK if bullets hit enemies
│   └── IF hit: remove enemy, add points
├── CHECK if enemies reached bottom
│   └── IF yes: game over
└── DRAW everything on screen
```

### Key Programming Concepts You Used

| Concept | What It Means | Example in Your Game |
|---------|---------------|---------------------|
| **Variables** | Stored information | Score, player position, lives |
| **Conditionals** | If/then decisions | If bullet hits enemy, destroy it |
| **Loops** | Repeated actions | Check all enemies every frame |
| **Events** | Responding to input | Arrow key pressed = move player |
| **Functions** | Reusable actions | Create bullet, move enemy |

---

## 🎮 Alternative Projects

If Space Invaders doesn't excite you, try these:

### Pong Clone
```
Create a simple Pong game with:
- Two paddles (one controlled by arrow keys, one by W/S keys)
- A ball that bounces off walls and paddles
- Score tracking for both players
- Ball speeds up slightly with each hit

Show me the game in Canvas so I can play it directly.
```

### Snake Game
```
Create a Snake game with:
- A snake that moves continuously and turns with arrow keys
- Food items that appear randomly
- Snake grows longer when it eats food
- Game over if snake hits the wall or itself
- Score based on food eaten

Show me the game in Canvas so I can play it directly.
```

### Flappy Bird Style
```
Create a Flappy Bird style game with:
- A bird that falls due to gravity
- Spacebar makes the bird jump/flap
- Pipes that scroll from right to left with gaps
- Score increases for each pipe passed
- Game over if bird hits a pipe or the ground

Show me the game in Canvas so I can play it directly.
```

---

## 🎪 Showcase & Play Testing

### Peer Play Testing

1. Pair up with a partner
2. Play each other's games
3. Give feedback using this format:

**Feedback Template:**
- "One thing I liked: _______________"
- "One thing that surprised me: _______________"
- "One suggestion: _______________"

### Class Showcase
- Volunteers demo unique features they added
- Discuss: What was the most creative modification?

---

## 📝 Reflection Journal

```
MODULE 3: THE BUILDER - VIBE CODING

GAME I CREATED:
[ ] Space Invaders
[ ] Pong
[ ] Snake
[ ] Other: _______________

MODIFICATIONS I MADE:
1. _______________
2. _______________
3. _______________

DEBUGGING EXPERIENCE:
Problem I encountered: _______________
How I fixed it: _______________

WHAT I LEARNED ABOUT CODE:
_______________________________________________

THE HARDEST PART WAS:
_______________________________________________

NEXT TIME I WANT TO BUILD:
_______________________________________________
```

---

## 📚 Key Vocabulary

| Term | Definition |
|------|------------|
| **Vibe Coding** | Creating code by describing what you want in natural language |
| **Iteration** | Making repeated improvements based on testing |
| **Debugging** | Finding and fixing problems in code |
| **HTML** | The language that structures web pages |
| **CSS** | The language that styles web pages (colors, sizes) |
| **JavaScript** | The language that makes web pages interactive |
| **Variable** | A container that stores information (like score = 0) |
| **Function** | A reusable set of instructions |
| **Loop** | Code that repeats multiple times |
| **Canvas** | Gemini's built-in code preview feature |

---

## ✅ Skills Checklist

By the end of this module, you should be able to:

- [ ] Use natural language to generate working code
- [ ] Use Gemini Canvas to preview and test code instantly
- [ ] Iterate on code through conversational prompts
- [ ] Debug issues by clearly describing problems
- [ ] Explain basic concepts: variables, loops, conditionals
- [ ] Modify existing code by requesting specific changes

---

## 🚀 Extension Activities

### Game Jam Challenge
In pairs, you have 15 minutes to add the most creative feature to your game:
- Boss enemy that takes multiple hits
- Shield power-up
- Different weapon types
- Two-player mode

### Remix a Classic
Ask Gemini to create a mashup:
```
Create a game that combines Space Invaders with Snake - the player is a snake that shoots at descending enemies while growing longer.

Show me the game in Canvas so I can play it directly.
```

### Personal Utility Tool
Move beyond games - create something useful:
```
Create a simple to-do list app with:
- Input field to add tasks
- Checkbox to mark tasks complete
- Delete button for each task
- Tasks saved even after page refresh

Show me the app in Canvas.
```

---

## 🏠 Take-Home Challenge

**The Personal Project**

Create something YOU want using Vibe Coding:

1. Think of a simple tool or game you wish existed
2. Describe it to Gemini (be specific!)
3. Get it working
4. Make at least 3 improvements
5. Bring it to share next time!

**Ideas:**
- A quiz game about your favorite topic
- A simple calculator with a custom theme
- A reaction time tester
- A virtual pet that you can feed and play with
- A random joke generator
- A countdown timer for homework

---

[⬅️ Back to Main Guide](../../README.md) | [Next Module: The AI Detective ➡️](../04-ethics-lab/README.md)
