---
title: "The Feynman Technique"
draft: false
date: 2025-05-11
author: Yanouk
description: "The Principle of Feynman Technique"
categories:
  - life 🌱
tags:
  - productivity
  - self-improvement
---

# Mastering Code with the Feynman Technique: Learn Faster, Understand Deeper

Learning to code isn't just about copying and pasting syntax. It's about **understanding** what the code does, how it works, and why it behaves the way it does. Whether you're a beginner or a seasoned developer, one of the best ways to deepen your knowledge is by using the **Feynman Technique**.

Originally developed by physicist **Richard Feynman**, this learning method forces you to go beyond surface-level memorization. It helps you internalize complex concepts, identify gaps in your knowledge, and retain what you learn for the long term.

---

## 💡 What is the Feynman Technique?

The Feynman Technique is a four-step process:

1. **Choose a concept you want to understand**
2. **Teach it in simple language**
3. **Identify your knowledge gaps**
4. **Review, simplify, and repeat**

The idea is simple: If you can’t explain a topic clearly to someone else (especially a child), you probably don’t fully understand it.

Feynman believed that "the first principle is that you must not fool yourself—and you are the easiest person to fool." The technique is built around exposing what you _don’t_ know—so you can fix it.

---

## 🧠 Why Use the Feynman Technique to Learn Code?

Programming concepts are often deeply interconnected and abstract. It's easy to fall into the trap of **memorizing** without truly **understanding**.

Using the Feynman Technique helps you:

- **Solidify your understanding** of key coding principles
- **Spot weaknesses** in your knowledge quickly
- **Make connections** between different topics
- **Improve your technical communication**, which is useful for interviews, collaboration, and documentation

---

## 🔍 Step-by-Step: How to Apply the Feynman Technique to Coding

### Step 1: Choose a Concept

Pick one concept or topic from your learning journey. It could be:

- How functions work in Python
- What the `this` keyword does in JavaScript
- Differences between REST and GraphQL APIs
- How Git handles branching and merging
- React state vs props
- CSS specificity

Start small and focused. For example, don’t try to explain _all of JavaScript_. Choose something like _how closures work_.

---

### Step 2: Teach It Like You’re Explaining to a 12-Year-Old

Grab a piece of paper, a whiteboard, or a markdown editor. Then explain the topic in **plain, simple language**. Use analogies, real-world examples, and visuals if necessary.

For example:

> A **function** is like a kitchen recipe. You give it ingredients (called parameters), and it follows steps to produce something new (the return value). If you use the same recipe with different ingredients, you get a different result.

Or:

> A **for loop** is like telling the computer, "Repeat this task a certain number of times."

Avoid technical jargon unless you can explain it too. The goal is clarity, not sounding smart.

---

### Step 3: Find the Gaps in Your Understanding

As you try to teach the concept, you’ll hit moments where you:

- Can’t explain why something works
- Forget a detail
- Feel unsure

These are **knowledge gaps**, and they’re incredibly valuable. Go back to the docs, watch a tutorial, or read an article to strengthen that part of your understanding.

Ask yourself:

- What would happen if I changed this?
- Can I explain this without code?
- Could I write this from scratch with no help?
- Can I give a working example?

For example:

> I said `.map()` in JavaScript returns a new array... but what if I don’t return anything from the function inside it?

---

### Step 4: Simplify, Refine, and Repeat

Now that you've filled in the gaps, go back and revise your explanation. Make it even simpler. Add examples or analogies. Remove any unnecessary complexity.

Try teaching it again—out loud, to a friend, or even by recording yourself.

By the end, you should feel confident that you understand the concept thoroughly.

---

## 💻 Real Coding Example: JavaScript Closures

### Step 1: Topic Chosen

> JavaScript closures.

### Step 2: Explain Simply

> A **closure** happens when a function remembers the variables around it, even after those variables would normally be gone.  
> It’s like having a backpack—your inner function keeps a copy of everything it needs from where it was created.

```js
function outer() {
  let count = 0;
  return function inner() {
    count++;
    return count;
  };
}

const counter = outer();
counter(); // 1
counter(); // 2
```
