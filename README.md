# Cognitive-load-analytics-in-VR_Capstone
Cognitive Load Analytics in VR Cooking Tasks
Overview
This project investigates how action-based metrics derived from VR cooking tasks can reflect differences in cognitive performance. Participants completed tasks of varying complexity (e.g., Simple Pie, Complex Stew), and their interaction data were analyzed using two-way ANOVA and post-hoc tests. The metrics were also correlated with cognitive scores (Block Design Test) to identify behavioral markers of mental effort and skill.
Objectives
•⁠  ⁠Quantify how task complexity and recipe type affect interaction metrics in VR.
•⁠  ⁠Use ANOVA to detect group-level performance differences.
•⁠  ⁠Explore correlations between action metrics and cognitive ability (BDT score).
Key Metrics Analyzed
Metric	Interpretation
Median Inter-Action Interval	Overall pacing of task execution
25th and 75th Percentiles	Fastest and slowest interaction bounds
Average Inter-Action Interval	Overall temporal rhythm of user actions
Inter-Action Interval STD	Variability in user pacing
Grab-None Count	Ineffective hand actions (e.g., empty grabs)
Action Repetition Count	Hesitation or redundant behaviors
Inter-Hand Coordination Index	Switching coordination across hands
Grab-Cookbook Count	Visual aid reliance (external cognitive support)
Results Summary
•⁠  ⁠Significant effects were found for:
  • 25th Percentile (p = 0.028)
  • 75th Percentile (p = 0.007)
  • Average Inter-Action Interval (p < 0.01 in post-hocs)
  • Inter-Action Interval STD (p = 0.021)
  • Grab-Cookbook Count (Recipe type effect: p = 0.006)
•⁠  ⁠Correlations with BDT (Cognitive Score):
  • Weak negative correlations overall (ρ from -0.21 to -0.04)
  • Strongest negative trends with:
     - Grab-Cookbook Count
     - Action Repetition Count
     - Inter-Action STD (especially for Simple Stew)
Folder Structure
VR_Cognitive_Load_Analytics/
├── data/
│   └── VR_Cognitive_Load_Features.csv
├── scripts/
│   └── VR_Cognitive_Load_Final_Analysis.ipynb
├── report/
│   ├── VR_Cognitive_Load_Report_Final.pdf
│   └── Capstone Report.pdf
├── images/
│   ├── latency_plot.png
│   ├── switch_lag_plot.png
│   └── correlation_heatmap.png
└── README.md
Tools & Technologies
•⁠  ⁠Python (pandas, seaborn, scipy, statsmodels)
•⁠  ⁠Jupyter Notebook
•⁠  ⁠ANOVA (Two-Way), Tukey's HSD
•⁠  ⁠Spearman Correlation
•⁠  ⁠GitHub for version control
Interpretation & Impact
Action-based VR metrics can provide subtle behavioral signatures of cognitive skill and load. Timing variability and reliance on external aids (like cookbooks) emerged as the strongest indicators. This project offers a scalable approach for studying cognitive performance using naturalistic VR tasks — relevant for training, assessment, and digital biomarker development.

Contact
For questions or suggestions, contact:
Neha Kowtharapu - nehakowtharapu@gmail.com
