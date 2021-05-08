# ML_Projects_InvestmentAnalysis

## Business Understanding:
Spark Funds, an asset management company wants to make investments in a few companies and wants to understand the global trends in investments to take the decisions effectively.

**Spark Funds has two minor constraints for investments:**
- It wants to invest between 5 to 15 million USD per round of investment
- It wants to invest only in English-speaking countries because of the ease of communication with the companies it would invest in

**Business objective:** The objective is to identify the best sectors, countries, and a suitable investment type for making investments. The overall strategy is to invest where others are investing, implying that the 'best' sectors and countries are the ones 'where most investors are investing'.

## Analysis:
### Checkpoint 1: Data Cleaning

### Checkpoint 2: Funding Type Analysis

The funding types such as seed, venture, angel, etc. depend on the type of the company (startup, corporate, etc.), its stage (early-stage startup, a funded startup, etc.), the     amount of funding (a few million USD to a billion USD), and so on. For example, seed, angel and venture are three common stages of startup funding.

**Goal:** Spark Funds wants to choose one of these four investment types for each potential investment they will make.
Considering that Spark Funds wants to invest between 5 to 15 million USD per investment round, Identify the investment type most suitable. For further analysis, filter the         data so it only contains the chosen investment type.

### Checkpoint 3: Country Analysis

Spark Funds wants to invest in countries with the highest amount of funding for the chosen investment type.
  - Spark Funds wants to see the top nine countries which have received the highest total funding (across ALL sectors for the chosen investment type)
  - For the chosen investment type, make a data frame named top9 with the top nine countries (based on the total investment amount each country has received)

**Goal:** Identify the top three English-speaking countries in the data frame top9. Identify the top three English-speaking countries in the data frame top9.

### Checkpoint 4: Sector Analysis
### Checkpoint 5: Plots
