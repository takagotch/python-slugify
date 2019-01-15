### python-slugify
---
https://github.com/un33k/python-slugify

```
easy_install python-slugify
pip install python-slugify
git clone http://github.com/un33k/python-slugify
cd python-slugify
python setup.py install

python test.py
```

```py
from slugify import slugify
txt = "This is a test ---"
r = slugify(txt)
self.assertEqual(r, "this-is-a-test")

txt = ''
r = slugify(txt)
self.assertEqual(r, "ying-shi-ma")
```

```
```


