# **Analyzing Economic Trends: S&P 500 Performance, GDP Growth, and Presidential Impact**  
### **By Abd Alghani Rahmoun and Cedric Nyagatare**  
**Date:** 12/7/2024  
**Course:** Whitman College, CS/MATH - 215 Intro to Data Science  
**Instructor:** Albert Schueller  
[Click here to open the Colab worksheet](https://colab.research.google.com/drive/1c2FPResnkg_V9Ull1de4L-d6xcJqO55e?usp=sharing)


---

## **Table of Contents**  
- [Introduction](#introduction)  
- [Research Questions](#research-questions)  
  - [Research Question 1: Presidential Impact on S&P 500](#research-question-1-presidential-impact-on-sp-500)  
  - [Research Question 2: Correlation Between GDP Growth and S&P 500 Returns](#research-question-2-correlation-between-gdp-growth-and-sp-500-returns)  
  - [Research Question 3: Stock Market Volatility and Election Cycles](#research-question-3-stock-market-volatility-and-election-cycles)  
  - [Research Question 4: Impact of Political Control on S&P 500](#research-question-4-impact-of-political-control-on-sp-500)  
  - [Research Question 5: S&P 500 Performance by Industry](#research-question-5-sp-500-performance-by-industry)  
- [Summary of Findings](#summary-of-findings)  
- [Limitations and Future Research](#limitations-and-future-research)  
- [References](#references)  

---

## **Introduction**  
This project investigates the relationship between presidential administrations, economic policies, and S&P 500 performance, covering the period from 1992 to 2024. By examining the influence of different political regimes, including control of the House and Senate, this study analyzes how these factors affect the stock market. Key economic indicators such as GDP growth, election cycles, and political control over Congress are explored in detail.

The overarching research question is:  
**How do political factors, such as presidential control, congressional majority, and economic growth, relate to market trends, particularly the S&P 500?**

---

## **Research Questions**  
### **Research Question 1: Presidential Impact on S&P 500**  
**How do different presidential administrations correlate with the performance of the S&P 500, and which president had the most significant impact on market performance?**

#### **Analysis Approach**  
To address this question, S&P 500 data was merged with timelines of key economic policy events, with specific attention to major policy dates. A time-series analysis was conducted to assess the pre- and post-policy impact on stock prices. Furthermore, the data was segmented by presidential terms to analyze differences between Democratic and Republican administrations.

#### **Findings**  
The S&P 500 has shown strong growth under both Democratic and Republican administrations. However, Democratic administrations, particularly during periods of economic recovery, exhibited sharper growth. For instance, the Obama administration (2009–2017) saw substantial market expansion, likely due to stimulus packages, recovery efforts, and business-friendly policy initiatives.  

![S&P 500 Performance and GDP Trends](https://drive.google.com/file/d/1GSg1zKzPDAOznfS99_efjgGyUGI2pqBT/view?usp=drive_link)  
**Figure 1:** S&P 500 performance and GDP growth trends under Democratic (blue) and Republican (red) administrations.

---

### **Research Question 2: Correlation Between GDP Growth and S&P 500 Returns**  
**What is the correlation between long-term economic growth indicators (like GDP growth rates) and the returns of the S&P 500? Are there periods where market performance leads or lags GDP growth?**

#### **Analysis Approach**  
To explore this relationship, GDP growth rate data was aggregated with S&P 500 performance. A lagged correlation analysis was conducted to determine whether GDP growth preceded or followed stock market returns. Regression modeling was also applied to quantify the strength of the correlation.

#### **Findings**  
The analysis reveals a positive correlation between GDP growth and S&P 500 returns. In particular, during years of high GDP growth (e.g., the late 1990s and mid-2010s), the S&P 500 experienced significant gains. This finding aligns with the economic theory that a growing economy drives corporate earnings, which in turn boosts stock market performance.  

![S&P 500 vs GDP Growth](https://drive.google.com/file/d/1gry-ZZnNPumTI3QXLGhXdfklqlynxWbW/view?usp=sharing)  
**Figure 2:** Correlation between S&P 500 performance and GDP growth over time.

---

### **Research Question 3: Stock Market Volatility and Election Cycles**  
**Is there a pattern of stock market volatility that coincides with presidential election cycles? Does the S&P 500 experience more volatility during election years, and does this vary by political party?**

#### **Analysis Approach**  
To assess the impact of presidential election cycles on market volatility, historical volatility metrics for the S&P 500 were calculated for both election and non-election years. Statistical tests were conducted to evaluate whether election years exhibit significantly more volatility and whether this varies between political parties.

#### **Findings**  
The data indicates increased market volatility during presidential election years, particularly in the 2000, 2008, and 2016 elections. This suggests that elections introduce a degree of uncertainty, influencing investor behavior regardless of the party in power.  

![Volatility Trends During Election Cycles](https://drive.google.com/file/d/1kdNkO8ddQNSOxSJqQjgnR4o_ooLjk_iK/view?usp=sharing)  
**Figure 3:** Volatility trends of the S&P 500 during election years (Democratic in blue, Republican in red).

---

### **Research Question 4: Impact of Political Control on S&P 500**  
**How do different combinations of control in Congress and the White House impact the S&P 500, and which political configurations lead to the best or worst performance?**

#### **Analysis Approach**  
Historical data on S&P 500 performance was analyzed under various combinations of political control (e.g., Democratic White House and Congress, Republican control, or divided government). Regression models were applied to identify any relationships between these political configurations and market performance.

#### **Findings**  
Periods of unified Democratic control over both the White House and Congress have historically been associated with stronger market performance, as observed in the early 1990s and during the first two years of the Obama administration. Divided government and Republican control, on the other hand, tend to result in more cautious market behavior.  

![Political Control and S&P 500 Returns](https://drive.google.com/file/d/1fT4XguHfJVisC1O4fTry3OPJGsD22NIM/view?usp=sharing)  
**Figure 4:** S&P 500 performance under different political control scenarios.

---

### **Research Question 5: S&P 500 Performance by Industry**  
**How has the performance of the S&P 500 varied across different industries, and what trends or patterns can be identified in sector-specific growth, volatility, and resilience to economic cycles?**

#### **Analysis Approach**  
The performance of the S&P 500 was broken down by sector. Key metrics such as average annual returns, volatility, and drawdowns were calculated for each industry. Time-series analysis was employed to identify periods of relative strength or weakness across sectors, with correlations to macroeconomic indicators explored.

#### **Findings**  
Sector-specific performance has varied significantly over time. The Technology sector, for instance, has experienced substantial growth during the dot-com bubble and the mid-2010s tech boom. Conversely, the Energy sector has shown more volatility due to fluctuations in oil prices and changes in energy policy. These findings highlight the importance of diversifying investments across sectors to mitigate risks related to macroeconomic trends and policy shifts.  

![S&P 500 Performance by Sector](https://drive.google.com/file/d/1dE-EFTQ-LQmr_fC5z-JjjFfgpjDhZtKY/view?usp=sharing)  
**Figure 5:** S&P 500 performance by sector under Democratic (blue) and Republican (red) presidencies.

---

## **Summary of Findings**  
1. **Impact of Presidential Administrations on S&P 500 Performance**: Democratic administrations, especially during periods of economic recovery, generally correlate with stronger market growth.  
2. **Correlation Between GDP Growth and S&P 500 Returns**: A positive correlation was found between GDP growth and stock market returns, particularly in high-growth periods.  
3. **Stock Market Volatility During Election Cycles**: Volatility tends to increase during election years, reflecting uncertainty in investor behavior.  
4. **Impact of Congressional and White House Control on S&P 500**: Unified Democratic control over the White House and Congress has historically led to stronger market performance.  
5. **S&P 500 Performance Across Different Industries**: The Technology sector has demonstrated robust growth, while the Energy sector has fluctuated in response to macroeconomic factors.

---

## **Limitations and Future Research**  
- **Limitations**: The accuracy of the analysis may be impacted by outliers caused by major national and global crises, such as the 2008 financial crisis and the COVID-19 pandemic.  
- **Future Research**: Future studies could explore how global political events interact with U.S. market trends, and how sector-specific factors respond to broader economic cycles.

---

## **References**  
- [Republicans or Democrats: Who's Better for the Stock Market?](https://retirementresearcher.com/are-republicans-or-democrats-better-for-the-stock-market/)  
- [S&P 500 Performance in Presidential Election Years](https://advisor.morganstanley.com/the-ernie-garcia-group/documents/field/e/er/ernie-garcia-group/S%26P%20500%20in%20Presidential%20Election%20years.pdf)  
- [Presidential Administrations and Stock Market Performance](https://funds.cifinancial.com/en/documents/3/19739_1604955570_en.pdf)
