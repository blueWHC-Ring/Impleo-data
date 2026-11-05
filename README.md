# Impleo Data

Data companion repository for [Impleo](https://github.com/blueWHC-Ring/Impleo).

## Contents

```text
example/
└── starmap_p128_v0/
    ├── input_panel.npy
    ├── truth.npy
    ├── protocol.json
    └── hidden_genes.json

training/
└── observations/
    └── <dataset>/full_obs.csv.gz
```

The complete expression matrices and preprocessing files are available in the [v1.0.0 data release](https://github.com/blueWHC-Ring/Impleo-data/releases/tag/v1.0.0).

## Download

From a local Impleo checkout, run:

```bash
python -m data.download --packs example training
```

The repository and release assets contain only the data required by the Impleo workflow.
