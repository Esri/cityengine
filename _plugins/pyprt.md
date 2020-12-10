---
layout: detail
fullpreview: true
order-of-appearance: 4
draft: false

name: PyPrt
platform: Python
logo: pyprt.png
github: https://github.com/Esri/pyprt

teaser-image: serlio_ex_1_3.png

hero-title: PyPRT
hero-subtitle: Python Bindings for the CityEngine SDK
hero-content:
  - type: image
    name: serlio_ex_1_3.png

teaser-image: pyprt-teaser-image.jpg

description: PyPRT is a Python binding for PRT (“Procedural Runtime”). It enables the execution of CityEngine CGA rules within Python. Using PyPRT, the generation of 3D content in Python is greatly simplified.

introduction: Therefore, Python developers, data scientists, GIS analysts, etc. can efficiently make use of CityEngine rule packages in order to create 3D geometries stored as Python data structures, or to export these geometries in another format (like OBJ, Scene Layer Package, … ). Given an initial geometry, on which to apply the CGA rule, the 3D generation is procedurally done in Python (Python script, Jupyter Notebook, …). This allows for efficient and customizable geometry generation. For instance, when modeling buildings, PyPRT users can easily change the parameters of the generated buildings (like the height or the shape) by changing the values of the CGA rule input attributes.</br>PyPRT 3D content generation is based on CGA rule packages (RPK), which are authored in CityEngine. RPKs contain the CGA rule files that define the shape transformations, as well as supplementary assets. RPK examples can be found below and directly used in PyPRT.</br>PyPRT allows generating 3D models on multiple initial geometries. Different input attributes can be applied on each of these initial shapes. Moreover, the outputted 3D geometries can either be used inside Python or exported to another format by using one of PRT encoders.</br>PyPRT is free for non-commercial use. Commercial use requires at least one commercial license of the latest CityEngine version installed in the organization. No redistribution is allowed. Please refer to the licensing section below for more detailed licensing information.

---
