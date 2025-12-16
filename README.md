Project: College Student Feedback Analysis
Intern: Krishnasree R
Date: December 16, 2025

PROJECT OVERVIEW:
This project analyzes 1,000 student feedback responses to identify drivers of course satisfaction. Since the data contained only numerical ratings, K-Means Clustering was used to segment students into distinct behavioral groups ("Independent Learners", "High-Support Seekers", etc.) to provide targeted recommendations for curriculum improvement.

FILES INCLUDED:
1. analysis_and_clustering.ipynb
   - The Jupyter Notebook containing all Python code for data cleaning, correlation analysis, and K-Means clustering.

2. cleaned_student_feedback.csv
   - The processed dataset used for the analysis (ID columns removed, headers renamed).

3. Student Feedback Analysis Report.pdf
   - A professional business report summarizing the methodology, visual insights, and strategic recommendations.

4. images/ (Folder)
   - Contains the generated charts used in the report:
     * avg_ratings_clean.png
     * correlation_heatmap_clean.png
     * student_segments_clean.png

HOW TO RUN THE CODE:
1. Ensure you have Python installed with the following libraries:
   - pandas
   - matplotlib
   - seaborn
   - scikit-learn

2. Open 'analysis_and_clustering.ipynb' in Jupyter Notebook or Google Colab.

3. Make sure 'cleaned_student_feedback.csv' is in the same directory (or upload it to Colab).

4. Run all cells to reproduce the visualizations and clustering analysis.

KEY INSIGHTS:
- Strength: Subject Knowledge (7.5/10) is the course's strongest asset.
- Weakness: Support Consistency (High Variance).
- Finding: Students who received the most help ("High-Support Seekers") were not the most satisfied, suggesting a need for structured tutorials rather than just Q&A support.
