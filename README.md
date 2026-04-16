Data Visualization and Visual Encoding in Python
This repository contains the implementation of Experiment 17, which focuses on the principles of graphical data representation. The project demonstrates how to use Python's powerful visualization libraries to map data attributes to visual channels such as position, length, and color.

👤 Student Information
Name: Shreyas Wani

PRN: 25070123131

Institute: Symbiosis Institute of Technology (SIT), Pune

🎯 Aim
To implement basic charts in Python and understand the concept of Visual Encoding—the process of converting data values into visual marks and channels.

🛠️ Technologies Used
Language: Python

Libraries: * Matplotlib: For core plotting and chart construction.

Seaborn: For high-level statistical data visualization.

Pandas: For handling and organizing data structures.

Environment: Google Colab / Jupyter Notebook

📑 Key Features Implemented
1. Categorical Data Encoding (Bar Charts)
Visual Channel: Length and Position.

Implementation: Using plt.bar() to compare discrete categories (e.g., Categories A-E).

Use Case: Effective for showing magnitude and comparing differences between groups.

2. Multi-Dimensional Encoding (Scatter Plots)
Visual Channels: 2D Position (X, Y), Size (Area), and Color.

Implementation: Utilizing plt.scatter() where the size of the marker is determined by a data array (sizes) and color is used for differentiation.

Use Case: Ideal for identifying correlations, clusters, and outliers in numerical data.

3. Distribution Analysis (Histograms)
Visual Channel: Height and Area.

Implementation: Visualizing the frequency distribution of a single numerical variable to understand the "shape" of the data.

4. Professional Formatting
Integration of axis labels, titles, and legends.

Customization of figure sizes and color palettes (e.g., skyblue, salmon) to improve readability and aesthetic appeal.

🚀 How to Run
Clone the repository:

Bash
git clone https://github.com/your-username/data-viz-encoding.git
Install dependencies:

Bash
pip install matplotlib seaborn pandas
Execution:
Open exp17.ipynb in your preferred notebook environment and run all cells to generate the visualizations.
