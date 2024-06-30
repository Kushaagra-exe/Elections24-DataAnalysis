
# Introduction to the 2024 Lok Sabha Elections Data Analysis Project

The 2024 Lok Sabha Elections Data Analysis Project aims to collect, process, and analyze data related to the recently conducted general elections in India. By leveraging government result declation sources, the project seeks to provide comprehensive insights into the electoral landscape. Our objective is to identify key trends, voter behavior, and potential outcomes, offering valuable information to political analysts, researchers, and the general public. This project not only focuses on the quantitative aspects of the election but also delves into qualitative analyses to understand the broader socio-political context influencing the 2024 Lok Sabha elections.


# Requirements / Dependencies

- **Pandas**
- **BeautifulSoup**
- **MatplotLib**
- **Seaborn**

```bash
pip install -r requirements.txt
```

## Data Collection
Data has been scrapped from the website - **ttps://results.eci.gov.in/**
Data Scrapping code can be found in `Scrapping` Directory


## Data Sets
- **Parties participated.csv** : Contains a list of Parties which Participated and Secured atleast 1 seat in Lok Sabha elections.
- **State wise data.csv** : Contains data about Candidates who won in which Constituencies, their Votes Secured and Margin of Votes by which they won, according to the States in which they won. 
- **party_wise_results.csv** : Cotains data about winner candidates from each Party, their Constituencies, their Votes Secured and Margin of Votes by which they won.
- **winner combined candidates.csv** : Contains data about winner candidates from each party combined and all their statistics.


## Key Insights

1. **Total Number of Votes given to Winning Candidates (State Wise)**
2. **Top 10 Parties with Highest Seats**
3. **Top 17 Parties with Lowest Seats**
4. **Party Wise Seat Distribution**
5. **Frequency Distribution of Winning Margins**
6. **Scatter Plot for Margins v/s Votes**
7. **Highest and lowest Victory Candidate**
8. **Top 10 candidates with highest votes**
9. **Top 10 candidates with Lowest votes**
10. **Top 10 Parties with Highest Votes**
11. **Top 10 Parties with Lowest Votes**

