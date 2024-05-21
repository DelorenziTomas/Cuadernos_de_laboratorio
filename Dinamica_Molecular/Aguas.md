# Registro de Laboratorio - Dinámica Molecular - Aguas con iones alcalinoterreos 🔬
---

## Viernes, 10/05/2024 📆
---

### Información General
- **Fecha:** Viernes, 10/05/2024 📆
- **Investigador:** Tomás Delorenzi 👨‍🔬
- **Molécula:** Agua SPC/E 🧪
- **Objetivo del Día:** Establecer el rumbo de la investigación. 🎯

### Resumen del Día 📝
Luego de la asunción como Consejero Directivo se tuvo una charla de aproximadamente 1 hora de duración en la que se estableció que vamos a seguir estudiando.

### Modificaciones y Avances Realizados 🛠️
Entendemos que el agua será el solvente sobre el que se va a tirar un modelo de molécula de ADN. Por eso la relevancia que tiene estudiar el fondo y cómo se estructuran las moléculas de agua cuando se encuentran con la presencia de algún ion alcalinotérreo a distinta concentración.

### Objetivos Cumplidos 🏆
- [x] Se establecieron objetivos claros de cómo va a seguir las investigaciones.
- [ ] Junto con Francisco Manuel Díaz Torres quedamos en ver qué ion iba a estudiar cada uno.
  
### Objetivos del trabajo 🎯
Para distintas concentraciones (dilución infinita, 1 mM y 10 mM) buscamos medir los siguientes parámetros:

- **G(r):**
- **Número de hidratación:**
- **Puentes de hidrógeno:** 
- **Radio de hidratación:**
- **Coeficiente de difusión:**

### Resultados 📊
Una coordinación entre la directora del grupo y los integrantes del grupo.

### Problemas y Desafíos 🚧
- **A resolver:** No sé si tengo todavía instalado Linux en mi notebook MSI. Consecuentemente no sé si tengo instalado GROMACS en mi notebook.

### Conclusiones 🧾
Hoy fueron los inicios de un estudio que vamos a tratar de llevar a la 109RAFA.

### Tareas Pendientes 📌
- [ ] Ponerme de acuerdo con Francisco en qué iones usará cada uno.
- [ ] Verificar si tengo instalado o no Linux y GROMACS.
- [ ] Hacer las cuentas para la caja de simulación tanto para las distintas concentraciones como para la cantidad de moléculas que voy a poner dentro de la caja de simulación.

### Recursos 📚
Se adjunta una imagen de lo que fue el día.
![WhatsApp Image 2024-05-10 at 16 12 56](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/24de681d-5808-45a1-8fa4-e0d3ee970012)


### Notas Adicionales 🗒️
Nada que agregar.

---

**Firma del Investigador:** Delorenzi, Tomás   **Redacción:** [12/05/2024] 🖋️

---

---

## Lunes, 13/05/2024 📆

---

### Información General
- **Fecha:** Lunes, 13/05/2024 📆
- **Investigador:** Tomás Delorenzi 👨‍🔬
- **Molécula:** Agua SPC/E 🧪
- **Objetivo del Día:** Buscar informacion sobre estos iones. 🎯

### Informacion obtenida 📝

Haciendo un relevamiento de la informacion de trabajos hechos en MD tenemos que un berenil en solucion acuosa a distinta concentraciones de iones. Con el objetivo de que la estadistica sea lo mas fiable buscamos una cantidad de moleculas de agua optima. No muchas (ya que si son demasiados vamos a gastar mucho almacenamiento y tambien mucho tiempo de computo) ni tampoco pocas (ya que no seria uno no podria fiarse de las mediciones estadisticas sobre el sistema). Anteriormente estuve trabajando con 2150 moleculas de agua y una moleculas de Berenil (formula: C14H15N7) a distintas concentraciones de iones. 

- **Que es un ion alcalinoterreo?** Un ion alcalinotérreo es un ion con una carga positiva de +2 que pertenece al grupo 2 de la tabla periódica de los elementos. Los elementos de este grupo son berilio (Be), magnesio (Mg), calcio (Ca), estroncio (Sr), bario (Ba) y radio (Ra). Estos elementos tienen dos electrones en su capa de valencia y tienden a formar iones con una configuración electrónica similar a la de los gases nobles más cercanos en la tabla periódica, perdiendo esos dos electrones para alcanzar una configuración estable. Los compuestos que contienen estos iones a menudo tienen propiedades similares y se pueden encontrar en minerales y en la estructura de muchos organismos vivos. 

https://es.wikipedia.org/wiki/Alcalinot%C3%A9rreos#:~:text=Los%20metales%20alcalinot%C3%A9rreos%20son%20un,tiempo%20de%20vida%20media%20corto.

- **Hay algun trabajo presentado sobre estos iones?**

Encontre este link, de un trabajo presentado en la revista Physical Chemistry Chemical Physics. ES ORO ESTE TRABAJO.

Molecular Dynamics Simulations of Alkaline Earth Metal Ions Binding to DNA Reveal Ion Size and Hydration Effects

Un trabajo realizado en GROMACS con informacion parecida a la que necesitamos.

Lo guardaste en C:\simu\Dinamica_Molecular\IonesAlcalinoterreos

https://www.osti.gov/servlets/purl/1803534

### Objetivos Cumplidos 🏆
- [x] Buscar informacion sobre los iones alcalinoterreos.
- [x] Encontrar algun trabajo similar. 

### Tareas Pendientes 📌
- [ ] Verificar si existen los iones alcalinoterreos en campo de fuerzas AMBER99.
- [ ] Preguntar a Griselda si usar la misma cantidad de moleculas de agua que el trabajo realizado con el Berenil es una buena estimacion.
- [ ] Revisar los articulos referenciados del trabajo encontrado
- [ ] Ponerse de acuerdo con Francisco sobre cuantas aguas vamos a usar.
- [ ] Ponerse de acuerdo con Francisco sobre cuales iones va a usar cada uno.

### Resultados 📊

Hice un fructifero relevamiento de informacion util a posteriori.

### Recursos 📚
Se adjunta una imagen de la topologia del Berenil en solucion acuosa con una concentracion 0.1M de iones.

![Captura de pantalla 2024-05-13 105214](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/30508e54-c1c1-4090-bf27-b20bbe2e1a3c)

### Notas Adicionales 🗒️


Sacar la cuenta de cuanto disminuye la cantidad de moleculas de agua cuando uno tenga concentraciones distintas de cada ion. 

Se anexa la imagen con el calculo de la cantidades de agua. 

![WhatsApp Image 2024-05-13 at 19 05 23](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/a3c74ddf-4b95-4d86-89fe-2c8ff8b21130)

Vamos a arrancar con una concentracion de 0.1M a 0.3M a 0.5M a 0.8M a 1.0M
Griselda recomienda trabajar entre las 3000 aguas. A las concentraciones mas grandes (1.0M) se puede trabajar con 1000 aguas y conviene hacer corridas separadas de 10ns en vez de una corrida entera de 100ns (ventajas podes empezar mediciones estimativas aun con la g(r)).

---

**Firma del Investigador:** Delorenzi, Tomás   **Redacción:** [13/05/2024] 🖋️

---

---
## Sabado, 18/05/2024 📆
---

### Información General
- **Fecha:** Sabado, 18/05/2024 📆
- **Investigador:** Tomás Delorenzi 👨‍🔬
- **Molécula:** Agua SPC/E 🧪
- **Objetivo del Día:** Volver a tomar contacto con GROMACS. 🎯

### Resumen del Día 📝
Me pongo a leer distintos tutoriales para ir volviendo a interiorizarme.

### Modificaciones y Avances Realizados 🛠️

Empiezo a completar un tutorial que encontre en Google (https://group.miletic.net/en/tutorials/gromacs/1-tip4pew-water/) el problema es que usa un modelo de agua que no es el que nosotros tenemos planeado utilizar. 

Indagando un poco mas encontre el siguiente trabajo **A systematic study of water models for molecular simulation: Derivation of water models optimized for use with a reaction field** Link: https://pure.rug.nl/ws/portalfiles/portal/71287254/1.476482.pdf que hace una comparativa entre distintos tipos de modelos de aguas.

### Notas Adicionales 🗒️
Nada que agregar.

---
**Firma del Investigador:** Delorenzi, Tomás   **Redacción:** [18/05/2024] 🖋️
---


---
## Martes, 21/05/2024 📆
---

### Información General
- **Fecha:** Sabado, 18/05/2024 📆
- **Investigador:** Tomás Delorenzi 👨‍🔬
- **Molécula:** Agua SPC/E 🧪
- **Objetivo del Día:** Volver a tomar contacto con GROMACS. 🎯

### Resumen del Día 📝



### Modificaciones y Avances Realizados 🛠️

Encontre un muy buen articulo parecido a lo que se quiere hacer ("C:\simu\Dinamica_Molecular\IonesAlcalinoterreos\2020A Molecular Dynamics Simulations of Alkaline Earth Metal Ions.pdf"). Queda como pendiente ponerte a leerlo.

Me puse a ver https://www.youtube.com/watch?v=MWafKFVgFTU tutorial de GROMACS para volver a tomar vuelo. 

Hablando con Mario G. Campo me soluciono varios problemas y me agrego algunas preguntas en el caso que alguien quiera estudiar el agua.
- [x]  ¿Cual es el mejor modelo de agua para hacer lo que se quiere hacer?
- [x]  ¿Hay modelos de iones desarrollados?

Mario me compartio y mostro commo llenar una caja de aguas (C:\simu\Dinamica_Molecular\IonesAlcalinoterreos\Mario\historial.txt). 

Tambien me aconsejo ir jugando con las dimensiones de las cajas para que con el comando "gmx solvate" vaya llenando con la cantidad de aguas necesarias que necesito para tener la concentracion deseada.

Me recomendo Griselda que primero haga la minimizacion, la estabilizacion y luego con "gmx genion" agregue la cantidad de iones alcalinoterreos (Ca o Mg) necesarios.

### Objetivos Cumplidos 🏆

- [x] Poder crear las distintas cajas para las distintas concentraciones deseadas.

### Resultados 📊

Una jornada exitosa en la que pude encontrar teoria reelevante, aunque no aun sobre la competencia (competencia = cual ion desplaza a cual) de iones. Tambien una fructifera charla con Mario que me ayudo compartiendome sus archivos .gro y sus .top para que pueda seguir adelante. 

### Problemas y Desafíos 🚧

Ninguno, todavia.

### Conclusiones 🧾

Una buena jornada.

### Tareas Pendientes 📌

- [ ] Hacer las corridas para cualquiera de los iones
- [ ] Crear un programita que calcule la cantidad exactas de aguas que tenemos que poner para una concentracion dada.

### Recursos 📚

Ninguno

### Notas Adicionales 🗒️
Nada que agregar.

---
**Firma del Investigador:** Delorenzi, Tomás   **Redacción:** [21/05/2024] 🖋️
---
