
# Neuro Niche — Streamlit Lesson (Fundamentals)

A 5‑slide interactive lesson for educators with scoring, branded certificate (drawn with Pillow), and CSV logging.

## Run locally
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Deploy on Streamlit Community Cloud
1. Push this folder to a public GitHub repo.
2. In Streamlit Cloud, set **Main file path** to `app.py`.
3. Deploy. Certificates are saved to `data/certificates/` and downloads use in‑memory bytes (no file‑path errors).

## Files
- `app.py` — Streamlit app
- `.streamlit/config.toml` — theme in Neuro Niche colors
- `requirements.txt` — dependencies
- `data/` — will hold `completions.csv` and generated certificate PNGs
