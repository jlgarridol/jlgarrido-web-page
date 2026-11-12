---
title: "Pseudo-etiquetado en datos tabulares: de los clasificadores clásicos a los modelos fundacionales"
authors:
- Juan José Rodríguez
- admin
- Jesús Maudes-Raedo
- César García-Osorio
author_notes: 
- Speaker
date: "2026-11-13"
doi: ""

# Publication type.
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "XXI Conferencia de la Asociación Española para la Inteligencia Artificial"
publication_short: "CAEPIA 2026"

abstract: "Los modelos fundacionales tabulares como TabPFN están
redefiniendo el aprendizaje sobre datos tabulares. Es razonable preguntarse si las técnicas clásicas de aprendizaje semi-supervisado (SSL) por
pseudo-etiquetado (como self-training y tri-training), concebidas para
clasificadores tradicionales, siguen siendo útiles, o incluso se comportan
igual, cuando el clasificador base es un modelo fundacional. En datos tabulares, estos métodos de tipo envoltorio (wrapper ) son atractivos por su
carácter plug-and-play: pueden combinarse con cualquier clasificador ba-
se. Sin embargo, su utilidad real en este dominio dista de ser uniforme. En
este trabajo evaluamos empíricamente self-training y tri-training sobre
cuatro clasificadores base de naturaleza muy distinta: Random Forest,
regresión logística, gradient boosting (LightGBM ) y un modelo fundacional tabular (TabPFN ), en 31 conjuntos de datos usando solo un 5% de
datos etiquetados. Nuestro hallazgo principal es que el efecto del pseudo-
etiquetado depende del clasificador base. Perjudica de forma significativa
a Random Forest, no produce mejora significativa en regresión logística,
y beneficia de forma significativa a LightGBM y al modelo fundacional
TabPFN. Un análisis de las pseudo-etiquetas muestra que su calidad no
explica el patrón observado, que parece depender más de propiedades del
propio clasificador base."
summary: "Este artículo evalúa la efectividad del pseudo-etiquetado en diferentes clasificadores base en un contexto semisupervisado."

tags: [aprendizaje semi-supervisado, datos tabulares, pseudo-etiquetado, self-training, modelos fundacionales, TabPFN]
featured: false

url_pdf: "https://simidat.ujaen.es/caepia26/trabajos/caepia2026_244.pdf"
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

image:
  caption: ''
  focal_point: ""
  preview_only: false

projects: []
slides: ""
---
