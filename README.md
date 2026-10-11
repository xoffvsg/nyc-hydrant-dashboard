# New York City Hydrant Density Dashboard

## Summary
Publish a public dashboard hosted on the `Streamlit Community Cloud`.
The dashboard can be seen at https://nyc-hydrant-dashboard-xoffvsg.streamlit.app/

## Method
A python file (`app.py`) and the underlaying data (`hydrant_density.parquet`) are stored in a public repo on Github. An App on streamlit.io (free if less than 1 GB memory per app) connects to the app.py file in the Github repo and publishes the dashboard with its own URL accessible to all.
<br><br>

## Local Alternative
If you just want to run the app on your machine:

```bash
cd <your folder containing app.py>
source .venv/bin/activate
streamlit run app.py
```

The app opens at http://localhost:8501. Press Ctrl+C to stop.