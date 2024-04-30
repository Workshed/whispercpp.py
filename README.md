Python bindings for whisper.cpp
===============================

<a href="https://www.buymeacoffee.com/lukeFxC" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

Forked from https://github.com/stlukey/whispercpp.py and word level timings added.

---
`pip install git+https://github.com/Workshed/whispercpp.py`

```python
from whispercpp import Whisper

w = Whisper('tiny')

result = w.transcribe("myfile.mp3")
text = w.extract_text(result)
```

Note: default parameters might need to be tweaked.
See Whispercpp.pyx.
