---
name: AI Project
tools: [C++]
image: "/assets/projects/AIProject/AIProjectMain.png"
category: solo
---

{% capture carousel_images %}
/assets/projects/AIProject/Pathfinding.gif
/assets/projects/AIProject/TerrainAnalysis.gif
{% endcapture %}
{% include elements/carousel.html %}

<br/>

# AI Project

##### Language: C++

<br/>

##### Features:
- A* algorithm
  - Calculate heuristic using Euclidean, Octile, Chebyshev, and Manhattan methods
  - Rubberband final path
  - Smooth using a Catmull-Rom spline
- Hide and seek
  - Terrain Analysis
    - Openness the closest wall
    - Visibility
    - Search
  - Occupancy Map
    - Propagation + normalize occupancy