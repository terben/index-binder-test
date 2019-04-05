# index-binder-test
test repository for a binder repository with a *Table of Contents*

For lecture notes, I would like a certain notebook (a Table of Contents) to be automatically launched when it is called via `BinderHub`.

To achieve this, I modified the original `BinderHub`-link

"""
https://mybinder.org/v2/gh/terben/index-binder-test/master
"""

to

"""
https://mybinder.org/v2/gh/terben/index-binder-test/master?urlpath=tree/index.ipynb
"""

Here `index.ipynb` is the notebook that is automatically launched when the link above is called.

Please test this setup with the button [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/terben/index-binder-test/master?urlpath=tree/index.ipynb)
