<!DOCTYPE html>
<html>
  <head>
    <title>Title</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <style type="text/css">
      /* Slideshow styles */
    </style>
  </head>
  <body>
    <textarea id="source">

name: inla
layout: true
class: middle, center
---
# Obiettivo

Analisi  delle  serie  di  dati  di  concentrazione  di  `\PM_{10}\`,  `\PM_{2.5}\`,  `\NO_2\`  e  `\O_3\`

---
# Riferimento

[The effect of Corona Virus Lockdown on Air Pollution: Evidence from the City of Brescia in Lombardia Region (Italy)](https://www.sciencedirect.com/science/article/pii/S1352231020305288)

Autore: Michela Cameletti

`\NO_2\`: 3 stazioni
`\PM_{10}\`: 2 stazioni

Periodo: 1 Gennaio - 27 Marzo 2020

Interrupted time series regression

    </textarea>
    <script src="http://gnab.github.io/remark/downloads/remark-latest.min.js" type="text/javascript"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/MathJax.js?config=TeX-AMS_HTML&delayStartupUntil=configured" type="text/javascript"></script>
    <script type="text/javascript">
      var slideshow = remark.create();

      // Setup MathJax
      MathJax.Hub.Config({
          tex2jax: {
          skipTags: ['script', 'noscript', 'style', 'textarea', 'pre']
          }
      });

      MathJax.Hub.Configured();
    </script>
  </body>
</html>
