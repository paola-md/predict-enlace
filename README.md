# predict-enlace

A [Dash](https://dash.plotly.com/) dashboard for exploring and predicting results of
**ENLACE**, Mexico's national standardised test for primary schools.

Folium maps and heat layers over school-level results, with a table view and date
filtering, packaged to run in Docker.

Companion to [Tesis-Enlace](https://github.com/paola-md/Tesis-Enlace), my MSc thesis on
building a data product to help allocate social programmes to primary schools in Mexico.

```
app.py            Dash app and layout
enlaceInfo.py     data access and prediction helpers
mapas/            generated folium maps
data/             school-level ENLACE data
```
