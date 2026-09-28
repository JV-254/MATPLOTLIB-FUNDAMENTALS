# MATPLOTLIB-FUNDAMENTALS
# Matplotlib Fundamentals

This repository contains my practice and learning notes for **Matplotlib**, a Python library used for data visualization.

## What I Learned

### 1. What is Matplotlib?

Matplotlib is a Python library used to create visualizations from data.

It can be used to create:

* Line charts
* Scatter plots
* Bar charts
* Histograms
* Pie charts
* Box plots

For this first chapter, I focused on **basic line charts**.

---

## 2. Importing Matplotlib

The `pyplot` module is commonly used for creating charts.

```python
import matplotlib.pyplot as plt
```

`plt` is an alias for `matplotlib.pyplot`, making it easier to write plotting commands.

---

## 3. Creating a Basic Line Plot

The `plt.plot()` function is used to create a line chart.

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5]
y = [10, 20, 15, 25, 30]

plt.plot(x, y)
plt.show()
```

The `x` values are plotted on the x-axis, while the `y` values are plotted on the y-axis.

---

## 4. Adding a Title

The `plt.title()` function adds a title to the chart.

```python
plt.title("Monthly Sales")
```

---

## 5. Labeling the Axes

### X-axis

```python
plt.xlabel("Month")
```

### Y-axis

```python
plt.ylabel("Sales (KSh)")
```

Axis labels make it easier to understand what the chart represents.

---

## 6. Adding Gridlines

Gridlines can make values easier to read.

```python
plt.grid()
```

---

## 7. Displaying the Chart

The `plt.show()` function displays the chart.

```python
plt.show()
```

---

# Basic Matplotlib Structure

The basic workflow I learned is:

```text
Import
   ↓
Prepare Data
   ↓
Create Plot
   ↓
Add Title
   ↓
Label Axes
   ↓
Add Grid
   ↓
Display Chart
```

A basic program looks like this:

```python
import matplotlib.pyplot as plt

x = [...]
y = [...]

plt.plot(x, y)

plt.title("Chart Title")
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.grid()

plt.show()
```

---

# Practice Project 1 — Study Hours

I created a line chart showing study hours from Monday to Friday.

```python
import matplotlib.pyplot as plt

days = ["Monday", "Tuesday", "Wednesday", "Thursday", "Friday"]
study_hours = [2, 4, 3, 5, 6]

plt.plot(days, study_hours)

plt.title("Study Hours Per Day")
plt.xlabel("Day")
plt.ylabel("Study Hours")
plt.grid()

plt.show()
```

### Data

| Day       | Study Hours |
| --------- | ----------: |
| Monday    |           2 |
| Tuesday   |           4 |
| Wednesday |           3 |
| Thursday  |           5 |
| Friday    |           6 |

### Observation

The data shows an overall increase in study hours throughout the week, although study hours decreased from Tuesday to Wednesday.

---

#  Practice Project 2 — Monthly Sales

I also created a line chart showing monthly sales.

```python
import matplotlib.pyplot as plt

months = ["Jan", "Feb", "Mar", "Apr", "May", "Jun"]
sales = [12000, 15000, 13000, 18000, 22000, 25000]

plt.plot(months, sales)

plt.title("Monthly Sales")
plt.xlabel("Month")
plt.ylabel("Sales (KSh)")
plt.grid()

plt.show()
```

### Data

| Month |  Sales |
| ----- | -----: |
| Jan   | 12,000 |
| Feb   | 15,000 |
| Mar   | 13,000 |
| Apr   | 18,000 |
| May   | 22,000 |
| Jun   | 25,000 |

### Observation

The sales data shows an overall upward trend from January to June, with a decrease in sales between February and March.

---

#  Matplotlib Functions Learned

| Function       | Purpose             |
| -------------- | ------------------- |
| `plt.plot()`   | Creates a line plot |
| `plt.title()`  | Adds a chart title  |
| `plt.xlabel()` | Labels the x-axis   |
| `plt.ylabel()` | Labels the y-axis   |
| `plt.grid()`   | Adds gridlines      |
| `plt.show()`   | Displays the chart  |

---

# Key Takeaways

* Matplotlib is used for **data visualization in Python**.
* `matplotlib.pyplot` provides many functions for creating charts.
* `plt.plot()` creates a basic line chart.
* The x-axis represents the independent or categorical/ordered variable.
* The y-axis represents the measured variable.
* Titles and axis labels make visualizations easier to understand.
* Gridlines can improve readability.
* `plt.show()` displays the visualization.

---

# Next Topics

The next chapter will focus on **customizing line charts**, including:

* Markers
* Line styles
* Line width
* Multiple lines
* Legends
* Better chart presentation

---

##  Learning Progress

* [x] Introduction to Matplotlib
* [x] Importing Matplotlib
* [x] Basic line plots
* [x] Titles
* [x] Axis labels
* [x] Gridlines
* [x] Displaying charts
* [ ] Line plot customization
* [ ] Scatter plots
* [ ] Bar charts
* [ ] Histograms
* [ ] Box plots
* [ ] Subplots
* [ ] Pandas + Matplotlib
* [ ] Data visualization projects
