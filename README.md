# **Analyzing Economic Trends: S&P 500 Performance, GDP Growth, and Presidential Impact**  
**By Abd Alghani Rahmoun and Cedric Nyagatare**  
**Date:** 12/7/2024  
**Course:** Whitman College, CS/MATH - 215 Intro to Data Science by Albert Schueller  

## **Introduction**  
This project investigates the correlation between presidential administrations, economic policies, and the performance of the S&P 500, spanning from 1992 to 2024. The study aims to analyze how varying political regimes—alongside control of the House and Senate—impact the U.S. stock market. We specifically focus on economic indicators, such as GDP growth, election cycles, and political power dynamics, to evaluate their effects on stock market performance. This research seeks to uncover trends and patterns that could offer insights into the interaction between economic policies and market behavior under different political conditions. The central question driving this research is: How do presidential administrations, economic growth indicators, and political control over Congress influence the S&P 500 performance over time?

### **Hypothesis**  
We hypothesize that Democratic presidencies are positively correlated with stronger S&P 500 performance, especially during economic recoveries. Furthermore, we expect that GDP growth rates will serve as a leading indicator for stock market returns. Additionally, we propose that market volatility will be higher during presidential election years, particularly in times of political transition.

## **Research Questions and Methodology**

This research is driven by several key questions, each aimed at analyzing specific aspects of the relationship between political control, economic performance, and stock market behavior. The following research questions guide the investigation:

### **Research Question 1**  
**How do different presidential administrations correlate with the performance of the S&P 500, and which president had the most significant impact on market performance?**

#### **Analysis Approach**  
To explore this question, we merged S&P 500 performance data with timelines of economic policy events, identifying critical dates for major policy changes. A time-series analysis was then conducted to compare pre- and post-policy stock performance across different presidential administrations. Statistical tests were used to verify the significance of observed differences in S&P 500 returns under different presidents.

#### **Findings**  
The analysis demonstrates that both Democratic and Republican presidencies have witnessed robust growth in the S&P 500. However, Democratic administrations, particularly during periods of economic recovery (e.g., Obama years), show sharper increases in stock prices. This suggests a positive correlation between policy support and market performance. The visual representation of this trend is shown below.

![S&P 500 Performance and GDP Trends](https://drive.google.com/file/d/1GSg1zKzPDAOznfS99_efjgGyUGI2pqBT/view?usp=drive_link)  
**Figure 1:** S&P 500 performance and GDP growth trends under Democratic (blue) and Republican (red) administrations.

---

### **Research Question 2**  
**What is the correlation between long-term economic growth indicators (like GDP growth rates) and the returns of the S&P 500? Are there periods where market performance leads or lags GDP growth?**

#### **Analysis Approach**  
To investigate this correlation, we aggregated GDP growth rate data with S&P 500 performance figures. We performed a lagged correlation analysis to determine whether GDP growth led or lagged S&P 500 returns, and used regression models to explore the predictive nature of GDP growth on stock market performance.

#### **Findings**  
The findings indicate a positive correlation between GDP growth and S&P 500 returns, with both economic indicators rising in tandem during periods of strong growth, such as the late 1990s and mid-2010s. This supports the notion that economic growth drives corporate earnings, which in turn boosts stock prices. The chart below provides a clear visualization of the correlation.

![S&P 500 vs GDP Growth](https://drive.google.com/file/d/1gry-ZZnNPumTI3QXLGhXdfklqlynxWbW/view?usp=sharing)  
**Figure 2:** Correlation between S&P 500 performance and GDP growth, showing the relationship across multiple presidential administrations.

---

### **Research Question 3**  
**Is there a pattern of stock market volatility that coincides with presidential election cycles? Does the S&P 500 experience more volatility during election years, and if so, does this vary by political party?**

#### **Analysis Approach**  
We calculated historical volatility metrics for the S&P 500, comparing election years to non-election years. The analysis also looked at whether volatility patterns differed based on the political party in power. Statistical tests were employed to assess whether election years exhibit more volatility and if this can be tied to party affiliation.

#### **Findings**  
The results show that the S&P 500 experiences higher volatility during presidential election years. This pattern is evident across both Democratic and Republican election cycles, with notable volatility spikes during the 2000, 2008, and 2016 elections. The increased uncertainty surrounding elections contributes to market fluctuations. The volatility trends are depicted in the following graph.

![Volatility Trends During Election Cycles](https://drive.google.com/file/d/1kdNkO8ddQNSOxSJqQjgnR4o_ooLjk_iK/view?usp=sharing)  
**Figure 3:** Volatility of the S&P 500 during election years, comparing Democratic (blue) and Republican (red) administrations.

---

### **Research Question 4**  
**How do different combinations of political control over Congress and the White House impact the S&P 500, and which combinations lead to the best or worst performance? Can market trends be predicted based on political control?**

#### **Analysis Approach**  
We calculated S&P 500 volatility under different combinations of political control (e.g., Democratic White House and Congress, Republican control, or divided government). We used regression analysis to identify correlations between political power structures and stock market performance, examining if certain combinations correlate with better or worse market outcomes.

#### **Findings**  
The data reveals that the S&P 500 tends to perform better when both the White House and Congress are controlled by the Democratic Party. Notably, this was seen in the early 1990s and during Obama's first two years. Divided government and Republican control showed relatively lower average returns. This suggests that political stability and unity in governance might contribute to more favorable market conditions. The chart below illustrates the performance of the S&P 500 across different political combinations.

![Political Control and S&P 500 Returns](https://drive.google.com/file/d/1fT4XguHfJVisC1O4fTry3OPJGsD22NIM/view?usp=sharing)  
**Figure 4:** S&P 500 performance based on political party control of Congress and the White House.

---

### **Research Question 5**  
**How has the performance of the S&P 500 varied across different industries over time, and what trends or patterns can be identified in sector-specific growth, volatility, and resilience to economic cycles?**

#### **Analysis Approach**  
We conducted a sector-specific breakdown of the S&P 500 performance, calculating key metrics such as average annual returns, volatility, and drawdowns for each industry. Time-series analysis was then performed to detect trends in sector growth and identify how industries reacted to macroeconomic events.

#### **Findings**  
Our analysis shows that sector performance varies widely, with the Technology sector experiencing substantial growth during the dot-com bubble and the mid-2010s. The Energy sector, in contrast, showed significant fluctuations tied to oil price changes. These variations highlight the need for diversified investments, as sector-specific events and policy changes can significantly impact overall market performance. The following chart shows the S&P 500 performance by sector over time.

![S&P 500 Performance by Sector](https://drive.google.com/file/d/1dE-EFTQ-LQmr_fC5z-JjjFfgpjDhZtKY/view?usp=sharing)  
**Figure 5:** S&P 500 performance by sector, comparing Democratic (blue) and Republican (red) presidencies.

---

## **Conclusions**

### **Summary of Findings**  
1. **Impact of Presidential Administrations on S&P 500 Performance**: Democratic administrations generally correlate with stronger market growth, particularly during recovery periods like the Obama years.
2. **Correlation Between GDP Growth and S&P 500 Returns**: There is a clear positive correlation, especially during periods of high GDP growth, aligning with economic theory.
3. **Stock Market Volatility During Presidential Election Cycles**: Volatility is higher in election years, likely due to political uncertainty.
4. **Impact of Congressional and White House Control on S&P 500**: Unified Democratic control of both the White House and Congress tends to result in higher market returns.
5. **S&P 500 Performance Across Different Industries**: Sector-specific performance is influenced by macroeconomic trends and policies, with significant variability across sectors such as Technology and Energy.

### **Limitations and Future Research**  
- **Limitations**: The analysis is limited by data constraints, such as the availability of accurate S&P 500 performance data by sector, and volatility concerns arising from extreme events like global crises (e.g., the 2008 financial crisis and the COVID-19 pandemic).
- **Future Research**: Further studies could explore the intersection of global political factors with U.S. market trends, as well as how sector-specific factors and geopolitical events influence market outcomes.

---

This revised structure enhances cohesion, ties together all research questions, and maintains a professional tone appropriate for academic writing. Each research question is clearly outlined with corresponding analysis and findings, while also adhering to the original content you provided. Let me know if you'd like any more adjustments!
