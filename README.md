# Installing python packages and libraries

- Before installing any package or library, make sure that your pip version is up-to-date. 

```
pip install --upgrade pip
pip --version
```

- You can list all the installed packages in your machine, including editables: 

```
pip list
```
[pip documentation - pip list](https://pip.pypa.io/en/stable/reference/pip_list/)

- If you want to know more about an installed package in your machine:

```
pip show pkg-name
```

*_Instead of ´´´pkg-name´´´ type the name of the package you want to show._

# Some Python packages and libraries:

## 1. Installing os-sys
[os-sys](https://pypi.org/project/os-sys/)

```
pip install os-sys
```
This command downloads:
- os-sys
  - pandas
  - mysql-connector
  - pyyaml
  - progressbar
  - mathparse
  - pygubu
  - PyInstaller
  - pint
  - cefpython3
  - tqdm
  - pytest
  - wifi


  - sqlalchemy
  - numpy
  - sqlparse
  - extract-zip
  - requests-download
  - Django
  - progressbar
  - netifaces
  - spacy
  - os-sys-php
  - Eel
  - tuspy
  - nltk
  - selenium
  - pyvalid
  - jupyter
  - pypiwin32
  - auto-py-to-exe
  - geocoder
  - beautifulsoup4
  - pyspeedtest
  - psutil
  - progress
  - matplotlib (will need the requirement: text-editor)

## 2. Installing wget
[wget](https://pypi.org/project/wget/)

```
pip install wget
```


## 3. Installing pandas
[pandas](https://pypi.org/project/pandas/)

```
pip install pandas
```


## 4. Installing matplotlib
[matplotlib](https://pypi.org/project/matplotlib/)

```
pip install matplotlib
```

## 5. Installing numpy
[numpy](https://pypi.org/project/numpy/)

```
pip install numpy
```


## 6. Installing tensorflow
[tensorflow](https://pypi.org/project/tensorflow/)

```
pip install tensorflow
```

## 7. Installing OpenCV
[OpenCV](https://pypi.org/project/mtcnn-opencv/)

```
#requires numpy: pip install numpy

pip install opencv-python
```
[OpenCV Documentation](https://docs.opencv.org/master/)
Usage:
```
import cv2
```

## 8. Installing fuzzywuzzy
[fuzzywuzzy](https://pypi.org/project/fuzzywuzzy/)

```
pip install fuzzywuzzy
```
Usage:

```
 from fuzzywuzzy import fuzz
 from fuzzywuzzy import process
 ```
