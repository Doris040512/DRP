📘 Sensitivity Analysis in Causal Inference

Author: Shuozishan (Doris) Wang
Mentor: Kenny Zhang

📌 Overview

This repository contains my research project on Sensitivity Analysis in Causal Inference, including a written report and a presentation.

Causal inference aims to understand cause-and-effect relationships, but observational data often suffer from unmeasured confounding. Sensitivity analysis provides a principled way to assess how robust a causal conclusion is when hidden bias may be present.

This project explains key concepts such as:

Correlation vs. Causation

Directed Acyclic Graphs (DAGs)

The Potential Outcomes Framework

Omitted Variable Bias (OVB)

Robustness Value (RV)

Partial R²

📂 Repository Structure
📁 sensitivity-analysis-causal-inference
│── Report.pdf          # Final written report (full explanation)
│── Presentation.pdf    # Slides for presentation
│── README.md           # Project description

🧠 Key Concepts
1. Correlation vs. Causation

The report highlights that correlation alone does not imply causation. For example, in the smoking–lung cancer scenario, an unmeasured confounder such as genetics may explain the observed association (see DAG on Presentation page 4).

2. Potential Outcomes Framework

As summarized in your report (page 1):

Y(1): outcome under treatment

Y(0): outcome under control

Causal effect: τ = Y(1) − Y(0)

This framework underpins many modern causal inference methods.

3. Omitted Variable Bias & Sensitivity Analysis

Your report describes how missing confounders distort causal estimates. Sensitivity analysis quantifies how strong an unmeasured confounder must be to overturn a conclusion (Report page 1).

This is reinforced in your slides (Presentation pages 6–7).

4. Robustness Value (RV) and Partial R²

From your slides (Presentation page 7):

RV: minimum confounder strength needed to explain away the observed effect

Partial R²: how strongly a confounder relates to both treatment and outcome

These tools help determine whether the causal claim is solid or fragile.

📑 Files Included
🔹 Final Report

A written explanation of all theoretical concepts and the importance of sensitivity analysis in observational studies.
👉 See Report.pdf (uploaded) 

Report

🔹 Presentation Slides

A visual summary, including diagrams, DAGs, and formula highlights.
👉 See Presentation.pdf (uploaded) 

Presentation

🎯 Why This Project Matters

Sensitivity analysis is essential in non-randomized studies—common in economics, social sciences, medicine, and policy research. When randomized trials are impossible, it provides the only principled way to judge whether findings are trustworthy despite hidden confounding.

📚 References

Key references included in your project (Presentation page 9):

Cinelli & Hazlett (2020). Making Sense of Sensitivity

Ding (2023). A First Course in Causal Inference

Microsoft Data Science Blog on causal analysis

🚀 Future Work

Implement Rosenbaum bounds

Add code reproducing RV/partial R² plots

Extend to nonlinear models or matching-based causal inference

🙋‍♀️ Contact

Feel free to reach out for collaboration or discussion!
