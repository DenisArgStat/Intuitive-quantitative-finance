Materials for the Article

“The Geometry of Option Pricing: An Intuitive and Visual Guide”

This folder contains all supporting materials for the article — code, figures, LaTeX formulas, and animations.

The article is designed as a complete, self-contained journey through the intuition and mathematics of European option pricing.

What we explore together
	1.	The definition of European options (calls and puts) and their payoff structures.
	2.	The fundamental challenge of pricing derivatives before expiration.
	3.	Put–call parity: expressing one option through another, the underlying asset, and a risk-free bond.
	4.	Delta hedging: how to price an option independently by dynamically managing a portfolio.
	5.	The binomial tree model — the most intuitive discrete method for pricing.
	6.	How the binomial model naturally leads to random walks, Itô’s lemma, and the need for a differential equation.
	7.	The derivation of the Black–Scholes PDE: continuous hedging, risk neutrality, and deeper implications.
	8.	A short introduction to Laplace, Poisson, and heat equations to build diffusion intuition.
	9.	How the Black–Scholes PDE becomes a heat equation after a clever transformation — enabling a beautifully simple solution.
	10.	The closed-form Black–Scholes formula, derived step by step.
	11.	How the same logic extends to any option simply by changing the payoff.
	12.	Visual intuition and surprising properties: why calls are typically more expensive than puts, why a call price never falls below its payoff while a put can.

⸻

Links to the Article

You can read the full article online:

📄 Medium: 
💼 LinkedIn: 

Both versions link back to this repository for:
	•	reproducible code
	•	all formulas in PNG + LaTeX source
	•	figures and animations
	•	full derivations
	•	extended examples beyond the original article

⸻

How to Use This Folder

The repository contains three main components:

⸻

1. Jupyter Notebook (Notebook.ipynb)

This is the heart of the project.

The notebook mirrors the article section by section:
•	full Python code for every graph, animation, and formula
•	interactive cells for experimentation
•	LaTeX formulas that auto-export to PNG

Start here if you want to reproduce or modify any material.

⸻

2. Figures (figures/)

All static images and animations used in the article:

All images and animations used in the article:
•    1_call_payoff.png
•    1_put_payoff.png
•    2_european_call_prices_for_different_maturities.png
•    2_european_call_option_payoff_at_expiry.png
•    3_put-call_parity.png
•    3_put-call_parity_call_price.png
•    4_delta_hedge.png
•    5_binomial_stock_model.png
•    5_binomial_tree_european_call.png
•    5_binomial_tree_european_call_8_layers.png
•    5_binomial_tree_european_call_different_number_of_layers.png
•    10_convolution_logic.gif
•    12_log_normal_kernel_product.png
•    12_normal_kernel_product.png

Images are generated automatically by the notebook and saved here.

⸻

3. Formulas (formulas/)

Medium does not support LaTeX, so every mathematical expression in the article is stored here as PNG.

The folder contains:
	•	high-resolution PNG exports
	•	original LaTeX code (in the notebook)

This ensures the formulas remain editable and easy to reuse.

⸻

Structure of Each Section (Notebook)

Every section follows the same pattern:
1.	Graphs or animations
Generated with Python (Matplotlib), fully reproducible.
2.	Code snippets
Exactly the code shown in the article.
3.	Mathematical formulas
LaTeX → automatically exported PNGs for Medium.