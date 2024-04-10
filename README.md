# Premise Item Price Dynamics Dashboard
Welcome to the Premise Item Price Dynamics Dashboard! This interactive dashboard is designed to provide you with a comprehensive overview of premise and item prices, offering valuable insights derived from the PriceCatcher dataset sourced from the Department of Statistics Malaysia (DOSM).

## Dataset Overview
In designing the dashboard, we utilize three datasets-PriceCatcher(2022/01), Premise Lookup and Item Lookup. The attribute details of each dataset are as following:

a) **PriceCatcher dataset (2022/01)**
- **Date:** Represents the date of observation in YYYY-MM-DD format.
- **Premise Code:** An integer representing the premise, mapped using the Premise Lookup Table, providing details such as premise name, address, district, and state.
- **Item Code:** An integer representing the item, mapped using the Item Lookup Table, offering details such as item name, unit of measurement, and categorization.
- **Price:** The price of the item in RM (Malaysian Ringgit).

_Link:_ [PriceCatcher dataset (2022/01)](https://open.dosm.gov.my/data-catalogue/pricecatcher_2022-01)

b) **Premise Lookup Dataset**- allows for left-joins against item codes contained in the PriceCatcher data
- **Premise Code (Integer):** Unique identifier for premises, used for left-joining against the main dataset.
- **Premise (Categorical):** Name of the premise.
- **Address (String):** Full address of the premise.
- **Premise Type (Categorical):** Type of premise, categorizing the nature of the establishment.
- **State (Categorical):** Name of the state where the premise is located.
- **District (Categorical):** Name of the district where the premise is situated.
  
_Link:_ [Premise Lookup Dataset](https://open.dosm.gov.my/data-catalogue/lookup_premise)

c) **Item Lookup Dataset** - allows for left-joins against item codes contained in the PriceCatcher data
- **Item Code (Integer):** Unique identifier for items, used for left-joining against the main dataset.
- **Item (Categorical):** Name of the item.
- **Unit (Categorical):** Unit of measurement for the item.
- **Item Group (Categorical):** Categorization of the item into specific groups.
- **Item Category (Categorical):** Broad category to which the item belongs.

_Link:_ [Item Lookup Dataset](https://open.dosm.gov.my/data-catalogue/lookup_item)

## Analysis and Dashboards
1. **Premise Overview**: Provides a thorough analysis of the distribution of premise sites across states and sheds light on the geographic dispersion of pricing recording locations.

2. **Item Price Analysis**: Delves into average prices, state-wise distributions, and notable trends, aiding users in understanding pricing dynamics This dashboard provides a thorough analysis of the distribution of premise sites across states and sheds light on the geographic dispersion of pricing recording locations.

3. **Pricing Strategies**: Highlights minimum prices and outliers, offering insights into unique pricing approaches adopted by premises.

## Interactivity and Storytelling
Every dashboard has interactive features that let users study the data in real time. In addition, a story has been developed to lead viewers through the analysis carried out, offering a structured story to improve comprehension and interpretation of the insights obtained from the data.

Feel free to download the [Tableau workbook file](https://github.com/WanYin0704/Premise-Item-Price-Dynamics-Dashboard/blob/main/Project2.twbx)
to browse the dashboards and delve into the fascinating realm of pricing dynamics!
