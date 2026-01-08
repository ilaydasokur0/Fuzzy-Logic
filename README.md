A Fuzzy Logic Based Price Estimation System for Second-Hand Clothing
This repository contains a Mamdani-type Fuzzy Inference System (FIS) designed to minimize human-induced uncertainty and subjective biases in second-hand clothing pricing. The project is backed by a comprehensive academic study and mathematical modeling.

📌 Project Overview
Pricing in the second-hand market is often inconsistent due to subjective evaluations. This system normalizes product features into mathematical variables to calculate an automated and fair "Price Multiplier" using fuzzy logic.

🛠 Technical Specifications
Methodology: Mamdani Fuzzy Inference System

Toolbox: MATLAB Fuzzy Logic Toolbox

Defuzzification: Centroid Method

Rule Base: 27 specifically defined "If-Then" rules for logical decision making.

📊 Model Inputs & Outputs
The system evaluates three primary criteria, all normalized to a [0, 1] range:

Brand Segment: Economy, Highstreet, Luxury.

Condition (Wear & Tear): Damaged, Used, New.

Material Quality: Synthetic, Natural, Noble.

Output: * Price Multiplier: A 5-level linguistic grading (Very Low to Very High) that calculates the final suggested price when applied to the base value.

📈 Performance & Validation
The model was validated using 20 real-world data points sourced from the "Dolap" e-commerce application.

Accuracy Rate: 93.59%

Mean Error: 6.41%

📂 Repository Structure
Fuzzy Final Final.zip: The core FIS file containing the membership functions and rule base (MATLAB).

Project.Paper.pdf: The full academic paper/report detailing the mathematical background, literature review, and experimental results.
