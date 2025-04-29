---
layout: detail
fullpreview: true
order-of-appearance: 1
draft: false

name: houdini
title: ArcGIS CityEngine for Houdini - Plugin for Houdini
platform: Houdini
logo: palladio.png
github: https://github.com/Esri/cityengine_for_houdini

teaser-image: palladio_teaser_image.png

hero-title: ArcGIS CityEngine for Houdini
hero-subtitle: CityEngine Plugin for SideFX Houdini
hero-content:
  - type: image
    name: palladio_teaser_image.png

description: ArcGIS CityEngine for Houdini is a plugin for SideFX Houdini. It provides "surface operator" nodes which enable the execution of CityEngine CGA rules within Houdini networks. Therefore, 3D environment artists do not have to leave their familiar Houdini toolset anymore to make use of the procedural modeling power of CityEngine.

gallery:
- image: palladio_ex_1_2.jpg
- image: palladio_ex_2_2.png
- image: palladio_ex_1_3.jpg

introduction: With ArcGIS CityEngine for Houdini (formerly known as "Palladio"), complicated export-import pipelines are no longer needed to get CityEngine models into Houdini. This also means that the procedural building models do not need to be “baked” anymore. The buildings stay procedural during the entire modeling workflow (optionally even at render time). Consequently, the 3D environment artist can change the height, style and appearance of buildings easily with a parametric interface at any point during production.<br/><br/>CityEngine for Houdini requires Rule Packages (RPK) as input, which are authored in CityEngine. An RPK includes assets and a CGA rule file which encodes an architectural style. Comprehensive RPK examples are available below and can be used “out-of-the-box” in CityEngine for Houdini. More examples for CGA rule files can additionally be found in the <a href="https://doc.arcgis.com/en/cityengine/latest/tutorials/introduction-to-the-cityengine-tutorials.htm" target="_blank">CityEngine tutorials</a>.<br/><br/>CityEngine for Houdini is well suited for managing the procedural generation of architectural 3D content in digital sets. However, CityEngine for Houdini is restricted to the procedural generation of single buildings/objects. CityEngine for Houdini does not include the city layout and street network editing tools of CityEngine (i.e. the rich CityEngine toolset to design a city from scratch, or based on geographic data, is still needed).<br/><br/><strong><i>ArcGIS CityEngine for Houdini is free for personal, educational, and non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. Redistribution or web service offerings are not allowed unless expressly permitted. Please refer to the licensing section below for more detailed licensing information.</strong></i>

ressource-1-title: Downloads
ressource-1-text: Download the latest version of ArcGIS CityEngine for Houdini here.
ressource-1-link-text: → Go to downloads
ressource-1-link-url: https://github.com/esri/cityengine_for_houdini/releases

ressource-2-title: Documentation
ressource-2-text: A full documentation of CityEngine for Houdini is available on our github repository.
ressource-2-link-text: → Read documentation
ressource-2-link-url: https://github.com/Esri/cityengine_for_houdini/blob/master/README.md#documentation

ressource-3-title: Github
ressource-3-text: For more information, assets and resources check our Github repository.
ressource-3-link-text: → Go to Github
ressource-3-link-url: https://github.com/esri/cityengine_for_houdini/



examples:

  - title: Angkor Thom
    text: This example includes full CityEngine and Houdini projects. It demonstrates how to use CityEngine to author procedural assets like Walls, Stairs, Porticos and combine them in Houdini via CityEngine for Houdini and Rule Packages.</br>Notes:</br></br><ul><li>Created by Matthias Buehler</li><li>Also covered in "Digital Production" Issue 05/18 (Article in German).</li></ul></br></br>Downloads&colon;

    files:
      - title: Houdini and CityEngine projects (CityEngine for Houdini 2.0)
        link: https://github.com/Esri/cityengine_for_houdini/releases/download/v2.0.0-beta.1/Palladio_Example_Angkor_Thom_v3.zip
      - title: Instructions
        link: ./assets/files/palladio_angkor_thom_instructions.txt

    images:
      - image-name: palladio_ex_1_4.png


  - title: Favela
    text: The Favela example demonstrates the packaging of a complex Rule Package into a Houdini Digital Asset with custom high-level parameters. The provided Houdini scene additionally shows how to prepare the input geometry for CityEngine for Houdini out of an Alembic archive (setup of random seed and start rule).</br></br>Notes:</br><ul><li>Requires Houdini 17.5 and CityEngine for Houdini 1.6.1 or later.</li><li>Based on the original "Favela" project (YouTube) created with CityEngine, Maya and Maxwell.</li><li>Created by Matthias Buehler</li></ul></br></br>Downloads&colon;

    files:
      - title: Houdini Project (CityEngine for Houdini 2.0)
        link: https://github.com/Esri/cityengine_for_houdini/releases/download/v2.0.0-beta.1/Palladio_Example_Favela_v2.zip
      - title: Favela RPK
        link: https://github.com/Esri/cityengine_for_houdini/releases/download/v1.6.0/FAVELA.rpk

    images:
      - image-name: palladio_ex_2_1.jpg



  - title: CityEngine material handling for the Mantra renderer
    text: This example shows how to use the generated CityEngine material attributes with Mantra.</br></br>Downloads&colon;

    files:
      - title: Houdini Scene (HIPNC) (CityEngine for Houdini 2.0)
        link: https://github.com/Esri/cityengine_for_houdini/releases/download/v2.0.0-beta.1/PalladioDemo03_v2.zip
      - title: Houdini Digital Asset (HDANC)
        link: https://github.com/Esri/cityengine_for_houdini/releases/download/v1.6.1/PalladioCityEngineMaterial-v2.hdanc

    images:
      - image-name: palladio_ex_3_1.png



  - title: Computer Case Graveyard
    text: Downloads&colon;

    files:
      - title: Houdini Scene (HIPNC) (for CityEngine for Houdini 2.0; Updated on 2023-03-28 to fix lighting and materials.)
        link: https://github.com/Esri/cityengine_for_houdini/releases/download/v2.0.0-beta.2/PalladioDemo02_v3.zip

    images:
      - image-name: palladio_ex_4_1.jpg


  - title: CityEngine for Houdini Basic Use Case
    text: Downloads&colon;

    files:
      - title: Houdini Scene (HIPNC) (CityEngine for Houdini 2.0)
        link: https://github.com/Esri/cityengine_for_houdini/releases/download/v2.0.0-beta.1/PalladioDemo01_v2.zip

    images:
      - image-name: palladio_ex_5_1.jpg



legal: <ul><li>ArcGIS CityEngine for Houdini is free for personal, educational, and non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. Redistribution or web service offerings are not allowed unless expressly permitted.</li><li>ArcGIS CityEngine for Houdini is under the same license as the included <a href="./cityenginesdk#legal-section">CityEngine SDK</a>.</li><li>All content in the "Examples" directory/section is licensed under the APACHE 2.0 license. You may obtain a copy of this license at <a href="https://www.apache.org/licenses/LICENSE-2.0" target="_blank">https://www.apache.org/licenses/LICENSE-2.0</a>.</li><li>The “Favela” example data is copyrighted by <a href="https://www.vrbn.io/" target="_blank">vrbn</a> studios. Please contact ​info@vrbn.io for commercial licensing options.</li><li>For questions or enquiries, please contact <a href= "mailto:cityengine-info@esri.com">cityengine-info@esri.com</a></li></ul>

---
