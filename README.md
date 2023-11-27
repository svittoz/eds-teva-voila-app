# EDS-TeVa Voila App

This repository contains an example of voila application that might be useful to AP-HP datascientists working on EDS data.

[Illuctration](docs/app-img.png)

__Source :__
REMAKI, Adam, PLAYE, Benoit, BERNARD, Paul Jules, et al. Adjusting for the progressive digitization of health records: working examples on a multi-hospital clinical data warehouse. medRxiv, 2023, p. 2023.08. 17.23294220.

## Requirements
EDS-TeVa stands on the shoulders of [Spark 2.4](https://spark.apache.org/docs/2.4.8/index.html) which requires:

- Python ~3.7.1
- Java 8

## Setting

You can install EDS-TeVa through ``pip``:

```
pip install -r requirements.txt
python -m voila .\prototypes\visits-app-details.ipynb
```

## Contributing

Contributions are welcome, and they are greatly appreciated! Every little bit helps, and credit will always be given.

## Acknowledgement

We would like to thank [Assistance Publique – Hôpitaux de Paris](https://www.aphp.fr/) and [AP-HP Foundation](https://fondationrechercheaphp.fr/) for funding this project.
