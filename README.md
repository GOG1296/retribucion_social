# Guía de instalación y uso de Quarto.

## Recursos oficiales de Quarto

- Página principal: https://quarto.org/
- Descarga de Quarto: https://quarto.org/docs/download/index.html
- Documentación completa: https://quarto.org/docs/guide/
- Guía para comenzar: https://quarto.org/docs/get-started/

## Guía oficial de instalación.

**Se recomienda encarecidamente consultar la guía para comenzar (https://quarto.org/docs/get-started/), ya que ofrece instrucciones completas y actualizadas para:**

- Instalar Quarto según el sistema operativo utilizado (Linux, Windows o macOS).

- Elegir y configurar la herramienta de trabajo preferida (VS Code, Jupyter, RStudio, Neovim o cualquier editor de texto).

- Aprender a renderizar documentos a distintos formatos, directamente desde la herramienta seleccionada, con ejemplos específicos para cada entorno.

![get_started](https://github.com/GOG1296/retribucion_social/blob/images/guide1.PNG)

### ¿Cómo funciona la guía?

- Paso 1 (Step 1): Selecciona la versión de Quarto correspondiente a tu sistema operativo.

- Paso 2 (Step 2): Elige la herramienta con la que deseas trabajar. Serás redirigido a una guía específica que explica cómo:

  - Instalar y configurar esa herramienta.

  - Integrar Quarto correctamente.

  - Renderizar tus documentos desde esa plataforma.

## Tutoriales de instalación y uso.

### Instalación de Quarto con Windows

https://www.youtube.com/watch?v=uHaDmPtO-YQ

### Instalación de Quarto con Linux

https://www.youtube.com/watch?v=-wgBm1aLmNY

### Instalación de Quarto con Mac OS

https://www.youtube.com/watch?v=aOGGPcWZKUs&pp=ygUMUXVhcnRvIE1hY09T

### Ejemplo de creación de tesis con Quarto

https://www.youtube.com/watch?v=T9D-lq-hP1o&list=PLvxMQVVqTtnX9wk0vPISS05CRd89RPk3H

## Archivos esenciales para utilizar el estilo INFOTEC en Quarto

- mcdi.png: Logo de la maestría en ciencia de datos e información.
- posgrados.png: Logo de Posgrados INFOTEC.
- apa.csl: Plantilla que define cómo deben formatearse las citas y bibliografías según el estilo APA

## Archivo refs.bib

Para abrir este archivo, es suficiente con utilizar un editor de texto plano, como:

- Bloc de Notas en Windows

- TextEdit (en modo texto plano) en macOS

- Gedit, Kate o nano en Linux

Este archivo contiene todas las referencias bibliográficas que se utilizarán en el proyecto. Cada entrada debe estar escrita en formato BibTeX, y debe tener una estructura como:

@tipo{nombre_de_referencia,
  autor = {...},
  título = {...},
  ...
}

Es en este archivo donde debemos colocar todas las citas de interés que deseamos incluir en el documento final.

Algunas fuentes donde puedes obtener referencias en formato .bib son:
- https://scholar.google.com
- https://arxiv.org
  
### Obteneción de referencias usando google scholar

Lo primero es ir a la dirección https://scholar.google.com/ y buscar la referencia de nuestro interés. En este caso, buscaremos "Attention is all you need" de Vaswani.

Obtendremos varios resultados. En cada uno aparece un icono de comillas ("), identificado como "Citar", como se muestra en amarillo en la siguiente imagen:

![gs1](https://github.com/gog14/retribucion_social/blob/images/gs1.PNG)

Hacemos clic en "Citar" y se abrirá una ventana con varias opciones de formato. Seleccionamos la opción BibTeX:

![gs2](https://github.com/gog14/retribucion_social/blob/images/gs2.PNG)

Al hacer clic en BibTeX, se abrirá una nueva página con el siguiente formato, que es el que debemos copiar y pegar dentro de nuestro archivo refs.bib:

@article{vaswani2017attention,
  title={Attention is all you need},
  author={Vaswani, Ashish and Shazeer, Noam and Parmar, Niki and Uszkoreit, Jakob and Jones, Llion and Gomez, Aidan N and Kaiser, {\L}ukasz and Polosukhin, Illia},
  journal={Advances in neural information processing systems},
  volume={30},
  year={2017}
}

### Obteneción de referencias usando arxiv.org

Primero nos dirigimos a la dirección https://arxiv.org/ y procedemos a buscar la referencia de nuestro interés. La barra de busqueda se encuentra en la parte superior derecha.

![arxiv1](https://github.com/gog14/retribucion_social/blob/images/arxiv1.PNG)

Obtenemos distintos resultados relacionados a nuestra busqueda. Por fines prácticos, damos click en el primer resultado.

![arxiv2](https://github.com/gog14/retribucion_social/blob/images/arxiv2.PNG)

En la parte inferior derecha de nuestro documento de interes se encuentra el apartado ```export BibTeX citation``` al cual le damos click.

![arxiv3](https://github.com/gog14/retribucion_social/blob/images/arxiv3.PNG)

Y nos dara una nueva ventana con el formato bib.

![arxiv4](https://github.com/gog14/retribucion_social/blob/images/arxiv4.PNG)

Finalmente copiamos el formato tal como está y lo pegamos en nuestro archivo refs.bib





