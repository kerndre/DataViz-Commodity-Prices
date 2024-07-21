# DataViz-Commodity-Prices
## Data Visualization and Visual Analytics
## WS 2022/23
#### 10.01.2023
---
As part of the module 'Data Visualization and Visual Analytics' at the Kiel University of Applied Science we had the task to visualize a topic of our choice. I decided to compare commodity prices over a time span from the year 2000 until 2022.

Due to the fact that Github's notebook viewer does not execute any embedded Javascript code, presumably for security reasons, altair charts do not appear in Github notebook views, because they are rendered via javascript. For this reason I have uploaded the actually interactive visualizations as .png.

## Potential Improvements
1) Since the euro values (especially the average values for the various individual goods) are not comparable, it would have made sense to normalize them, e.g. to the first value in the time series. Then the relative changes would still be visible and the irrelevant level would fade into the background. 
2) Naturally, this topic was very time series-heavy, which is ok. Maybe some aspects could have been deepened. For example, in the case of the Ukraine war, we could have looked at the prices of the individual crops in more detail. There are probably interesting insights to be gained here.
3) 
---
## Introduction
The inflation rate in Germany in 2022 was partly as high as it had last been around 40 years ago. It was 7.3% in March and even reached 10.4% in October. The economic aftereffects of the COVID-19 pandemic and the Ukraine war that began last year drove the inflation rate up. The difficult export of grain products from Ukraine, the looming import stop of Russian oil and gas, and supply bottlenecks due to interrupted supply chains caused by the pandemic significantly increased the prices of goods and raw materials and the inflation rate.

### What is understood by inflation?
Literally, inflation means the "swelling" of prices. In the consumer's daily life, this is reflected in increased prices, meaning the consumer can buy less for the same amount of money.

### Aim of this paper
The aim of this paper is to compare price developments between 2022 and other 'crisis years' within the dataset period (2000-2022). The years of the global financial crisis 2007/08 were chosen for this purpose. The goal is to investigate whether, despite different circumstances, similarities in the course of price developments can be discovered. These findings would be extremely useful in potentially recognizing upcoming price fluctuations early and taking appropriate measures.

---
## Summary
### Findings:
This paper showed that the two compared crises (Ukraine War 2022, Global Financial Crisis 2007/08) both led to an increase in commodity prices. However, when the two "shock" moments are directly compared, it is evident that they were followed by different price increases. While 2007/08 saw a slower but more consistent rise, the increase in 2022 was more abrupt. Both times, industrial metals and grains experienced the greatest fluctuations. Prices for livestock and softs were virtually unaffected by the events. Interestingly, despite the strong fluctuations in industrial metals, the prices in the two years studied were nearly the same, even though strong increases were recorded both times.

### Reflection:
Generally, attempting to compare the impacts of two crises at different times under different conditions is a challenging endeavor. More conditions and circumstances need to be examined than just the price development. Additionally, there are difficulties due to the dataset. It did not allow insight into how price differences within individual commodity categories looked. This offers a question for future research, such as whether specific industrial metals are responsible for the strong price fluctuations. It should also be considered what price increase the crises themselves caused, instead of comparing the values for the entire years (the war in 2022 began at the end of February, while the crisis in 2007 began only in August of that year). The general increase since 2000 should also be taken into account. A base price level for a time period should be calculated, and from this, the increases with the onset of each crisis. All in all, however, this paper provides a good overview and rough traceability of the impacts of the two studied crises on the commodities presented here.

---
### Quellen:
- https://www.handelsblatt.com/finanzen/geldpolitik/10-prozent-inflation-die-inflationsrate-in-deutschland-von-2005-bis-2022/26252124.html
- https://www.dw.com/de/der-krieg-in-der-ukraine-und-getreide-f%C3%BCnf-fakten/a-62567350
- https://hilfe.onvista.de/in-welchen-einheiten-werden-rohstoffe-gehandelt-
