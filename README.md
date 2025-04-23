# 🚢 Titanic Network Analysis: "My Heart Will Go On (but not yours?!?)"

This project explores **social network analysis** using character interactions from James Cameron's 1997 film *Titanic*. Instead of focusing on real-life survival data, this fun and educational notebook analyzes the **relationships and co-occurrences** between characters to humorously investigate why Rose didn't save Jack. 🥶

> _Inspired by a student's question: Can we apply network analysis to the Titanic story?_  
> The answer is yes—and here's how.

## 📁 Dataset

- `nodes.csv`: Contains all characters appearing in the film.
- `edges.csv`: Represents co-occurrence of characters per scene, with weights showing how often they appear together.
- Data was manually extracted from the film script and simulates a realistic social graph.

## 🎯 Objectives

This notebook is divided into key network analysis tasks:
1. **Graph Construction**  
   Build and visualize a network where:
   - Nodes = Characters  
   - Edges = Scene co-occurrences  
   - Edge Weights = Number of co-appearances

2. **Network Properties**  
   Explore the graph’s:
   - Degree distribution  
   - Centralities (Degree, Betweenness, Closeness)  
   - Clustering coefficients

3. **Community Detection**  
   Use modularity-based algorithms to find character communities and subgroups.

4. **Gender-Based Subgraphs**  
   Create separate networks for male and female characters and compare:
   - Connectivity  
   - Centrality  
   - Structure

5. **Final Hypothesis**  
   Answer the (somewhat ridiculous but fun) question:  
   _"Why didn’t Rose help Jack?"_ using network-based insights.

## 🛠️ Technologies Used

- Python (Jupyter Notebook)
- NetworkX
- Matplotlib
- Pandas
- NumPy

## 📸 Sample Visuals

- Character Co-occurrence Network
- Centrality Graphs
- Gender-based Subgraph Comparisons
- Community Structure Highlighting

## 📚 Learning Outcomes

By completing this project, you’ll gain experience in:
- Network graph construction and visualization
- Centrality and connectivity metrics
- Graph partitioning and community detection
- Gender-based analytical comparison
- Storytelling through data science

## 💡 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/yourusername/Titanic-Network_Analysis.git
   cd Titanic-Network_Analysis
   ```

2. Launch the notebook:

   ```bash
   jupyter notebook Titanic_network_analysis.ipynb
   ```

## 📦 Requirements

the following libaries are required to run the notebook:

```txt
networkx
matplotlib
pandas
numpy
```

## 📝 License

This project was developed for educational purposes. All character data is derived from a publicly available movie script and used under fair use.
