# Candidate Assessment using Emotion, Gaze, and Transcript Data

This project analyzes multi-modal data from candidate introduction videos — including emotion scores, gaze tracking, and transcripts — to evaluate recruitability, communication skills, and suitability for various job roles. The approach combines data science techniques, prompt engineering, and NLP to derive meaningful insights and recommendations.

## 📌 Problem Statement

The objective is to evaluate 10 candidates based on:

- Emotional consistency and variability
- Communication strengths and sentiment
- Gaze behavior and attentiveness
- Skillset and resume data

The end goal is to recommend job roles (e.g., Software Engineer, Data Analyst) based on a comprehensive scoring mechanism.

## ⚙️ Methodology

1. **Data Preprocessing**  
   - Emotion, gaze, and transcript CSVs were loaded and cleaned.
   - Organized into structured Pandas DataFrames.

2. **Primary Analysis**  
   - Statistical and visual exploration of emotion and gaze data.
   - Sentiment and behavioral analysis of transcripts.
   - Final composite scoring using weights derived through prompt engineering.

3. **Secondary Analysis**  
   - Feature correlation and dependency checks using heatmaps.
   - Outlier detection and reassessment of average-based scoring.
   - Dimensionality reduction by removing highly correlated features.

4. **Soft Skills Inference & Job Suggestions**  
   - Soft skill estimation using behavioral indicators.
   - Scaled scores with job-role matching algorithms (multiple approaches used).

5. **Insights**  
   - Role fitment for each candidate.
   - Emotional consistency and soft skill mapping.

## 📊 Tools & Technologies

- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-learn, NLTK
- **Other:** Prompt Engineering (GPT-based), Natural Language Processing

## 🚀 How to Run

1. Clone the repository:
   git clone https://github.com/sidbajaj/emotion-candidate-analysis.git
   cd emotion-candidate-analysis
Install required packages:
pip install -r requirements.txt
Run the notebook:
jupyter notebook candidate_analysis.ipynb

📁 Folder Structure
emotion-candidate-analysis/
├── data/
│   ├── candidate_*.csv       # Emotion, Gaze, and Transcript data
├── notebooks/
│   ├── candidate_analysis.ipynb
├── prompt_engineering/
│   ├── weight_generation_prompts.md
├── outputs/
│   ├── visualizations/
│   └── final_scores.csv
├── README.md
└── requirements.txt

📌 Key Findings
Candidates 6, 2, and 8 showed strong potential for technical roles.

Emotional consistency was a key differentiator.

Transcript confidence and sentiment were crucial in assessing communication.

Gaze data helped spot signs of nervousness or distraction.

Created by Sidharth Bajaj
Let me know if you'd like help generating the `requirements.txt`, sample data structure, or setting up `.gitignore`!







