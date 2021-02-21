# Jupyter

How to add Python virtualenv to IPython Jupyter notebook
1)
Install jupyter
```$pip install -U jupyter```

2)
Create virtual environment
```$virtualenv myenv1```

3)
Activate virtual environment
```$source myenv1/bin/activate```

4)
Install ipykernel in virtual environment
```$ pip install ipykernel```

5)
Add python and ipykernel in the virtual environment to jupyter notebook
```$ python -m ipykernel install --user --name=myenv1```

You should now be able to see your (virtualenv) kernel in the IPython
notebook menu: Kernel -> Change kernel and be able so switch to it.

https://youtu.be/jv8gQd4g0Og
