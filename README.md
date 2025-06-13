# Dataset of Electrochemical Impedance Spectroscopy (EIS) vs. Temperature

Electrochemical Impedance Spectroscopy (EIS) is a powerful tool for examining the internal chemical and physical environment of electrochemical systems. In this study, we collected EIS data from lithium-ion batteries under varying conditions of temperature, state of charge, and state of health. The dataset includes over 200 EIS measurements, primarily from LiFePO4/Graphite 18650-type cells, with a smaller portion from LiCoO2 and NCM coin-type cells.

All data were collected under more than five different temperature conditions ranging from 25°C to 90°C. Our goal is to investigate the relationship between EIS and temperature, which could serve as a potential method for probing the internal temperature of batteries.

The structure of the dataset is as follows:

```python
data = {
    'soc': [],
    'soh': [],
    'info': {
        'cycle_temperature/C': [],
        'cycle_crate': [],
        'cycle_number': [],
        'cell_type': [],
        'cell_serial': [] 
    },
    'eis': {
        'temperature/C': [],
        'frequency/Hz': [],
        'real/ohm': [],
        '-imag/ohm': [],
        'magnitude/ohm': [],
        '-phase/degree': [],
        'time/s': []
    }
}
```

And the example can be found in the notebook.

# Distribution and Release Information

The BIT-EIS dataset is freely available under the MIT license from this site.

# System requirements

This dataset is created by Python, to use this dataset properly, you need packages numpy, pickle.

# How to cite this work?

# How to get support?

Just write to lzkjack@qq.com
