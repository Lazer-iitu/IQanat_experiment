# Human vs AI Face Perception Experiment

This project presents a comparative experiment between human perception and
AI-based facial attribute analysis using the DeepFace library.

The experiment was designed and conducted as an educational and mentoring
example to demonstrate how real-world data science experiments are structured,
analyzed, and documented.

## Goal of the Experiment
To compare how accurately humans and artificial intelligence can predict
facial attributes such as:
- Age
- Gender
- Race

## Data Description
- 22 facial images with known ground-truth attributes
- Human participants: 20 school students (age 15)
- Human predictions collected via an online survey
- AI predictions generated using the DeepFace model

## Methodology
- Human and AI predictions were evaluated on the same image set
- Age predictions were converted into categorical bins
- Performance comparison was conducted using standard evaluation metrics

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- Mean Absolute Error (MAE)

##Findings
- Human participants outperformed AI in age and gender prediction
- AI showed higher precision in race classification
- The experiment highlights both strengths and limitations of AI perception
  compared to human cognition

## Educational Purpose
This project was used as a mentoring case study to teach school students:
- how to formulate a research question
- how to design and conduct an experiment
- how to analyze results using data science metrics
- how to present findings in a scientific-style paper

## Paper
The full experiment description and results are available in the accompanying
research paper:
`Human_and_AI_Face_Perception_Experiment.pdf`

## Tools & Technologies
- Python
- DeepFace
- Pandas, NumPy
- Kaggle
