# EcoMonitor WQI

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<usuario>/<repo>/blob/main/notebooks/EcoMonitor_WQI.ipynb)

Cuaderno interactivo para evaluar la **calidad recreativa del agua** mediante un **índice híbrido** (subíndice físico‑químico ponderado + subíndice sanitario con **criterio de veto**), aplicado inicialmente al **río del Valle (Catamarca, Argentina)**.

> ⚠️ **Recordatorio**: actualizá `<usuario>/<repo>` en el botón de Colab cuando subas este repo a GitHub.

## Estructura
```
EcoMonitor-WQI/
├─ notebooks/
│  └─ EcoMonitor_WQI.ipynb
├─ templates/            # plantillas de umbrales / configuración (opcional)
├─ data/
│  └─ sample/            # datos de ejemplo/anónimos (opcional)
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
- Este repo **no** incluye datos reales por defecto. Podés colocar **datos anónimos o sintéticos** en `data/sample/` para demostrar la ejecución.
- Evitá subir información sensible. Para archivos grandes, usá Git LFS.

## Licencia
- **Código**: MIT (ver `LICENSE`).
- **Textos y figuras** del repositorio: CC‑BY‑4.0 (añadílo si corresponde).

## Cita
Ver `CITATION.cff` y el DOI de **Zenodo** una vez creada la release.
