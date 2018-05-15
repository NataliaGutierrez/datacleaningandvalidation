# Práctica 2: Neteja i validació de les dades

## Descripció

Aquesta pràctica s'engloba dins de l'assignatura Tipologia i Cicle de Vida de les Dades, del Màster de Ciència de les Dades de la UOC. L'objectiu ha sigut tractar el dataset *Red Wine Quality* seguint les principals etapes d'un projecte analític. Tot el desenvolupament s'ha fet en R.

## Autors

La pràctica s'ha realitzat de manera individual per Natalia Gutiérrez.

## Fitxers codi font

* src/main.py: exemple d'ús del scraper. És el que s'ha fet servir per generar el dataset inclòs aqui.
* src/vaacscraper.py: conté la classe *VAACScraper*, que pot generar un fitxer csv amb la informació dels Volcanic Ash Advisories a partir de l'[arxiu del VAAC de Washington](http://www.ssd.noaa.gov/VAAC/archive.html) compresos en un interval de temps.
* src/advisory.py: mòdul per extreure els camps requerits d'un VAA Advisory.
