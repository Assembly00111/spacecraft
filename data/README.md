# Dataset

The dataset was provided through the ME F321 course and is **not included** in this repository.

Place it here so that the folder looks like this:

```
data/
├── train/
│   ├── data/            Case001.csv … Case177.csv
│   └── labels.xlsx
└── test/
    ├── data/            Case178.csv … Case223.csv (46 cases)
    └── labels_spacecraft.xlsx
```

Each case CSV holds the pressure at sensors P1–P7, sampled at 1 kHz for 1200 ms.
The notebook reads the data from `DATA_DIR = 'data'`.
