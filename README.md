# PyFemap
Useful tools for interfacing Femap with Python

## Instalation

To use the Femap interface you must `pip install pywin32` and run the script
```python3
import sys
from win32com.client import makepy
sys.argv = ["makepy", "-o PyFemap.py", r"{YOUR FEMAP INSTALATION DIRECTORY}\femap.tlb"]
makepy.main()
```
source: https://community.sw.siemens.com/s/article/writing-the-femap-api-in-python

