# Life Expectancy in North America (1960–2022)

**Interactive data visualization built with Flask, JSON, and SVG**  
Tracks and compares life expectancy trends in **Canada**, **Mexico**, and the **United States** over six decades using official World Bank data.

---

## Highlights & Skills Used
- **Full-Stack Development** — Flask backend with SVG/CSS frontend visualizations.  
- **Data Storytelling** — Converted raw data into clear, comparative insights.  
- **Performance** — Minimal dependencies for fast, reliable deployment.  
- **Professional Presentation** — Polished, portfolio-ready design with interactivity.
- **Skills Used** - Flask, Python, HTML5, CSS3, SVG, Jinja2, JSON, Data Visualization, RESTful Principles, Git 

---

## Website Features
- **Multi-Country Line Graph** — Visualize trends from 1960–2022
- **Interactive Year Selector** — Pick a year to see map-based life expectancy comparisons
- **SVG-Driven Visuals** — Crisp, scalable charts and maps
- **Simple, Readable Codebase** — Easy to maintain and extend

---

## Project Structure
```plaintext
├── server.py               # Flask backend: routes, data loading, template rendering
├── styles.css              # Styling for graphs, maps, and layout
├── life_expectancy.json    # Historical data (1960–2022)
├── templates/
│   ├── index.html          # Homepage with trend graph + year selector
│   ├── year.html           # Year-specific map visualization
│   ├── line_graph.svg      # Line chart visualization
│   └── north_america.svg   # Map of North America
