# Palmer Penguins — Quick Classroom Cheat Sheet

- **What it is:** Real-world measurements for three Antarctic penguin species—**Adélie, Chinstrap, Gentoo**—collected near **Palmer Station** (Antarctica). Designed as a friendlier, more engaging alternative to the Iris dataset.

- **Who:** Field data by **Dr. Kristen Gorman** with the **Palmer Station LTER** program; organized for teaching by **Allison Horst, Alison Hill, and Kristen Gorman** (the “palmerpenguins” project).

- **When:** Observations from **2007–2009**.

- **Where:** Three islands in the Palmer Archipelago — **Biscoe**, **Dream**, **Torgersen**.

- **How many rows:** **344 penguins** total.

- **Core variables (with units):**
  - `species` (Adélie / Chinstrap / Gentoo)
  - `island` (Biscoe / Dream / Torgersen)
  - `sex` (male / female; some missing)
  - `year` (2007–2009)
  - `bill_length_mm` (mm)
  - `bill_depth_mm` (mm)
  - `flipper_length_mm` (mm)
  - `body_mass_g` (g)

- **Data quality notes:**
  - Contains **missing values** (e.g., sex or some measurements) — great for practicing cleaning.
  - Measurement scales are consistent (mm, g), so unit conversions are minimal.

- **Why it’s great for teaching:**
  - **Clear species separation** in simple 2D plots (e.g., bill length vs bill depth).
  - Multiple categorical factors (`species`, `island`, `sex`, `year`) enable **grouped visuals** and **faceting**.
  - Natural context to discuss **sampling**, **confounding**, and **ethics** (wildlife studies).

- **Typical beginner plots:**
  - Scatter: `bill_length_mm` vs `bill_depth_mm` (color by `species`)
  - Hist/KDE: `flipper_length_mm` by `species`
  - Bar or box/violin: `body_mass_g` by `species` (optionally split by `sex`)
  - Facet by `island` or `year`

- **Common classroom tasks:**
  - Handle **NAs** (drop, impute, or explain impact).
  - Compare species means with **CIs**; discuss overlap vs separation.
  - Build a simple **classifier** (e.g., logistic regression/KNN) using two features.
  - Practice **tidy data** operations: groupby → summarize → visualize.

- **License & sharing:** **CC0 (public domain)** — free to use in slides, assignments, and handouts.

- **Attribution (paste-ready):**
  - “Data collected by Dr. Kristen Gorman and the Palmer Station Antarctica LTER; compiled for teaching by Horst, Hill, & Gorman (palmerpenguins).”

- **One-liner for your slide:**
  - “344 penguins, 3 species, 3 islands (2007–2009) — clean units (mm, g), a few NAs, and crystal-clear species patterns. Perfect for demoing tidy analysis and visualization.”
 
  [Slides: The untold Story of Palmerpenguins](https://apreshill.github.io/palmerpenguins-useR-2022/#/title-slide)
