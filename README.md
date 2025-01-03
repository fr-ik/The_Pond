====================================
           THE POND - README
====================================

https://fr-ik.github.io/The_Pond/

Abstract
--------
Mining pools, algae and floods, from the artificial broth a digital life is born.
Aerial perspective isn’t tactical, invaders are no longer the enemy, guns do not kill anymore.

Overview
--------
The Pond is a digital art project that combines the mechanics of Conway’s Game of Life 
with a Space Invader-inspired aesthetic. It dynamically integrates environmental imagery 
and tailored "Gun" patterns to create a living, evolving canvas. 

This project explores the intersection of nature, artificial intelligence, and digital life, 
blending algorithmic art with themes of environmental change.

Features
--------
- Dynamic Style Sets:
  * Nine unique styles with:
    - Background images inspired by environmental themes.
    - Invader sprites with thematic variations.
    - Cell colors for life and death states.
    - Unique Gosper Gun-style patterns.

- Randomized Reloads:
  * Every reload applies a random style set for a fresh visual experience.

- Custom Patterns:
  * Predefined patterns such as Bi Gun, Period 156 Gun, Simkin Glider Gun, and more.

How It Works
------------
1. **Canvas Rendering**:
   The project uses an HTML5 <canvas> element to display the evolving grid.

2. **Background and Sprite Integration**:
   Background images align with high-quality visuals, overlaid with invader sprites.

3. **Algorithmic Evolution**:
   Patterns evolve based on Conway's Game of Life rules, forming dynamic shapes.

Style Set Details
-----------------
Each style set includes:
- `backgroundImage`: A unique environmental or geological theme.
- `invaderImage1` and `invaderImage2`: Invader sprite variations.
- `liveCellColor` and `deadCellColor`: Colors for active and inactive cells.
- `gunPattern`: Specific configurations for Conway's Game of Life guns.

Themes include:
1. **Deforestation**
   - Background: bg1.png Deforestation at NovoProgreso, Parà state, Brazilian Amazon - Coordenecao-Geral de Obsevacao da Terra, INPE 
   - Colors: Black and vibrant green hues
   - Pattern: Gosper Glider Gun

2. **Lithium Mine**
   - Background: bg2.png Lithium Mine at Bolivia's Uyuni Salt Flat - Coordenecao-Geral de Obsevacao da Terra, INPE
   - Colors: Black and light blue hues
   - Pattern: Bi Gun

3. **Floodway**
   - Background: bg3.png Morganza Floodway after five days of flow - NASA Goddard Space Flight Center (modified)
   - Colors: Black and aquatic tones
   - Pattern: Simkin Glider Gun

4. **Lava Flows**
   - Background: bg4.png Roiling Flows on Holuhran Lava Field - NASA Goddard Space Flight Center
   - Colors: Black, aquatic tones and red
   - Pattern: Period 156 Gun

5. **Cultivation circles**
   - Background: bg5.png Cultivating Egypt's Desert - NASA Goddard Space Flight Center
   - Colors: Black and aquatic tones
   - Pattern: AK 94

6. **Dune Agriculture**
   - Background: bg6.png Lop Nur, Xinjiang, China - NASA Goddard Space Flight Center (modified)
   - Colors: Black, sand and green
   - Pattern: Simkin Glider Gun

7. **Flood**
   - Background: bg7.png Large flood in Russia - Coordenecao-Geral de Obsevacao da Terra, INPE
   - Colors: Black and red neon tones
   - Pattern: P58 Pi-heptomino Hassler

8. **Blooms of algae**
   - Background: bg8.png Blooms in the Sea of Marmara - NASA Goddard Space Flight Center
   - Colors: Black and dark aquatic tones
   - Pattern: B-52 Bomber

9. **River Delta**
   - Background: bg9.png Lena Delta - NASA Goddard Space Flight Center
   - Colors: Black and red and blue neon tones
   - Pattern: P24 Gliderless LWSS Gun

Usage Instructions
------------------
1. Open the `index.html` file in a modern browser.
2. Refresh the page to explore different styles and patterns.

Dependencies
------------
- A browser supporting HTML5 Canvas (e.g., Chrome, Firefox).
- Ensure all assets (`bg#.png`, `invader#.png`, etc.) are in the same directory.

Additional Notes
----------------
- **Credits**:
  Inspired by environmental change, with images sourced from NASA and INPE archives.
  
- **Creative Message**:
  Includes unique ASCII art in the CSS, a nod to the project’s artistic roots.

- **Customization**:
  To add or modify style sets, edit the `styleSets` array in the JavaScript section.

Authors
-------
This project is created by **fric and lunasquare**. Contributions and adaptations for 
educational and artistic purposes are welcome.

====================================
           END OF README
====================================

 
 
