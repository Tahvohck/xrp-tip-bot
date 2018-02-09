# Branches
* master -> Releases. No changes on this branch.
* release-candiates -> Pulled from development branch. Minor tweaks allowed.
* dev -> Mainline development. Changes allowed but discouraged.
* ftr-* -> Feature branch. Used for developing new features. Splits from dev and merges back in WITHOUT a FF.
* bfx-* -> bugfix branch. Used for fixing bugs

# Python code
Python interpreter version: 3.5  
Tab size: 4 characters. This holds whether you use tabs or spaces. If you can't change the tabstop in your editor, get a better editor.  
PEP8. Use `pycodestyle` to verify.
##### Changes to PEP8 that are allowed:
```ini
[pycodestyle]
# W191: Indentation contains tabs
# W503: line break occurred before a binary operator
# E1:   INDENTATIONS
# E121: continuation line under-indented for hanging indent
# E123: closing bracket does not match indentation of opening bracket’s line
# E126: continuation line over-indented for hanging indent
# E2:   WHITESPACE
# E24:  E241 multiple spaces after ‘,’ + E242 tab after ‘,’
# E274: tab before keyword
# E401: Multiple imports on one line
# E704: multiple statements on one line (def)
ignore = W191,W503,E121,E123,E126,E24,E274,E401,E704
max-line-length = 119
```

# JavaScript code
No standards yet.

# HTML code
Must be XHTML5 compliant on final rendering.

# CSS code
No standards yet.
