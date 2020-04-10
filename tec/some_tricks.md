# colab

## debug in colab

you can read this notebook for help. [Link](https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/01.06-Errors-and-Debugging.ipynb#scrollTo=rkiYEtSo8mW_)

```python
pip install ipdb
import ipdb
ipdb.set_trace() # set a breakpoint
python -m ipdb code.py
b 18 # the line that you want to set a breakpoint
c # run the program until meets a breakpoint
p a # print variable a
```

---------

## Command 

----------

| Command      |                         Description                         |
| ------------ | :---------------------------------------------------------: |
| `list`       |            Show the current location in the file            |
| `h(elp)`     | Show a list of commands, or find help on a specific command |
| `q(uit)`     |              Quit the debugger and the program              |
| `c(ontinue)` |         Quit the debugger, continue in the program          |
| `n(ext)`     |             Go to the next step of the program              |
| `enter`      |                 Repeat the previous command                 |
| `p(rint)`    |                       Print variables                       |
| `s(tep)`     |                   Step into a subroutine                    |
| `r(eturn)`   |                 Return out of a subroutine                  |
| `b(reak)`    |              b 18 Set a breakpoint at line 18               |

-----------

