# Webmap — Classification results for artificial land surfaces

This repository contains a webmap that was originally produced for [A²S](https://a2s.unistra.fr/index.php/Accueil) in 2016. Its aim was to showcase the results of a pipeline prototype written in R, for extracting artificial land surfaces from satellite imagery. Said surfaces were obtained by classifying SPOT images, using a Random Forest classifier, Copernicus data and specific sampling scheme.

<div class="warning" style='background-color:#e1f5fe; color: #0277bd; border-left: solid #0277bd 8px; border-radius: 8px; padding: 8px 16px;'>
    <p style='margin-top:1em;'><strong>Note</strong></p>
    <p>
    The data showcased in this webmap is the result of a processing pipeline that was still in its infancy, and that would later be adapted so as to process Sentinel-2 images. The corresponding pipeline would then become the prototype that <a href="https://www.theia-land.fr/product/urba-opt/">Urba-Opt</a> was built upon.
    </p>
    <p>
    The webmap was briefly updated in September 2022, following the new standards in web development. However, the original pipeline and data were not modified.
    </p>
</div>

## Technologies

<p align="center">
	<img alt="R" src="https://img.shields.io/badge/-r-276DC3?style=for-the-badge&logo=r&logoColor=white">
	<img alt="Openlayers" src="https://img.shields.io/badge/-Openlayers-039be5?style=for-the-badge&logo=openlayers&logoColor=white">
	<img alt="JavaScript" src="https://img.shields.io/badge/-javascript-fdd835?style=for-the-badge&logo=javascript&logoColor=black">
	<img alt="NPM" src="https://img.shields.io/badge/-npm-e53935?style=for-the-badge&logo=npm&logoColor=white">
</p>

## 📁 Project structure

This project includes the following directories:

- `data/` — TopoJSON files containing classification results and region of interest.
- `dist/` — Build directory.

## 🏗️ Build

In order to build this portfolio, Node.js v16.15.0+ is required.

The following lines can be used to run the webmap in a built-in development server:

```bash
git clone https://github.com/poterekq/a2s-urban-webmap.git
cd a2s-urban-webmap
npm install
npm run dev
```
