# Comparative Analysis of Mobile Crowdsensing and Ecological Momentary Assessment Systems
This repository supports the research paper *Comparative Analysis of Mobile Crowdsensing and Ecological Momentary Assessment Systems*. It contains datasets and their corresponding codebooks for two distinct data sources: **EMA** and **MCS**. For further details on the study and its findings, please refer to the metadata of this repository.

```
├── csv
│   ├── ema_data.csv
│   ├── ema_structure.csv
│   ├── mcs_data.csv
│   └── mcs_structure.csv
├── json
│   ├── ema_data.json
│   ├── ema_structure.json
│   ├── mcs_data.json
│   └── mcs_structure.json
└── README.md
```



## Repository Contents

- Contains the EMA and MCS datasets in CSV and JSON format.
- Contains a codebook describing the structure and columns of the EMA and MCS datasets in CSV and JSON format.



## Detailed Data Information
Detailed information about the content of both the EMA and MCS datasets can be found in the corresponding codebooks provided in the structure files (`*_structure.csv` and `*_structure.json`). These codebooks offer comprehensive descriptions of each dataset's fields and columns.



## Important Data Field Note
**All dataset columns and fields may contain the values `N/A` (indicating an unknown value or in database terms the value `NULL`).**  
This is a critical aspect for data processing and analysis. Take these special markers into account to avoid misinterpretations or inaccurate analyses.
