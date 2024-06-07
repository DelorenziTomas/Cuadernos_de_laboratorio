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
- **Fecha:** Martes, 21/05/2024 📆
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

Acomode las carpetas para cada concentracion que vamos a trabajar. Tambien fui creando cajas de distintos tamaños pero con la cantidad de aguas justas.

Griselda me aconsejo crear mi propio modelo de aguas, Water Tomas, jugando con el Avogadro. Avogadro es un programa que permite al usuario crear moleculas agregando y sacando esferas. Tambien me recomendo que compare con el archivo.itp del agua spc-e de gromacs con mi Water Tomas. Que saque las cargas parciales con Mulliken de mis 3 atomos de mi molecula de agua, Water Tomas, y que agregue a una caja dada con el "gmx solvate" varias moleculas de aguas spc-e pero ahora que sean si de gromacs para ver como cambia. Se podria estudiar de mis dos moleculas de agua el coeficiente de difusion para ver como se va movimiendo en el solvente.

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

---
## Miercoles, 22/05/2024 📆
---

### Información General
- **Fecha:** Miercoles, 22/05/2024 📆
- **Investigador:** Tomás Delorenzi 👨‍🔬
- **Molécula:** Agua SPC/E 🧪
- **Objetivo del Día:** Empezar a hacer uso de Avogadro y armar mi modelo itp de la molecula de agua SPC/E. 🎯

### Resumen del Día 📝

Volvi a tomar contacto con el programa Avogadro. Cree mi archivo.itp de una molecula de agua.

### Modificaciones y Avances Realizados 🛠️

Empece mi dia hablando con Francisco Manuel Diaz Torres sobre como iban a hacer nuestras primeras concentracion y cuales iban a ser nuestros primeros numeros de aguas en las cajas. Empezaremos con simulaciones de 10ns e iremos aumentando el tiempo de la corrida en la medida de que el analisis exploratorio de los datos asi lo requieran. Griselda comento que con tener 10 o 11 iones ibamos a estar bien. Asi que habria que sacar la cuenta de cuantas aguas necesitaremos para cada concentracion.

Luego Griselda me recomendo que cree una molecula de agua en el Avogadro. Consulte el siguiente video [como usar Avogadro](https://www.youtube.com/watch?v=DgzRri0uH7E) para acordarme de como usar Avogadro. Este programa me permitio sacar paramatros valiosos para luego armar mi archivo.itp de mi primera molecula de agua (C:\simu\Dinamica_Molecular\IonesAlcalinoterreos\Water_Tomas\water_tomas.itp). Tambien me permitio generar una archivo.pdb (C:\simu\Dinamica_Molecular\IonesAlcalinoterreos\Water_Tomas\water_tomas.pdb) que con GROMACS luego lo puedo cambiar a un archivo.gro y tendre asi mi caja de simulacion.

En el armado de mi molecula de agua fui consultando "C:\simu\Dinamica_Molecular\IonesAlcalinoterreos\ffbondedAM99.itp" y "C:\simu\Dinamica_Molecular\IonesAlcalinoterreos\Data\atomtypesAM99.atp" para consultar los enlaces y el tipo de atomo de mi moleculas en el campo de fuerzas AMBER99. Los valores que no aparecian los consultaba en los parametros que me arrojaba el programa Avogadro. Este programa posee una opcion de optimizacion GAFF que, segun Griselda, era el mismo que AMBER. 

### Objetivos Cumplidos 🏆

- [x] Ponerme de nuevo de acuerdo con Griselda y Francisco con el desarrollo del estudio.
- [x] Aprender a usar Avogadro.
- [x] Crear mi archivo water_tomas.itp . 

### Resultados 📊

Una jornada exitosa.

### Problemas y Desafíos 🚧

Ninguno, todavia.

### Tareas Pendientes 📌

- [ ] Hacer las corridas para una caja en las que esten mis dos moleculas de agua.
- [ ] Crear un programita que calcule la cantidad exactas de aguas que tenemos que poner para una concentracion dada.

### Recursos 📚

Ninguno

### Notas Adicionales 🗒️
Nada que agregar.

---
**Firma del Investigador:** Delorenzi, Tomás   **Redacción:** [23/05/2024] 🖋️
---

---
## Jueves, 23/05/2024 📆
---

### Información General
- **Fecha:** Jueves, 23/05/2024 📆
- **Investigador:** Tomás Delorenzi 👨‍🔬
- **Molécula:** Agua SPC/E 🧪
- **Objetivo del Día:** Hacer una corrida de 10ns de mi molecula de agua water tomas. 🎯

### Resumen del Día 📝

Tratar de hacer mi primera corrida 10ns con Water_Tomas

### Modificaciones y Avances Realizados 🛠️

Trate de convertir el archivo PDB que consegui el dia de Miercoles (22/05/2024) y no me deja convertir el archivo a .gro. Sin embargo consultando a ChatGPT me recomendo lo siguiente:

- **Posibles soluciones:** Editar el archivo PDB
  
    Cambia los nombres de los residuos para que coincidan con lo que GROMACS espera. En tu archivo PDB, parece que los residuos de agua están numerados incorrectamente (0 en lugar de 1). Además, asegúrate de que los nombres de los átomos coincidan con los que GROMACS espera para el agua.

Anteriormente estaba asi

COMPND    UNNAMED
AUTHOR    GENERATED BY OPEN BABEL 2.3.90
HETATM    1  O   HOH     1       0.902   1.921  -0.037  1.00  0.00           O  
HETATM    2  H   HOH     0       2.001   1.879  -0.007  1.00  0.00           H  
HETATM    3  H   HOH     0       0.585   1.064   0.575  1.00  0.00           H  
CONECT    1    2    3                                                 
CONECT    2    1                                                      
CONECT    3    1                                                      
MASTER        0    0    0    0    0    0    0    0    3    0    3    0
END

Y me lo entrega corregido de la siguiente manera

COMPND    UNNAMED
AUTHOR    GENERATED BY OPEN BABEL 2.3.90
HETATM    1  OW  HOH     1       0.902   1.921  -0.037  1.00  0.00           O  
HETATM    2  HW1 HOH     1       2.001   1.879  -0.007  1.00  0.00           H  
HETATM    3  HW2 HOH     1       0.585   1.064   0.575  1.00  0.00           H  
CONECT    1    2    3                                                 
CONECT    2    1                                                      
CONECT    3    1                                                      
MASTER        0    0    0    0    0    0    0    0    3    0    3    0
END



### Objetivos Cumplidos 🏆

- [x] Crear mi 'water_tomar.gro'.

### Resultados 📊

Una jornada exitosa.

### Problemas y Desafíos 🚧

Ninguno, todavia.

### Tareas Pendientes 📌

- [ ] Hacer las corridas para una caja en las que esten mis dos moleculas de agua.
- [ ] Crear un programita que calcule la cantidad exactas de aguas que tenemos que poner para una concentracion dada.

### Recursos 📚

Ninguno

### Notas Adicionales 🗒️
Nada que agregar.

---
**Firma del Investigador:** Delorenzi, Tomás   **Redacción:** [23/05/2024] 🖋️
---

---
## Viernes, 24/05/2024 📆
---

### Información General
- **Fecha:** Viernes, 24/05/2024 📆
- **Investigador:** Tomás Delorenzi 👨‍🔬
- **Molécula:** Agua SPC/E 🧪
- **Objetivo del Día:** Comunicacion con la directora. 🎯

### Resumen del Día 📝

Se le comento a Griselda Monica Corral mis avances del dia anterior. Comentandole que he podido pasar mis archivo de formato pdb a formato gro y poder hacer mi primera caja.

### Modificaciones y Avances Realizados 🛠️

Griselda me comento que como es que yo se la forma que tiene mi caja que crea la herramienta pdb2gmx. Asi ella me comento la herramienta de gromacs GENBOX. Estuve googleandola y no he encontrado nada.

### Objetivos Cumplidos 🏆

- [x] Comentarles mis avances a mi directora.

### Resultados 📊

Poner a prueba mis conocimientos sobre las herramientas que voy utilizando para ir avanzando.

### Problemas y Desafíos 🚧

No se ha encontrado la herramienta sugerida por mi directora.

### Tareas Pendientes 📌

- [ ] Corroborar con la herramienta Protein Viewer de Visual Studio Code si la caja es cuadrada

### Recursos 📚

Ninguno

### Notas Adicionales 🗒️
Nada que agregar.

---
**Firma del Investigador:** Delorenzi, Tomás   **Redacción:** [27/05/2024] 🖋️
---

---
## Lunes, 27/05/2024 📆
---

### Información General
- **Fecha:** Lunes, 27/05/2024 📆
- **Investigador:** Tomás Delorenzi 👨‍🔬
- **Molécula:** Agua SPC/E 🧪
- **Objetivo del Día:** Corrobar que todavia sigue andando mis extensiones para visualizar mi "archivo.gro". 🎯

### Resumen del Día 📝

Pude visualizar mi caja de simulacion y vi como se estructura las aguas dentro de la caja.

### Modificaciones y Avances Realizados 🛠️

Pude ver que la caja de simulacion es cuadrada. Con la extension Protein Viewer.

![WATER_TOMAS](https://github.com/DelorenziTomas/Cuadernos_de_laboratorio/assets/134660680/59e4310a-de95-44ca-8a7d-c26152e6692d)

Con la herramienta [editconf](https://manual.gromacs.org/current/onlinehelp/gmx-editconf.html) encontramos que uno puede hacerle distintas operaciones a la caja de simulacion. Como cambiar su geometria, centrar, darle las mediciones a la caja, etc.

Usando el archivo: water_tomas.pdb

gmx editconf -f water_tomas.pdb -box 4 4 4 -bt cubic -d 0 -o water_box4-5.gro

Se genera una caja cubita de aristas 4 nm y se centra la molecula de agua en el centro de la caja.

### Objetivos Cumplidos 🏆

- [x] Volver a tomar contacto con la extension Protein Viewer.
- [x] Corroborar que estoy trabajando que mi caja es cuadrada.

### Resultados 📊

Positivos.

### Problemas y Desafíos 🚧

Ninguno.

### Tareas Pendientes 📌

- [ ] Terminar de hacer la corrida de 10ns por dinamica molecular.

### Recursos 📚

Ninguno

### Notas Adicionales 🗒️
Nada que agregar.

---
**Firma del Investigador:** Delorenzi, Tomás   **Redacción:** [27/05/2024] 🖋️
---

---
## Viernes, 07/06/2024 📆
---

### Información General
- **Fecha:** Viernes, 07/06/2024 📆
- **Investigador:** Tomás Delorenzi 👨‍🔬
- **Molécula:** Agua SPC/E 🧪
- **Objetivo del Día:** Realizar mi primera corrida de dinamica molecular 🎯

### Resumen del Día 📝



### Modificaciones y Avances Realizados 🛠️



### Objetivos Cumplidos 🏆

- [x] 

### Resultados 📊



### Problemas y Desafíos 🚧



### Tareas Pendientes 📌

- [ ] 

### Recursos 📚



### Notas Adicionales 🗒️


---
**Firma del Investigador:** Delorenzi, Tomás   **Redacción:** [07/06/2024] 🖋️
---
