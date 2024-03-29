---
layout: detail
fullpreview: true
order-of-appearance: 2
draft: false

name: Serlio
title: Serlio - Plugin for Maya
platform: Maya
logo: serlio.png
github: https://github.com/esri/serlio

teaser-image: serlio_ex_2_2.jpg

hero-title: Serlio
hero-subtitle: CityEngine Plugin for Autodesk Maya
hero-content:
  - type: video
    name: 1rFuGmc-Jac

description: Serlio is a plugin for Autodesk Maya. It provides a modifier node which enables the execution of CityEngine CGA rules within a Maya scene. This allows the 3D environment artist to make use of the power of procedural modeling in CityEngine without have to leave the familiar Maya toolset.

gallery:
  - image: serlio_ex_2_1.png
  - image: serlio_ex_1_1.png

introduction: With Serlio, complicated export-import pipelines are no longer needed, which also means that the procedural building models do not need to be “baked” in future. The buildings stay procedural during the entire modeling workflow. Consequently, the 3D environment artist can change many attributes, for example the height, style and appearance of buildings easily with a parametric interface at any point during production.<br/><br/>Serlio requires Rule Packages (RPK) as input, which are authored in CityEngine. An RPK includes assets and a CGA rule file which encodes an architectural style. Comprehensive RPK examples are available below and can be used “out-of-the-box” in Serlio.<br/><br/>Serlio is well suited for managing the procedural generation of architectural 3D content in digital sets. However, Serlio is restricted to the procedural generation of singular objects - particularly buildings. Serlio does not include the city layout and street network editing tools of CityEngine (i.e. the rich CityEngine toolset to design a city from scratch, or based on geographic data, is still needed).<br/><br/><strong><i>Serlio is free for personal, educational, and non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. Redistribution or web service offerings are not allowed unless expressly permitted. Please refer to the licensing section below for more detailed licensing information.</strong></i>

ressource-1-title: Downloads
ressource-1-text: Download the latest version of Serlio here.
ressource-1-link-text: → Go to downloads
ressource-1-link-url: https://github.com/esri/serlio/releases

ressource-2-title: Documentation
ressource-2-text: A full documentation of Serlio is available on our Github repository.
ressource-2-link-text: → Read documentation
ressource-2-link-url: https://github.com/esri/serlio/blob/main/README.md#documentation

ressource-3-title: Github
ressource-3-text: For more information, assets and resources check our Github repository.
ressource-3-link-text: → Go to Github
ressource-3-link-url: https://github.com/esri/serlio/

examples:

  - title: Street Segment Maya Project
    text: The Street Segment example demonstrates the main features of Serlio in a compact scene. Starting from various input shapes (street shapes and building/floor footprints), multiple different Rule Packages are applied to create models ranging from abstract building volumes to realistic facades and street-level scenes.</br></br><strong>Instructions:</strong><ol><li>Extract the contents of all 3 zips into a <strong>single directory</strong>.</li><li>Open Maya and set this directory (containing the <em>workspace.mel</em> file) as the current project (File > Set Project).</li><li>Open one of the four Maya scenes.</li></ol></br></br><strong>Notes:</strong><ul><li>Requires Maya 2020, 2022 or 2023. </li><li>v1 released on 2022-06-20 for Serlio v2.0.0</li></ul>

    files:
    - title: Street Segment Example Part 1 (Maya Scene files)
      link: https://github.com/esri/serlio/releases/download/v2.0.0/street_segment_part1_maya_project_files_v1.zip
    - title: Street Segment Example Part 2 (RPKs)
      link: https://github.com/esri/serlio/releases/download/v2.0.0/street_segment_part2_maya_assets_v1.zip
    - title: Street Segment Example Part 3 (RPKs)
      link: https://github.com/esri/serlio/releases/download/v2.0.0/street_segment_part3_maya_assets_v1.zip

    images:
      - image-name: serlio_ex_2_1.png



  - title: Favela Maya Project
    text: The Favela example demonstrates how a complex CityEngine Rule Package (RPK) is applied on one or more polygons. The provided Maya project includes an Alembic file with shapes from CityEngine, the Favela RPK itself and Maya scenes.</br></br><strong>Instructions:</strong> <ol><li>Extract the contents of the zip. </li><li>Open Maya and set the directory with the <em>workspace.mel</em> file as the current project (File > Set Project). </li><li>Open one of the three Maya scenes. </li></ol></br></br><strong>Notes:</strong><ul><li>Requires Maya 2020, 2022 or 2023. </li><li>Based on the <a href="https://www.youtube.com/watch?v=IY5gU1J39Ec" target="_blank">original "Favela" project (YouTube)</a> created with CityEngine, Maya and Maxwell created by Matthias Bühler and Cyrill Oberhänsli. </li><li>v3 released on 2022-06-20 for Serlio v2.0.0</li></ul>

    files:
    - title: Favela Maya Project
      link: https://github.com/esri/serlio/releases/download/v2.0.0/favela_maya_project_v3.zip

    images:
      - image-name: serlio_ex_1_1.png


legal: <ul><li>Serlio is free for personal, educational, and non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. Redistribution or web service offerings are not allowed unless expressly permitted.</li><li>Serlio is under the same license as the included <a href="./cityenginesdk#legal-section">CityEngine SDK</a>.</li><li>All content in the "Examples" directory/section is licensed under the APACHE 2.0 license. You may obtain a copy of this license at <a href="https://www.apache.org/licenses/LICENSE-2.0" target="_blank">https://www.apache.org/licenses/LICENSE-2.0</a>.</li><li>The “Favela” example data is copyrighted by <a href="https://www.vrbn.io/" target="_blank">vrbn</a> studios. Please contact ​info@vrbn.io for commercial licensing options.</li><li>For questions or enquiries, please contact <a href= "mailto:cityengine-info@esri.comm">cityengine-info@esri.com</a></li></ul>

---
