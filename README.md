# EcoMonitor WQI

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AugustoBellanich/EcoMonitor-WQI/blob/main/notebooks/EcoMonitor_WQI.ipynb)

Cuaderno interactivo para evaluar la **calidad recreativa del agua** mediante un **índice híbrido** (subíndice físico‑químico ponderado + subíndice sanitario con **criterio de veto**), aplicado inicialmente al **río del Valle (Catamarca, Argentina)**.

## Estructura
```
EcoMonitor-WQI/
├─ notebooks/
│  └─ EcoMonitor_WQI.ipynb
├─ templates/            # plantillas de umbrales / configuración 
├─ data/
│  └─ sample/            # datos de ejemplo
├─ assets/               # logos e imágenes opcionales
├─ CITATION.cff
├─ LICENSE
├─ README.md
├─ requirements.txt
└─ zenodo.json
```

## Cómo ejecutarlo
### En Google Colab (recomendado)
1. Hacé clic en el **botón “Open in Colab”** arriba.  
2. En la **Sección 1** del notebook, seguí las instrucciones para **cargar datos** y/o **plantillas** (puede generar plantillas automáticamente).
3. Ejecutá las celdas secuencialmente.

### Local (Jupyter)
```bash
python -m venv .venv && source .venv/bin/activate  # (Windows: .venv\Scripts\activate)
pip install -r requirements.txt
jupyter notebook notebooks/EcoMonitor_WQI.ipynb
```

## Datos
- Este repo por el momento **no** incluye datos reales por defecto. 

## Licencia
- **Código**: MIT (ver `LICENSE`).
- **Textos y figuras** del repositorio: CC‑BY‑4.0.

## Cita
Ver `CITATION.cff` y el DOI de **Zenodo** una vez creada la release.
