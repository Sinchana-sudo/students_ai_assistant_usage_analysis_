 AI Assistant Usage in Student Life

Overview
This project analyzes the usage patterns, satisfaction levels, and correlations of AI assistance among students across different academic disciplines. Using both visual analytics and statistical correlations, it aims to understand how AI-powered tools impact student productivity, engagement, and satisfaction.

The dataset contains **10,000 session records** with details such as session length, number of prompts, task type, AI assistance level, and satisfaction ratings.

Project Files
- **`ai_assistant_usage_student_life.csv`** → Raw dataset of AI assistant usage by students.
- **`final report.ipynb`** → Jupyter Notebook containing data cleaning, analysis, and visualizations.
- **`final.pbix`** → Power BI dashboard for interactive exploration.
- **Images**:
  - Correlation heatmap
  - Monthly session count trend
  - Average satisfaction by task type

Dataset Description
| Column Name         | Description |
|---------------------|-------------|
| SessionID           | Unique identifier for each session |
| StudentLevel         | Academic level (Undergraduate, Postgraduate, etc.) |
| Discipline           | Field of study |
| SessionDate          | Date of session |
| SessionLengthMin     | Duration of the session in minutes |
| TotalPrompts         | Number of prompts exchanged |
| TaskType             | Type of task (e.g., Coding, Writing, Studying) |
| AI_AssistanceLevel   | Degree of AI involvement (scale 1-5) |
| FinalOutcome         | Result of the session |
| UsedAgain            | Whether the student would use the AI assistant again |
| SatisfactionRating   | Rating of satisfaction (scale 1-5) |

---

## 📊 Key Insights

### 1. Correlation Analysis
- **High correlation (0.90)** between `SessionLengthMin` and `TotalPrompts`.
- **Strong positive correlation (0.78)** between `AI_AssistanceLevel` and `SatisfactionRating`.
- Minimal correlation between session length and satisfaction.


<img width="800" height="600" alt="plot3_correlation_heatmap" src="https://github.com/user-attachments/assets/8c69ff82-a0e9-47be-9825-00bbf46387b7" />

---

### 2. Monthly Session Trends
- Sessions peaked in **August 2024** (~900 sessions) and **January 2025** (~890 sessions).
- Seasonal dips are observed in **June** and **December**, possibly due to academic breaks.


<img width="800" height="500" alt="plot2_monthly_sessions" src="https://github.com/user-attachments/assets/cfd0937f-730d-47e6-9682-95f43d33443f" />

---

 3. Satisfaction by Task Type
- **Highest satisfaction**: Homework Help & Coding (~3.4/5 average rating).
- **Lowest satisfaction**: Research (~3.3/5 average rating).
- All task types maintain ratings above 3.3, showing overall positive user experience.

<img width="800" height="500" alt="plot1_tasktype_vs_satisfaction" src="https://github.com/user-attachments/assets/ed7dfa43-c642-4b81-b79c-2aea437a978b" />

Conclusion
- Students who receive higher levels of AI assistance tend to report **greater satisfaction**.
- Session length is highly tied to the number of prompts, suggesting more engagement leads to longer sessions.
- While satisfaction is generally high across task types, research tasks could benefit from more tailored AI support.
- Seasonal trends highlight peaks during active academic months and drops during breaks.

 How to Use
1. **View the Power BI dashboard (`final.pbix`)** for interactive exploration.
2. **Run the Jupyter Notebook (`final report.ipynb`)** to reproduce the analysis.
3. **Explore `ai_assistant_usage_student_life.csv`** for raw data insights.
4.**For excel file(`final_draft_ai_usage.xlsx`)** for cleaned data
