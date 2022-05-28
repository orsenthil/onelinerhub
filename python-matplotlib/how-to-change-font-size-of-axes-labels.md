# How to change font size of axes labels

```python
import matplotlib as mpl
import matplotlib.pyplot as plt

mpl.rc('axes', labelsize=30)

plt.plot([2,1,3])
plt.set_xlabel('X')
plt.set_xlabel('Y')
plt.show()
```

- `import matplotlib.pyplot as plt` - loads [lib:Matplotlib module](python-matplotlib/how-to-install-matplotlib-python-lib-in-ubuntu-ubuntuversion) to use plotting capabilities
- `mpl.rc` - manage configuration
- `xtick` - setup x-axis ticks params
- `ytick` - setup y-axis ticks params
- `labelsize` - change size of labels for specified param
- `.show()` - render chart in a separate window

group: font_size

## Example: 
```python
import matplotlib as mpl

plt.plot([2,1,3])
plt.set_xlabel('X', fontsize=30)
plt.show()
```
