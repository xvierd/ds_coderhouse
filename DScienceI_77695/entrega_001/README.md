# Análisis de Publicidad en Redes Sociales

Este proyecto analiza datos de campañas publicitarias en redes sociales. Básicamente quería entender cómo se comporta la gente con los anuncios y qué campañas funcionan mejor.

## Para empezar

Necesitas tener conda instalado. Después creas el entorno:

```bash
conda env create -f environment.yml
conda activate datascience_proyecto
```

Para abrir el notebook:
```bash
jupyter lab
```

## Qué hay en el proyecto

```
primera entrega/
├── environment.yml                   # dependencias
├── ProyectoDSParteIGutierrez.ipynb  # notebook principal
├── storage/                         # datos CSV
│   ├── ad_events.csv
│   ├── ads.csv
│   ├── campaigns.csv
│   └── users.csv
└── README.md
```

## Lo que necesitas

- Python 3.11
- pandas, matplotlib, numpy
- jupyter

Los datos los bajé de [Kaggle](https://www.kaggle.com/datasets/alperenmyung/social-media-advertisement-performance) y me ayudó mucho el archivo SQLite que venía incluido para entender cómo se conectaban las tablas.