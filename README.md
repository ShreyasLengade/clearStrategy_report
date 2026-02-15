<h1>⚽ Cristiano Ronaldo Statistics Analysis &amp; Power BI Dashboard</h1>

<h2>🧾 About the Project</h2>
<p>
  This project analyses Cristiano Ronaldo’s match and performance data using Python for data preparation and exploratory analysis,
  followed by interactive visualisation in Power BI.
</p>
<p>
  The workflow includes data cleaning, enrichment through API calls, feature preparation, and exporting structured datasets that are
  then used to build a dynamic dashboard for performance insights.
</p>
<p>
  The goal of the project is to transform raw match-level data into meaningful metrics that help understand scoring patterns, match impact,
  and overall performance trends over time.
</p>

<h2>👥 Who This Is Helpful For</h2>
<ul>
  <li><b>Sports analysts:</b> To study player performance trends and match impact</li>
  <li><b>Football fans and researchers:</b> To explore Ronaldo’s career statistics interactively</li>
  <li><b>Data analysts learning analytics workflows:</b> To see an end-to-end pipeline from Python to Power BI</li>
  <li><b>Scouting and performance teams:</b> To identify strengths, consistency, and performance patterns</li>
  <li><b>Students building portfolio projects:</b> Demonstrates data cleaning, API usage, and dashboarding</li>
</ul>

<h2>🎯 What Problem This Project Solves</h2>
<p>
  Sports data often exists in raw or fragmented formats, making it difficult to extract meaningful insights quickly.
  This project solves that by:
</p>
<ul>
  <li><b>Creating a structured dataset:</b> Cleans and prepares raw match data for analysis</li>
  <li><b>Enriching data with external sources:</b> Uses APIs to fill missing match or event information</li>
  <li><b>Enabling performance analysis:</b> Builds metrics such as goals, match impact, and trends</li>
  <li><b>Providing interactive visual exploration:</b> Power BI dashboard lets users slice performance by season, competition, and match context</li>
  <li><b>Demonstrating a real analytics pipeline:</b> Shows how Python processing integrates smoothly with BI tools</li>
</ul>

<h2>💡 Value Delivered</h2>
<ul>
  <li>Clear view of scoring and performance patterns</li>
  <li>Easy exploration of trends across seasons and competitions</li>
  <li>Reusable workflow (Python → Power BI)</li>
  <li>Portfolio-ready sports analytics project</li>
  <li>Better storytelling through interactive visuals</li>
</ul>

<h2>📊 Power BI Report Pages</h2>
<p>
  The report is built as a 3-page story: (1) quick player overview, (2) season-level trends, and (3) detailed shot map exploration.
  Each page answers a different set of questions and supports interactive filtering (season, location, distance, minutes, shot area, goal result).
</p>

<hr/>

<h2>🟦 Page 1: Player Overview (Ronaldo Summary)</h2>

<h3>✅ What this page shows (Visuals)</h3>
<ul>
  <li><b>KPI Cards:</b> Total Matches Played, Goal Contribution, Assist Count, Goal Count, Total Knockout Matches, Total Goals in Knockout</li>
  <li><b>Slicers:</b> Match Location (Home/Away), Game Season (dropdown)</li>
  <li><b>Radar Chart 1:</b> Goals by <b>Range of Shot</b> (e.g., &lt; 8 ft, 8–16 ft, 16–24 ft, 24+ ft)</li>
  <li><b>Radar Chart 2:</b> Goals by <b>Scored Goal Position</b> (e.g., Center, Left, Right, etc.)</li>
  <li><b>Player/Club panel:</b> Player name and club branding (for context)</li>
</ul>

<h3>❓ Key questions this page answers</h3>
<ul>
  <li>How many matches has Ronaldo played and what is his overall output (goals, assists, goal contributions)?</li>
  <li>How does performance differ between <b>Home vs Away</b> matches?</li>
  <li>From which <b>shot ranges</b> does he score most often?</li>
  <li>From which <b>field positions</b> do most goals come?</li>
  <li>How strong is his record in <b>knockout matches</b>?</li>
</ul>

<img width="2029" height="1258" alt="image" src="https://github.com/user-attachments/assets/ee09f6ac-6424-44a4-9591-05b6b4ebc619" />

<hr/>

<h2>🟦 Page 2: Season-wise Performance &amp; Shot Context</h2>

<h3>✅ What this page shows (Visuals)</h3>
<ul>
  <li><b>Combo chart:</b> Season-wise goals achievements
    <ul>
      <li><b>Bars:</b> Individual goals and Assisted goals (season by season)</li>
      <li><b>Line:</b> Shots attempted trend across seasons</li>
    </ul>
  </li>
  <li><b>Line chart:</b> Shot Distance Trends by Game Minute (distance in feet vs minutes left in game, split by seasons)</li>
  <li><b>Donut chart:</b> Goals per time and distance (goal vs no goal distribution)</li>
  <li><b>Slicers:</b> Match Location (Home/Away), Season, Distance in feet, Remaining Minutes</li>
</ul>

<h3>❓ Key questions this page answers</h3>
<ul>
  <li>How did Ronaldo’s <b>goals and assisted goals</b> change across seasons?</li>
  <li>Do <b>shots attempted</b> increase or decrease over time (and does that match goal output)?</li>
  <li>In which seasons was he most productive?</li>
  <li>How does <b>shot distance</b> vary with <b>game time</b> (remaining minutes)?</li>
  <li>What is the overall split of <b>goals vs no goals</b> for selected time/distance filters?</li>
  <li>Does Home vs Away change the season-level trend?</li>
</ul>

<img width="2032" height="1270" alt="image" src="https://github.com/user-attachments/assets/7714d1b2-0220-46fb-888f-f526f0ab3eee" />


<hr/>

<h2>🟦 Page 3: Shot Map &amp; Goal Outcome Exploration</h2>

<h3>✅ What this page shows (Visuals)</h3>
<ul>
  <li><b>Football pitch scatter plot:</b> Shot locations plotted on the pitch</li>
  <li><b>Colour/legend grouping:</b> Shot area categories (e.g., Right Side, Center, Mid Ground, Left Side, etc.)</li>
  <li><b>Filters:</b>
    <ul>
      <li><b>Area of Shot</b> (multi-select)</li>
      <li><b>Goal Result</b> (Is a goal / No goal)</li>
    </ul>
  </li>
  <li><b>Interactive exploration:</b> Users can isolate zones and compare goal vs no-goal patterns</li>
</ul>

<h3>❓ Key questions this page answers</h3>
<ul>
  <li>From which <b>exact pitch locations</b> does Ronaldo take most shots?</li>
  <li>Which <b>shot areas</b> convert better (goal vs no goal)?</li>
  <li>Are there “hot zones” where he scores more often?</li>
  <li>How do shot patterns change when filtering by a specific shot area (Right/Left/Center/Mid-ground)?</li>
  <li>What is the distribution of shots that did not result in goals (misses/blocked/saved) across the pitch?</li>
</ul>
<img width="2252" height="1261" alt="image" src="https://github.com/user-attachments/assets/b4935c93-8feb-403c-a211-475121841fff" />


<hr/>

<h2>🧠 How to Use the Report</h2>
<ul>
  <li>Start with <b>Page 1</b> for overall KPIs and quick patterns (range + position).</li>
  <li>Move to <b>Page 2</b> to understand season trends and how time/distance affect outcomes.</li>
  <li>Use <b>Page 3</b> to deep-dive into shot locations and conversion by zones.</li>
</ul>
