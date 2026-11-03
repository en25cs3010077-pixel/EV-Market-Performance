# EV Market Performance Website

A Flask website that presents the EV Market Performance project and embeds its own Tableau Public dashboard and story.

## Project structure

```text
EV_Market_Performance_Website/
├── app.py
├── requirements.txt
├── Procfile
├── README.md
├── .gitignore
├── templates/
│   └── index.html
└── static/
    └── style.css
```

## Run locally

1. Create and activate a virtual environment.
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Start the Flask app:

   ```bash
   python app.py
   ```

4. Open http://127.0.0.1:5000

## Deploy on Render

- Build command: `pip install -r requirements.txt`
- Start command: `gunicorn app:app`

## Tableau embeds

The website currently embeds the project's existing Tableau Public visualizations:
- Dashboard: `Dashboard1_17934688053880/Dashboard1`
- Story: `EVMARKET-STORY_17934681361330/Story1`

The website uses Tableau Public iframes. The visualizations must remain published and publicly accessible for the embeds to load.

## Update Tableau links

When replacing a visualization, update both:
- The iframe `src` URL
- The corresponding “Open Full Dashboard/Story” link

in `templates/index.html`.
