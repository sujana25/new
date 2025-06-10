

#  Mean-Variance-Std Calculator

This Python project computes statistics (mean, variance, standard deviation, max, min, sum) on a 3×3 matrix using NumPy.

## Functionality

The `calculate(input_list)` function:

* Accepts a list of **9 numbers**
* Converts it into a **3×3 matrix**
* Calculates stats across:

  * **Columns** (axis=0)
  * **Rows** (axis=1)
  * **Entire matrix**

##  Requirements

```bash
pip install numpy
```

## Example

```python
from mean_var_std import calculate
print(calculate([0, 1, 2, 3, 4, 5, 6, 7, 8]))
```

### Output (example):

```python
{
  'mean': [[3.0, 4.0, 5.0], [1.0, 4.0, 7.0], 4.0],
  'variance': [...],
  'standard deviation': [...],
  'max': [...],
  'min': [...],
  'sum': [...]
}
```

##  Error Handling

Raises `ValueError` if the list does not contain exactly 9 elements.

##  Files

* `mean_var_std.py` – main logic
* `README.md` – project info

