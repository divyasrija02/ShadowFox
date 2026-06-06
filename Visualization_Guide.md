# Visualization Library Documentation

## Matplotlib

### Overview
Matplotlib is a Python library used for creating charts and graphs.

### Line Plot
Used to show trends over time.

```python
import matplotlib.pyplot as plt

x=[1,2,3,4]
y=[10,20,15,30]

plt.plot(x,y)
plt.show()
## Seaborn

### Overview
Seaborn is a Python visualization library built on Matplotlib. It provides attractive and informative statistical graphics.

### Histogram
Used to show the distribution of data.

```python
import seaborn as sns
import matplotlib.pyplot as plt

tips = sns.load_dataset("tips")
sns.histplot(tips["total_bill"])
plt.show()
### Scatter Plot

Used to show the relationship between two variables.

```python
import seaborn as sns
import matplotlib.pyplot as plt

tips = sns.load_dataset("tips")
sns.scatterplot(x="total_bill", y="tip", data=tips)
plt.show()
```

## Comparison

| Feature | Matplotlib | Seaborn |
|----------|-----------|----------|
| Ease of Use | Medium | Easy |
| Customization | High | Medium |
| Appearance | Basic | Attractive |
| Statistical Graphs | Basic | Excellent |

## Conclusion

Matplotlib is a powerful visualization library with high customization options. Seaborn is built on Matplotlib and provides more attractive and statistical visualizations with less code. Both libraries are widely used in Data Science projects.
