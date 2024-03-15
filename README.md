# Dot Counter

This program is used to count dots on images.
Uses HughesCircles dot counting algorithm from Open CV.

```
.
├── circount.py #  main program to execute
├── images
│   └── dots.jpg # sample input image
├── README.md    # this file.
└── requirements.txt # packages needed to install
```

## Installation

Requires Python 3.11 or later to run.

```
python -m pip install -r requirements.txt
```

## Sample Usage

```sh
python circcount.py images/dots.jpg
```

```sh
python circcount.py images/dots.jpg --show # shows matplotlib display to screen
```

