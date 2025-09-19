<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <meta name="description" content="Netflix catalog analysis with Python & Jupyter: genres, countries, yearly trends, top directors/actors, and many exploratory queries." />
  <title>Netflix Data Analysis Project</title>
  <style>
    body { font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial; line-height:1.6; color:#222; padding:28px; max-width:900px; margin:auto; }
    h1 { color:#0b5ed7; margin-bottom:4px; }
    h2 { color:#0b5ed7; margin-top:24px; }
    p.lead { margin-top:0; color:#333; }
    ul { margin:8px 0 16px 20px; }
    code { background:#f6f8fa; padding:2px 6px; border-radius:6px; font-family:SFMono-Regular,Menlo,Monaco,Consolas,"Liberation Mono","Courier New",monospace; }
    .box { background:#fbfbfd; border:1px solid #e6e9ef; padding:14px; border-radius:8px; }
    .small { color:#666; font-size:0.95em; }
    .note { background:#fff7e6; border-left:4px solid #ffd580; padding:10px 12px; margin:16px 0; border-radius:4px; }
  </style>
</head>
<body>
  <h1>🎥 Netflix Data Analysis Project</h1>
  <p class="lead">Exploratory data analysis of Netflix's content library using Python and Jupyter Notebook. Visualizations and queries reveal trends in genres, countries, release years, and top contributors.</p>

  <div class="box">
    <strong>Description</strong>
    <p class="small">Analyze Netflix's catalog using Python (Jupyter) to uncover insights on movies & TV shows: genres, countries, release trends, top directors/actors, and keyword-based searches.</p>
  </div>

  <h2>📁 Dataset Overview</h2>
  <ul>
    <li><strong>Show ID</strong> — Unique identifier</li>
    <li><strong>Title</strong> — Name of movie or TV show</li>
    <li><strong>Type</strong> — Movie or TV Show</li>
    <li><strong>Director, Cast</strong> — Contributors</li>
    <li><strong>Country</strong> — Production country</li>
    <li><strong>Date Added, Release Year</strong></li>
    <li><strong>Rating</strong>, <strong>Duration</strong>, <strong>Listed In (Genres)</strong></li>
  </ul>

  <h2>🔍 Queries & Analysis Covered</h2>
  <p class="small">(All queries implemented in the Jupyter notebook)</p>
  <ul>
    <li><strong>Total Movies vs TV Shows</strong> — counts and comparison.</li>
    <li><strong>Top Countries by Content</strong> — which countries contribute most titles.</li>
    <li><strong>Yearly Content Additions</strong> — titles added per year.</li>
    <li><strong>Most Common Genres</strong> — genre frequency distribution.</li>
    <li><strong>Ratings Breakdown</strong> — distribution of content ratings (TV-MA, PG-13, etc.).</li>
    <li><strong>Top Directors & Actors</strong> — most frequent contributors.</li>
    <li><strong>Oldest & Most Recent Titles</strong> — by release and added dates.</li>
    <li><strong>Top 10 Countries (Movies vs Shows)</strong> — regional comparisons.</li>
    <li><strong>Longest Duration Movie</strong> — max runtime.</li>
    <li><strong>Movies/Shows Released Per Year</strong> — production trends.</li>
    <li><strong>Most Common Ratings by Content Type</strong> — ratings split for movies vs shows.</li>
    <li><strong>Count of Titles Per Country</strong> — global content distribution.</li>
    <li><strong>Most Popular Genre by Year</strong> — genre trends across years.</li>
    <li><strong>Keyword Search Examples</strong> — search titles by keywords (e.g., "Love", "War").</li>
    <li><strong>Top-N Queries</strong> — top 5 / top 10 lists for many metrics (countries, directors, actors, genres).</li>
  </ul>

  <h2>🛠 Tools & Libraries</h2>
  <ul>
    <li>Python (Pandas, NumPy)</li>
    <li>Jupyter Notebook</li>
    <li>Matplotlib & Seaborn for visualizations</li>
    <li>CSV / Excel dataset as the data source</li>
  </ul>

  <h2>🚀 How to Run</h2>
  <ol>
    <li>Clone or download the repo: <code>git clone https://github.com/your-username/Netflix-Data-Analysis.git</code></li>
    <li>Open <code>Netflix_Data_Analyst.ipynb</code> in Jupyter Notebook or VS Code.</li>
    <li>Install dependencies: <code>pip install pandas numpy matplotlib seaborn</code></li>
    <li>Run cells to reproduce analysis and visualizations.</li>
  </ol>

  <div class="note">
    <strong>Tip:</strong> For GitHub front-page rendering, add a short <code>README.md</code> (Markdown) — GitHub displays that by default. Keep this HTML as <code>README.html</code> for a richer file view.
  </div>

  <h2>📊 Sample Insights</h2>
  <ul>
    <li>US and India typically have the largest number of titles.</li>
    <li>TV shows have grown faster than movies in recent years.</li>
    <li>Ratings such as <code>TV-MA</code> and <code>TV-14</code> are common across the catalog.</li>
  </ul>

  <h2>📜 License</h2>
  <p>MIT License — see <code>LICENSE</code> in the repository.</p>

  <hr />
  <p class="small">Created with ❤️ — run the notebook to explore queries, tweak visualizations, and extend analyses.</p>
</body>
</html>
