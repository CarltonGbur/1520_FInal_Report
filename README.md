# 1520_FInal_Report
Stacked bar chart showing goals scored by Ronaldo for each club, broken down by type (e.g., header, penalty, free kick).
Bars:
Each bar represents the total number of goals Ronaldo scored for a specific club.
The bar is stacked with color-coded segments, each representing a different goal type  (header, penalty, solo run, etc.).
X-Axis:
Displays the club names Ronaldo played for.
Y-Axis:
Indicates the number of goals scored, broken down by goal type.
Helps visualize not just quantity, but the diversity of scoring methods across clubs.
Color Legend (Right Panel):
Each color block corresponds to a goal type:

Goal matrix silhouette visualization showing each of Ronaldo’s goals mapped onto a human silhouette using colored tiles grouped by shot type.

Each square block represents a grouping of goals scored by Cristiano Ronaldo.
The silhouette is constructed using a grid of goal tiles arranged in the shape of his signature celebration pose.
Each block is color-coded by goal type
Goal types represented in the figure include Header, Direct Free Kick,  Left-footed,  Right-footed, Penalty, Tap-in,  Solo, Other
The figure highlights Ronaldo’s scoring methods, with a noticeable concentration of right-footed and header goals.
Interactive map pinpointing the European cities where Ronaldo has scored, with circle size reflecting goal volume by club.

Each circle represents a city where Ronaldo scored goals, corresponding to the club he played for at the time.
The size of each circle is scaled to reflect the total number of goals scored at that club.
The color of each marker identifies the club Ronaldo played for when scoring in that location.
Legend :
The legend lists each club along with the number of goals Ronaldo scored there:
Design Insight:
The map uses a dark theme and minimalist styling to highlight goal hotspots across Europe and the Middle East.
Madrid, Manchester, and Turin clearly stand out as Ronaldo’s most prolific cities, aligned with his longest tenures.
Data and Methods
Data:
 Goal data was sourced from two CSV files obtained from Kaggle.
 The first file (data.csv) included club affiliations, match metadata, and goal types such as header, penalty, and direct free kick.
The second file (location_goals.csv) provided exact shot coordinates and additional goal attributes, such as range and shot context.
I manually attached the club city locations based on the stadium.
Methods:
Used pandas for cleaning, filtering, and aggregating goal data by type and club.
Constructed a stacked bar chart in matplotlib to visualize goal type distribution per club.
Designed a goal matrix silhouette using a pixel-grid technique, mapping goals onto a human figure outline shaped like Ronaldo’s famous “Siiuu” celebration pose, with each block color-coded by shot type.
Created an interactive map using folium, with markers sized by goal count and colored by club. A custom HTML legend was added for clarity.
Significance Statement:
Cristiano Ronaldo is one of the most prolific goal scorers in football history. This project visually breaks down not just how many goals he scored, but how and where he scored them.
The silhouette matrix delivers a unique look at Ronaldo’s shooting versatility, offering fans and analysts a visual breakdown of headers, free kicks, penalties, and more. The silhouette itself is modeled after his famous goal celebration pose, adding an iconic and immediately recognizable shape to the visualization.
The stacked bar chart allows viewers to compare goal types across clubs, revealing how his role evolved over time, from Sporting CP to Real Madrid and Al-Nassr.
The interactive map adds geographic insight, showing Ronaldo’s scoring hotspots and helping fans connect his club success to global locations.
