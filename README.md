<img src="https://i.ibb.co/j3q7B0n/Grupo-115-2.png" alt="Grupo-115-2" border="0">

**Documento de manejo de imagenes**
# Chef company

- [Chef company](#chef-company)
- [Antes de leer](#antes-de-leer)
    - [Horizontales.](#horizontales)
    - [Verticales.](#verticales)
    - [Cuadradas.](#cuadradas)auto    - [Uso de imágenes para tarjetas [Cards]:](#uso-de-imágenes-para-tarjetas-cards)
- [Cuando los contenedores son cuadrados:](#cuando-los-contenedores-son-cuadrados)
    - [Imágenes ideales:](#imágenes-ideales)
- [Cuando los contenedores son verticales:](#cuando-los-contenedores-son-verticales)
    - [Imágenes ideales:](#imágenes-ideales-1)
- [Cuando los contenedores son horizontales:](#cuando-los-contenedores-son-horizontales)
    - [Imágenes ideales:](#imágenes-ideales-2)auto    - [Notas adicionales](#notas-adicionales)
- [Manejo de imagenes para dispositivos, pantallas de alta densidad](#manejo-de-imagenes-para-dispositivos-pantallas-de-alta-densidad)
- [JPG](#jpg)
- [PNG](#png)
- [SVG](#svg)


> Notas:
> 
	hasta el momento, los tipos de imágenes que se han documentado son:
	- Cards
	- Banner horizontal
	La documentación es continúa. En caso de hallazgos 
	(obviamente relacionados con imágenes); tener en cuenta que,
	 todos los componentes de este documento están disponibles para: 
	**Ampliar, modificar, eliminar.**

### Antes de leer
Antes de empezar el documento, conviene enumerar los tipos de dimensiones que vamos a manejar,

#### Horizontales.
El ancho supera a la altura: w > (h + 1/2w)

<img src="https://i.ibb.co/RP1WFJH/h-s-2x.png" alt="h-s-2x" border="0">
<img src="https://i.ibb.co/87nFtbX/horizontal-2x.png" alt="horizontal-2x" border="0">


#### Verticales.
El alto supera al ancho: h > (w + 1/2h)

<img src="https://i.ibb.co/NyGmtzM/v-s-2x.png" alt="v-s-2x" border="0">
<img src="https://i.ibb.co/4JtN26X/vertical-2x.png" alt="vertical-2x" border="0">

#### Cuadradas.
Todas las demás relaciones en donde una dimension (width or height) no supera a la otra en 1/2

<img src="https://i.ibb.co/TPH2HD1/sq-s-2x.png" alt="sq-s-2x" border="0">
<img src="https://i.ibb.co/85tmr4R/cuadrada-2x.png" alt="cuadrada-2x" border="0">

## Uso de imágenes para tarjetas [Cards]:
Propuesta para manejo de imagenes en tarjetas *(basado en grid + object-fit)*, [Revisar este ejemplo](https://codepen.io/sanchez-dev/pen/GRRajqQ)
> Diseñadores, el punto de atención de la imagen siempre debe estar en el centro.

### Cuando los contenedores son cuadrados:
<img src="https://i.ibb.co/hdFmw9d/sq-crop-2x.png" alt="sq-crop-2x" border="0">

- Priorizan el ancho antes que el alto
- Si se agota el ancho, expande el alto.

#### Imágenes ideales:
- [x] Horizontales
- [x] Verticales
- [x] Cuadradas

### Cuando los contenedores son verticales:
<img src="https://i.ibb.co/FKfdTk3/v-crop-2x.png" alt="v-crop-2x" border="0">

- Priorizan el espacio a lo alto (height)
- Si se agota el alto, expanden el ancho (width).

#### Imágenes ideales:
- [ ] Horizontales
- [x] Verticales
- [x] Cuadradas

### Cuando los contenedores son horizontales:
<img src="https://i.ibb.co/Kw4WgCt/h-crop-2x.png" alt="h-crop-2x" border="0">

- Priorizan el espacio a lo ancho (width)
- Si se agota el ancho, expanden el alto.

#### Imágenes ideales:
- [x] Horizontales
- [ ] Verticales
- [x] Cuadradas

---

## Notas adicionales
### Manejo de imagenes para dispositivos, pantallas de alta densidad
En espera

### JPG
En espera

### PNG
En espera

### SVG 
Recomendaciones, uso optimo:

- logos.
- Pequeños iconos, bottones, bullets.
- Animaciones.

Mucha gente no sabe que el formato svg, se redibuja entero en cada loop del navegador, por lo que una imagen con muchos componentes o nodos, aumentan el uso de procesamiento. 
	