# ab-test
 ## An example of data analysis from a product A/B test.

**Case description:**  

A company develops an online shooting game. The game features an in-game currency that can be earned by winning matches or purchased with real-world money.

An A/B test is being conducted to gather insights on a promotional campaign offering a discount on an in-game item. It checks how the promo affected metrics:

- ARPU (average revenue per user) 
- ARPPU (Average revenue per paying user) 
- Spending of the in-game currency

However, the metrics are also influenced by users who cheat the game. The data is not entirely excluded for these users; thus, the project aims to clean the data for further analysis first, and than gather insights on the metrics.

**Project files:**

**initial-data-processing** -  file uploads the initial data provided in .CSV files, deduplicates it, explores relations between entities, and rearranges it in a format suitable for further analysis.  

**cheaters-filter** - exploring behaviour pattern of users, who cheated the game, identifying and removing new users with the same pattern.  

**main** - the file with insights from the A/B test.
