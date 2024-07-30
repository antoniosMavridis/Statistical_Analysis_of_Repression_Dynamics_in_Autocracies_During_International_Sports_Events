# Statistical_Analysis_of_Repression_Dynamics_in_Autocracies_During_International_Sports_Events
In this project we will replicate partly a study on the relationship between repression in autocratic regimes and international sports events:
* [Scharpf, A., Gläßel, C., Pearce, E. (2022) *International Sports Events and Repression in Autocracies: Evidence from the 1978 FIFA World Cup*, American Political Science Review, 1-18.](https://www.cambridge.org/core/journals/american-political-science-review/article/abs/international-sports-events-and-repression-in-autocracies-evidence-from-the-1978-fifa-world-cup/19FA0D5B0DD55259AA6A3E4FEBB7978A). 
This project uses statistical techniques to analyze the impact of international sports events on repression in autocratic regimes, focusing on the 1978 FIFA World Cup in Argentina. It employs regression models, data visualization, and robustness checks to explore how regimes adjust repression under international media scrutiny.

## Objectives

The project is divided into five core tasks:

### 1. Data Replication and Descriptive Analysis
  - Replication of summary statistics in Tables SI.3.1 and SI.3.2.
    - **Table SI.3.1**: Shows summary statistics for all variables used in the main analyses, robustness checks, and mechanism tests at the department-day level.
    - **Table SI.3.2**: Summarizes the variables used to analyze repression during and after the 1978 FIFA World Cup
  - Visualization of trends:
    - **Figure 1**: Depicting the increasing trend of autocratic regimes hosting international sports events.
    - **Figure SI.1.1**: Illustrating the political nature (autocratic vs. democratic) of host countries since 1945.

### 2. Hypothesis Testing Using Regression Analysis

- Test hypotheses on the timing and location of state repression related to international sports events.
  - **Hypotheses**:
    - **H1**: Increased repression in host cities during the lead-up to events, not mirrored in non-host cities.
    - **H2**: Reduced repression in host cities during the event itself, with no change in non-host cities.
  - **Techniques**:
    - Implementation of Ordinary Least Squares (OLS) regression using **statsmodels** to estimate the impact of international events on repression levels, with comparison to negative binomial models for robustness.

### 3. Visualization of Repression Trends

- Reproduction of **Figure 5** from the main study which provide a detailed visualization of repression trends before, during, and after the 1978 FIFA World Cup.

### 4. Robustness Check Using Logistic Regression

- Confirm findings using alternative measures of repression by conducting logistic regression on a binary outcome of repression (presence vs. absence) as a robustness check, utilizing **statsmodels** for analysis, and aligning results with those reported in Table SI.4.5 of the Supporting Information.

### 5. Matched Samples Analysis
- Validate findings through controlled comparisons between matched samples of departments by implementing both manual and algorithmic matching techniques to create comparable groups of departments with and without host cities, replicating Table SI.4.7 and Figure 6

## Conclusion

This project leverages statistical modeling, data visualization, and robust analytical techniques to explore the dynamics of repression in autocratic regimes during international sports events. The findings contribute to a deeper understanding of how these events are used as tools of both international diplomacy and domestic control.

