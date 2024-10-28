---
layout: detail
fullpreview: true
order-of-appearance: 3
draft: false

name: rhino
title: ArcGIS CityEngine for Rhino - Plugin for Rhino and Grasshopper
platform: Rhino
logo: puma.png
github: https://github.com/esri/cityengine_for_rhino

teaser-image: puma_street_segment_overview_1920x1080.jpg

hero-title: ArcGIS CityEngine for Rhino
hero-subtitle: CityEngine Plugin for Rhino and Grasshopper
hero-content:
  - type: video
    name: JHMathmLBY8

description: ArcGIS CityEngine for Rhino is a plugin for Rhino and Grasshopper. It provides a Rhino command and Grasshopper components which enable the execution of CityEngine rules within a Rhino scene.

gallery:
- image: puma_street_segment_street_level_1920x1080.jpg
- image: puma_street_segment_overview_1920x1080.jpg

introduction: ArcGIS CityEngine for Rhino (formerly known as "Puma") is a plugin for <a href="https://www.rhino3d.com">Rhino and Grasshopper</a>. It provides a Rhino command and Grasshopper components which enable the execution of <a href="https://www.esri.com/software/cityengine">CityEngine</a> rules within a Rhino scene. Therefore, a Rhino artist or designer does not have to leave their familiar Rhino environment anymore to make use of CityEngine’s procedural modeling power. Complicated export-import steps are no longer needed, which also means that the procedural models do not need to be “baked” anymore. The building or street models stay procedural during the entire design or planning workflow. Consequently, the user can change any attributes of the building or street models easily by connecting them to other Grasshopper components.<br/><br/>CityEngine for Rhino requires Rule Packages (RPK) as input, which are authored in CityEngine. An RPK includes assets and a CGA rule file which encodes an architectural style. Comprehensive RPK examples are available below and can be used “out-of-the-box”. More examples for CGA rule files can additionally be found in the <a href="https://doc.arcgis.com/en/cityengine/latest/tutorials/introduction-to-the-cityengine-tutorials.htm" target="_blank">CityEngine tutorials</a>.<br/><br/>CityEngine for Rhino is well suited for managing the procedural generation of architectural 3D content in design and urban planning scenarios. However, CityEngine for Rhino is restricted to the procedural generation of buildings and street detailing/furniture. CityEngine for Rhino does not include the city layout and street network editing tools of CityEngine itself (i.e. the rich CityEngine toolset to design a city from scratch or based on geographic data is still needed).<br/><br/><strong><i>ArcGIS CityEngine for Rhino is free for personal, educational, and non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. Redistribution or web service offerings are not allowed unless expressly permitted. Please refer to the licensing section below for more detailed licensing information.</strong></i>

ressource-1-title: Downloads
ressource-1-text: Search for ArcGIS CityEngine for Rhino in the built-in <strong>Package Manager of Rhino</strong> (recommended) or manually download from the Food4Rhino app store.
ressource-1-link-text: → Go to the Food4Rhino app store
ressource-1-link-url: https://www.food4rhino.com/en/app/arcgis-cityengine-rhino-and-grasshopper

ressource-2-title: Documentation
ressource-2-text: A full documentation of ArcGIS CityEngine for Rhino is available on our github repository.
ressource-2-link-text: → Read documentation
ressource-2-link-url: https://github.com/esri/cityengine_for_rhino/blob/master/README.md

ressource-3-title: Github
ressource-3-text: For more information, assets and resources check our Github repository.
ressource-3-link-text: → Go to Github
ressource-3-link-url: https://github.com/esri/cityengine_for_rhino

examples:

  - title: Street Segment
    text: This example demonstrates the main features of ArcGIS CityEngine for Rhino in a compact scene. Starting from various input shapes (street shapes and building/floor footprints), multiple different Rule Packages are applied to create models ranging from abstract building volumes to realistic facades and street-level scenes. Extract the contents of all 5 zips into a <strong>single directory</strong> then open the Rhino and Grasshopper files and CityEngine for Rhino will find the RPKs automatically.

    files:
      - title: Street Segment Example Part 1 (Rhino Scene files)
        link: https://github.com/Esri/cityengine_for_rhino/releases/download/v1.0.0/Puma_Street_Segment_Example_Part_1_Rhino.Files.zip
      - title: Street Segment Example Part 2 (Building Construction RPKs)
        link: https://github.com/Esri/cityengine_for_rhino/releases/download/v1.0.0/Puma_Street_Segment_Example_Part_2_Building_Construction_RPKs.zip
      - title: Street Segment Example Part 3 (Complete Streets RPKs)
        link: https://github.com/Esri/cityengine_for_rhino/releases/download/v1.0.0/Puma_Street_Segment_Example_Part_3_Complete_Street_RPKs.zip
      - title: Street Segment Example Part 4 (Generic Modern Building RPKs)
        link: https://github.com/Esri/cityengine_for_rhino/releases/download/v1.0.0/Puma_Street_Segment_Example_Part_4_Generic_Modern_Building_RPKs.zip
      - title: Street Segment Example Part 5 (Floor RPKs)
        link: https://github.com/Esri/cityengine_for_rhino/releases/download/v1.0.0/Puma_Street_Segment_Example_Part_5_Floor_RPKs.zip

    images:
      - image-name: puma_street_segment_overview_1920x1080.jpg

legal: <ul><li>ArcGIS CityEngine for Rhino is free for personal, educational, and non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. Redistribution or web service offerings are not allowed unless expressly permitted.</li><li>ArcGIS CityEngine for Rhino is under the same license as the included <a href="./cityenginesdk#legal-section">CityEngine SDK</a>.</li><li>All content in the "Examples" directory/section is licensed under the APACHE 2.0 license. You may obtain a copy of this license at <a href="https://www.apache.org/licenses/LICENSE-2.0" target="_blank">https://www.apache.org/licenses/LICENSE-2.0</a>.</li><li>For questions or enquiries, please contact <a href= "mailto:cityengine-info@esri.com">cityengine-info@esri.com</a></li></ul>

---
