# binder-test
[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/knowsuchagency/binder-test)
Click me!


## This is a [Jupyter](http://jupyter.org/) notebook brought to you by [Binder](http://mybinder.org)
## Binder is magic! So are Jupyter notebooks


### We can link to other notebooks in this repo via [relative links](subfolder/hello.ipynb) (double click this cell to view the raw markdown)
### Check out other cool notebooks at [nbviewer](https://nbviewer.jupyter.org/)


```python
from IPython.display import Image
Image(url="http://i.imgur.com/hvFv1ow.png")
```




<img src="http://i.imgur.com/hvFv1ow.png"/>



### Let's play with some sample data in the repo


```python
from pprint import pprint
import json

with open('MOCK_DATA.json') as foo:
    data = json.load(foo)

pprint(data[:3])
```

    [{'email': 'jmoreno0@narod.ru',
      'first_name': 'Jeffrey',
      'gender': 'Male',
      'ip_address': '230.166.67.38',
      'last_name': 'Moreno'},
     {'email': 'tfernandez1@dagondesign.com',
      'first_name': 'Timothy',
      'gender': 'Male',
      'ip_address': '1.230.150.151',
      'last_name': 'Fernandez'},
     {'email': 'dtorres2@com.com',
      'first_name': 'Dorothy',
      'gender': 'Female',
      'ip_address': '154.135.188.14',
      'last_name': 'Torres'}]


--------

### This notebook is the first page that came up when you clicked on the **launch binder** button because I named it index.ipynb

Had I named it something else like example.ipynb, it would open a page like the one you see if you click on _File -> Open..._

Go ahead and click on that button now and see what comes up.

You should see something like **this**: 

<img src='http://i.imgur.com/8xky9GD.png'>

### You can open a terminal to play in the command line if you need to as well 

<img src='http://i.imgur.com/ZOh16Ak.png'>

### In order to get started, you'll need to first have python installed on your system (preferrably the latest version of python 3)

**Step 1**

```pip install jupyter```

**Step 2**

```jupyter notebook```

**Step 3**

Create a notebook and save it.

**Step 4**

Push the folder with the notebook to github.

**Step 5**

Insert the link into the repo in the [binder](http://mybinder.org/) build repository form.

<img src='http://i.imgur.com/IRHFtbJ.png'>

Binder will build a VM for others to run your notebook and will give you a link to add to the project's README to add a button to allow people to do so. 

<img src='http://i.imgur.com/ezRPTjv.png'>

Wait for binder to finish, add the link to your README (in this case: \[!\[Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/knowsuchagency/binder-test) ) and voilà!




```python

```
