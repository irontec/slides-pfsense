<!-- MDTOC maxdepth:6 firsth1:1 numbering:0 flatten:0 bullets:1 updateOnSave:1 -->

- [Transparencias curso pfSense](#transparencias-curso-pfsense)   
   - [Pasos para editar las transparencias](#pasos-para-editar-las-transparencias)   
   - [Trucos](#trucos)   
      - [Imprimir](#imprimir)   

<!-- /MDTOC -->
# Transparencias curso pfSense

Vas a necesitar, como dependencias, al menos los siguientes paquetes:
* [npm](https://www.npmjs.com/)


## Pasos para editar las transparencias
Básicamente lo que tienes que hacer es hacer un clone de este repositorio. Necesitarás las dependencias puestas arriba.

Los comandos a ejecutar una vez hecho el clone:

```
npm install

npm start

```

### Para subir al repositorio


```
npm run build

npm deploy:gh

```



## Trucos
Existen varios atajos de teclado que nos facilitan las cosas:
* **esc**: nos muestra todas las transparencias
* **?**: nos muestra estos atajos de teclado
* **s**: nos abre una nueva ventana con la transparencia actual, la siguiente, las notas y un reloj
* **m**: como hemos añadido el plugin de menú, nos abre el menú

### Imprimir

``` 
npm run create:pdf
```

* [descargar PDF](https://irontec.github.io/slides-pfsense/pfsense-slides.pdf)
