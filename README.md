#Capstone-1-Springboard is an analysis of a dataset of boardgames taken from the Board Game Geek website. This was a sql database that I converted to a csv file. 

The steps are detailed in the data cleaning juptyer notebook, but I undertook the following steps:
  1. Filtered and deleted extraneous data, such as data that concerned videogames
  2. Deleted expansions from the dataset--at a later point, I'll return to this issue
  3. Deleted games with less than five ratings as a means of taking out any unpublished or poorly circulating games
  4. Filtered the database to only contain games after 1930
  5. Replaced subjective measurements in some categories such as "No" or "Best" with numeric values
  6. Split off polls and more detailed categorical stats into separate dataframes
  7. made a categorical and publisher dictionary for later use
  8. turned it into a csv file
