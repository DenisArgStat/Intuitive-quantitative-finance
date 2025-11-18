About This Article

This folder contains all materials for the article
“Option Pricing from First Principles: An Intuitive and Deep Exploration.”

The article is structured as a complete, self-contained journey through the mathematics and intuition of European option pricing.
Here is what we explore together:
    1.    The definition of European options (calls and puts) and their payoff structures.
    2.    The fundamental challenge of pricing derivatives before expiration.
    3.    Put–call parity, showing how the price of one option can be expressed through another together with the underlying asset and a risk-free bond.
    4.    Delta hedging, demonstrating how an option can be priced independently by dynamically managing a portfolio of the underlying asset and a risk-free asset.
    5.    The binomial tree model — the most intuitive discrete method for option pricing.
    6.    How the binomial model naturally leads to random walks, Itô’s lemma, and the idea of expressing option value changes through a differential equation.
    7.    The derivation of the Black–Scholes PDE, including continuous hedging, risk neutrality, and their implications.
    8.    A brief introduction to other PDEs — Laplace, Poisson, and heat equations — to build intuition for diffusion and its economic interpretation.
    9.    How the Black–Scholes PDE is actually a transformed heat equation, and how reversing the transformation gives an elegant convolution-based solution.
    10.    The closed-form Black–Scholes formula, derived step by step.
    11.    How this framework extends to other options simply by changing the payoff and reapplying the same logic.
    12.    A visual intuition and intriguing properties on why a call is usually more expensive than a put, and why the call price never falls below its payoff while the put can.

⸻

Links to the Article

You can read this article online:

📄 Medium 


💼 LinkedIn 


Both versions point readers back to this GitHub repository for:
    •    reproducible code,
    •    detailed formulas,
    •    figures and animations,
    •    and full mathematical derivations.
    
⸻

How to Use This Folder

This article is supported by three main components:

⸻

1. Jupyter Notebook (Notebook.ipynb)

The notebook mirrors the structure of the article.

Each section contains:
    •    the exact Python code that generates the graphs, visualizations and formulas used in the article
    •    additional examples that did not fit in the written article
    •    interactive elements to modify parameters and experiment

If you want to reproduce or extend any figure from the article, start here.

⸻

2. Figures (figures/)

All images and animations used in the article:
    •    payoff diagrams
    •    binomial trees
    •    convolution animations
    •    Gaussian/lognormal kernels
    •    PDE visualizations
    •    comparative call/put properties

Images are generated automatically by the notebook and saved here.

⸻

3. Formulas (formulas/)

Medium does not support LaTeX, so all mathematical expressions used in the article are saved here as PNG images.

This folder contains:
    •    PNG exports of every formula generated from LaTeX in the notebook

The notebook includes the corresponding LaTeX code for each formula, so you always retain a clean, editable copy.

⸻

Structure of Each Section in the Notebook and Article

Every section follows the same pattern:
    1.    Graphs or animations
    •    produced by Python, with code visible
    2.    Code snippets
    •    the exact code included in the article
    3.    Mathematical formulas
    •    LaTeX source
    •    auto-exported PNG version for Medium
