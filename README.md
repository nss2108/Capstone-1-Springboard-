#Capstone-1-Springboard is an analysis of a dataset of boardgames taken from the Board Game Geek website. This was a sql database that I converted to a csv file. 

The steps are detailed in the data cleaning juptyer notebook, but I undertook the following steps:
  -Filtered and deleted extraneous data, such as data that concerned videogames
  -Deleted expansions from the dataset--at a later point, I'll return to this issue
  -Deleted games with less than five ratings as a means of taking out any unpublished or poorly circulating games
  -Filtered the database to only contain games after 1930
  -Replaced subjective measurements in some categories such as "No" or "Best" with numeric values
  -split off polls and more detailed categorical stats into separate dataframes
  -made a categorical and publisher dictionary for later use
  -turned it into a csv file
