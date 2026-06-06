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
