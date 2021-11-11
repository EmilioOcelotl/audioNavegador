# audioNavegador

## Introducción

Tone.js es un marco para la generación de audio en el navegador. La librería tiene las siguientes premisas: familiaridad con músicos y programadores de audio

Si bien hay muchas maneras de incoporar la librería en un proyecto, mostraré un ejemplo en el editor de P5.js para llegar rápido a la acción. Esto permitirá la integración con imagen. 

Se pueden cambiar algunos parámetros asociados a eventos que suceden en el navegador. Para live coding, otras plataformas funcionan mejor. 

## Antecedentes y proyectos cercanos

- [Web Audio API](https://developer.mozilla.org/es/docs/Web/API/Web_Audio_API)
- [Estuary](https://estuary.mcmaster.ca/) ( y sus habitantes )
  - [seis8s](https://github.com/luisnavarrodelangel/seis8s)
- [sema-engine](https://github.com/frantic0/sema-engine)

## Entorno

Vamos a utilizar el editor en línea de P5.js como marco de trabajo. Todo esto se puede subir a un servidor 

Descripción de la estructura de archivos en p5

### Pasos

0. Estructura de un proyecto en p5.js

- index.html
- sketch.js > aquí vamos a trabajar, el editor se centra en la modificación de este archivo
- style.css
- carpetas > donde colocaremos los archivos que usaremos 

1. Agregar la librería Tone.js a index.html

`<script src="https://cdnjs.cloudflare.com/ajax/libs/tone/13.0.1/Tone.min.js" type="text/javascript"></script>`

Nota: En algunos casos el audio no se reproducirá a menos de que haya un gesto ( una tecla o un clic ). El editor de p5.js realiza esto entonces no es problema. 

## Enlaces de muestra

- [Reproducción de muestras](https://editor.p5js.org/emilioocelotl/sketches/j2YOB826v)
- [Secuenciadores]()
- Síntesis
- Análisis
- Otros recursos 

## Caso de estudio: anti

También se puede integrar con otros entornos gráficos 

[anti](https://github.com/EmilioOcelotl/4NT1) 

## Recursos

- https://tonejs.github.io/
- https://p5js.org/es/
- https://developer.mozilla.org/es/docs/Web/API/Web_Audio_API
- https://estuary.mcmaster.ca/
- https://threejs.org/
- https://github.com/frantic0/sema-engine