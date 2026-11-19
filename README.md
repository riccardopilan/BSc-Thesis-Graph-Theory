# BSc Thesis: The Four Color Theorem – History and Proofs

**Degree:** BSc in Mathematics, Department of Mathematics "Tullio Levi-Civita", University of Padova (UniPD)  
**Author:** Riccardo Pilan  
**Advisor:** Prof. Manuel Francesco Aprile  
**Academic Year:** 2023–2024  

**[Download the Full Thesis (Italian) – PDF](Pilan_Riccardo.pdf)**  
**[Download the Defense Presentation Slides (Italian) – PDF](Presentazione_Pilan_Riccardo.pdf)**

---

## Extended Abstract

This thesis presents a historical and theoretical analysis of the Four Color Theorem, examining both its foundational role in the development of Graph Theory and the structure of its computer-assisted proofs. It traces the problem from Francis Guthrie's 1852 conjecture and the early flawed proofs by Kempe (1879) and Tait (1880), through key structural advances by Birkhoff, Whitney, and Heesch, up to Appel and Haken's 1976 proof and the simplified 1996 proof by Robertson, Sanders, Seymour, and Thomas.

On the theoretical side, the work formalizes the translation of the planar map-coloring problem into vertex coloring via dual graphs. It introduces the fundamental Graph Theory concepts—including planarity, Kuratowski's Theorem, Euler's Formula ($|V| - |E| + |F| = 2$), and the reduction of minimal counterexamples to maximal planar graphs (triangulations).

Key mathematical results and proofs analyzed in detail include:
* **Kempe's Error and Heawood's Five Color Theorem:** A rigorous reconstruction of Kempe's inductive proof using Kempe chains, showing how simultaneous color inversion fails in the degree-5 case through the **Fritsch Graph** (minimal counterexample), followed by a complete proof of Heawood's Five Color Theorem ($\chi(G) \le 5$).
* **The Proof by Robertson, Sanders, Seymour, and Thomas (1996):** A breakdown of the proof by contradiction structured around three main theorems:
  * **Internal 6-Connectivity (Birkhoff, 1913):** Proof that any minimal counterexample must be an internally 6-connected triangulation.
  * **Reducibility:** Definition of configurations, free completions, consistency, D-reducibility, and C-reducibility (with safe reducers), illustrated through the explicit reduction of the **Birkhoff Diamond**.
  * **Unavoidability and Discharging:** Formulation of the 32 discharging rules over 633 unavoidable configurations and proof of the total charge invariant ($\sum_{v \in V(T)} \Theta_T(v) = 120$), guaranteeing the existence of a positively charged vertex whose neighborhood contains a reducible configuration.

The thesis concludes by addressing open problems and generalizations—most notably Hadwiger's Conjecture and chromatic polynomials—and reflecting on the theorem's legacy as the milestone that inaugurated computer-assisted proofs in mathematics.

---

## Key Mathematical Concepts Covered
* **Graph Theory Fundamentals:** Planarity, Dual Graphs, Kuratowski's Theorem, Euler's Formula, Chromatic Number.
* **Kempe Chains:** Cyclic and non-cyclic alternating paths, Fritsch Graph counterexample, Five Color Theorem.
* **Structural Reductions:** Minimal counterexamples, triangulations, separating cycles, internal 6-connectivity.
* **Configuration & Discharging Theory:** Ring-size, free completions, D-reducibility and C-reducibility, discharging rules.

---

## Repository Structure
* `Pilan_Riccardo.pdf` – Complete BSc thesis (Italian).
* `Presentazione_Pilan_Riccardo.pdf` – Defense presentation slides (Italian).
* `latex/` – Complete LaTeX source files (`Tesi.tex`, `Presentazione.tex`, `bibliografia.bib`) and all required graphic assets for compilation.