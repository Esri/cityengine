---
layout: detail
fullpreview: true
order-of-appearance: 1
draft: false

name: Palladio
platform: Houdini
logo: palladio.png
github: https://github.com/Esri/palladio

teaser-image: palladio_ex_5_1.jpg

description: Palladio is a plugin for SideFX Houdini. It provides operator nodes which enable the execution of CityEngine ‘rules’ within Houdini networks. Therefore, a 3D environment artist does not have to leave their familiar Houdini toolset anymore to make use of CityEngine’s procedural modeling power.

introduction: Complicated export-import pipelines are no longer needed, which also means that the procedural building models do not need to be “baked” anymore. The buildings stay procedural during the entire modeling workflow (optionally even at render time). Consequently, the 3D environment artist can change the height, style and appearance of buildings easily with a parametric interface at any point during production.</br>Palladio requires Rule Packages (RPK) as input, which are authored in CityEngine. An RPK includes assets and a CGA rule file which encodes an architectural style. Comprehensive RPK examples are available below and can be used “out-of-the-box” in Palladio. More examples for CGA rule files can be found in the CityEngine tutorials.</br>Palladio is well suited for managing the procedural generation of architectural 3D content in digital sets. However, Palladio is restricted to the procedural generation of single buildings / objects. Palladio does not include the city layouting and street network editing tools of CityEngine i.e. the rich CityEngine toolset to design a city from scratch (or based on geographic data) is still needed.

examples:

  - title: Angkor Thom
    text: This example includes full CityEngine and Houdini projects. It demonstrates how to use CityEngine to author procedural assets like Walls, Stairs, Porticos and combine them in Houdini via Palladio and Rule Packages. The scene consists of three major steps:</br></br><ul><li>The "/obj/PALLADIO_BASE" geometry node generates the various CityEngine Rules via Palladio and assigns them to multiple outputs.</li><li>Multiple "/obj/process_palladio_xxx" nodes reference above outputs, apply a stone weathering effect and cache out the geometry.</li><li>The "/obj/creepers_xxx" nodes apply some creeper plant effects.</li></ul></br></br>How to change one of the rule attribute values:</br></br></br><ul><li>Activate the "render" flag of the "OUT_columnRowWithBeams" node in PALLADIO_BASE.</li><li>Find "attribcreate3" above the out node and change the value of "Total_Height", the model will regenerate.</li><li>Go to "process_palladio_columnRowWithBeams" and render "file1", will take a while.</li><li>Set the "render" flag back to "uvtransform1" and click "reload geometry" on "file2"."</li><li>Repeat the previous step for the file nodes in "creepers_columnRowWithBeams".</li></ul></br></br>Notes:</br></br><ul><li>Created by Matthias Buehler</li><li>Also covered in "Digital Production" Issue 05/18 (Article in German).</li><li>Update 2 on 2019-06-27&colon; Fixed wrong RPK path and "creepers" input references.</li><li>Known issue&colon; warning in 17.5 regarding "hair generate" node at scene open (internal Houdini problem).</li></ul></br></br>Downloads&colon;

    files:
      - title: Houdini and CityEngine projects
        link: https://github.com/Esri/palladio/releases/download/v1.6.0/Palladio_Example_Angkor_Thom_v2.zip

    images:
      - image-name: palladio_ex_1_1.jpg
      - image-name: palladio_ex_1_2.jpg
      - image-name: palladio_ex_1_3.jpg


  - title: Favela
    text: The Favela example demonstrates the packaging of a complex Rule Package into a Houdini Digital Asset with custom high-level parameters. The provided Houdini scene additionally shows how to prepare the input geometry for Palladio out of an Alembic archive (setup of random seed and start rule).</br></br>Notes:</br><ul><li>Requires Houdini 17.5 and Palladio 1.6.1 or later.</li><li>Based on the original "Favela" project (YouTube) created with CityEngine, Maya and Maxwell.</li><li>Created by Matthias Buehler</li></ul></br></br>Downloads&colon;

    files:
      - title: Houdini Project
        link: https://github.com/Esri/palladio/releases/download/v1.6.1/favela_houdini_project_v1.zip
      - title: Favela RPK
        link: https://github.com/Esri/palladio/releases/download/v1.6.0/FAVELA.rpk

    images:
      - image-name: palladio_ex_2_1.jpg
      - image-name: palladio_ex_2_2.png



  - title: CityEngine Material Handling (MANTRA)
    text: This example shows how to use the generated CityEngine material attributes with Mantra.</br></br>Downloads&colon;

    files:
      - title: Houdini Scene (HIPNC)
        link: https://github.com/Esri/palladio/releases/download/v1.4.0/PalladioDemo03.zip
      - title: Houdini Digital Asset (HDANC)
        link: https://github.com/Esri/palladio/releases/download/v1.6.1/PalladioCityEngineMaterial-v2.hdanc

    images:
      - image-name: palladio_ex_3_1.png



  - title: Computer Case Graveyard
    text: Downloads&colon;

    files:
      - title: Houdini Scene (HIPNC)
        link: https://github.com/Esri/palladio/releases/download/v1.1/PalladioDemo02.zip

    images:
      - image-name: palladio_ex_4_1.jpg


  - title: Palladio Basic Use Case
    text: Downloads&colon;

    files:
      - title: Houdini Scene (HIPNC)
        link: https://github.com/Esri/palladio/releases/download/v1.0/PalladioDemo01.zip

    images:
      - image-name: palladio_ex_5_1.jpg



legal: Palladio is free for non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. No redistribution is allowed.</br>Palladio is under the same license as the included CityEngine SDK.</br> An exception is the Palladio source code (without CityEngine SDK, binaries, or object code), which is licensed under the Apache License, Version 2.0 (the “License”); you may not use this work except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.</br>The “Favela” example data is copyrighted by vrbn studios. Please contact ​info@vrbn.io for commercial licensing options.

---
