# tutorial Markdown basico
![logo de markdown](https://automatismosmundo.com/wp-content/uploads/2020/08/Foto-Portada-Markdown820x315.jpg "logo de markdown")
## ¿ Qué es markdown?

> Markdown es un lenguaje de marcado que facilita la aplicación de formato a un texto empleando una serie de caracteres de una forma especial. Originalmente, fue pensado para elaborar textos destinados a la web con más rapidez y sencillez que si estuviéramos empleando directamente HTML. Sin embargo, su utilidad no se limita solo a la web; podemos emplearlo para cualquier tipo de texto, independientemente de su destino.

## ¿Por qué usar mardowns? 

MarkDown es un lenguaje que brinda diversas facilidades, entre ellas destacan 

* **Facilidades de uso:** su sintaxis de escritura es altamente simple por que aprenderla es algo que toma extremadamente poco tiempo.

* **Su velocidad:** escribir en markdown es muy rápido debido a lo fácil y simple que es su sintaxis 

* **Su flexibilidad:** markdown es compatible con casi cualquier plataforma de edición de texto y con una gran cantidad de entornos de desarrollo.

Por estos y otros motivos mardown se presenta como la opción mas sencilla confiable a la hora de crear archivos readme siendo compatible con una infinidad de entornos y sitios web, favoreciendo la creación de blogs, tutoriales, repositorios entre otros.

---
## ¿Donde puedo usar markdown?

Como se mencionó anteriormente mardown es compatible con una gran variedad de entornos de edición de texto entre los que destacan:

**[Stckeit:](https://stackedit.io/)** es quisa la opción mas amigable para aquellas personas que no son muy afines a los lenguajes de texto.

**[Visual studio code:](https://code.visualstudio.com/)** Es uno de los entornos de desarrollo mas conocidos y usados a nivel mundial, este brinda acceso al uso y previsualización de markdown en su forma estándar.

**[Atom:](https://atom-editor.cc/)** dentro de la comunidad de programadores es muy popular y brinda opciones de configurar para el uso de markdown.

**[Typora:](https://typora.io/)** es simple y libre de distracciones visuales, brinda acceso a previsualizar el texto y la gran mayoría de las funciones de markdown

**[Gooble colab:](https://colab.google/)** es un entorno de desarrollo web que ha cobrado gran popularidad entre la comunidad de la programación, debido a que permite el ahorro de recursos del equipo y tiene acceso a las funciones de markdown.

También cabe mencionar a [github](https://github.com/) que es un entorno web el cual nos permite editar texto en línea y que cuante con el mardown estándar y algunas funciones propias de este sitio para markdown 

---

## Sintaxis para markdown

### Formato itálica

Para escribir en italica lo que haremos será colocar el texto al que deseamos aplicar este formato ente astericos `*asi se estcribe en italica*` 

:*asi se estcribe en italica*

---

### Formato en negritas 

Para escribir en negritas lo que haremos será colocar el texto al que deseamos aplicar este formato ente astericos doble `**asi se estcribe en negrita**` 

:*asi se estcribe en negrita*

---

### texto tachado 

Para escribir un texto tachado lo que haremos será colocar el texto al que deseamos aplicar este formato ente dbles guiones omdulados `~~asi se tacha un texto~~` 

~~asi se tacha un texto~~

---
### Para agregar links entre lineas 

se va a escribir la descripción entre corchetes y al lado se le va a agregar la dirección url entre parentesis asi `[sorpresa](https://www.youtube.com/watch?v=_e9yMqmXWo0)`

[sorpresa](https://www.youtube.com/watch?v=_e9yMqmXWo0)

---

### agregar imagenes

se va a escribir primero un signo de excamación al comiezo luego la descripción entre corchetes y al lado se le va a agregar la dirección url de la imagen entre parentesis asi `![Github](https://www.kindpng.com/picc/m/128-1280192_github-logo-png-github-png-transparent-png.png)`

![Github](https://www.kindpng.com/picc/m/128-1280192_github-logo-png-github-png-transparent-png.png)

----
### agregar imagenes mas un link

se va a escribir primero un signo de excamación al comiezo luego la descripción entre corchetes y al lado se le va a agregar la dirección url de la imagen entre parentesis y al lado la direccion url de la pagina tambien entre parentesis asi `![Github](https://www.kindpng.com/picc/m/128-1280192_github-logo-png-github-png-transparent-png.png)](https://github.com/)]`

![Github](https://www.kindpng.com/picc/m/128-1280192_github-logo-png-github-png-transparent-png.png)(https://github.com/)

---

### salto de linea 
esta seccion es ta sencilla como dar un doble enter, no hay mucho que explicar respecto a esto 

---

### listas no ordenadas 
Para contruirlas se coloca un asterisco antes del elemento que se deseea colocar en la lista es importante usar un espacio entre el asterisco y el elemento asi:
``` 
* tema1
* tema2
* tema3 
```

* tema1
* tema2
* tema3 

---

### listas ordenadas 
Para contruirlas se coloca un número seguido de un punto antes del elemento que se deseea colocar en la lista es importante usar un espacio entre el numero con el punto y el elemento asi:
``` 
1. tema1
2. tema2
3. tema3 
```

1. tema1
2. tema2
3. tema3 

---

### listas combinadas 

Se usan las misas reglas de los puntos anteriores la unica diferencia es que estas se utilizan para hacer listas dentro de otras listas creando un lista ordenada y debajo dandole a tap para posteriormente empezar una lista desordenada asi: 

``` 
1. tema1
    * sub1
    * sub2
```

1. tema1
    * sub1
    * sub2

---

### citas 

se crea usando el signo de mayor que de la siguiente manera:

`> carpe diem `

> carpe diem

---

### insertar lineas de codigo

se va a colocar la linea de codigo que se desee insertar entre apostrofes 
```
`print(hello world)`
```
`print(hello world)`

---

### bloque de codigo

![alt text](<Screenshot 2024-03-22 154100.png>)


 ```python
import random
for i in range(10):
    x = random.choice([1,2,3])
    print(x)
 ```
 ---

 ### Encabezados

`#, ##, ###, ####, #####, ######` (van desde h1  hasta h6)

----

### tablas 

las tablas se crean entre barras del siguiente modo:
```
|elemento1|elemento2|elemento3|
|----|----|----|
|a|b|c|
|a|b|c|
```
|elemento1|elemento2|elemento3|
|----|----|----|
|a|b|c|
|a|b|c|

----
### comandos adionales de github
markdown contiene algunas configuraciones propias de github que para ser visibles en otros editores de texto tienen que ser vinculados a la cuenta de github las mismas son detallas en este video de youtube [markdowun para principiantes](https://www.youtube.com/watch?v=oxaH9CFpeEE)

----