---
layout: detail
fullpreview: true
order-of-appearance: 2
draft: false

name: Serlio
platform: Maya
logo: serlio.png
github: https://github.com/Esri/serlio

teaser-image: pyprt-teaser-image.jpg

description: Serlio is a plugin for Autodesk Maya. It provides a modifier node which enables the execution of CityEngine ‘rules’ within a Maya scene. Therefore, a 3D environment artist does not have to leave their familiar Maya toolset anymore to make use of CityEngine’s procedural modeling power.

introduction: Complicated export-import pipelines are no longer needed, which also means that the procedural building models do not need to be “baked” anymore. The buildings stay procedural during the entire modeling workflow. Consequently, the 3D environment artist can change the height, style and appearance of buildings easily with a parametric interface at any point during production. </br>Serlio requires so-called rule packages (RPK) as input, which are authored in CityEngine. An RPK includes assets and a CGA rule file which encodes an architectural style. Comprehensive RPK examples are available below and can be used “out-of-the-box” in Serlio.</br> Serlio is well suited for managing the procedural generation of architectural 3D content in digital sets. However, Serlio is restricted to the procedural generation of single buildings / objects. Serlio does not include the city layouting and street network editing tools of CityEngine i.e. the rich CityEngine toolset to design a city from (or based on geographic data) is still needed.


downloads:

  - filename: file.file
  - filename: file.file
  - filename: file.file


examples:

  - title: Favela Maya Project
    text: The Favela example demonstrates how a complex CityEngine Rule Package (RPK) is applied on one or more polygons. The provided Maya project includes an Alembic file with shapes from CityEngine, the Favela RPK itself and Maya scenes.</br></br><strong>Guide:</strong><ul><li>Call "File | Set Project..." and set it to the downloaded Favela Maya project (otherwise Serlio will not find the Favela RPK).</li><li>Open one of the two provided Maya scenes, this will immediately trigger the generation of the Favela model - it might take a while to load the RPK on the first time after starting Maya.</li></ul> </br></br><strong>Notes:</strong><ul><li>Requires Maya 2018 or later. </li><li>Based on the <a href="https://www.youtube.com/watch?v=IY5gU1J39Ec" target="_blank">original "Favela" project (YouTube)</a> created with CityEngine, Maya and Maxwell created by Matthias Bühler and Cyrill Oberhänsli. </li><li>v2 released on 2020-06-03 for Serlio v1.1.0</li></ul>
    filename: asf.asdf
    images:
      - image-name: favela.png
      - image-name: favela2.png

  - title: Example 2
    text: asdf asdf asdf asdf
    filename: asdf.asdf
    images:
      - image-name: sdk-teaser-image.jpg


legal: Serlio is free for non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. No redistribution is allowed. </br>Serlio is under the same license as the included CityEngine SDK. An exception is the Serlio source code (without CityEngine SDK, binaries, or object code), which is licensed under the Apache License, Version 2.0 (the “License”); you may not use this work except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.

---
