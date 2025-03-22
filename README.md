# COSMIC-CLASSIFIER-Galactic-Classification-Challenge
Cognizance 2025(IITR) Hackathon

INTRODUCTION 
In 2547, Dr. Klaus Reinhardt, a renowned scientist and explorer, made a groundbreaking discovery while traversing a distant galaxy. After years of experimentation, he successfully categorized planets based on their potential for human survival and use. However, as fate would have it, his ship was caught in the gravitational pull of a black hole. In his final moments, he transmitted the data to Earth before being consumed by the singularity.

Unfortunately, the immense gravitational forces of the black hole caused interference during transmission, permanently removing some part of data while adding noise to some parts. The names of the categories, though not meaning anything, are standard use in the scientific community. Humanity is relying on you to classify planets accurately to secure our survival.

This repository contains my solution for the COSMIC CLASSIFIER hackathon project, where I developed a machine learning model to classify planets based on their attributes.

Problem Statement

The dataset contains 10 attributes of planets, such as atmospheric density, surface temperature, gravity, and water content. The goal is to classify each planet into one of 10 categories (e.g., Bewohnbar, Terraformierbar, Rohstoffreich) using a machine learning model. The dataset is noisy and contains missing values, adding complexity to the task.

Dataset Details

Input Features
1. Atmospheric Density: Measure of the thickness of the planet's atmosphere (in kg/m³).
2. Surface Temperature: Average surface temperature of the planet (in Kelvin).
3. Gravity: Surface gravity of the planet (in m/s²).
4. Water Content: Percentage of the planet's surface covered by water (0-100%).
5. Mineral Abundance: Index representing the availability of valuable minerals (scale 0-1).
6. Orbital Period: Time the planet takes to orbit its star (in Earth days).
7. Proximity to Star: Distance from the planet to its star (in AU).
8. Magnetic Field Strength: Measure of the planet's magnetic field (in Tesla).
9. Radiation Levels: Average radiation levels on the planet's surface (in Sieverts/year).
10. Atmospheric Composition Index: Index measuring the suitability of the atmosphere for human life (scale 0-1).


Output Classes
The transmitted classifications are as follows, but their meanings remain unclear.
1. Bewohnbar
2. Terraformierbar
3. Rohstoffreich
4. Wissenschaftlich
5. Gasriese
6. Wüstenplanet
7. Eiswelt
8. Toxischetmosäre
9. Hohestrahlung
10. Toterahswelt



How to Replicate My Results

1.Clone the repository:

git clone https://github.com/your-username/cosmic-classifier.git
cd cosmic-classifier

2.Install dependencies:

pip install -r requirements.txt

3.Open the Jupyter notebook:

jupyter notebook notebooks/cosmic_classifier.ipynb

4.Run the notebook cells to preprocess data, train the model, and generate predictions.
