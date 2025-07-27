# Analysis of Indian Railways Ticket Confirmation

### Project Overview

This project is the capstone for the Google Data Analytics Professional Certificate. The objective is to analyze a synthetic dataset of Indian Railway ticket bookings to identify key factors that influence the confirmation of waitlisted tickets. The goal is to provide actionable insights for travelers to help them make smarter booking decisions.

---

### Data Source

The dataset used for this analysis is a synthetic dataset of railway bookings.

**Important Note:** As the data is synthetic, some features are uniform. For instance, all bookings were found to be made exactly 244 days prior to the journey. The analysis, therefore, focuses on other variables to uncover insights.

---

### Tools Used

- **Python:** For data analysis and manipulation.
- **Pandas:** For data wrangling and cleaning.
- **Matplotlib & Seaborn:** For data visualization.
- **Google Colab:** As the development environment.

---

### Key Questions & Insights

1.  **How do Travel Class and Quota interact?**
    - **Insight:** The combination of class and quota is a powerful predictor. The 'Ladies' quota in 1AC has the highest confirmation rate (37.6%), while 'Tatkal' in Sleeper has the lowest (31.3%).

2.  **Does group size affect confirmation?**
    - **Insight:** Yes, there's a clear penalty for larger groups. Solo travelers have a ~34% confirmation rate, which drops to ~32% for groups of five.

3.  **How does group size impact different classes?**
    - **Insight:** The negative effect of group size is most severe in premium classes. For groups of 4+, it's statistically better to book in 3AC or Sleeper than in 1AC.

---

### Actionable Recommendations

- **For Solo Travelers:** The 'Ladies' quota in 1AC offers the highest probability of confirmation.
- **For Large Groups (4+):** Book in 3AC or Sleeper class, as your confirmation chances will be significantly higher than in premium classes.
- **For All Travelers:** If possible, book your tickets on a weekday (especially Friday) rather than on the weekend.

---

### How to Use This Repository

1.  Clone the repository: `git clone [your-repo-link]`
2.  The full analysis can be found in the `notebooks/eda.ipynb` file.
3.  A summary of the findings is available in the `presentation/` folder.