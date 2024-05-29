# Registro de Laboratorio - Laboratorio 1 - 2024 📆

# Pendulo de Torsión
### Integrantes:
- [x] Tomás Delorenzi
- [x] Alba Belén Muñiz
- [x] Ximena Vanessa Irazabal

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Fecha: Miercoles, 27/03/2024

### Información General
- **Investigador que redacta:**  Tomás Delorenzi👨‍🔬
- **Materia:** Laboratorio I 🧪
- **Teoria:** Elasticidad: Modulo de torsión

### Resumen del Día 📝
Durante la clase se desarrollo la teoria del modelo del movimiento de un solido rigido.

### Desarrollo 🛠️

#### Ecuacion de movimiento de un solido rigido.

$\frac{d \vec{\  L}}{dt} = \vec{\tau}$

Uno de los puntos al cual se refiere el torque es al centro de masa o a un punto externo de referencia en el laboratorio.

Si gira alrededor de uno de los ejes principales uno puede escribir.

$\vec{\ L} = I. \vec{\ \omega }$

Asi: 

$\frac{d I. \vec{\ \omega }}{dt} = \vec{\tau}$

$I. \frac{d  \vec{\ \omega }}{dt} = \vec{\tau}$

Definiendo la aceleración angular como:

$\vec{\alpha} = \frac{d \vec{\omega}}{dt}$

$I. \vec{\alpha} = \vec{\tau}$

El eje de giro lo vamos a poner alrededor de uno de los ejes principales. 
Una de las formas para medirla es el **pendulo de torsión**:

![WhatsApp Image 2024-05-17 at 15 50 59](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/df2e91a2-f6e2-4022-9ff7-9c1896e4f919)

Si $\theta < < $ podemos escribir:

$\tau = - \kappa . \theta$

Como la Ley de Hooke para la torsion.
¿Donde se cumple esta linealidad? Veamos que dicen las ecuaciones 

$I. \frac{d \omega }{dt} = \tau = -\kappa . \theta$

Podemos escribir lo siguiente:

$\frac{d \omega }{dt} = \frac{d^{2} \theta }{dt^{2}} = \ddot{\theta}$

Asi: 
$I. \ddot{\theta} = -\kappa . \theta$

$I. \ddot{\theta} + \kappa . \theta = 0$

$\ddot{\theta} + \frac{ \kappa }{I}. \theta = 0$

Buscamos un armonico simple, para tener un periodo que se repita.
Hay que tener en cuentalas condiciones del laboratorio

Tales como: 
- [x] Temperatura (se dilata, se contrae, etc).
- [x] Corrientes de aire.
- [x] Otras.

De la ecuacion diferencial tenemos que:

$\omega^{2} = \frac{I}{\kappa}$

$\omega = \frac{2 \pi }{T}$

con periodo $T$. El periodo es cuando se pasa por la misma posicion y en el mismo sentido.
Asi si las combinamos estas dos ultimas ecuaciones llegamos a la siguiente ecuacion.

$T = 2.\pi \sqrt{\frac{I}{\kappa}}$

Haces 10 oscilaciones, lo paras, lo volves a poner a andar para un angulo dado.

![WhatsApp Image 2024-05-17 at 16 14 29](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/a5852750-1eff-4f6d-94df-7b6a88aaacb3)

#### Cizallamiento

El cizallamiento es un término utilizado en mecánica de materiales y en ingeniería para describir un tipo de deformación que ocurre cuando fuerzas opuestas se aplican paralelamente y en direcciones opuestas sobre un objeto. Estas fuerzas generan un esfuerzo cortante en el material, causando que sus capas internas se deslicen unas sobre otras.

###### Detalles Clave sobre el Cizallamiento

###### Esfuerzo Cortante
- **Definición**: El esfuerzo cortante es la fuerza por unidad de área que actúa paralelamente a la superficie de un material. Se mide en pascales (Pa) o en unidades equivalentes.
- **Fórmula**: 
  $\[
  \tau = \frac{F}{A}
  \]$
  donde $\( \tau \)$ es el esfuerzo cortante, $\( F \)$ es la fuerza aplicada, y $\( A \)$ es el área sobre la cual actúa la fuerza.

###### Deformación por Cizallamiento
- La deformación ocurre cuando las capas internas de un material se deslizan unas sobre otras debido a la aplicación de fuerzas paralelas.
- La magnitud de esta deformación se mide en términos del ángulo de deformación, usualmente en radianes.

###### Aplicaciones Prácticas
- **Ingeniería Estructural**: En la construcción de edificios y puentes, el cizallamiento es una consideración crucial para garantizar que las estructuras puedan resistir fuerzas laterales, como las causadas por el viento o terremotos.
- **Materiales de Ingeniería**: En el diseño de componentes como ejes, vigas y pernos, es vital entender cómo estos materiales se comportarán bajo cargas cortantes para evitar fallas.

###### Ejemplos Comunes
- **Corte con Tijeras**: Al cortar papel con tijeras, las hojas de las tijeras aplican fuerzas en direcciones opuestas a lo largo del papel, creando un cizallamiento que corta el material.
- **Deslizamiento de Capas Geológicas**: En geología, el cizallamiento puede describir el movimiento de fallas y deslizamientos de tierra donde capas de roca se desplazan lateralmente unas sobre otras.

###### Representación Gráfica del Cizallamiento

Para entender visualmente el cizallamiento, imagina un libro con varias páginas. Si empujas la parte superior del libro hacia un lado mientras sostienes la parte inferior fija, las páginas intermedias se deslizarán unas sobre otras. Este deslizamiento representa la deformación por cizallamiento.

###### Importancia en Diseño e Ingeniería

En el diseño y análisis de estructuras y componentes mecánicos, es crucial calcular y considerar el esfuerzo cortante para garantizar la seguridad y durabilidad de los materiales utilizados. Las fallas por cizallamiento pueden ser catastróficas, por lo que los ingenieros deben asegurarse de que los materiales y las uniones sean capaces de soportar las cargas previstas.

En resumen, el cizallamiento es un concepto fundamental en la mecánica de materiales que describe cómo las fuerzas paralelas causan deslizamientos internos dentro de un material, afectando su integridad estructural y funcional.

![WhatsApp Image 2024-05-17 at 16 23 46](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/3ee04c91-d2b9-4b32-ba45-2047b541e356)

$d_{c}= \frac{\Delta x}{L}$

$\frac{\Delta x}{L}=tg(\varphi)=d_{c}$

Para deformaciones pequeñas:

$\varphi< < tg(\varphi)\approx sen(\varphi)\simeq \varphi$

$$d_{c} = \varphi$

###### Modulo de cizalladura

$G=\frac{T_{c}}{d_{c}}$

Entonces para $\varphi< <$ tenemos lo siguiente:
$T_{c} \simeq G. \varphi$

donde $G$ varia de un material a otro, es una caracteristica de cada material.

Existe ya un modelo, veamos:

### Modelo para una barra cilindrica de radio R y longitud L

![WhatsApp Image 2024-05-17 at 16 46 53](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/5e57d221-a549-4682-9c73-425d31e8ad4f)

Suponemos que el cilindro de radio $R$ esta formado por infinitas laminas concentricas de espesor $dr$ y radio $r$ . El torque de la fuerza $dF$ a la distancia $r$ es de $d\tau = r .dF$

Si sumamos el efecto sobre todas las laminas 

$\tau = \int_{0}^{R}r .dF =\frac{2\pi \theta G}{L}\int_{0}^{R}r^{3} .dr = \frac{2\pi \theta G}{L}\frac{R^{4}}{4}$

$\tau = \frac{\pi \theta G R^{4}}{2L}$

$\tau = \kappa \theta$

$\kappa \theta=\frac{\pi \theta G R^{4}}{2L}$

Donde $\kappa$ **coeficiente de torsion del alambre**, $G$ es el modulo de torsion del material, $R$ es el radio del alambre, $L$ es la longitud del alambre y $d$ es el diametro del alambre. 

$\kappa=\frac{\pi G R^{4}}{2L}$

Como $d=2R=> d^{4}=16R^{4}$

$\kappa = \frac{4\pi^{2}I}{T^{2}}$

$\kappa = \frac{\pi G d^{4}}{32L}$

Sabiendo $\kappa$ podemos conocer el modulo de torsion G.


### Objetivos Cumplidos 🏆
- [x] Entendimos la teoria.
- [x] Entendimos que era lo que habia que calcular.

### Objetivos para el Próximo Día 🎯
Empezar a diseñar la pieza en el Freecad. Software para diseñar objetos 3D y mandarlos a imprimir (Kura Craft, archivos.stl) a la impresora de GFSG.

### Resultados 📊
Nulos.

### Problemas y Desafíos 🚧
- [x] ¿Como calcular el momento de inercia de un objeto compuesto? Buscar en la teoria de Mecanica Clasica
- [x] ¿El objeto tiene que estar necesariamente agarrado del centro de masa? No, necesariamente tiene que estar en el punto de agarre, pero si en el mismo eje de rotación.
- [x] ¿Como lo vamos a diseñar? Todavia no sabemos, no sabemos que tipos de pesas vamos a usar para los distintos momentos de inercia que necesitamos.

### Conclusiones 🧾

Vimos el objetivo final del proyecto.

### Tareas Pendientes 📌
- [x] Interiorizarnos con el Freecad.
- [x] Ponernos de acuerdo con el set-up experimental.
- [x] Que pesas vamos a utilizar? Utilizaremos imanes? (idea de Alba, descartada por Griselda, no sabiamos las lineas de campo) 

### Recursos 📚

Preguntar a Griselda de donde saco la teoria.

### Notas Adicionales 🗒️
Nada que agregar.
---

**Firma del Investigador:** Tomás Delorenzi   **Fecha de redación:** 17/05/2024 🖋️


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Fecha: Viernes, 05/04/2024

### Información General
- **Investigador que redacta:**  Tomás Delorenzi👨‍🔬
- **Materia:** Laboratorio I 🧪
- **Equipos Utilizados:** Calibre (precision: 0.2 mm). Regla (precision: 0.1 cm) 🧲

### Resumen del Día 📝
Hicimos un primer modelo del dispositivo experimental. Tambien se tomaron las primeras mediciones.

### Modificaciones y Avances Realizados 🛠️
Comprendimos la teoria y vimos cual era el interes final del trabajo que vamos a llevar a cabo. 
Se adjuntan las imagenes del primer set up experimental que pensamos.

(insertar imagenes)

**Objetivo final:** Poder calcular el módulo de torsión para diversos alambres.


### Objetivos Cumplidos 🏆
- [x] Entender la teoria (limitaciones del modelo, que es lo que tenemos que hacer, etcetc).
- [x] Tomar las primeras mediciones.
- [x] Esquematizar un modelo inicial

### Objetivos para el Próximo Día 🎯
- [ ] Empezar a diseñar una pieza para mandar a la impresora 3D.
- [ ] Consultar a Luis Pugnaloni si podemos utilizar la impresora 3D del GFSG
- [ ] Ponernos de acuerdo en que modelo vamos a desarrollar.

### Resultados 📊
Barra (cada unx fue efectuando las mediciones pertinentes):
**Diametros:**

 - $D_{1}=(3.90\pm 0.2)mm$ Tomas
 - $D_{1}=(4.00\pm 0.2)mm$ Xime
 - $D_{1}=(4.10\pm 0.2)mm$ Alba

 - $D_{2}=(3.00\pm 0.2)mm$ Tomas
 - $D_{2}=(3.00\pm 0.2)mm$ Xime
 - $D_{2}=(3.00\pm 0.2)mm$ Alba

 - $D_{3}=(2.26\pm 0.2)mm$ Tomas
 - $D_{3}=(2.36\pm 0.2)mm$ Xime
 - $D_{3}=(2.28\pm 0.2)mm$ Alba

 - $D_{4}=(2.58\pm 0.2)mm$ Tomas
 - $D_{4}=(2.60\pm 0.2)mm$ Xime
 - $D_{4}=(2.56\pm 0.2)mm$ Alba

**Longitud:**

 - $L_{1}=(27.0 \pm 0.1)cm$ Tomas
 - $L_{1}=(26.9 \pm 0.1)cm$ Xime
 - $L_{1}=(26.9 \pm 0.1)cm$ Alba

 - $L_{2}=(11.38 \pm 0.1)cm$ Tomas
 - $L_{2}=(11.38 \pm 0.1)cm$ Xime
 - $L_{2}=(8.6 \pm 0.1)cm$ Alba

 - $L_{3}=(2.06 \pm 0.1)cm$ Tomas
 - $L_{3}=(2.06 \pm 0.1)cm$ Xime
 - $L_{3}=(1.98 \pm 0.1)cm$ Alba

### Problemas y Desafíos 🚧
Todavia nos quedan muchos detalles del diseño de la impresora 3D que ajustar como por ejemplo como vamos a hacer que la figura conster de distintos momentos de inercia. 

Todavia que software vamos a utilizar para diseñar la pieza. Tenemos que preguntarle a los que saben.

Tambien vamos a tener que familiarizarnos con el programa de diseño.

### Conclusiones del dia🧾
Establecimos objetivos claros y entendimos cuales son nuestras limitaciones.

### Tareas Pendientes 📌
- [ ] Empezar a diseñar una pieza para mandar a la impresora 3D.
- [ ] Consultar a Luis Pugnaloni si podemos utilizar la impresora 3D del GFSG
- [ ] Ponernos de acuerdo en que modelo vamos a desarrollar.

### Recursos 📚
No usamos ningun libro de teoria.

### Notas Adicionales 🗒️
Notamos que tomamos mediciones distintas.


---

**Firma:** Delorenzi, Tomás   **Fecha de redacción:** 16/05/2024 🖋️
---

---
## Fecha: Viernes, 26/04/2024

### Información General

- **Investigador que redacta:**  Tomás Delorenzi👨‍🔬
- **Materia:** Laboratorio I 🧪
- **Equipos Utilizados:** Lapiz, computadora y mente 🧲

### Resumen del Día 📝

Seguimos avanzando con el modelo del sistema. 

### Modificaciones y Avances Realizados 🛠️

Sorteamos varios problemas maquinando como podiamos hacer que nuestra figura tenga varios momentos de inercia distintos. De mismo modo que si nuestra figura iba a estar sostenida tanto de arriba como de abajo. 

Concluimos que en principio ibamos a pensar la figura de tal manera como para que quede solo sostenido desde la parte de arriba. Como si quedase colgado.

El modelo debe tener simetria en el eje *x* y tambien en el eje *y*. En el eje *z*, el eje de rotacion, debe estar NECESARIAMENTE sobre el eje z.

![WhatsApp Image 2024-04-27 at 18 16 47](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/e48fff5f-b175-4d34-8076-891f19e4797c)

![WhatsApp Image 2024-04-27 at 18 15 46](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/d90a566d-5e27-478f-924d-d6270f256b14)

### Objetivos Cumplidos 🏆
- [x] Ponernos de acuerdo en como medianamente va a ser el primer modelo que vamos a empezar a diseñar.
- [ ] Empezar a diseñarlo en el Freecad.

### Objetivos para el Próximo Día 🎯

- [ ] Empezar a diseñarlo en Freecad.


### Resultados 📊

Una jornada exitosa en la que pensamos de que manera podemos tener una figura 3D con distintos momentos de inercia

### Problemas y Desafíos 🚧

Todavia no sabemos usar Freecad

### Conclusiones 🧾

Una jornada pensar los posibles problemas que podemos llegar a tener con los discos duros que rotan, que se desplacen, que roten uno con respoecto de otro cuando gire la figura entera.

### Tareas Pendientes 📌

Entender como se usa freecad.

### Recursos 📚

https://www.youtube.com/watch?v=U0rO1oU4Akg

### Notas Adicionales 🗒️

Ninguna


---

**Firma del Investigador:** Delorenzi, Tomás  **Fecha de redacción:** 20/05/2024 🖋️

---

---
## Fecha: Miercoles, 01/05/2024

### Información General
- **Investigador que redacta:**  Tomás Delorenzi👨‍🔬
- **Materia:** Laboratorio I 🧪
- **Equipos Utilizados:** Calibre (precision: 0.2 mm). Regla (precision: 0.1 cm) 🧲

### Resumen del Día 📝
Fue feriado, no hicimos nada.


---

**Firma del Investigador:** Delorenzi, Tomás  **Fecha de redaccion:** 20/05/2024 🖋️

---

---
## Fecha: Viernes, 03/04/2024

### Información General
- **Investigador que redacta:**  Tomás Delorenzi👨‍🔬
- **Materia:** Laboratorio I 🧪
- **Equipos Utilizados:** Notebook, Calibre (precision 0.2 mm) 🧲

### Resumen del Día 📝
Sacamos las primeras mediciones de los discos duros, tambien empezamos a usar Freecad.

### Modificaciones y Avances Realizados 🛠️

Precisamos los tamaños de las pesas y los discos duros para hacer la pieza que se va a imprimir en la impresora 3D. Para contener los discos rigidos; puse eso para recalcar que solamente hicimos esa parte de la pieza.

Tambien aprendimos a usar Freecad, software para diseñar la figura.

A continuacion se van a anexar los bocetos de la figura.

### Objetivos Cumplidos 🏆
- [x] Tomar las primeras mediciones.
- [x] Empezar a aprender a usar Freecad.

### Objetivos para el Próximo Día 🎯
- [x] Terminar el diseño en el Freecad.
- [x] Ver cuanto tiempo toma hacer las primeras figuras en la impresora 3D para ver si es factible que podamos imprimirla dentro de los tiempos que podemos usar la impresora 3D

### Resultados 📊

Un jornada de aprendizaje e interiorizacion con el software de diseño 3D.

### Problemas y Desafíos 🚧

Entender como movernos a traves de la interfaz de manera mas fluida

### Conclusiones 🧾

Encontramos una muy buena herramienta en la recomendacion de Julian Montero.

### Tareas Pendientes 📌

Terminar la pieza donde quedan los discos duros.

### Recursos 📚
https://www.youtube.com/watch?v=U0rO1oU4Akg

### Notas Adicionales 🗒️
Nada que agregar.

---

**Firma del Investigador:** Delorenzi, Tomás.   **Fecha de redacción:** 20/05/2024 🖋️

---

---
## Fecha: Miercoles, 08/05/2024

### Información General

- **Investigador que redacta:**  Tomás Delorenzi👨‍🔬
- **Materia:** Laboratorio I 🧪
- **Equipos Utilizados:** Lapiz, computadora y mente 🧲

### Resumen del Día 📝

Seguimos avanzando con el modelo del sistema. 

### Modificaciones y Avances Realizados 🛠️

Comentario fuera de la materia: este dia vino la FAN (Fundacion Argentina de Nanotecnologia) a dar una charla para investigadores en el Consejo Superior. Tomás Delorenzi y Tomás Navarro Febre se quedaron en la biblioteca a seguir laburando. Ximena y Alba fueron invitadas a seguir laburando con todas las mediciones que habiamos tomado dias anteriores tambien en la biblioteca central. Los 4 trabajamos desde ahi ese dia. Este dia no fuimos al campo. 

El dia arranco cuando le mostre la figura que hicimos en clases anteriores a Tomás Navarro Febre y vimos en el software Cura KutterCraft cuanto tiempo nos iba a llevar imprimir la pieza que llevabamos diseñando en la impresora 3D del GFSG. Encontramos que el tiempo que llevaba imprimir la pieza excedia por mucho el tiempo que un alumno podia permanecer dentro del campo de enseñanza hasta que se vaya el ultimo colectivo del dia (la pieza tardaba alrededor de 1dia y 18horas) y la impresora no puede quedar funcionando sin que nadie este supervisandola. 

Asi arrancamos con Tomás Navarro Febre otra pieza que se pueda imprimir y que cumpla con todos los requisitos previamente descriptos en dias anteriores (momento de inercia variable, simetria en los ejes x e y, que los discos duros no roten cuando la pieza rote, etcetc). 

Despues de revisar las dimensiones de la pieza nos dimos cuenta que la figura se habia guardado con otras dimensiones. Por eso tardaba tanto en imprimirse. Se decidio volver a empezar de cero. Sin embargo esta vez con el conocimiento de como iba a ser la figura, ya con las mediciones pertinentes y con el modelo decidido. 

Se adjuntan imagenes de lo que fue este dia.

![WhatsApp Image 2024-05-20 at 16 08 31](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/73fdd495-4789-4561-bac8-085481e7e93c)

![WhatsApp Image 2024-05-20 at 16 08 30](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/3988eaed-f3cb-47b7-a746-b5a25224eb10)

Terminada la pieza principal dimos por finalizada la jornada. Estuvimos trabajando desde las 10am hasta las 5pm aproximadamente. En ese momento Francisco Manuel Diaz Torres asumia con consejero superior por eso nos quedamos trabajando en la biblioteca central.

### Objetivos Cumplidos 🏆

- [x] Terminar de diseñar, la pieza C, la pieza principal.

### Objetivos para el Próximo Día 🎯

- [ ] Seguir diseñando las demas piezas de nuestra figura.

### Resultados 📊

Una jornada exitosa en la que pudimos diseñar de manera completa la pieza C. De manera coordinada y eficaz trabajamos a la par aportando nuevas ideas y peleandonos con el software Freecad.

### Problemas y Desafíos 🚧

Entendimos la importancia de guardar correctamente los archivos con fecha del dia que se editaron. Tambien vimos que hay que asegurarse de que los archivos hayan sido guardados correctamente abriendolos otra vez para asegurarse que el archivo es correcto y no trabajar al pedo.

### Conclusiones 🧾

Una jornada laboriosa en la que nos dedicamos a diseñar la pieza principal. 

### Recursos 📚

Cura Kuttercraft:

https://www.kuttercraft.com/software

### Notas Adicionales 🗒️

Por primera vez dimos a entender a otra persona (fuera del grupo que esta avocado a esta tarea) que es lo que estamos haciendo y por qué estamos haciendo lo que estamos haciendo. En este caso fue a Tomás Navarro Febre.

---

**Firma del Investigador:** Delorenzi, Tomás  **Fecha de redacción:** 21/05/2024 🖋️

---

---
## Fecha: Viernes, 10/05/2024

### Información General

- **Investigador que redacta:**  Tomás Delorenzi👨‍🔬
- **Materia:** Laboratorio I 🧪
- **Equipos Utilizados:**  🧲

### Resumen del Día 📝

No se hizo nada.

### Modificaciones y Avances Realizados 🛠️

Asumimos como Consejeros Directivos. Ese dia no se hizo nada.
![WhatsApp Image 2024-05-21 at 11 12 59](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/f4105689-3b71-4524-beab-f52172e0e1c4)


### Objetivos Cumplidos 🏆

- [x] Nada

### Resultados 📊

Ninguno, fuimos consejeres.

### Problemas y Desafíos 🚧

Ninguno.

### Conclusiones 🧾

Ninguno.

### Tareas Pendientes 📌

Ninguno.

### Recursos 📚

Ninguno.

### Notas Adicionales 🗒️

Ninguno.

---

**Firma del Investigador:** Delorenzi, Tomás  **Fecha de redacción:** 29/05/2024 🖋️

---


---
## Fecha: Miercoles, 15/05/2024

### Información General

- **Investigador que redacta:**  Tomás Delorenzi👨‍🔬
- **Materia:** Laboratorio I 🧪
- **Equipos Utilizados:**  🧲

### Resumen del Día 📝

Este dia fue feriado por dia del docente universitario y nos juntamos en la casa de Alba a terminar de diseñar la pieza G y dejamos a medias tintas la pieza C
El apuro de tener las piezas ya diseñadas era para mandar a imprimir lo mas pronto posible,

### Objetivos Cumplidos 🏆

- [x] Diseñar la pieza G
- [x] Dejar la pieza C media completa

### Objetivos para el Próximo Día 🎯

- [ ] Terminar la pieza C

### Resultados 📊

Una jornada exitosa de laburo en el freecad.

### Problemas y Desafíos 🚧

No sabiamos que freecad contaba con angulos de euler para girar piezas


### Recursos 📚

![WhatsApp Image 2024-05-21 at 11 37 24](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/c347bd0e-49c1-47e4-8e01-6f7427c0d2a7)


---

**Firma del Investigador:** Delorenzi, Tomás  **Fecha de redacción:** 29/05/2024 🖋️

---


---
## Fecha: Jueves, 16/05/2024

### Información General

- **Investigador que redacta:**  Tomás Delorenzi👨‍🔬
- **Materia:** Laboratorio I 🧪
- **Equipos Utilizados:**  Impresora 3D 🧲

### Resumen del Día 📝

Mandamos a imprimir la primera pieza.

### Modificaciones y Avances Realizados 🛠️

Terminamos de diseñar las piezas y mandamos a imprimir la primera pieza, la pieza G, el agujero por donde pasa el tornillo nos quedo chico por lo tanto no pudimos hacer pasar el tornillo por este.

No solamente paso eso sino que tambien nos quedo chicas los lados del poligono de la cabeza del tornillo cuando aumentamos los lados 0.2mm nos olvidamos de aumentar el radio del agujero por donde pasa el tornillo. Tomas lo agarro con el taladro de pie en dias posteriores.

Tambien vimos cual era la dureza de las piezas impresas en 3D agarrandolas con el taladro de pie cerca del borde externo con distintas mechas del taladro de pie. 

Kevin nos comento que el taladro de pie tiene distintas velocidades y que disminuir las rpm ayuda a que el plastico PLA no se derrita. Cambiar la configuracion de correas ayuda a cambiar las rpm del taladro.

En la seccion recursos se adjuntan las imagenes de lo que fue el dia.

### Objetivos Cumplidos 🏆

- [x] Terminar de diseñar las piezas.
- [x]  Mandar a imprimir la pieza.

### Objetivos para el Próximo Día 🎯

- [ ] Agrandar el agujero

### Resultados 📊

Una jornada casi exitosa.

### Problemas y Desafíos 🚧

Imprimimos 2 veces mal la pieza G. Aun asi la pudimos recuperar.

### Conclusiones 🧾

Nos dimos cuenta de cuanto tarda en imprimir la impresora 3D las piezas, y verifcamos la dureza del plastico

### Recursos 📚

![WhatsApp Image 2024-05-21 at 11 15 36](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/c0f17e7a-a43e-422c-ae6a-2a4efba3f100)
![WhatsApp Image 2024-05-21 at 11 15 35 (1)](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/d441fe48-553c-495a-8402-2d99af303b4e)
![WhatsApp Image 2024-05-21 at 11 15 35 (2)](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/bbafb518-d1d8-4e64-a222-0c83c547f655)
![WhatsApp Image 2024-05-21 at 11 15 36 (1)](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/a26d9c53-9c7c-439d-9c37-a797c5ed7c3e)
![WhatsApp Image 2024-05-21 at 11 15 35](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/0f51eded-defc-4cfa-8e42-f48deaa265ac)
![WhatsApp Image 2024-05-20 at 22 04 34](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/e467d3a0-6ffb-4b37-920e-bad188de7961)


---

**Firma del Investigador:** Delorenzi, Tomás  **Fecha de redacción:** 29/05/2024 🖋️

---





---
## Fecha: Viernes, 17/05/2024

### Información General

- **Investigador que redacta:**  Tomás Delorenzi👨‍🔬
- **Materia:** Laboratorio I 🧪
- **Equipos Utilizados:**  Impresora 3D 🧲

### Resumen del Día 📝

Terminamos de diseñar las piezas que nos quedaron incompletas del dia anterior. Y seguimos imprimiendo las piezas que nos faltaban.

### Modificaciones y Avances Realizados 🛠️

Imprimimos exitosamente la pieza B, y tambien los palitos que se insertan en la pieza B para verificar que el agujero estaba bien y que restar 0.2mm deja espacio suficiente a la pieza para que encastre 

### Objetivos Cumplidos 🏆

- [x] Terminar de diseñar las piezas.
- [x]  Mandar a imprimir la pieza B

### Objetivos para el Próximo Día 🎯

- [ ] Agujeriar la pieza G. Asi nos ahorramos tiempo y podemos recuperar esas piezas ya impresas.

### Resultados 📊

Una jornada exitosa. 

### Problemas y Desafíos 🚧

Griselda nos aconsejo que consideremos sacar teoricamente el centro de masa de la pieza. Encontramos que en freecad podemos sacarlo el problema es que no sabemos donde esta el origen y desde donde esta calculandolo.

### Recursos 📚

https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/5dd5786e-75e7-4ee2-aa7d-ebb558e4cc13

![WhatsApp Image 2024-05-21 at 11 18 40](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/221dd716-63b9-48aa-980d-06eaca1bee02)

https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/a0791cee-0197-41cd-9b64-a90df00bedf4

![WhatsApp Image 2024-05-21 at 11 18 48](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/1382dd22-4fe2-4b70-969b-4edd5d9f69ea)
![WhatsApp Image 2024-05-21 at 11 18 48 (1)](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/b98b1b61-cbfb-45bb-b92f-d7124551d2c9)


---

**Firma del Investigador:** Delorenzi, Tomás  **Fecha de redacción:** 29/05/2024 🖋️

---
