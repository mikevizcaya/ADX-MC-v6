# Trading Analitic — ADX MC

Analizador en Streamlit para señales JAPY2 con comparación entre ADX estándar y ADX-MC.

## Funciones principales

- Descarga de velas desde IQ Option.
- Línea de tiempo navegable con toda la historia solicitada.
- Vista inicial enfocada en las últimas 30 velas, con escala de precio ajustada al tramo visible.
- Navegación horizontal con el mouse y zoom con la rueda.
- Selección independiente de **ADX estándar** y **ADX-MC**.
- Si ambos están activos, aparecen en paneles separados para evitar mezclar las curvas.
- Selección de una vela para análisis visual.
- Selección múltiple de velas para generar un PDF por vela y descargarlos juntos en un ZIP.
- Vistas Todo / Antes / Inicio / Fin.
- PDF de tres páginas con ADX estándar y ADX-MC separados.

## Archivos del repositorio

- `app.py`
- `charts.py`
- `iqoption_service.py`
- `japy2.py`
- `pdf_report.py`
- `requirements.txt`
- `README.md`

## Ejecución

```bash
streamlit run app.py
```
