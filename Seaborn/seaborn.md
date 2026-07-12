# Seaborn Plot Types

## Types of Functions

### 1. Figure-level Functions
- Create and manage the entire figure automatically.
- Can generate multiple subplots based on categorical variables.
- Usually return a `FacetGrid`, `PairGrid`, or `JointGrid`.
- Examples: `relplot()`, `catplot()`, `displot()`, `lmplot()`, `pairplot()`, `jointplot()`

### 2. Axes-level Functions
- Draw plots on a single Matplotlib Axes.
- Used when you want more control over subplot layouts.
- Can be combined with `plt.subplot()` or `plt.subplots()`.
- Examples: `scatterplot()`, `lineplot()`, `barplot()`, `countplot()`, `boxplot()`, `violinplot()`, `histplot()`, `kdeplot()`, `regplot()`, `heatmap()`

---

# Categories of Seaborn Plots

## 1. Relational Plots
Used to visualize the relationship between two continuous variables.

**Examples**
- `scatterplot()`
- `lineplot()`

**Figure-level Equivalent**
- `relplot()`

---

## 2. Categorical Plots
Used to analyze data based on discrete groups or categories.

**Examples**
- `barplot()`
- `countplot()`
- `boxplot()`
- `violinplot()`
- `stripplot()`
- `swarmplot()`
- `pointplot()`

**Figure-level Equivalent**
- `catplot()`

---

## 3. Distribution Plots
Used to show the distribution of one or more variables.
Univariate analysis, Central tendency, any outliners

**Examples**
- `histplot()`
- `kdeplot()`
- `ecdfplot()`
- `rugplot()`

**Figure-level Equivalent**
- `displot()`

---

## 4. Regression Plots
Used to visualize the relationship between variables along with a regression line.

**Examples**
- `regplot()`

**Figure-level Equivalent**
- `lmplot()`

---

## 5. Matrix Plots
Used to visualize matrices, correlations, or large datasets using colors.

**Examples**
- `heatmap()`
- `clustermap()`

> `clustermap()` is a figure-level function, while `heatmap()` is an axes-level function.

---

## 6. Multi-plot Grids
Used to create multiple related plots arranged in a grid.

**Examples**
- `pairplot()`
- `jointplot()`
- `PairGrid`
- `FacetGrid`
- `JointGrid`

---

# Summary Table

| Plot Category | Axes-level Functions | Figure-level Functions |
|---------------|----------------------|------------------------|
| Relational | `scatterplot()`, `lineplot()` | `relplot()` |
| Categorical | `barplot()`, `countplot()`, `boxplot()`, `violinplot()`, `stripplot()`, `swarmplot()`, `pointplot()` | `catplot()` |
| Distribution | `histplot()`, `kdeplot()`, `ecdfplot()`, `rugplot()` | `displot()` |
| Regression | `regplot()` | `lmplot()` |
| Matrix | `heatmap()` | `clustermap()` |
| Multi-plot Grids | `PairGrid`, `FacetGrid`, `JointGrid` | `pairplot()`, `jointplot()` |