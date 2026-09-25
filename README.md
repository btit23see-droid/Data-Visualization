# Data Visualization using Matplotlib & Seaborn

A hands-on collection of Jupyter notebooks for learning **data visualization in Python** using **Matplotlib** and **Seaborn** — starting from the basics, moving through arranging multiple plots in one figure, and on to statistical visualizations, customization, and practical charting.

**Python · Matplotlib · Seaborn · NumPy · Pandas · Jupyter Notebook**

---

## 📁 Project Structure

```text
Data-Visualization/
└── Practice/
    ├── Matplotlib/
    │   ├── .gitkeep
    │   └── matplotlib_for_beginners.ipynb
    │
    ├── Seaborn/
    │   ├── .gitkeep
    │   └── Seaborn_for_Beginners.ipynb
    │
    ├── .gitkeep
    └── subplot.ipynb
```

The notebooks are designed to be followed step by step, with examples and explanations alongside the code.

---

## 📓 Notebooks

| # | Notebook | Location | What you'll learn |
|---|---|---|---|
| 1 | `matplotlib_for_beginners.ipynb` | `Practice/Matplotlib/` | Matplotlib from zero; first line chart; titles and axis labels; line, bar, histogram, scatter and pie charts; colors, line styles and markers; chart customization; choosing between Matplotlib, Seaborn, Pandas plotting and interactive libraries |
| 2 | `subplot.ipynb` | `Practice/` | Arranging multiple plots in a single figure; `plt.subplot()` vs `plt.subplots()`; indexing Axes on a grid; `figsize`; sharing axes with `sharex`/`sharey`; whole-figure titles with `suptitle`; mixing plot types in one grid; spacing with `subplots_adjust` and `tight_layout`; custom layouts with `GridSpec`; saving multi-plot figures |
| 3 | `Seaborn_for_Beginners.ipynb` | `Practice/Seaborn/` | What Seaborn is; relationship between Pandas, Seaborn and Matplotlib; loading and inspecting datasets; scatter, line, bar, count, histogram, box and heatmap plots; `x`, `y`, `data` and `hue`; basic chart customization; visualizing relationships, distributions and categories |

### Suggested order

**1 → 2 → 3**

Start with Matplotlib to understand the fundamentals of Python visualization, then learn to arrange multiple plots in one figure with subplots, and finally move to Seaborn for easier statistical and DataFrame-based visualizations.

---

## 📊 What You'll Learn

### Matplotlib (`Practice/Matplotlib/matplotlib_for_beginners.ipynb`)

The Matplotlib notebook teaches visualization from the beginning in small, easy-to-follow steps.

Topics include:

- Introduction to Matplotlib
- Setting up Matplotlib and NumPy
- Creating your first line chart
- Adding titles
- Adding X-axis and Y-axis labels
- Line charts
- Bar charts
- Pie charts
- Histograms
- Scatter plots
- Changing chart colors
- Changing marker sizes
- Customizing charts
- Saving charts to a file
- Understanding when to use Matplotlib versus other visualization libraries

The notebook is designed so that each new concept is introduced gradually, allowing you to see exactly what changes in the resulting chart. It ends with 10 practice tasks covering everything introduced.

### Subplots (`Practice/subplot.ipynb`)

The subplot notebook focuses specifically on combining multiple plots into a single figure with Matplotlib.

Topics include:

- `plt.subplot(rows, cols, position)` — selecting one plot at a time in a grid
- `plt.subplots(rows, cols)` — creating the Figure and Axes together
- Indexing Axes: `axes[row, col]`
- Differences between `plt.subplot()` and `plt.subplots()`
- Controlling figure size with `figsize`
- Sharing axes with `sharex` and `sharey`
- Giving the whole figure one title with `fig.suptitle()`
- Mixing different plot types (line, bar, scatter, histogram) in one grid
- Manual spacing with `subplots_adjust` vs. automatic `tight_layout`
- Uneven layouts with `matplotlib.gridspec.GridSpec`
- Saving a full multi-subplot figure with `fig.savefig()`

### Seaborn (`Practice/Seaborn/Seaborn_for_Beginners.ipynb`)

The Seaborn notebook introduces statistical visualization and explains how Seaborn works together with Pandas and Matplotlib.

Topics include:

- What Seaborn is
- Why Seaborn is used
- Seaborn vs Matplotlib
- Working with Pandas DataFrames
- Loading datasets with Seaborn
- Inspecting data with Pandas
- Scatter plots
- Line plots
- Bar plots
- Count plots
- Histograms
- Box plots
- Heatmaps
- Using `x`, `y`, `data` and `hue`
- Titles and labels
- Themes and basic customization
- Visualizing relationships
- Visualizing distributions
- Visualizing categories

The notebook uses Seaborn's built-in **`tips` dataset** for the visualization examples, and ends with a mini practice project and a final cheat sheet.

---

## 🔗 How the Libraries Work Together

A key concept covered in the notebooks is the relationship between Pandas, Seaborn and Matplotlib:

```text
Pandas
   ↓
Handles and organizes data
   ↓
Seaborn
   ↓
Makes statistical visualizations easier
   ↓
Matplotlib
   ↓
Provides the underlying plotting engine, subplots, and fine control
```

In simple terms:

> **Pandas → handles the data**  
> **Seaborn → makes statistical plots easier**  
> **Matplotlib → provides full control, including multi-plot layouts (subplots)**

Seaborn is built on top of Matplotlib, so understanding Matplotlib — and how to lay out multiple plots with subplots — first provides a useful foundation for working with Seaborn.

---

## 📊 Dataset

### Seaborn `tips` Dataset

The Seaborn notebook uses the built-in `tips` dataset for the visualization examples.

The dataset is used to demonstrate:

- Relationships between variables
- Categories
- Distributions
- Grouping with `hue`
- Different statistical plots

The Matplotlib and subplot notebooks use small, hand-written sample data (lists and NumPy arrays) defined directly in the notebook cells.

---

## 🖼️ Sample Visualizations

The notebooks contain generated chart outputs demonstrating the concepts being taught.

Examples include:

- 📈 Line charts
- 📊 Bar charts
- 🥧 Pie charts
- 📉 Histograms
- 🔵 Scatter plots
- 📦 Box plots
- 🌡️ Heatmaps
- 📊 Count plots
- 🧩 Multi-plot grids (subplots)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/btit23see-droid/Data-Visualization.git
cd Data-Visualization/Practice
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

**Windows:**

```bash
venv\Scripts\activate
```

**macOS / Linux:**

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install matplotlib seaborn pandas numpy jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Then start with:

```text
Matplotlib/matplotlib_for_beginners.ipynb
```

After completing the Matplotlib notebook, continue with:

```text
subplot.ipynb
```

Then finish with:

```text
Seaborn/Seaborn_for_Beginners.ipynb
```

---

## 🛠️ Tech Stack

- **Python 3** — programming language
- **NumPy** — numerical operations and data preparation
- **Pandas** — working with DataFrames and datasets
- **Matplotlib** — core Python visualization library (including subplots/multi-plot layouts)
- **Seaborn** — statistical data visualization
- **Jupyter Notebook / Google Colab** — interactive learning environment

---

## 🎯 Learning Goals

By working through this repository, you will practice:

- Creating charts from Python data
- Understanding different chart types
- Customizing chart appearance
- Adding titles and axis labels
- Arranging multiple plots in a single figure
- Comparing Matplotlib and Seaborn
- Working with Pandas DataFrames
- Creating statistical visualizations
- Understanding relationships between variables
- Visualizing distributions and categories
- Using `hue` to separate categories
- Choosing an appropriate visualization for your data

---

## 📚 Learning Path

```text
Python Basics
     ↓
Matplotlib Fundamentals
     ↓
Line / Bar / Pie / Histogram / Scatter
     ↓
Chart Customization
     ↓
Subplots — Multiple Plots in One Figure
     ↓
Seaborn Fundamentals
     ↓
Statistical Visualizations
     ↓
Relationships / Distributions / Categories
```

---

## 🙋 Author

**Seema Chaudhary**

If you find this repository helpful, consider giving it a ⭐!
