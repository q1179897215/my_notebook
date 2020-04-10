# sklearn

## model_selection.train_test_split

+ allowed inputs are lists, numpy arrays or pandas dataframes
+ two sequence with same shape[0]

+ shuffle = True 
+ random state

### Examples

```python
import numpy
import sklearn.model_selection
x, y = np.arange(10).reshape(5, 2), np.arange(100).reshape(5, 2, 10)
x_train, x_test, y_train, y_test = sklearn.model_selection.train_test_split(
    x, 
    y, 
    train_size=0.8,
    shuffle=True,
    random_state=1)
y_train #just having the same shape[0] will be ok
```

```
array([[[20, 21, 22, 23, 24, 25, 26, 27, 28, 29],
        [30, 31, 32, 33, 34, 35, 36, 37, 38, 39]],

       [[80, 81, 82, 83, 84, 85, 86, 87, 88, 89],
        [90, 91, 92, 93, 94, 95, 96, 97, 98, 99]],

       [[ 0,  1,  2,  3,  4,  5,  6,  7,  8,  9],
        [10, 11, 12, 13, 14, 15, 16, 17, 18, 19]],

       [[60, 61, 62, 63, 64, 65, 66, 67, 68, 69],
        [70, 71, 72, 73, 74, 75, 76, 77, 78, 79]]])
```







 