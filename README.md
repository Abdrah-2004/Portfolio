# **Analyzing Economic Trends: S&P 500 Performance, GDP Growth, and Presidential Impact**  
### **By Abd Alghani Rahmoun and Cedric Nyagatare**  
**Date:** 12/7/2024  
**Course:** Whitman College, CS/MATH - 215 Intro to Data Science  
**Instructor:** Albert Schueller  
[Click here to open the Colab worksheet](https://colab.research.google.com/drive/1c2FPResnkg_V9Ull1de4L-d6xcJqO55e?usp=sharing)

---

## **Abstarct**  
This research project explores the interplay between presidential administrations, congressional control, economic policies, and the performance of the S&P 500 from 1993 to 2024. Through a comprehensive analysis integrating S&P 500 data with key economic events, policy changes, and GDP growth, we investigate how different political regimes influence market dynamics. Our hypothesis posits that Democratic presidencies often correlate with enhanced market performance, asserting that GDP growth significantly forecasts stock market trends and that election years amplify market volatility due to political transitions. By dissecting the performance across various industries, our findings reveal that sectors such as technology, healthcare, and consumer discretionary generally flourish under Democratic policies promoting innovation and consumer protection, whereas energy and financials sectors tend to perform better under Republican administrations favoring deregulation. The research highlights the necessity for investors to adopt diversified strategies to navigate the sector-specific volatility and the profound impact political and economic climates have on market performance.

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
This project delves into the correlation between presidential administrations, economic policies, and S&P 500 performance, using data spanning from 1992 to 2024. Our analysis explores how different political regimes, including the control of the House and Senate, impact the stock market’s behavior. We examine key economic indicators such as GDP growth, election cycles, and control over Congress, seeking to understand their combined effects on the performance of the S&P 500. 

### **Hypothesis**  
Our hypothesis suggests that Democratic presidencies are correlated with stronger S&P 500 performance, and that GDP growth is a leading indicator of stock market returns. Moreover, we hypothesize that market volatility tends to increase during election years, particularly in contexts where there is a shift in political power.

The overarching research question is:  
**How do political factors, such as presidential control, congressional majority, and economic growth, relate to market trends, particularly the S&P 500?**


---

## **Research Questions**  
### **Research Question 1: Presidential Impact on S&P 500**  
**How do different presidential administrations correlate with the performance of the S&P 500, and which president had the most significant impact on market performance?**

#### **Analysis Approach**  
To address this question, S&P 500 data was merged with timelines of key economic policy events, with specific attention to major policy dates. A time-series analysis was conducted to assess the pre- and post-policy impact on stock prices. Furthermore, the data was segmented by presidential terms to analyze differences between Democratic and Republican administrations.

![**Figure 1:** S&P 500 performance and GDP growth trends under Democratic (blue) and Republican (red) administrations.
](https://github.com/Abdrah-2004/Portfolio/blob/main/Graph1.png)
**Figure 1:** S&P 500 performance and GDP growth trends under Democratic (blue) and Republican (red) administrations.

#### **Findings**  
Observations from the graph and data analysis indicate that the S&P 500 has historically shown robust growth under both Democratic and Republican administrations. However, sharper increases are often seen during Democratic administrations, particularly during periods of economic recovery and strong policy support, such as during the Obama years from 2009 to 2017. This suggests that while the broader economic environment plays a critical role, policy initiatives during Democratic terms have had a positive correlation with market performance.


---

### **Research Question 2: Correlation Between GDP Growth and S&P 500 Returns**  
**What is the correlation between long-term economic growth indicators (like GDP growth rates) and the returns of the S&P 500? Are there periods where market performance leads or lags GDP growth?**

#### **Analysis Approach**  
To explore this relationship, GDP growth rate data was aggregated with S&P 500 performance. A lagged correlation analysis was conducted to determine whether GDP growth preceded or followed stock market returns. Regression modeling was also applied to quantify the strength of the correlation.



#### **Findings**  
The datasets indicate a positive correlation between GDP growth and S&P 500 returns, aligning with economic theory that a growing economy boosts corporate earnings and thereby stock prices. Particularly in years of high GDP growth, such as the late 1990s and mid-2010s, the S&P 500 also significantly increased. This finding with Regression analysis would likely confirm the economic theory that a growing economy drives corporate earnings, which in turn boosts stock market performance.  



---

### **Research Question 3: Stock Market Volatility and Election Cycles**  
**Is there a pattern of stock market volatility that coincides with presidential election cycles? Does the S&P 500 experience more volatility during election years, and does this vary by political party?**

#### **Analysis Approach**  
To assess the impact of presidential election cycles on market volatility, historical volatility metrics for the S&P 500 were calculated for both election and non-election years. Statistical tests were conducted to evaluate whether election years exhibit significantly more volatility and whether this varies between political parties.

![****Figure 2:** Volatility trends of the S&P 500 Over years (Democratic in blue, Republican in red).
](https://github.com/Abdrah-2004/Portfolio/blob/main/Graph31.png)
**Figure 3:** Volatility trends of the S&P 500 Over years (Democratic in blue, Republican in red).

![****Figure 3:** Volatility trends of the S&P 500 during election years (Democratic in blue, Republican in red).
](https://github.com/Abdrah-2004/Portfolio/blob/main/Graph32.png)
**Figure 3:** Volatility trends of the S&P 500 during election years (Democratic in blue, Republican in red).

#### **Findings**  
The volatility graphs reveal increased market volatility during presidential election years, reflecting the market's sensitivity to political uncertainty. This trend holds across both Democratic and Republican election cycles, with heightened volatility evident in election years such as 2000, 2008, and 2016. This pattern suggests that elections introduce a degree of uncertainty that affects market behavior, regardless of the party.
![Volatility Trends During Election Cycles](https://drive.google.com/file/d/1kdNkO8ddQNSOxSJqQjgnR4o_ooLjk_iK/view?usp=sharing)  


---

### **Research Question 4: Impact of Political Control on S&P 500**  
**How do different combinations of control in Congress and the White House impact the S&P 500, and which political configurations lead to the best or worst performance?**

#### **Analysis Approach**  
Historical data on S&P 500 performance was analyzed under various combinations of political control (e.g., Democratic White House and Congress, Republican control, or divided government). Regression models were applied to identify any relationships between these political configurations and market performance.

![**Figure 4:** S&P 500 performance under different political control scenarios.
](https://github.com/Abdrah-2004/Portfolio/blob/main/Graph41.png)
**Figure 4:** S&P 500 performance under different political control scenarios.

#### **Findings**  
Periods of unified Democratic control over both the White House and Congress have historically been associated with stronger market performance, as observed in the early 1990s and during the first two years of the Obama administration. Divided government and Republican control, on the other hand, tend to result in more cautious market behavior.  

---

### **Research Question 5: S&P 500 Performance by Industry**  
**How do shifts in political power in the White House influence the performance of different industries within the S&P 500, and what are the notable trends and patterns in sector-specific growth, volatility, and resilience throughout various economic cycles?**

#### **Analysis Approach**  
The performance of the S&P 500 was broken down by sector. Key metrics such as average annual returns, volatility, and drawdowns were calculated for each industry. Time-series analysis was employed to identify periods of relative strength or weakness across sectors, with correlations to macroeconomic indicators explored.
graph right here interaqcrive and 

![**Figure 5:** S&P 500 performance by sector under Democratic (blue) and Republican (red) presidencies.
](https://github.com/Abdrah-2004/Portfolio/blob/main/Graph500.png)
You can view the interactive graph by clicking the link below:
[Interactive Graph - View Here](https://abdrah-2004.github.io/Portfolio/Graph50)

#### **Findings**  
The performance of various S&P 500 sectors demonstrates clear correlations with shifts in political power, illustrating how different industries respond to the policies of Democratic and Republican administrations. During Democratic terms, sectors like technology, healthcare, and consumer discretionary often experience growth, supported by policies that promote innovation, healthcare reform, and consumer protection. Conversely, Republican administrations tend to boost sectors like energy and financials through deregulation and support for traditional energy sources. The analysis underscores the importance of a diversified investment strategy, as it highlights the sector-specific volatility and resilience to economic cycles, which are significantly influenced by political climates. This approach can help investors mitigate risks and capitalize on growth opportunities by aligning their portfolios with prevailing and anticipated policy environments.

---

## **Summary of Findings**  
1. **Impact of Presidential Administrations on S&P 500 Performance**: Democratic administrations, especially during periods of economic recovery, generally correlate with stronger market growth.  
2. **Correlation Between GDP Growth and S&P 500 Returns**: A positive correlation was found between GDP growth and stock market returns, particularly in high-growth periods.  
3. **Stock Market Volatility During Election Cycles**: Volatility tends to increase during election years, reflecting uncertainty in investor behavior.  
4. **Impact of Congressional and White House Control on S&P 500**: Unified Democratic control over the White House and Congress has historically led to stronger market performance.  
5. **S&P 500 Performance Across Different Industries**: The Technology sector has demonstrated robust growth, while the Energy sector has fluctuated in response to macroeconomic factors.

---

## **Conclusion**  
Our analysis has shed light on the nuanced relationships between political climates, economic indicators, and the S&P 500's performance, revealing key insights into how different administrations influence market dynamics.
The S&P 500 has shown growth under both Democratic and Republican leadership, though the nature of this growth often reflects the distinct policies and economic strategies of each party. Under Democratic administrations, the market frequently benefits from robust policy support and initiatives that focus on economic recovery, leading to notable upturns. On the other hand, Republican leadership has also driven periods of strong market performance, particularly when pro-business policies like tax cuts and deregulation have been prioritized, spurring investment and corporate profitability.
The data also highlights that market volatility tends to spike during presidential election cycles, showing the market's acute sensitivity to political uncertainty, a trend that holds true regardless of the party in power. Additionally, the impact of who controls Congress and the White House is significant, with market performance often reflecting the economic policies favored by the prevailing party. Democratic control is generally associated with higher returns, likely due to investor confidence in their economic management, while sectors such as energy and manufacturing often see better performance under Republicans, who typically provide more favorable policy environments for these industries. Sector-specific analyses further reveal that different industries react variably to changing economic conditions and policy environments, with sectors like Technology and Energy experiencing significant fluctuations.
Overall, this exploration underscores that while markets respond to immediate political changes, long-term performance is deeply connected to broader economic policies and the global economic landscape. These insights are invaluable for investors and policymakers, providing the necessary context to anticipate market trends and make informed decisions in a politically dynamic economic environment. This balanced perspective recognizes the complex interplay between politics, economics, and market performance, emphasizing the importance of a well-rounded understanding in navigating investment strategies.

## **Limitations**
- **Data Scope and Availability**: Limited data might not capture all factors affecting the S&P 500, such as global events or unexpected market shifts.
- **Historical Bias**: Past market trends may not reliably predict future movements due to evolving economic and political landscapes.
- **Political and Economic Complexity**: Reducing the impact of administrations to a binary political distinction may overlook nuanced economic influences.
- **Causation vs. Correlation**: Identifying correlations does not imply causation; multiple interacting factors typically drive market changes.
- **Sector-Specific Variations**: Differences in industry-specific dynamics might not be fully accounted for, affecting the accuracy of sectoral analysis.
- **Time Lag Effects**: Economic policies often have delayed impacts on the markets, complicating the attribution of effects to specific policies or administrations.

## **Areas for Further Study**  
Further research could focus on sector-specific responses, global market influences, and predictive modeling of market trends under varying political conditions and political policies (Tax cuts, tariffs, investment incentives). This analysis provides a foundation but highlights the need for more detailed investigations.

---

## **References**  
- Party Division." U.S. Senate, United States Senate, www.senate.gov/history/partydiv.htm. Accessed 3 Dec. 2024.
- The Presidents Timeline." White House History, White House Historical Association, www.whitehousehistory.org/the-presidents-timeline.     Accessed 7 Dec. 2024.
- Gross Domestic Product." Bureau of Economic Analysis, U.S. Department of Commerce, www.bea.gov/data/gdp/gross-domestic-product. Accessed 7 Dec. 2024.
- "S&P Sectors: Overview." S&P Global, S&P Dow Jones Indices, www.spglobal.com/spdji/en/index-family/equity/us-equity/sp-sectors/#overview. Accessed 3 Dec. 2024.
  Additional Note for Personal Communication:
I obtained the raw data for analysis through personal communication with Howard Silverblatt, who emailed the data to me on 4 Dec. 2024.
- Throughout the development of this document, assistance from ChatGPT was utilized to refine grammar and improve coding practices.

