---
layout: detail
fullpreview: true
order-of-appearance: 2
draft: false

name: Serlio
title: Serlio - Plugin for Maya
platform: Maya
logo: serlio.png
github: https://github.com/Esri/serlio

teaser-image: serlio_ex_1_3.png

hero-title: Serlio
hero-subtitle: CityEngine Plugin for Autodesk Maya
hero-content:
  - type: video
    name: G6MpB4dDhx0

description: Serlio is a plugin for Autodesk Maya. It provides a modifier node which enables the execution of CityEngine CGA rules within a Maya scene. Therefore, a 3D environment artist does not have to leave their familiar Maya toolset anymore to make use of the procedural modeling power of CityEngine.

gallery:
  - image: serlio_ex_1_2.png
  - image: serlio_ex_1_1.png

introduction: With Serlio, complicated export-import pipelines are no longer needed, which also means that the procedural building models do not need to be “baked” anymore. The buildings stay procedural during the entire modeling workflow. Consequently, the 3D environment artist can change the height, style and appearance of buildings easily with a parametric interface at any point during production.<br/><br/>Serlio requires so-called rule packages (RPK) as input, which are authored in CityEngine. An RPK includes assets and a CGA rule file which encodes an architectural style. Comprehensive RPK examples are available below and can be used “out-of-the-box” in Serlio.<br/><br/>Serlio is well suited for managing the procedural generation of architectural 3D content in digital sets. However, Serlio is restricted to the procedural generation of single buildings or objects. Serlio does not include the city layouting and street network editing tools of CityEngine i.e. the rich CityEngine toolset to design a city from (or based on geographic data) is still needed.

ressource-1-title: Downloads
ressource-1-text: Download the latest version of Serlio here.
ressource-1-link-text: → Go to downloads
ressource-1-link-url: https://github.com/esri/serlio/releases

ressource-2-title: Documentation
ressource-2-text: A full documentation of Serlio is available on our Github repository.
ressource-2-link-text: → Read documentation
ressource-2-link-url: https://github.com/esri/serlio/blob/master/README.md#documentation

ressource-3-title: Github
ressource-3-text: For more information, assets and resources check our Github repository.
ressource-3-link-text: → Go to Github
ressource-3-link-url: https://github.com/esri/serlio/

examples:

  - title: Favela Maya Project
    text: The Favela example demonstrates how a complex CityEngine Rule Package (RPK) is applied on one or more polygons. The provided Maya project includes an Alembic file with shapes from CityEngine, the Favela RPK itself and Maya scenes.</br></br><strong>Notes:</strong><ul><li>Requires Maya 2018 or later. </li><li>Based on the <a href="https://www.youtube.com/watch?v=IY5gU1J39Ec" target="_blank">original "Favela" project (YouTube)</a> created with CityEngine, Maya and Maxwell created by Matthias Bühler and Cyrill Oberhänsli. </li><li>v2 released on 2020-06-03 for Serlio v1.1.0</li></ul>

    files:
    - title: Favela Maya Project
      link: https://github.com/Esri/serlio/releases/download/v1.1.0/favela_maya_project_v2.zip
    - title: Instructions
      link: ./assets/files/serlio_favela_instructions.txt

    images:
      - image-name: serlio_ex_1_1.png


legal: <ul><li>Serlio is free for non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. No redistribution is allowed. </li><li>Serlio is under the same license as the included CityEngine SDK. An exception is the Serlio source code (without CityEngine SDK, binaries, or object code), which is licensed under the Apache License, Version 2.0 (the “License”); you may not use this work except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.</li></ul>

---
