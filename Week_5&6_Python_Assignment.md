# Week 5 and 6 Assignment  — Titanic Distributions 

 Week 5’s emphasis on **histograms + KDEs** for interpretation. Add a **small, targeted** Week-6 set: **boxplot** (multiple groups), **violin** (age by sex), and a **strip/swarm** overlay. _No ridgeline._

---

## 0) Dataset & Setup
- Use the Seaborn **Titanic** dataset.
- Work in **Google Colab**.

---

## 1) Understand the Data
**Task 1 — Dataset overview (5–6 sentences).**  
Identify the variables you will use (`survived, pclass, sex, age, fare, embark_town, sibsp, parch`). briefly explain why these columns matter for your analysis.

---

## 2) Fare & Survival (Week 5 core)
**Task 2 — Fare distribution (histogram + KDE).**  
Create a histogram and a KDE of `fare`. Discuss right-skew, outliers, and a socioeconomic interpretation.

**Task 3 — Fare × Survival (distribution comparison).**  
Compare `fare` distributions for `survived = 0` vs `1` (e.g., overlaid KDEs). Focus your interpretation on **distribution shapes**, not just means.

---

## 3)  Week-6 Add-Ons (exactly three plots)

**Task 4 — Boxplot across multiple groups (fare).**  
Make a boxplot of `fare` grouped by `pclass`, with an additional split by `sex`. Interpret what differs across groups.

**Task 5 — Violin (age by sex).**  
Create a violin plot of `age` by `sex`. State any meaningful differences and what they suggest.

**Task 6 — Strip (detail on top of violin or boxplot).**  
Overlay individual observations to expose clusters and outliers. Explain what becomes visible with points that’s not obvious from the aggregate shape alone.

---

## 4) Submission
1. Work in **Google Colab**.  
2. Push your notebook to **GitHub**.  
3. Post your **GitHub link** in **MS Teams**.  
4. Keep code clean and commented; label axes; add concise captions.
