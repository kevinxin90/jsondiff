jsondiff
========

Small tool which making diff between json data sources in RFC 6902 format.

Usage:
```
>>> import jsondiff
>>> src = {'foo': 'bar'}
>>> dest = {'foo': 'baz'}
>>> patch = jsondiff.make(src, dest)
```
