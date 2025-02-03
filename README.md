# DataMining_Data_Processing_Visualization_and_Analysis
Data Processing, Visualization and Analysis, Graph Dataset,  Exploratory Data Analysis (EDA)

Data Processing, Visualization and Analysis
Lab Task 1: (Dataset bread basket)
Data Visualization and Analysis:
1. Load and represent the data using an appropriate library.
2. Apply any preprocessing steps that might be required to clean or filter the data before analysis (if
required).
3. Convert 'date_time' column in right format.
4. Extract different columns from 'date_time', the columns will be ‘date’, ‘time’, ‘month’, ‘hour’,
‘weekday.’
5. Extract ‘hour_span’ from ‘hour’ column e.g., transaction performed at 9th hour will be in span of
9-10.
6. Replace month numbers with respective names e.g., 1 by January.
7. Replace weekday numbers with respective names e.g., 0 by Monday.
8. Plot “Top 20 Items purchased by customers.”
9. Plot “Number of orders received each month.”
10. Plot “Number of orders received each day.”
11. Plot “Count of orders received each hour_span.”
12. Plot “Count of orders received each period of a day.”
13. Plot “Top 10 items people like to order in different periods of day.”
Lab Task 2: (Dataset bread basket)
Data Visualization and Analysis:
1. 1.Load and represent the data using an appropriate library.
2. Apply any preprocessing steps that might be required to clean or filter the data before analysis (if
required).
3. Convert 'date_time' column in right format.
4. 4.Make a different data frame in which you have columns ‘Transaction’, ‘Item’, ‘period_day’ and
‘Item Count’. Display a new data frame.
5. Make four different baskets on the basis of ‘period_day’.
6. Define a function for one hot encoding function and also generate one hot encoding through the
built-in library.
7. Apply the above function on four baskets.
Lab Task 3: (Dataset sales_data_sample)
Analyze the provided sales dataset to derive insights related to product performance, customer behavior,
and pricing strategies.
1. Data Cleaning
● Load the Dataset: Use pandas to load the dataset.
● Handle Missing Values: Identify columns with missing values and decide on appropriate methods
to handle them (e.g., imputation, removal).
● Remove Duplicates: Check for duplicate rows and remove them if necessary.
● Data Types: Ensure all columns have the correct data types (e.g., convert discounted_price and
actual_price to float).
To preprocess the sales data for accurate analysis and model performance, perform the following
steps for scaling and normalization of numerical features:
● Min-Max Scaling: Apply this technique to the 'discounted_price' and 'actual_price' columns
to rescale the values to a range of [0, 1], ensuring that all price-related features contribute
equally to distance calculations.
● Standardization (Z-score Normalization): Apply this technique to the 'discount_percentage'
and 'rating' columns to transform the data, ensuring a mean of 0 and a standard deviation of
1, which is especially useful for features with Gaussian distributions or those affected by
outliers.
2. Exploratory Data Analysis (EDA)
● Summary Statistics: Generate summary statistics for numerical columns (mean, median,
standard deviation).
● Distribution Analysis: Plot histograms for discounted_price, actual_price, and rating to
understand their distributions.
● Correlation Matrix: Create a correlation matrix to identify relationships between numerical
variables.
3. Visualizations
● Sales by Category: Create a bar chart showing total sales per product category.
● Price vs. Rating: Create a scatter plot to analyze the relationship between discounted_price and
rating. Include a trend line.
● Discount Impact: Visualize how discount percentages affect sales volume using a boxplot.
Lab Task 4: (Graph Dataset)
● Load a graph dataset (can be synthetic or real-world).
o A graph dataset consists of nodes (vertices) representing entities and edges
representing relationships between them.
o You can manually create a synthetic graph or load a real-world dataset.
● Visualize the graph.
o Graph visualization helps us understand the connections between nodes.
o We use NetworkX and Matplotlib to plot the graph.
● Compute basic graph properties like the number of nodes, edges, degree, and connectivity.
o Number of nodes – Total entities in the graph.
o Number of edges – Total connections in the graph.
o Degree of nodes – How many edges a node has.
o Connectivity – Whether all nodes are connected.
● Perform graph traversal (BFS/DFS).
o Breadth-First Search (BFS) explores neighbors first.
o Depth-First Search (DFS) explores deep paths first.
● Compute the shortest path between two nodes.
o Finding the shortest path is useful in network routing, logistics, and AI.
o We can use Dijkstra’s Algorithm for weighted graphs or BFS for unweighted graphs.
Concepts Learned in Task 4:
Libraries:
● Networkx
● Matplotlib
● Pandas
● numpy
