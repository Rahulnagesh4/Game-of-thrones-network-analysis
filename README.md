🕸️ Game of Thrones Network Analysis
This project analyzes the intricate web of character relationships in the Game of Thrones book series using Network Analysis techniques. By representing characters as nodes and their interactions as edges, we explore the central figures, alliances, and social dynamics across five books using graph theory and Python tools.

📌 Key Objectives
Build character interaction networks from five books.
Analyze and visualize the network structure using various centrality measures.
Identify the most influential characters using:
Degree Centrality
Betweenness Centrality
Closeness Centrality
PageRank
Detect communities and subplots through modularity-based clustering.
Compare centrality measures and examine character evolution over time.
🗂️ Dataset
The dataset was sourced from Kaggle - Game of Thrones Network Analysis and includes:

book1.csv to book5.csv — each file represents character interactions per book.
Each dataset contains:

Source: Character initiating the interaction
Target: Character being interacted with
Weight: Frequency of interaction
Type: Undirected edge
Book: Book number (1–5)
🛠️ Technologies Used
Python
NetworkX
Pandas
Matplotlib
Seaborn
Jupyter Notebook
📊 Analysis Performed
Constructed undirected weighted graphs for each book.
Calculated:
Degree, Closeness, and Betweenness centrality
PageRank scores
Plotted:
Degree distribution and log-log scale charts
Evolution of key characters across books
Correlation matrix of centrality metrics
Detected:
Community structures
Largest cliques
k-core subgraphs
Measured:
Graph density, mean degree, and network components
🧠 Key Insights
Eddard Stark, Tyrion Lannister, and Jon Snow consistently rank among the top central characters.
Character influence shifts over time as the plot evolves.
The degree distribution suggests a scale-free network — typical of real-world social networks.
Communities align closely with narrative alliances and major plotlines.
📎 Visual Samples
See Jupyter Notebook (.ipynb) for full code and output visualizations.

Top 10 characters by centrality
Character evolution plots across books
Heatmap showing correlation between centrality measures
Community and clique visualizations
🔮 Future Work
Add sentiment analysis of character interactions.
Perform dynamic network analysis across chapters instead of books.
Integrate annotated book data or fan wiki knowledge bases.
📄 References
Kaggle: Game of Thrones Network Analysis
Moretti, F. (2011). Network theory, plot analysis.
Beveridge & Shan (2016). Network of Thrones. Math Horizons.
🧠 Skills Demonstrated
Python, Network Analysis, Graph Theory, NetworkX, Pandas, Matplotlib, Seaborn, Jupyter Notebook, Data Visualization, Data Wrangling, Degree Centrality, Betweenness Centrality, Closeness Centrality, PageRank, Correlation Analysis, Community Detection, Problem Solving, Critical Thinking, Data-Driven Storytelling, Project Documentation, Exploratory Data Analysis, Time-Series Analysis, Social Network Analysis
