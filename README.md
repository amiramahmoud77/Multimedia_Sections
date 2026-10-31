# 📚 Multimedia Sections - Practical & Theoretical Guide

Welcome to the **Multimedia Sections** repository! This repository contains comprehensive practical lab materials, step-by-step algorithms, solved examples, and quick review questions designed for university multimedia courses.

---

## 🛠️ Software & Tools Download
* 🔴 **Adobe Flash CS6:** [Download Adobe Flash CS6 (Official / Archive Resource)](https://archive.org/details/adobe-flash-cs6)

---

## 🚀 Contents Overview & Lecture Links

### 1️⃣ Adobe Flash CS6 (Practical Labs)
* **Topics Covered:**
  * Workspace navigation, Stage setup, and Timeline organization.
  * Working with Layers and keyframing (`F5`, `F6`, `F8`).
  * **Symbols & Types:** Understanding the core differences and use cases for **Graphic**, **Button** (with its 4 interactive states), and **Movie Clip** (independent timeline) symbols.
  * **Animations:** Step-by-step implementation of **Shape Tweens** (raw vector shapes) and **Motion Tweens** (symbols, rotation, scaling, and `Alpha` transparency).
  * **Preview & Testing:** Testing movies using `Ctrl + Enter`.
* 🎥 **Section Video / Tutorial:** [Watch Adobe Flash CS6 Basics & Tweens Tutorial](https://www.youtube.com/results?search_query=adobe+flash+cs6+motion+tween+tutorial)

---

### 2️⃣ Digital Audio Fundamentals
* **Key Formulas & Practice Problems:**
  * **Nyquist Rate:** Minimum sampling rate = 2 × f_max
  * **Signal-to-Noise Ratio (SNR):** SNR = 20 × log10(A_signal / A_noise)
  * **Signal-to-Quantization Noise Ratio (SQNR):** SQNR ≈ 6.02 × N (where N is bits per sample)
* 🎥 **Section Video / Tutorial:** [Watch Digital Audio & Nyquist Rate Explanation](https://www.youtube.com/results?search_query=digital+audio+nyquist+rate+snr+sqnr)

---

### 3️⃣ Shannon-Fano Compression Algorithm
* **Lossless Compression Method:** Assigning shorter codes to frequent symbols and longer codes to rare ones.
* **Step-by-Step Methodology:**
  1. Count symbol frequencies and sort them in descending order.
  2. Split the list into two groups with nearly equal totals.
  3. Assign bit `0` to the upper group and bit `1` to the lower group.
  4. Recursively repeat until each symbol is isolated.
  5. Read the code from the root down to the leaf.
* **Core Formulas:**
  * Probability: p = Count / Total
  * Ideal Code Length: L_ideal = log2(1 / p)
  * Total Bits Before (B0) & After (B1) Compression
  * Average Code Length & Entropy (H)
  * Compression Ratio: CR = B0 / B1
* 🎥 **Section Video / Tutorial:** [Watch Shannon-Fano Algorithm Step-by-Step](https://www.youtube.com/results?search_query=shannon+fano+compression+algorithm+example)

---

