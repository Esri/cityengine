---
layout: detail
fullpreview: true
order-of-appearance: 5
draft: false

name: PyPRT
title: PyPRT - Python Bindings for PRT
platform: Python
logo: pyprt.png
github: https://github.com/Esri/pyprt

teaser-image: pyprt-teaser-image.jpg

hero-title: PyPRT
hero-subtitle: Python Bindings for the CityEngine SDK
hero-content:
  - type: image
    name: pyprt-teaser-image.jpg

description: PyPRT provides a Python binding for PRT (Procedural RunTime) of CityEngine. This enables the execution of CityEngine CGA rules within Python. Using PyPRT, the generation of 3D content in Python is greatly simplified.

gallery:
- image: pyprt_ex_5_1.jpg
- image: pyprt_gallery_2.png

introduction: Users, such as Python developers, data scientists, or GIS analysts, can efficiently make use of CityEngine Rule Packages (RPK) in order to create 3D geometries stored as Python data structures, or to export these geometries in another format (like OBJ, Scene Layer Package, … ). Given an initial geometry, on which to apply the CGA rule, the 3D generation is procedurally done in Python (Python script, Jupyter Notebook, …). This allows for efficient and customizable geometry generation. For example, when modeling buildings, PyPRT users can easily change the parameters of the generated buildings (like the height or the shape) by changing the values of the CGA rule input attributes.<br/><br/>PyPRT 3D content generation is based on CGA Rule Packages (RPK), which are authored in CityEngine. RPKs contain the CGA rule files that define the shape transformations, as well as supplementary assets. RPK examples can be found below and directly used in PyPRT.<br/><br/>PyPRT allows generating 3D models on multiple initial geometries. Different input attributes can be applied on each of these initial shapes. Moreover, the output 3D geometries can either be used from within Python or exported to another format by using one of the built-in PRT encoders.<br/><br/>PyPRT is free for non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. No redistribution is allowed. Please refer to the licensing section below for more detailed licensing information.<br/><br/><strong><i>PyPRT is free for personal, educational, and non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. Redistribution or web service offerings are not allowed unless expressly permitted. Please refer to the licensing section below for more detailed licensing information.</strong></i>

ressource-1-title: Installation
ressource-1-text: Simply run <code class="language-plaintext highlighter-rouge">pip install pyprt</code> in your desired Python environment or <code class="language-plaintext highlighter-rouge">conda install -c esri pyprt</code> in a Conda environment. Then use <code class="language-plaintext highlighter-rouge">import pyprt</code> in your scripts.
ressource-1-link-text: → Installation instructions
ressource-1-link-url: https://github.com/Esri/pyprt/blob/master/README.md#installation

ressource-2-title: Documentation
ressource-2-text: A full documentation of PyPRT is available on our github repository.
ressource-2-link-text: → Read documentation
ressource-2-link-url: https://github.com/Esri/pyprt/blob/master/README.md#documentation

ressource-3-title: Github
ressource-3-text: For more information, assets and resources check our Github repository.
ressource-3-link-text: → Go to Github
ressource-3-link-url: https://github.com/Esri/pyprt



examples:

  - title: 3D Model Optimization
    text: This example tries to answer the following question&colon; given the architectural design of a building (defined by a CGA rule) and a parcel, which values for the building parameters should we choose in order to maximize the green potential of the building?
    files:
    - title: Link to the example notebook
      link: https://github.com/Esri/pyprt-examples/blob/master/ex7_building_modeling_optimization.ipynb
    - title: ArcGIS Notebooks and PyPRT (Instruction)
      link: ./assets/files/ArcGIS-Notebooks-and-PyPRT.txt
    images:
      - image-name: pyprt_ex_1_1.jpg

  - title: 3D GIS Content Creation
    text: This example presents a possible workflow consisting of collecting and selecting city parcels, and populating them with procedurally generated trees. To do so, PyPRT is used in combination with other Python libraries, e.g. the <a href="https://developers.arcgis.com/python">ArcGIS API for Python</a>.
    files:
    - title: Link to the example notebook
      link: https://github.com/Esri/pyprt-examples/blob/master/ex8_3d_gis_content_generation.ipynb
    - title: ArcGIS Notebooks and PyPRT (Instruction)
      link: ./assets/files/ArcGIS-Notebooks-and-PyPRT.txt
    images:
      - image-name: pyprt_ex_2_1.png

  - title: Other Examples and blog entries
    text: Other examples of PyPRT usage are located in the pyprt-examples Github repo. Ready-to-use rule packages and initial shapes are available there.
    files:
    - title: More Examples
      link: https://github.com/Esri/pyprt-examples
    - title: Generating 3D content in Python&colon; PyPRT, a new Python library
      link: https://www.esri.com/arcgis-blog/products/city-engine/3d-gis/generating-3d-content-in-python-pyprt-a-new-python-library/
    - title: Converting 3D geometry formats made simple using PyPRT
      link: https://www.esri.com/arcgis-blog/products/city-engine/3d-gis/converting-3d-geometry-formats-made-simple-using-pyprt/
    images:
      - image-name: pyprt_ex_4_1.png







legal: <ul><li>PyPRT is free for personal, educational, and non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. Redistribution or web service offerings are not allowed unless expressly permitted.</li><li>PyPRT is under the same license as the included <a href="./cityenginesdk#legal-section">CityEngine SDK</a>.</li><li>All content in the "Examples" directory/section is licensed under the APACHE 2.0 license. You may obtain a copy of this license at <a href="https://www.apache.org/licenses/LICENSE-2.0" target="_blank">https://www.apache.org/licenses/LICENSE-2.0</a>.</li><li>For questions or enquiries, please contact <a href= "mailto:cityengine-info@esri.com">cityengine-info@esri.com</a></li></ul>

---
