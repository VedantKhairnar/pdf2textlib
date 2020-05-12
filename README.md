# pdf2textlib



[![PyPI Status](https://img.shields.io/pypi/v/pdf2textlib.svg)](https://pypi.org/project/pdf2textlib/)
[![Downloads](https://img.shields.io/pypi/dm/pdf2textlib.svg)](https://pypistats.org/packages/pdf2textlib)
![Stars](https://img.shields.io/github/stars/VedantKhairnar/pdf2textlib.svg?style=social)
![Forks](https://img.shields.io/github/forks/VedantKhairnar/pdf2textlib.svg?style=social)
![GitHub contributors](https://img.shields.io/github/contributors/VedantKhairnar/pdf2textlib.svg)
![Language](https://img.shields.io/github/languages/top/VedantKhairnar/pdf2textlib.svg)
[![GitHub](https://img.shields.io/github/license/VedantKhairnar/pdf2textlib.svg)](https://choosealicense.com/licenses/mit)
[![Say Thanks!](https://img.shields.io/badge/Say-Thanks!-yellow.svg)](https://vedantkhairnar.ml)
[![HitCount](http://hits.dwyl.io/VedantKhairnar/pdf2textlib.svg)](http://hits.dwyl.io/VedantKhairnar/pdf2textlib)
![Issues](https://img.shields.io/github/issues/VedantKhairnar/pdf2textlib)
![PRsWelcome](https://img.shields.io/badge/PRs-welcome-informational)

Simple Multilingual PDF text extraction, Also extracts from images

```python
import pdf2textlib

print(pdf2textlib.getText("Demo.pdf","eng+tel+urd"))  
# parameter 1 : Path to the PDF file
# parameter 2 : string of language codes separated by '+' sign 

```


## OS Dependencies

### Debian, Ubuntu, and friends

```
sudo apt-get install build-essential libpoppler-cpp-dev pkg-config python-dev
```

### Fedora, Red Hat, and friends

```
sudo yum install gcc-c++ pkgconfig poppler-cpp-devel python-devel redhat-rpm-config
```

### macOS

```
brew install pkg-config poppler
```

Conda users may also need `libgcc`:

```
conda install -c anaconda libgcc
```

### Windows

Currently tested only when using conda:

 - Install the Microsoft Visual C++ Build Tools
 - Install poppler through conda:
   ```
   conda install -c conda-forge poppler
   ```


## Install

```
pip install pdf2textlib
```
