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

hero-title: Palladio
hero-subtitle: CityEngine Plugin for Houdini
hero-content:
  - type: video
    name: rOH_oZ1doLU

description: Palladio is a plugin for SideFX Houdini. It provides operator nodes which enable the execution of CityEngine ‘rules’ within Houdini networks. Therefore, a 3D environment artist does not have to leave their familiar Houdini toolset anymore to make use of CityEngine’s procedural modeling power.

gallery:
- image: palladio_ex_1_2.jpg
- image: palladio_ex_2_2.png
- image: palladio_ex_1_3.jpg

introduction: Complicated export-import pipelines are no longer needed, which also means that the procedural building models do not need to be “baked” anymore. The buildings stay procedural during the entire modeling workflow (optionally even at render time). Consequently, the 3D environment artist can change the height, style and appearance of buildings easily with a parametric interface at any point during production.</br>Palladio requires Rule Packages (RPK) as input, which are authored in CityEngine. An RPK includes assets and a CGA rule file which encodes an architectural style. Comprehensive RPK examples are available below and can be used “out-of-the-box” in Palladio. More examples for CGA rule files can be found in the CityEngine tutorials.</br>Palladio is well suited for managing the procedural generation of architectural 3D content in digital sets. However, Palladio is restricted to the procedural generation of single buildings / objects. Palladio does not include the city layouting and street network editing tools of CityEngine i.e. the rich CityEngine toolset to design a city from scratch (or based on geographic data) is still needed.

ressource-1-title: Downloads
ressource-1-text: Download the latest version of Palladio here.
ressource-1-link-text: → Go to downloads
ressource-1-link-url: https://github.com/esri/palladio/releases

ressource-2-title: Documentation
ressource-2-text: A full documentation of Palladio is available on our github repository.
ressource-2-link-text: → Read documentation
ressource-2-link-url: https://github.com/Esri/palladio/blob/master/README.md#documentation

ressource-3-title: Github
ressource-3-text: For more information, assets and resources check our Github repository.
ressource-3-link-text: → Go to Github
ressource-3-link-url: https://github.com/esri/palladio/



examples:

  - title: Angkor Thom
    text: This example includes full CityEngine and Houdini projects. It demonstrates how to use CityEngine to author procedural assets like Walls, Stairs, Porticos and combine them in Houdini via Palladio and Rule Packages.</br>Notes:</br></br><ul><li>Created by Matthias Buehler</li><li>Also covered in "Digital Production" Issue 05/18 (Article in German).</li></ul></br></br>Downloads&colon;

    files:
      - title: Houdini and CityEngine projects
        link: https://github.com/Esri/palladio/releases/download/v1.6.0/Palladio_Example_Angkor_Thom_v2.zip
      - title: Instruction
        link: ../assets/files/palladio_angkor_thom_instructions.txt

    images:
      - image-name: palladio_ex_1_1.jpg


  - title: Favela
    text: The Favela example demonstrates the packaging of a complex Rule Package into a Houdini Digital Asset with custom high-level parameters. The provided Houdini scene additionally shows how to prepare the input geometry for Palladio out of an Alembic archive (setup of random seed and start rule).</br></br>Notes:</br><ul><li>Requires Houdini 17.5 and Palladio 1.6.1 or later.</li><li>Based on the original "Favela" project (YouTube) created with CityEngine, Maya and Maxwell.</li><li>Created by Matthias Buehler</li></ul></br></br>Downloads&colon;

    files:
      - title: Houdini Project
        link: https://github.com/Esri/palladio/releases/download/v1.6.1/favela_houdini_project_v1.zip
      - title: Favela RPK
        link: https://github.com/Esri/palladio/releases/download/v1.6.0/FAVELA.rpk

    images:
      - image-name: palladio_ex_2_1.jpg



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






legal: <ul><li>Palladio is free for non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. No redistribution is allowed.</li><li>Palladio is under the same license as the included CityEngine SDK.</li><li>An exception is the Palladio source code (without CityEngine SDK, binaries, or object code), which is licensed under the Apache License, Version 2.0 (the “License”); you may not use this work except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0.</li><li>The “Favela” example data is copyrighted by vrbn studios. Please contact ​info@vrbn.io for commercial licensing options.</li></ul>

---
