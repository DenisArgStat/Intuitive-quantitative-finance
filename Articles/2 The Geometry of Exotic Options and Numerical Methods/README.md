Materials for the Article

“The Geometry of Exotic Options: Visual Intuition and Numerical Methods”

This folder contains all supporting materials for the article — code, figures, LaTeX formulas, and animations.

The article is designed as a complete, self-contained journey through the intuition and mathematics of exotic option pricing and numerical methods.

What we explore together
    1.  A clear classification of exotic options, organised by the structural feature that shapes their behaviour: exercise features, reset / multi-period structure, multi-asset interactions, state-space–restrictions , and path accumulating logic.
    2.  How each of these exotic families modifies the geometry of the pricing problem - by adding dimensions, introducing boundaries, resetting payoffs, or creating memory through path dependence.
    3.  Why these geometric changes break the assumptions that make the Black–Scholes formula easily solvable, and why closed-form solutions exist only in special cases.
    4.  How finite-difference schemes (explicit, implicit, Crank–Nicolson) generalize the heat-equation intuition to handle early exercise, barriers, and other structural constraints.
    5.  How projection and constraint-solving methods (PSOR, projected Newton, semi-smooth Newton) enforce the exercise condition in American-style problems.
    6.  How Poisson subordination ideas extend the heat-equation intuition.
    7.  How Monte-Carlo methods tackle high-dimensional and path-dependent exotics, including regression for early-exercise and stochastic mesh techniques.
    8.  Why quasi–Monte-Carlo (low-discrepancy) sequences often outperform standard simulation by injecting structure into the sampling of uncertainty.
    9.  How the choice of numerical method shapes accuracy, stability, and computational cost, and how practitioners balance these trade-offs when implementing real pricing engines
    10. Finally, a practical map matching each numerical method to each exotic option type - showing where each approach shines, where it struggles, and how practitioners make choices in real pricing systems.

⸻

Links to the Article

You can read the full article online:

📄 Medium: 
💼 LinkedIn: 

Both versions link back to this repository for:
    •    reproducible code
    •    all formulas in PNG + LaTeX source
    •    figures and animations
    •    full derivations
    •    extended examples beyond the original article

⸻

How to Use This Folder

The repository contains three main components:

⸻

1. Jupyter Notebook (Notebook.ipynb)

This is the heart of the project.

The notebook mirrors the article section by section:
•    full Python code for every graph, animation, and formula
•    interactive cells for experimentation
•    LaTeX formulas that auto-export to PNG

Start here if you want to reproduce or modify any material.

⸻

2. Figures (figures/)

All static images and animations used in the article:

All images and animations used in the article:
•    2_option_on_option.gif
•    2_call_on_put_on_call_3_layers_logic.png
•    2_payoff_geometry_usual_call_vs_call_on_call.png
•    2_bermudian_option_logic.png
•    2_bermudian_european_compare.png
•    2_american_european_compare.png
•    2_cliquet_2d_call_log_domain.gif
•    2_cliquet_2d_standard.gif
•    2_cliquet_option_payoff.png
•    2_cliquet_payoff.png
•    2_cliquet_pipeline.gif
•    2_bivariate_transition_kernel_different_p.png
•    2_best_of_call_pipeline.gif
•    2_bestof_call_convolution_logS.gif
•    2_margrabe_convolution_logS.gif
•    2_margrabe_pipeline.gif
•    2_spread_call_convolution_logS.gif
•    2_spread_option_pipeline.gif
•    2_image_method_for_the_1D_heat.png
•    2_barrer_call_convolution.gif
•    2_barrer_call_pipeline.gif
•    2_lookback_call_pipeline.gif
•    2_lookback_kerenl_difusion.png
•    2_lookback_fixed_strike_convolution.gif
•    2_asian_call_pipeline.gif
•    2_asian_convolution.gif
•    4_FTCS_for_option_pricing_PDE.png
•    7_MC_logic.gif
•    8_qmc_sobol_call.png

Images are generated automatically by the notebook and saved here.

⸻

3. Formulas (formulas/)

Medium does not support LaTeX, so every mathematical expression in the article is stored here as PNG.

The folder contains:
    •    high-resolution PNG exports
    •    original LaTeX code (in the notebook)

This ensures the formulas remain editable and easy to reuse.

⸻

Structure of Each Section (Notebook)

Every section follows the same pattern:
1.    Graphs or animations
Generated with Python (Matplotlib), fully reproducible.
2.    Code snippets
Exactly the code shown in the article.
3.    Mathematical formulas
LaTeX → automatically exported PNGs for Medium.
