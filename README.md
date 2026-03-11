# Python for Computational Sensorimotor Control

A complete series of interactive Python tutorials designed for **graduate students in movement neuroscience and sensorimotor control**. Every concept is taught through examples drawn from real research — EMG signals, kinematic trajectories, reaction times, trial metadata, and experimental data analysis.

---

## 📚 Lessons

| # | Notebook | Topics | Open |
|---|---------|--------|------|
| L0 | [Python Basics](L0_Python_Basics.ipynb) | Variables, types, strings &amp; string methods, booleans, None, if/elif/else, for/while loops, break/continue, range | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tarkeshsingh/python-for-sensorimotor-control/blob/main/L0_Python_Basics.ipynb) |
| L1 | [Intro to NumPy](L1_Intro_to_Numpy.ipynb) | Arrays, element-wise ops, linspace/arange, indexing &amp; slicing, views vs copies, Boolean &amp; fancy indexing, NaN handling, ufuncs, statistics with axis, random seeds, meshgrid, np.where, linear algebra, reshaping, broadcasting | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tarkeshsingh/python-for-sensorimotor-control/blob/main/L1_Intro_to_Numpy.ipynb) |
| L2 | [Functions, Structures &amp; Controls](L2_Functions_Structures_Controls.ipynb) | Tuples, lists, slicing, dicts, sets, enumerate, zip, sorted, comprehensions, functions, \*args/\*\*kwargs, docstrings &amp; type hints, recursion, lambda, generators, try/except | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tarkeshsingh/python-for-sensorimotor-control/blob/main/L2_Functions_Structures_Controls.ipynb) |
| L3 | [Intro to Matplotlib](L3_Intro_to_Matplotlib.ipynb) | Line, bar, histogram, scatter, pie, box, heatmap plots; customization (color, markers, error bars); Figures vs Axes; subplots; multi-panel figures; saving to PDF/PNG | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tarkeshsingh/python-for-sensorimotor-control/blob/main/L3_Intro_to_Matplotlib.ipynb) |
| L4 | [Intro to Pandas](L4_Intro_to_Pandas.ipynb) | Series, DataFrames, read/write CSV &amp; Excel, loc/iloc, Boolean indexing, missing data (dropna/fillna/interpolate), sorting, merge &amp; concat, pivot_table &amp; melt, apply/applymap, groupby, hierarchical indexing | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tarkeshsingh/python-for-sensorimotor-control/blob/main/L4_Intro_to_Pandas.ipynb) |
| L5 | [Seaborn Data Visualization](L5_Seaborn_Data_Visualization.ipynb) | Line, bar, box, violin plots; lmplot regression; joint plots; bar+swarm overlays; KDE contours; PairGrid; pairplot; 3-D regression; heatmaps &amp; clustermaps | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tarkeshsingh/python-for-sensorimotor-control/blob/main/L5_Seaborn_Data_Visualization.ipynb) |
| L6 | [Intro to OOP](L6_Intro_to_OOP.ipynb) | Classes, instances, attributes, methods, \_\_init\_\_/\_\_str\_\_, inheritance, super(), polymorphism, @property, encapsulation, composition, dataclasses | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tarkeshsingh/python-for-sensorimotor-control/blob/main/L6_Intro_to_OOP.ipynb) |
| L7 | [Intro to ODEs](L7_Intro_to_ODEs.ipynb) | Euler method, RK4, solve_ivp, systems of ODEs, exponential decay, spring-mass-damper, inverted pendulum, two-state motor adaptation | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tarkeshsingh/python-for-sensorimotor-control/blob/main/L7_Intro_to_ODEs.ipynb) |

---

## 🧠 Who Is This For?

These tutorials are designed for **graduate students in movement neuroscience, kinesiology, biomechanics, and motor control** who are new to Python or transitioning from MATLAB. Every lesson uses domain-specific examples:

- EMG signals and muscle activation envelopes
- Kinematic trajectories and velocity profiles
- Reaction times and endpoint errors across experimental conditions
- Trial metadata, participant demographics, and grouped analyses
- Publication-quality figures with individual data points

---

## 🗺️ Recommended Learning Path

```
L0: Python Basics
 └─▶ L1: NumPy (arrays & numerical computing)
      └─▶ L2: Functions, Structures & Controls (data structures & flow)
           ├─▶ L3: Matplotlib (visualization)
           │    └─▶ L5: Seaborn (statistical visualization)
           └─▶ L4: Pandas (tabular data)
                └─▶ L6: OOP (organizing your code)
                     └─▶ L7: ODEs (simulating dynamic systems)
```

Lessons are designed to be completed in order (L0 → L6), but students with prior Python experience can start at L1 or L2.

---

## 🚀 Getting Started

### Option 1: Google Colab (Recommended — No Installation)
Click any **"Open in Colab"** badge in the table above. Colab provides a free Python environment with all libraries pre-installed.

### Option 2: Local Jupyter Notebook
```bash
# Clone this repository
git clone https://github.com/tarkeshsingh/python-for-sensorimotor-control.git
cd YOUR_REPO_NAME

# Install dependencies
pip install numpy matplotlib pandas seaborn statsmodels

# Launch Jupyter
jupyter notebook
```

---

## 📦 Dependencies

All notebooks use standard scientific Python libraries that come pre-installed in Google Colab:

- Python 3.8+
- NumPy
- Matplotlib
- Pandas
- Seaborn
- Statsmodels (L5 only — for 3-D regression example)

---

## 📖 What Each Lesson Covers

### L0 — Python Basics
Your first steps: variables, printing, importing libraries, indentation, scalar types (int, float, str, bool, None), string methods (split, join, strip, startswith), f-string formatting, and basic control flow (if/elif/else, for, while, break, continue, pass, range).

### L1 — Introduction to NumPy
The foundation of scientific computing: creating arrays, element-wise operations, linspace vs arange, 2-D arrays, indexing and slicing (with the critical view-vs-copy distinction), Boolean and fancy indexing, **NaN handling** (nanmean, nanstd, isnan), universal functions, statistics with axis control, random number generation with seeds, meshgrid, np.where, linear algebra, reshaping, concatenation, and broadcasting.

### L2 — Functions, Data Structures & Control Flow
Python's core toolkit: tuples, lists, slicing, dictionaries, sets, if/elif/else, for/while loops, **enumerate**, **zip**, **sorted vs .sort()**, list/set/dict comprehensions, functions with default arguments, **\*args and \*\*kwargs**, **docstrings and type hints**, recursion, lambda functions, generators, and try/except error handling.

### L3 — Introduction to Matplotlib
Visualization from basics to publication quality: line, bar, histogram, scatter, pie, box, and heatmap plots; customization (color, linewidth, markers, alpha, error bars); the Figure/Axes object model; creating subplots with add_axes, subplot, subplot2grid, and the recommended plt.subplots(); multi-panel figures; and saving to PDF/PNG/SVG.

### L4 — Introduction to Pandas
Tabular data mastery: Series and DataFrames, **reading/writing CSV and Excel files** with key parameters, loc vs iloc indexing, Boolean indexing, **handling missing data** (isna, dropna, fillna, interpolate), **sorting by values**, useful utilities (value_counts, unique, rename, corr), **merging and concatenating** DataFrames, **reshaping with pivot_table and melt**, arithmetic and broadcasting, apply/applymap, descriptive statistics, hierarchical indexing, and groupby aggregation.

### L5 — Seaborn Data Visualization
Statistical visualization: line plots with CI bands, grouped bar charts, box plots, violin plots, lmplot regression by group, joint plots with marginal distributions, **bar+swarm overlays** (the modern standard for scientific figures), KDE contours, PairGrid, pairplot scatterplot matrices, 3-D regression surfaces, and heatmaps/clustermaps.

### L6 — Introduction to OOP
Organizing research code: classes, instances, class vs instance attributes, instance methods, \_\_init\_\_ and \_\_str\_\_, inheritance and super(), polymorphism, **@property for computed attributes**, **encapsulation with the \_ convention**, **composition ("has-a" relationships)** for building Experiment → Participant → Trial hierarchies, and **dataclasses** for reducing boilerplate in data containers. Includes a complete Signal → EMGSignal / KinematicSignal framework.

### L7 — Introduction to ODEs
Numerical simulation of dynamic systems: what an ODE is and why it matters for motor control, Euler's method (implementation, accuracy, and limitations), the 4th-order Runge-Kutta method (RK4) with step-by-step derivation, comparing Euler vs RK4 convergence, SciPy's `solve_ivp` with adaptive step sizes, and four worked examples — passive muscle force decay, spring-mass-damper limb dynamics, inverted pendulum postural control with PD controller, and a two-state motor adaptation model showing savings and spontaneous recovery.

---

## ✏️ Each Lesson Includes

- **Structured explanations** with markdown cells before every code block
- **Inline comments** on every key line of code
- **Reference tables** for quick lookup of parameters, functions, and patterns
- **Movement neuroscience examples** throughout (not generic textbook examples)
- **Hands-on exercises** (3–5 per lesson) with scaffolded starter code
- **Summary table** and **further reading links** at the end

---

## 📄 License

These materials are provided for educational use. Feel free to adapt them for your own courses with attribution.

---

## 🙏 Acknowledgments

Tutorials developed for graduate instruction in computational sensorimotor control. Content informed by [Real Python](https://realpython.com/), [Python for Data Analysis](https://wesmckinney.com/book/) by Wes McKinney, and the official documentation of [NumPy](https://numpy.org/doc/), [Pandas](https://pandas.pydata.org/docs/), [Matplotlib](https://matplotlib.org/stable/), and [Seaborn](https://seaborn.pydata.org/).
