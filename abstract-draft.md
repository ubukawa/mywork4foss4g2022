Vector tile has been one of the key topics in the web mapping. Thanks to the pioneers who have contributed a lot to open source development in the filed of vector tile, we can now develop our geospatial information service with open source vector tile technique. 
UN Vector Tile Toolkit, or UNVT, was established in 2018 under the UN Open GIS Initiative, and has provided various tools to facilitate the production and use of vector tiles. UNVT grows with the global partnership among United Nations and various contributors, and now we have various experience in (1) producing, (2) styling, (3) hosting, (4) optimizing, and (5) consuming vector tiles.

In out talk, through introducing our experiences and lessons from selected projects, we will share how we can create vector tiles and their map application using open-source tools including UNVT. 
Our work experiences covers the followings.

- Production
    - Global development and regular update (UNGSC) of the vector tiles from UN internal data and OSM
    - simple data production using ruby or nodejs scripts in other projects
- Styling
    - Development of UNVT/charites
    - Techniques to editing external styles (esri, etc) 
- Hosting
    - Development of UNVT/marble, an interface for Esri's Geoportal
    - Raspberry pi server
- Application
    - storytelling
    - 3D expression (boxed-cell) (terrain could be introduced, but we need to make a balance with FOSS4G.)
    - overlay with satellite? (tbd)
    - Data consumption in ArcGIS platform
- Others
    - equinox - use of UNVT in raspberry pi 
    - unvt/nanban - use of UNVT in Docker for windows user
    - UNVT in WSL (if possible)
    - Other updates of UNVT application (UNVT deplyment in UNGSC, GSI vector tile development, UNVT Portable)

Resources
- UNVT Story telling workshop
    - Slide https://speakerdeck.com/hfu/unvt-storytelling 
    - Recording https://www.youtube.com/watch?v=CVajhAUDLMs
- UNVT styleing tool - Charites
    - URL https://github.com/unvt/charites
    - An example of usecase - charites use for editing esri based style https://qiita.com/T-ubu/items/6e31a6bc5a458b91d4cd


