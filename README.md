# IIC2133 - Estructuras de Datos y Algoritmos
## 2021-1

Bienvenido al sitio web del curso de Estructuras de Datos y Algoritmos. En esta página podrás encontrar la información administrativa del curso. En el repositorio podrás encontrar código ya preparado por tus ayudantes, junto con los eventuales enunciados de las tareas y las diapositivas de clases.

## Tabla de contenidos 
 * [Clases y ayudantías](#clases-y-ayudantías)
 * [Equipo](#equipo)
     * [Profesores](#profesores)
     * [Ayudantes](#ayudantes)
 * [Política de Integridad Académica](#política-de-integridad-académica)



 ## Clases y Ayudantías

 #### [Videos de C](https://github.com/DCCentral-de-Apuntes/intro-C)

| Tipo | Número | Tema | Fecha | Grabación | Material |
| :--: | :--: | :--: | :--: | :--: | :--: |
| Clase | 00 | Introducción al curso | 15/03 | [Video](https://youtu.be/qv4tOsyU5gw) | [Slides](https://github.com/IIC2133-PUC/2021-1/blob/master/Clases/00.%20Introducción%20al%20curso.pdf)|
|Taller | 01|  Intro a C | 17/03 |[Video](https://youtu.be/7kCqp5JBMs0)| [Slides](https://github.com/IIC2133-PUC/2021-1/blob/master/Ayudant%C3%ADas/Ayudant%C3%ADa%200%20-%20Intro%20a%20C/Taller%20C.pdf)|

     
## Equipo

### Profesores

| Nombre               |  Sección         |  Email         |
|:-------------------- |:--------------|:--------------|
| Yadran Eterovic | 1 | yadran@ing.puc.cl |
| Cristóbal Gazali | 2 | cjgazali@uc.cl |


### Ayudantes

| Nombre                | Email       | Github |
|:--------------------- |:-------------| :---------|
| Trinidad Vargas | mtvargas1@uc.cl | [@TrinidadVargas](https://www.github.com/TrinidadVargas)|
| Ignacio Zúñiga | inzuniga@uc.cl | [@inzuniga](https://www.github.com/inzuniga)|
| Rocío Hernández | rbhernandez@uc.cl | [@rbhernandez](https://www.github.com/rbhernandez)|
| Lucas Valenzuela | lucas.valenzuela@uc.cl | [@lucas-valenzuela](https://www.github.com/lucas-valenzuela)|
| Agustín Ríos | arios6@uc.cl | [@agustin-rios](https://www.github.com/agustin-rios)|
| Carlos Paredes | cparedesr@uc.cl | [@CarloGauss33](https://www.github.com/CarloGauss33)|
| Manuel Muñoz | mimunoz11@uc.cl | [@mimunoz11](https://www.github.com/mimunoz11)|
| Tanya Garrido | tcgarrido@uc.cl | [@tcgarrido ](https://www.github.com/tcgarrido )|
| Vicente Larraín | vlarrain2@uc.cl | [@vlarrain2](https://www.github.com/vlarrain2)|
| Diego Cartagena | dlcartagena@uc.cl | [@dlcartagena](https://www.github.com/dlcartagena)|
| Fernando De Diego | fadediego@uc.cl | [@fadediego](https://www.github.com/fadediego)|
| Nicolás Mc Intyre | nmcintyre@uc.cl | [@nmcin](https://www.github.com/nmcin)|
| Cristóbal González | cgonz@uc.cl | [@cristobalgon](https://www.github.com/cristobalgon)|
| Cristian Alonso Carrasco | cristian.carrasco@uc.cl | [@Aloncarrasco](https://www.github.com/Aloncarrasco)|
| Juan Carlos Echavarri | jcechavarri@uc.cl | [@jcechavarri](https://www.github.com/jcechavarri)|
| María Jesús Retamales | mjretamales@uc.cl | [@mjretamales](https://www.github.com/mjretamales)|

## Evaluación

El curso consta de una parte teórica, evaluada mediante evaluaciones escritas (interrogaciones), y una parte práctica, evaluada mediante tareas de programación en C.

### Evaluaciones Escritas

Habrá 3 interrogaciones, donde se evaluarán los aspectos más teóricos del contenido.

| Evaluación | Fecha |
|:----------|:----------|
| Interrogación 1 | 3 de mayo |
| Interrogación 2 | 4 de junio |
| Interrogación 3 | 14 de julio |


### Tareas

Habrá 4 tareas de programación en C, donde deberán resolver un problema complejo y analizarlo en un informe escrito. 

La nota final del curso se calcula de la siguiente manera:

```c++
double nota_final()
{
    /* La nota de cada tarea */
    double T0,T1,T2,T3;    
    /* La nota de cada interrogación*/
    double I1,I2,I3;

    /* Promedio de tareas */
    double NT = (T0 + T1 + T2 + T3) / 4;
    /* Promedio de interrogaciones */
    double NI = (I1 + I2 + I3) / 3;
    
    /* Nota final */
    double NF = (NT + NI) / 2;
    
    /* Es necesario tener sobre 3.7 en las evaluaciones escritas y las tareas por separado para aprobar el curso */
    if(NI < 3.7 || NT < 3.7)
    {
       return min(3.9, NF);
    }
    else
    {
       return min(NF, 7);
    }
}
```

## Política de integridad académica

Este curso se adscribe a la política de integridad académica de la Escuela de Ingeniería y el Departamento de Computación.

---

Los alumnos de la Escuela de Ingeniería de la Pontificia Universidad Católica de Chile deben mantener un comportamiento acorde a la Declaración de Principios de la Universidad.  En particular, se espera que **mantengan altos estándares de honestidad académica**.  Cualquier acto deshonesto o fraude académico está prohibido; los alumnos que incurran en este tipo de acciones se exponen a un Procedimiento Sumario. Es responsabilidad de cada alumno conocer y respetar el documento sobre Integridad Académica publicado por la Dirección de Docencia de la Escuela de Ingeniería (disponible en SIDING).

Específicamente, para los cursos del Departamento de Ciencia de la Computación, rige obligatoriamente la siguiente política de integridad académica. Todo trabajo presentado por un alumno para los efectos de la evaluación de un curso debe ser hecho individualmente por el alumno, sin apoyo en material de terceros.  Por “trabajo” se entiende en general las interrogaciones escritas, las tareas de programación u otras, los trabajos de laboratorio, los proyectos, el examen, entre otros.

**En particular, si un alumno copia un trabajo, o si a un alumno se le prueba que compró o intentó comprar un trabajo, obtendrá nota final 1.1 en el curso y se solicitará a la Dirección de Docencia de la Escuela de Ingeniería que no le permita retirar el curso de la carga académica semestral.**

Por “copia” se entiende incluir en el trabajo presentado como propio, partes hechas por otra persona.  **En caso que corresponda a “copia” a otros alumnos, la sanción anterior se aplicará a todos los involucrados**.  En todos los casos, se informará a la Dirección de Docencia de la Escuela de Ingeniería para que tome sanciones adicionales si lo estima conveniente. Obviamente, está permitido usar material disponible públicamente, por ejemplo, libros o contenidos tomados de Internet, siempre y cuando se incluya la referencia correspondiente y sea autorizado por los ayudantes.

Lo anterior se entiende como complemento al Reglamento del Alumno de la Pontificia Universidad Católica de 
Chile<sup><a name="pucCLBack">[1](#pucCL)</a></sup>.  Por ello, es posible pedir a la Universidad la aplicación de sanciones adicionales especificadas en dicho reglamento.

<sub>**<a name="pucCL">[1](#pucCL)</a>**: Reglamento del Alumno de la Pontificia Universidad Católica de Chile disponible en: http://admisionyregistros.uc.cl/alumnos/informacion-academica/reglamentos-estudiantiles [&#8593;](#pucCLBack)</sub>
