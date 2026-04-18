# ☕ Optimal Cafeteria Placement using Genetic Algorithms

## 📌 Overview

This repository presents a project focused on solving a facility location problem using a **Genetic Algorithm (GA)** approach. The objective is to determine the optimal selection and placement of cafeterias in a grid-based environment to maximize customer coverage.

The model simulates customer distribution and evaluates different configurations of cafeteria locations, considering both **direct demand** and **proximity-based coverage**.

---

## 🧠 Problem Description

Given:

* A set of potential cafeteria locations distributed over a grid
* A population of customers assigned to different zones

The goal is to:

* Select a subset of cafeterias (fixed number)
* Maximize the number of customers served
* Account for customers that can be served by nearby cafeterias within a distance threshold

Additionally, the model derives **warehouse (distribution center) locations** based on clustering of selected cafeterias.

---

## ⚙️ Methodology

The solution is based on a **Genetic Algorithm**, which includes:

* **Population Initialization**
  Random generation of candidate solutions (chromosomes)

* **Fitness Function**
  Evaluation based on:

  * Number of customers directly served
  * Customers covered by proximity

* **Selection**
  Preference for higher-performing solutions

* **Crossover**
  Combination of parent solutions to generate offspring

* **Mutation**
  Random alterations to maintain diversity

* **Termination Criteria**
  The algorithm stops when a high-quality solution is found or a generation limit is reached

---

## 📊 Key Features

* Grid-based simulation environment
* Randomized customer distribution
* Distance-aware coverage model
* Optimization using evolutionary computation
* Post-processing to determine warehouse locations

---

## 🏭 Output

The model produces:

* An optimal configuration of cafeteria locations
* Total customer coverage achieved
* Suggested warehouse locations based on spatial grouping

---

## 🔒 Code Availability

**This repository is for informational purposes only.**

The implementation code is not publicly available due to reasons related to:

* Intellectual property
* Academic and/or publication considerations

---

## 📄 License

No license is provided since the source code is not distributed.

---

## 👤 Author

Hiram Efraín Orocio García

MSc in Computational and Industrial Mathematics
Background in Machine Learning, Optimization, and Computer Vision

---

## 📬 Contact

For questions, collaborations, or access inquiries, feel free to reach out.
