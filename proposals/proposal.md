# Research Proposal: How the Pandemic Impacted the Supply Chain (updated)
By Kyra Grodman, Jersey Krupp, and Qiyu Yang

## Research Question
We will explore how the supply chain network has reformed and changed following the pandemic based on customer/supplier contracts from the [Compustat Customer Supplier dataset](inputs/cust_supply_2019_2022.csv). Our initial hypothesis is that the amount of technology based companies will increase as the number of sellers does. Another hypothesis we have is that the amount of contracts involving healthcare/pharmaceutical companies will also increase. Moreover, we hypothesize that there are more new firms in healthcare and technology in comparison to 2019. Overall, we want to compare the number of contracts as well as compare the growth of technology companies within the supply chain network.


## Necessary Data
1. The final dataset will include:
      1. A cleaned version of the contracts data from 2019 and 2022 
          1. This is using data from the [cust_supply_2019_2022.csv](inputs/cust_supply_2019_2022.csv) provided by Dr. Bowen
          1. The above dataset will be merged with SP500 dataset (obtained from scarping Wikipedia)
          1. It will also include data from the accounting dataset provided by Dr. Bowen based on variables we deem necessary
      2. Observations that are firm level and firm-pair networks (firm A sells to firm B, etc.)
      3. A sample period of 2019 & 2022
      4. A sample conditions of 2019 & 2022 and companies in the SP500   
      6. We will obtain accounting statistics of the companies, to determine the financial health of the company
2. Our data:
    1. We have: [cust_supply_2019_2022.csv](inputs/cust_supply_2019_2022.csv) and can easily obtain the SP500 data.
        1. We will gain a deeper understanding of the [Compustat Customer Supplier data](inputs/cust_supply_2019_2022.csv) by looking at the SEC 10Ks
    1. We need: accounting data which will be provided by Dr. Bowen
3. We believe that after obtaining the accounting data from Dr. Bowen we will have all of the data needed for this project. Should we need any more data, we will cross that bridge if needed.
4. Raw inputs: 
    1. [cust_supply_2019_2022.csv](inputs/cust_supply_2019_2022.csv) provided by Dr. Bowen 
    1. SP500 data (obtained from scarping Wikipedia)
    1. accounting data provided by Dr. Bowen
    3. The above raw data files will be stored in the input folder
5. Transforming the raw data into the final form
    1. Filter the necessary data from [cust_supply_2019_2022.csv](inputs/cust_supply_2019_2022.csv)
    1. Merge the above with SP500 data
    1. Merge the [cust_supply_2019_2022.csv](inputs/cust_supply_2019_2022.csv) & SP500 dataframe with accounting data
    1. Filter out unnecessary data
    2. Create a single dataframe or multiple dataframes to store our results
    1. Add these results to the outputs folder & analyze the results throughout this process
    5. Convert results into a dashbaord using the dashboard chapter in the textbook and the accompanying resource [streamlit.io](https://streamlit.io) to show the outputs made in python
    
## Sample Dashboard (subject to change)
![](Proposals/Initial_proposal_dashboard.excalidraw_screenshot.png)
