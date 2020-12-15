---
layout: detail
fullpreview: true
order-of-appearance: 5
draft: false

name: CityEngineSDK
title: CityEngine C++ SDK
platform: C++
logo: sdk.png
github: https://github.com/Esri/cityengine-sdk

hero-title: CityEngine SDK
hero-subtitle: C++ APIs, Documentation and Examples for the Procedural Runtime (PRT)
hero-content:
  - type: video
    name: rOH_oZ1doLU

teaser-image: cityengine_teaser_image.png

description: One of the most important components of CityEngine is the "Procedural Runtime" (PRT). It consumes Rule Packages (RPK) authored with CityEngine and generates the 3d geometry of building models.

gallery:
- image: cityengine_gallery_1.png
- image: cityengine_gallery_2.png
- image: cityengine_gallery_3.png

introduction: The CityEngine SDK consists of the "Procedural Runtime" (PRT) C++ APIs, documentation and source code examples. PRT consumes "Rule Packages" (RPK) authored within CityEngine and generates the 3d geometry of building models.<br/><br/>PRT can be used for the (1) development of custom importers and exporters for CityEngine, or to (2) create plugins for other 3D apps which need a procedural geometry engine.<br/><br/>For the first use case, this means that the SDK enables you to develop CityEngine plugins to read or write additional 3D geometry and image formats or your own proprietary 3D data format. An example is 3D printing where the STL geometry format is often needed. STL support is not provided out-of-the-box in CityEngine, but you can develop your own STL exporter as shown in the included examples below.<br/><br/>In the second use case, PRT is integrated into your own 3D applications taking full advantage of the procedural geometry generation without running CityEngine. PRT takes as input an initial geometry and then applies a given rule package (= CGA rules authored in CityEngine) to generate more detailed 3D geometry as output. For example, PRT can generate - based on given rules - a 3D model of a building out of a parcel polygon. This is how our plugins for e.g. Houdini operate in principle.

ressource-1-title: Downloads
ressource-1-text: Download the latest version of CityEngine SDK here.
ressource-1-link-text: → Go to downloads
ressource-1-link-url: https://github.com/esri/cityengine-sdk/releases

ressource-2-title: Documentation
ressource-2-text: A full documentation of Palladio is available on our github repository.
ressource-2-link-text: → Read documentation
ressource-2-link-url: https://github.com/Esri/cityengine-sdk/blob/master/README.md

ressource-3-title: Github
ressource-3-text: For more information, assets and resources check our Github repository.
ressource-3-link-text: → Go to Github
ressource-3-link-url: https://github.com/esri/cityengine-sdk

examples:

  - title: Source Code Examples
    text: We provide source code examples in the "examples" directory on github. Each example contains a README with detailed instructions how to build and use it:<ul><li>prt4cmd&colon; a simple command line utility to apply rule packages onto initial shapes and generate models.</li><li>stlenc&colon; demonstrates how to write a custom encoder, in this case for the STL geometry format.</li><li>stldec&colon; demonstrates how to write a custom decoder for the STL geometry format.</li></ul>

    files:
      - title: Example Folder
        link: https://github.com/Esri/cityengine-sdk/tree/master/examples

    images:
      - image-name: cityengine_ex_1_1.png


legal: <ul><li>Copyright (c) 2020 Esri</li><li>You may not use the content of this repository except in compliance with the following Licenses&colon;</li><li>All content in the "examples" directory tree is licensed under the APACHE 2.0 license. You may obtain a copy of this license at http://www.apache.org/licenses/LICENSE-2.0.</li><li>All other content is licensed under the Esri Terms of Use (also see Product-Specific Terms of Use).</li></ul>
---
