# 🧮 LeetCode 1 — Two Sum (Brute Force Method)

This repository contains my implementations of the **Two Sum** problem solved using the **Brute Force** approach, written in multiple programming languages:

✔ C  
✔ C++  
✔ C#  
✔ Java  
✔ Python  
✔ JavaScript  
✔ TypeScript  
✔ Go  

The goal is simple:  
👉 Take one problem  
👉 Solve it in many languages  
👉 Using **one common logic** — the BRUTE FORCE method  
👉 So anyone can compare and learn easily.

📘 What is the Brute Force Method?

Imagine you are in a classroom.
Your teacher says:

“I hid 2 candies somewhere among your friends. They add up to 10 rupees. 
Find those 2 people.”

What will you do?

Simple:
You ask EACH friend:
  “What is your amount?”

And for EVERY friend,  
You check with EVERY OTHER friend.

Friend 1 → check with friend 2, 3, 4…  
Friend 2 → check with friend 3, 4, 5…  
Friend 3 → check with friend 4, 5, 6…  

This is exactly what brute force does.

How Brute Force Works

for i from 0 to n:
    for j from i+1 to n:
        if nums[i] + nums[j] == target:
            return [i, j]

Two loops.
Check every pair.
Return the first matching pair.

⏱️ Time & Space Complexity

Type	Complexity
Time	O(n²) — because we test all pairs
Space	O(1) — no extra memory except variables

This repository focuses on learning, clarity, and multi-language consistency. Each solution follows the same brute force strategy so learners can easily understand logic before moving to optimized techniques.