# Research Proposal: How the pandamic impacted the supply chain
By Kyra Grodman, Jersey Krupp, and Qiyu Yang

## Research Question
We want to know supply chain network reformed and changed following the pandemic based on customer/supplier contracts from SEC filings. We hypothesize that digital/technology companies will increase as sellers.

## Necessary Data
1. This dataset should cover:
  - SEC contracts from 2019 and 2022
  - An observation is a firm-year
  - The sample period is 2019 & 2022
  - The sample conditions: 2019 & 2022, include all industries, maybe limit the amount of firms we look at??
    - SP 500, start at technology intustries and see where the connections lead, other big supply chain companies (Walmart, Target, etc.)   
  - We would like SEC Exhibit 10s,  maybe 10Ks
2. We will need SEC Exhibit 10s & maybe 10Ks
3. ?? based on results of our sample data?? - to see what other companies/firms to use
4. raw inputs: the names of buyers and sellers in 2019 & 2022
    1. Will store the E10 & maybe 10Ks in zip folders
    2. Will store the scraped data in dataframes
5. Similar to the midterm
    1. Figure out which companies to look at
    2. Use URLs/code from Midterm to obtain the buyers/seller names
    3. Add these to a dataframe
    4. Analyze the results
    5. Convert results into a dashbaord

---
[Instructions for Overall Report](https://ledatascifi.github.io/ledatascifi-2023/content/assignments/project.html)

[Instructions for Proposal](https://ledatascifi.github.io/ledatascifi-2023/content/assignments/project_prop_template.html)

[Teams Google Sheet](https://docs.google.com/spreadsheets/d/1kRbuRKfKh9lCdoVBGLxSbDTIRBEfnV7Y8AcP-hZbmTw/edit#gid=1508330834)

Initial Idea
- Identify customer/supplier contracts from SEC filings and build a dashboard visualization exploring how the supply chain network reformed and changed following the pandemic.
  - Collect SEC exhibit 10 files for 2019 and 2022. Restrict to customer/supplier contracts. Decide which firm is buyer and which is seller. Augment with 10-K based CustSupplier data. Compare/contrast the Exhibit10 data with 10-K based data.
- Links
  - [EY](https://www.ey.com/en_us/supply-chain/how-covid-19-impacted-supply-chains-and-what-comes-next#:~:text=The%20pandemic%20also%20forced%20supply,the%20next%20crisis%20requires%20optimization).
  - [WEF](https://www.weforum.org/agenda/2022/01/5-ways-the-covid-19-pandemic-has-changed-the-supply-chain/)
  - [McKinsey](https://www.mckinsey.com/capabilities/operations/our-insights/how-covid-19-is-reshaping-supply-chains)
  - [Sample E10](https://www.sec.gov/Archives/edgar/data/845091/000119312511222394/dex10.htm)
