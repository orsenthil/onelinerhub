# How to enlarge (scale up) an image

```python
from PIL import Image

im = Image.open('/var/www/examples/small.png')
im = im.resize((150, 150))

im.show()
```


## Example: 
```python
from PIL import Image

im = Image.open('/var/www/examples/small.png')
im = im.resize((150, 150))

im.show()
```
