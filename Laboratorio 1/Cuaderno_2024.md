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

$\frac{d \vec{\ L}}{dt} = \vec{\tau}$

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

$\ddot{\theta} + \frac{d \kappa }{I}. \kappa . \theta = 0$

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

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Fecha: Miercoles, 05/04/2024

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
- [x] Medición de dicroismo
- [x] Espectros de absorción
- [x] Birrefringencia
- [ ] Otro objetivo (si no se completó)

### Objetivos para el Próximo Día 🎯
[Establece los objetivos que planeas alcanzar en el próximo día de trabajo, considerando los experimentos a realizar.]

### Resultados 📊
[Registra los resultados obtenidos durante los experimentos, incluyendo gráficos, datos numéricos, y cualquier observación relevante.]

### Problemas y Desafíos 🚧
[Cualquier problema o desafío que hayas enfrentado durante el día y cómo lo resolviste. Esto podría incluir dificultades técnicas, errores en las mediciones, etc.]

### Conclusiones 🧾
[Conclusiones y observaciones importantes del día en relación a los experimentos realizados. Puedes discutir tendencias, patrones, o resultados inesperados.]

### Tareas Pendientes 📌
[Tareas que debes realizar en el próximo día de trabajo para avanzar en tus investigaciones o experimentos.]

### Recursos 📚
[Lista de recursos, referencias, equipos y documentos utilizados durante el día, incluyendo manuales, libros, y otros materiales de referencia.]

### Notas Adicionales 🗒️
[Cualquier otra información relevante o notas adicionales que quieras incluir.]

---

**Firma del Investigador:** ___________________________   **Fecha:** [Fecha] 🖋️

