

#Especificaciones Funcionales
Dreamz 2015**





Entrega 01 – **Lunes 05 de Octubre

**Elaborado por: Jorge Reyes
Versión: 1.0**




#**Consideraciones Generales**#

Dreamz es un sistema pensado para estructuras con hasta 5 niveles jerárquicos. Dentro de los cuales estamos considerando los siguientes perfiles de usuario:

##**Super Adminisrador: Rony Zagursky.**
 
1.- **Este es el perfil de máxima autoridad para el sistema.** 

>Es el único perfil que tiene la capacidad de crear empresas y realizar consultas a nivel empresas. Su perfil le permitirá descender en la consulta de información en forma de cascada respetando las jerarquías creadas por empresa; respetando el nivel y tipo de usuario que les fue asignado.


1.2.- *Usuario Dreamz: Administrador Dreamz y CEO.*
 
- En diferentes organizaciones, podemos tener la posibilidad de colocar varios empleados en un mismo nivel. **El nivel 0 siempre será otorgado al administrador Dreamz. Sin embargo, El CEO será asignado al nivel 01** que en la estructura jerárquica de creación de áreas dentro de las empresas, representa la posición más alta.

1.3- Usuario Final:  *Empleados*

> Este perfil de usuario es asignado a todos los empleados restantes de la empresa. Sin embargo, es importante recalcar que dependiendo la jerarquía podrán ver toda la información de sus empleados en forma de cascada.









##Pantalla 1 de Login 
*Tipo: Front end & Back End, pantalla 1*

###Características Pantalla 1  - Login

> El usuario deberá capturar su nombre de *usuario y contraseña.* 
El sistema validará los datos de acceso y les permitirá la visualización del mismo de acuerdo a su perfil.

- El sistema tendrá la opción de recuperar la contraseña del usuario vía validación por email.

- Es importante considerar que esta acción generará puntos para el apartado de Gaming.


 



##Pantalla 2  Emociones / Bienvenida
*Tipo: Front end & Back End, pantalla 2*

Después de que un usuario hace login en el sistema, esta es la primera pantalla que verá:

 

###Características Pantalla 2 - Emociones
 

>El usuario deberá seleccionar una emoción por día al iniciar sesión.
>
>El sistema generará una base de datos con los siguientes campos:

>- Fecha, Hora y emoción que se seleccionó.

>Posteriormente, en el área de reportes podremos visualizar los resultados por puntos generados por tipo de emoción y cuál es la más escogida por nivel de usuario área y empresa. 

>los puntos generados por registrar emociones serán canjeables en la parte de *Rewarding*.

> + Aparece una vez por día, aunque inicies sesión más de una vez.



##Pantalla 3 Dashboard para Súper Administrador 
*Tipo: Front end, pantalla 3* 

>Una vez que el *súper administrador* ha hecho `login` y ha seleccionado su emoción diaria, el sistema desplegará la pantalla DASHBOARD. La cual, es una pantalla resumen de las empresas dadas de alta que muestra el resultado global de:

>-	Objetivos
-	Prioridades
-	Emoción más escogida.
-	Resumen de valores otorgados por categoría.
	
 Por cliente.

###Características Pantalla 3 – Dashboard Súper Administrador


+ *Prioridades*:  

 Muestra el promedio del grado de cumplimiento a nivel empresa de las prioridades propuestas.

+ *Emociones*: 

 Muestra el tipo y el porcentaje de la emoción más escogida en la empresa en el periodo.

+ *Valores / Badges*:  

 Muestra los valores establecidos por empresa y la veces que cada valor ha sido otorgado en la empresa.

*Es importante considerar que el Súper Admnistrador puede consultar el detalle de toda la empresa partiendo desde este dashboard, dando click a Objetivos, Prioridades, Emociones o Valores /Badges.* 





##Pantalla 4 Dashboard para CEO y Administrador Dreamz
*Tipo: Front end,  pantalla 4.*
 
>Es una pantalla similar a la pasada pero a nivel de usuario CEO o Administrador Dreamz, sirve para ver la información general de su empresa, y los objetivos y prioridades del usuario que está en su perfil.  Una vez que hayan hecho `login` y han seleccionado su `emoción diaria`, el sistema desplegará la pantalla DASHBOARD con el resultado global por áreas en las secciones siguientes:


>-	Objetivos
-	Prioridades
-	Emoción más escogida.
-	Resumen de valores otorgados por categoría.


###Características Pantalla 4 – Dashboard CEO / Administrador Dreamz

 + *Balance General*
 
El Usuario Dreamz o CEO, podrá ver los resultados globales de la empresa por área.

+ *Objetivos* 

Muestra el promedio del grado de cumplimiento a nivel áreas de los objetivos propuestos.

+ *Prioridades* 

 Muestra el promedio del grado de cumplimiento a nivel áreas de las prioridades propuestas.

+ *Emociones*

 Muestra el porcentaje con el que se define la emoción más escogida en cada área y muestra que emoción es.

+ *Valores / Badges*

Muestra los valores establecidos por empresa y la veces que cada valor ha sido otorgado en cada una de las áreas.

*Es importante considerar que el Administrador Dreamz o CEO, puede consultar el detalle de todas las áreas partiendo desde este dashboard, dando click a Objetivos, Prioridades, Emociones o Valores /Badges según el área que le interese observar* 




##Pantalla 5  Dashboard Director de Área o Gerente de Área

*Tipo: Front end, pantalla 5*
 
>Despúes de que el usuario CEO o Administrador Dreamz hayan seleccionado alguna área del negocio, descrita en forma general en la pantalla 4, podrán ingresar a la información general de dicha área; la pantalla tiene la misa estructura que la 4 pero muestra los resultados generales por miembro del área en los rubros:
>
-	Objetivos
-	Prioridades
-	Emoción más escogida.
-	Resumen de valores otorgados por categoría.

###Características Pantalla 5 –  Director de Área o Gerente de Área

+ *Balance General*

 El Usuario Director de área o gerente de área, podrá ver los resultados globales de la empresa en el dashboard **Balance General**.

+ *Balance Área*

 El Usuario Director de área o gerente de área, podrá ver los resultados globales de su área en el dashboard **Balance Área**


+ *Balance Usuario Final*
 
 Aunque no está descrito con ese nombre en las pantallas es evidente que el sistema tendrá que mostrar seguido de los dashboards `Balance General`y `Balance Área`los dashboards **por miembro del área** con la misma información global de objetivos, prioridades, emociones y valores.

+ *Objetivos* 

 Muestra el promedio del grado de cumplimiento a nivel empleado de los objetivos propuestos.


+ *Prioridades* 

 Muestra el promedio del grado de cumplimiento a nivel empleado de las prioridades propuestas.

+ *Emociones* 

 Muestra el porcentaje con el que se define la emoción más escogida por cada empleado y muestra que emociones.

+ *Valores / Badges* 

 Muestra los valores establecidos por empresa y las veces que cada valor ha sido otorgado a cada uno de los empleados.

*Es importante considerar que el Director o Gerente de área, puede consultar el detalle de todos su empleados desde este dashboard, dando click a Objetivos, Prioridades, Emociones o Valores /Badges. Las tablas que se observan del lado inferior con los nombres de **objetivos y prioridades** son datos referentes al usuario que está en sesión. 



##Pantalla 6 Dashboard de Empleado / Usuario final

*Tipo: Front end, pantalla 6* 

>Despúes de que el usuario CEO o Administrador Dreamz hayan seleccionado el perfil general de algún empleado perteneciente a `x` área de negocio, descrita en forma general en la pantalla 5, podrán observar la información general de dicho usuario respecto a resultados y avances laborales en el periodo.


> Del lado del usuario final, unicamente podrá ver el estatus de su actividad general en la empresa, tanto en la situación actual como en su acumulado por periodo (trimestres), el cumplimiento de prioridades en tiempo y forma y el resumen general de los puntos acumulados en el periodo por recepción de badges y los sueños que desea hacer realidad. 
###Características Pantalla 6 – Pantalla Dashboard Empleado / Usuario Final

+ *Balance Área*

 El Usuario final, podrá ver los resultados globales de su área en el dashboard **Balance Área**

+ *Mis Objetivos*

El usuario final registrará de manera diaria `deseable` el progreso que tiene en el cumplimiento de sus objetivos trimestrales, y el sistema le mostrará un resumen gráfico con su avance diario y el acumulado en el periodo por actividad. 

 **OJO:  La ilustración describe los datos diarios vs acumulados de manera inversa, considerar que solo es un ejemplo gráfico.**

+ *Mis Prioridades* 

 Las prioridades siempre serán evaluadas de forma semanal. Por lo que se considera que un periodo cuenta con 13 semanas. Los usuarios podrán ver las actividades que han cargado como prioridades y el nivel de trabajo que han efectuado para lograrlas por medio de un semáforo, en el que verde significa tarea completa para el objetivo de la semana establecida. El amarillo tarea incompleta y el rojo tarea no realizada. 

La columna de **AVANCE** es el promedio de las actividades realizadas en el periodo, por lo que un avance verde significa que la tarea está terminada.

+ *Valores / Badges*

 El usuario podrá ver el balance de qué tipo de valores sus compañeros le han asignado y la cantidad.

El botón encontrado en la parte inferior derecha `*Ver historias de badges otorgados*` esta direccionado al resumen general por detalle del por qué sus compañeros le han otorgado Valores o incluso Antivalores. Los antivalores sólo podrán ser vistos por el empleado/usuario final y el Administrador Dreamz. (Pantalla 7).

+ *Sueños*

Los empleados / usuarios finales, podrán definir qué sueño quieren alcanzar para que estos sean la guía del programa principal de recompensa de la empresa.`no confundir con Rewarding`

1.- Un usuario podrá editar únicamente 3 veces sus sueños en el periodo,cualquiera que sea. 

2.- Cada edición de sueño, debe ser autorizada por el Administrador Dreamz, por lo que debemos encontrar un procedimiento práctico para que sea rápido y sencillo para todas las partes.

+ *Assessments*

 Los usuarios finales podrán encontrar los archivos de resultados de sus exámenes aplicados, como pruebas de talento, pruebas psicométricas, encuestas para la compañía etc. Estos archivos serán cargados por el Administrador Dreamz o bien, por el Super Usuario.

+ *Top Grading* 

En la parte superior derecha podemos ver una apartado llamado *Top Grading* **ver pantalla `Empresas` para explicación general** 

+ *Puntos* 

En todas las pantallas a nivel usuario, podremos encontrar un apartado en la parte superior derecha llamado “Puntos”. Que es la sumatoria total de los puntos adquiridos por las actividades realizadas en el sistema Dreamz y son de dos naturalezas:

1.- *Por otorgamiento de badges* que influyen en la calificación final del usuario relacionada con calificación `KPIs`.

2.-Por actividad en el sistema que genera puntos para el cambio de premios mostrados en la sección del programa `Rewards`.


## Pantalla 7 Resumen de Badges Recibidos, Valores y Antivalores

*Tipo: Front end, pantalla 7*

>Una vez que el usuario final dio `click` en el botón `ver historias de badges otorgados`en la pantalla 6, tendrá acceso a esta nueva pantalla para poder leer la descripción del por qué recibió un badge de **Valor** o uno de **Antivalor**.
 
> La empresa solamente podrá cargar hasta 6 valores asignándole puntos a cada uno, cabe destacar que el valor de cada badge será determinado por la empresa o el Súper Administrador y puede ser que todoslos badges de valor creados tengan el mismo valor.
> 
>  El  **Antivalor** se dará cuando un empleado considera que su compañero está efectuando la actividad inversa al valor creado *LEAL - DESLEAL*; en este caso el sistema en lugar de sumar puntos restará y podrá mostrar balances incluso negativos en caso de que un usuario no tenga puntos por valores y comience con antivalores.

 
###Características Pantalla 7 – Resumen de Badges Recibidos, Valores y Antivalores

+ Un usuario puede otorgar únicamente cuatro valores diarios al día: Los puede distribuir entre las personas que así deseé. En caso de querer asignarle a un sólo usuario cuatro valores tendrán que ser cuatro distintos, es decir **NO** pueden otorgar más de un valor similar el mismo día. 
 
+ Cada valor o antivalor otorgado debe tener una historia que lo justifique.

+ Cada que un empleado otorgue un valor a o un antivalor, este deberá estar sujeto a autorización del Administrador Dreamz. Mismo que revisará las historias para certificar la veracidad del hecho y autorizar su publicación. 

+ Todos los usuarios a todos los niveles, podrán ver los Valores y Antivalores publicados en los perfiles de sus compañeros.


+ El sistema reiniciará cada fin de periodo (trimestre) los valores otorgados por usuario, sin embargo, la base de datos contempla el acumulado histórico. 

+ *Columna Tipo* 

Describe si el usuario ha recibido un “Valor” o un “Antivalor”.
 
+  *Contador Valores & Antivalores* 

 Lo podemos observar del lado superior derecho; describe a manera de resumen cuántos valores y antivalores ha recibido el usuario en el periodo.





#PANTALLAS DE ADMINISTRADOR TIPO BACKEND



##Consideraciones Generales
>`Dreamz` es un sistema pensado para estructuras con hasta 5 niveles jerárquicos. Dentro de los cuales estamos considerando los siguientes perfiles de usuario:


+ *Super Adminisrador* **Rony Zagursky**.
 

1.- Este es el perfil de máxima autoridad para el sistema. Es el único perfil que tiene la capacidad de crear empresas y realizar consultas a nivel empresas. Su perfil le permitirá descender en la consulta de información en forma de cascada respetando las jerarquías creadas por empresa; respetando el nivel y tipo de usuario que les fue asignado. Perfil de gestión con todos los privilegios.

2.- Usuario Dreamz: **Administrador Dreamz y CEO**. 

 En diferentes organizaciones, podemos tener la posibilidad de colocar varios empleados en un mismo nivel. Sin embargo:

+ Unicamente habrá una persona asignada con el nivel `0` que será otorgado al administrador Dreamz. 

+ Unicamente habrá una persona asignada con el nivel `1` que será otorgado al  CEO quien representa la posición más alta de la empresa.

+ *Usuario Final*  **Empleados**

 Este perfil de usuario es asignado a todos los empleados restantes de la empresa. Sin embargo, es importante recalcar que deben respetar la jerarquía de su puesto. Es decir, un gerente de área, deberá poder ver toda la información de sus empleados a manera de cascada pero no podrá ver los de los Usuarios Dreamz ni CEO.


*Es importante destacar los permisos de operación del sistema por nivel jerárquico dentro de la organización que se resumen en las siguientes dos tablas nombradas “Permisos”  y “Vistas”.*

+ *Permisos*

La matriz permisos muestra el nivel de acción que puede tener cada tipo de usuario dentro de la plataforma.

Dónde:


+ **RW** = Read and Write.

+ **R** = Read


* **N** = No acces


######INTEGRAR MATRIZ DE PERMISOS

+ *Visitas*.

La matriz vistas  nos muestra quién puede tener acceso a cada pantalla configurada en el sistema.  



###### INTEGRAR MATRIZ VISITAS



## Pantalla 8 *Empresas* sólo para Súper Administrador . 
*Tipo: Back end, pantalla 8*

> El Súper Administrador es el único usuario que podrá tener acceso a esta pantalla. Al ingresar lo primero que observará es la pantalla `Empresas` que muestra las compañías en donde el sistema actualmente está instalado. 
> 
> Del lado derecho cada empresa tiene dos botones **Modificar y Eliminar** para poder generar cambios en la configuración de su perfil. En caso de no existir ninguna empresa, el sistema desplegará la leyenda **No existen empresas dadas de alta en el sistema** y el botón `Agregar empresa`.
> 
>  La última columna se llama **Activación** la cual contiene un Check box en cada renglón de empresas, cuando se seleccione automáticamente quedará inactivo el sistema en la compañía que se indica.
 

###Características Pantalla 8:  Empresas

+ *Alta de empresas*

 Pantalla para crear el perfil de una nueva empresa.
 
+ *ID Empresa*

 Número serial autoincremental.

+ *Logotipo* 

 El súper administrador deberá seleccionar de su computadora la imagen del logotipo de la empresa que está creando. Dicha imagen deberá ser de formato JPG o PNG del tamaño especificado en el manual de usuario.

*En caso de que el usuario no seleccione un logotipo, el sistema mostrará por defecto el de Dreamz.*


+ *País* 

 El Súper Administrador seleccionará el país donde la empresa opera. En caso de no encontrar el país, lo podrá integrar gradualmente a través del catálogo de países.

+ *Descripción* 

 Es un breve texto que describe a la empresa en general.

+ *Idioma*

El sistema es multi idioma, por lo que el súper administrador podrá seleccionar el o los idiomas con los la empresa vaya a operar. Puede haber dos idiomas al mismo tiempo *Español e Inglés* por ejemplo  En caso de que haya empleados de otra nacionalidad en México. 

Si el Súper Administrador desea cargar un nuevo idioma tendrá que agregar el archivo con la etiqueta del idioma correspondiente.

+ *Industria*

 El Súper Administrador deberá seleccionar del listado la industria a la que pertenezca la empresa que está creando.  En caso de no encontrarse en el listado,  podrá integrar la industria faltante a través del catálogo de Industrias.

+ *Nombre o Razón Social*

 Razón social de la empresa a donde se deberá facturar.

+ *Slogan*

 Texto que describe la promesa de marca de la empresa. En caso de que no se capture el sistema no mostrará nada.

+ *Nombre Comercial*

 Es el nombre con el que se conoce la empresa en el mercado.

+ *RFC*

 Cédula fiscal de la empresa.

+ *Tamaño de empresa*

 El Súper Administrador deberá seleccionar de la lista el tamaño de empresa. En caso de que la opción no se encuentre en la lista, deberá ser agregado a través del catálogo de `Tamaño de empresa`.

+ *WebSite*

 Sitio web de la empresa.

+ *Dirección Fiscal*

 El Súper Administrador dará de alta la dirección fiscal de la empresa creada. El teléfono debe incluir la lada de país.

+ *Dirección Física*

 El Súper Administrador dará de alta la dirección física de la empresa creada, en caso de que coincida con la dirección fiscal, habrá un Check Box  que al ser seleccionado,  replicará los datos de manera automática.

+ *Dirección Sucursales*

 En caso de que el cliente tenga sucursales, el Súper Administrador podrá registrar todas de manera individual, y mediante el botón “Agregar Sucursal” podrán listar las que sean necesarias. 


+ *Valores Top Grading*

 
La calificación general del empleado en la compañía es resultado de la calificación obtenida en los **KPI** ( el cual determina el eje de las `X`), y esta que es la obtenida en puntos acumulados por valores recibidos en el periodo (eje de las `Y`). Los empleados no podrán ver la metodología ni conocer el valor de los puntos por valor, solamente el Súper Administrador, CEO y Administrador Dreamz.

---

######Metodologia Top Grading - **Sección especial** 


Recordemos que *La empresa definirá cuántos valores ( badges) va a configurar,  pueden configurar hasta 6 badges de valor. A cada uno le podrá asignar un valor o también puede que todos los badges valgan lo mismo*.

De esta manera al final del periodo se multiplicarán:  el número de veces que le fue otorgado cada valor, por su valor en puntos, para tener el número total de puntos por periodo recibidos por valor.

La suma de éstos determinará la posición en el eje de las `Y` y el límite superior será determinado por el número máximo logrado por cualquier usuario de la compañía formando rangos que podrá cambiar el Súper Administrador, de acuerdo a sus intereses.  


+ **Rango Verde 20%**
 
 hacía abajo a partir del máximo valor de puntos logrados.

+ **Amarillo 30%**

 Hacia abajo del 20% del rango verde para determinar la zona media.

+ **Rojo 50%** 

 Hacia abajo Del primer 50% del eje de las `Y` para generar la zona baja.

La calificación de este apartado se combinará con la calificación de los **KPI** para determinar que tipo de empleado tiene la empresa, si es un `Engaged = A`, `Not Engaged = B ` ó  un `Actively Disengaged = C`



Dicha calificación se definirá con la siguiente combinación de resultados:

**INSERTAR TABLA**


**Valores** **KPIs**	**Total**
   Verde	  Verde	     **A**
Amarillo	Amarillo	B
Rojo	Rojo	C
Verde	Amarillo	B
Verde 	Rojo	B
Amarillo	Verde	B
Amarilo	Rojo	C
Rojo	Amarillo	C
Rojo	Verde	C

y así determinaremos cuál es la calificación general del empleado.

----




## Pantalla 9 *Usuarios*  para Súper Administrador /Administrador Dreamz

*Tipo: Back end, pantalla 9*

>El Súper Administrador y Usuario Dreamz serán los únicos que podrán tener acceso a esta pantalla. 
>
>Al ingresar lo primero que observarán es la pantalla `Usuarios` que muestra el número de usuarios dados de alta en el sistema y área a la que pertenecen dentro de la compañía. 
>
>En las primeras columnas son campos independientes para registrar Nombre, Apellido Paterno, Apellido Materno y área.
>
> Del lado izquierdo cada usuario tiene dos botones **Modificar” y Eliminar** para poder generar cambios en la configuración de su perfil. 
> 
>Seguida de esta columna, encontramos la opción **Activación** con un Check box que cuando se seleccione, automáticamente el usuario quedará inactivo en el sistema.
>
>Y por último en esta pantalla encontramos la columna **Tipo de empleado**, con un Check box que en caso de ser seleccionado el usuario tomará una posición de empleado **High Potential** y en caso de no ser seleccionado será considerado como **Non High Potential**.
>
>**NOTA** **Esto será un valor cualitativo para los empleados en la compañía por lo que se tendrá que correlacionar al check box, una señal para que el sistema entienda de que si Alejandro Tejeda es High Potential, cuando grafique su nombre en la tabla de calificación general, salga con una marca que permita saber que es High Potential.
>
> Ejemplo.  Alejandro Tejeda **HP**
>
>Y mismo caso con usuarios Nuevos que tendrán un periodo de tres meses de gracia con la marca de usuario nuevo.
>
>Ejemplo. Jorge Reyes **Nuevo** 


> En caso de no existir ninguno dado de alta, el sistema desplegará la leyenda **No existen usuarios dados de alta en el sistema** y el botón **Agregar usuario** 
> 
 

### Características Pantalla 2  *Usuarios*  

Al dar `click`en la pestaña `Agregar Usuario`se desplegará la siguiente pantalla:

+ *Alta de Usuarios* 

Pantalla para crear el perfil de un nuevo Usuario. 

+ *ID Usuario*

 Identificador serial autoincremental.

+ *Check Box Quality Usuer* 

El administrador Dreamz al dar de alta a cada usuario podrá seleccionar que tipo de usuario será para la organización, si su perfil es alto tendrá que escoger  el Check Box marcando que es High Potential, de lo contrario será considerado como Non High Potential. 


+ *Nombre*

 Nombre/s del usuario seguido por sus apellidos paterno y materno.

+ *Fecha de Nacimiento*

 La fecha de nacimiento del nuevo usuario registrado se tendrá que seleccionar en el calendario desplegable.

+ *Sexo*

 Se tendrá que seleccionar el sexo del nuevo usuario sea Masculino o Femenino establecidos en el combo box.

+ *Móvil*

Teléfono de contacto con el nuevo usuario.

+ *Tipo de Sangre* 

Se tendrá que seleccionar el tipo de sangre del nuevo usuario establecido en el combo box.

+ *Alergias* 

Se tendrá que especificar si el usuario es sensible a padecer una o distintos tipos de alergias.
 
*Contacto de Emergencia* 

El nuevo usuario definirá al Administrador Dreamz, a qué persona la empresa puede contactar en caso de tener alguna emergencia.

+ *Teléfono* El nuevo usuario definirá al Administrador Dreamz, a qué teléfono la empresa puede contactar en caso de tener alguna emergencia.

+ *Área/Depto* 

Se establecerá el departamento para el cual el nuevo usuario trabaja en la compañía.  El combo Box incluirá dentro de su lista, las direcciones o distintos niveles jerárquicos de la empresa para que se identifiquen que tipo de usuarios se están creando.
 
Jefe: El Usuario Dreamz definirá quién es el jefe inmediato del nuevo usuario seleccionándolo desde el combo box. y así el sistema detectará automáticamente el nivel del usuario creado.

+ *Fecha de Ingreso* 

Fecha en la que el usuario ingresó a la compañía.
  
+ *Perfiles Sociales* 

El Usuario Dreamz podrá capturar las diferentes cuentas de perfiles sociales que el nuevo usuario deseé compartir con la empresa.

+ *Assessments* 

El Súper Administrador capturará los campos con los valores obtenidos en el DISC y en el DISC ADAPTADO, así mismo podrá capturar los valores obtenidos para WELTH DYNAMICS mediante su Combo Box y los cinco valores para STRENGHTS FINDER.

+ *Guardar Usuario* 

El Administrador Dreamz deberá hacer click sobre el botón Guardar Usuario para generar la captura completa en el sistema del nuevo empleado. 



			

## Pantalla 10 *Valores* para Súper Administrador y Usuario Dreamz 

*Tipo: Back end pantalla 10* 

>El Súper Administrador/Administrador Dreamz serán los únicos usuarios que podrán tener acceso a esta pantalla. 

>Al ingresar lo primero que observarán es la pantalla **Valores** que muestra el número de valores (badges) dados de alta en el sistema por la empresa, su descripción, el tipo de valor que es y su icono gráfico con el que se identifica. 

> Recordando *cada empresa puede dar de alta hasta 6 valores distintos y sólo se podrán cambiar al finalizar cada periodo*
> 
> Del lado derecho cada usuario tiene dos botones **Modificar y Eliminar** para poder generar cambios en la configuración de su perfil. En caso de no existir ninguno, el sistema desplegará la leyenda **No existen valores dados de alta en el sistema** Seguido del botón, `Agregar Valor`. Cuando la empresa tenga 6 valores cargados, dicho botón se tendrá que bloquear activándose hasta que eliminen o inactiven uno de los valores configurados.



### Características Pantalla 10 – *Valores*   Súper Administrador y Usuario Dreamz

Al dar `click`en el botón `Agregar Valor`el usuario accederá a la siguiente pantalla de configuración donde:

+  *Agregar Valor*

 Es la Pantalla para dar de alta valores (badges).

+ *ID Valor*

 Identificador serial autoincremental.

+ *Tipo* 

 Se tendrá que escoger del combo box qué tipo de badge es, si es valor o antivalor.

+ *Nombre* 

Nombre del valor configurado.

+ *Descripción* 

Texto descriptivo del valor.
 
+ *Icono*

 El súper administrador deberá seleccionar de su computadora la imagen del icono del valor que está creando. Dicha imagen deberá ser de formato JPG o PNG del tamaño especificado en el manual de usuario.

  *En caso de que el usuario no seleccione un logotipo, el sistema mostrará por defecto el de Dreamz.* 

+ *Ponderación* 

 Valor que tendrá el badge en otorgamiento de puntos.

+ *Valor Activo* 

Activando el Check Box estará habilitado en el sistema y visible para todas las 
jerarquías del sistema.

+ *Guardar Valores*  

El usuario tendrá que dar `click` en “Guardad Valores” para que el sistema capture e integre los cambios a la plataforma que estará habilitada para todos los usuarios, de lo contrario nadie podrá ver la programación hecha. 




## Pantalla 11 Estructura Organizacional para Súper Administrador y Administrador Dreamz 

*Tipo: Back end, pantalla 11*

>El Súper Administrador y el Usuario DreamZ son los únicos usuarios que podrán tener acceso a esta pantalla.
>
> Al ingresar lo primero que observarán es la pantalla **Estructura Organizacional** que muestra las distintas áreas de la empresa que han sido dadas de alta en el sistema.
> 
Inmediatamente encontramos la columna **Responsable/Jefe** en donde se tendrá que registrar el nombre de la persona encargada del área registrada para la gestión de Dreamz.

> Del lado izquierdo cada bloque tiene la sección de `Acciones`en donde el usuario puede **Modificar” y “Eliminar** la configuración del perfil de cada área registrada.
> 
>  En caso de no existir área registrada, el sistema desplegará la leyenda **No existen áreas dadas de alta en el sistema** y el botón **Agregar área**.  


### Características Pantalla 11 *Estructura Organizacional* 

Al dar `click`en el botón `Agregar Área`el usuario accederá a la siguiente pantalla:

+ *Alta de Áreas* 

 Pantalla para generar la configuración de cada área y el nivel que tienen dentro de la organización.

+ *ID Área* 

Número serial autoincremental.

+ *Nombre* 

Nombre del área registrada.

+ *Nivel* 

Nivel jerárquico del área registrada, se seleccionará desplegando el combo box y los niveles aplican de la siguiente manera:

1.- **Nivel 0** 

 Solamente habrá una persona asignada con este nivel dentro de la organización y será el Usuario Dreamz.

2.- **Nivel 1**

Solamente habrá una persona asignada con este nivel y será el CEO.

3.- **Nivel 2,3 y 4**  

Puede haber cualquier cantidad de usuarios asignados a este nivel pues corresponden a las distintas estructuras jerárquicas de las empresas. 

+ *Graficar Organigrama*

El objetivo es generar el organigrama de la empresa donde se muestran La estructura operativa por áreas de operación del sistema Dreamz en la empresa.

 **se tiene que comentar con Alejandro Tapia si esta es la mejor manera de hacerlo o prefiere otra forma que permita lograr el mismo resultado**.

+ *Imprimir PDF*

 Obtener una impresión en formato PDF del organigrama institucional.

 


## Pantalla 12 Emociones  para Súper Administrador y Usuario Dreamz. 

*Tipo: Back end, pantalla 12*
  
El Súper Administrador y el Usuario Dreamz son los únicos usuarios que podrán tener acceso a esta pantalla. Después de configurada será la primer pantalla que verá todo tipo de usuario con icono y nombre Feliz, Sorprendido, Estresado, Cnsado, Soñoliento, Enojado. 

Al ingresar lo primero que observarán es la sección **Emociones** que muestra las distintas emociones que han sido dadas de alta en el sistema.  

Una empresa puede dar de alta hasta 6 emociones distintas y se pueden cambiar únicamente hasta terminado el periodo de operación que corresponde a un trimestre y el cambio lo tendrá que gestionar el Usuario Dreamz con Súper Administrador.

En la misma pantalla,  la columna **descripción** detalla el significado general de cada una de las emociones.

Mientras que la columna  **Icono** agregará la descripción gráfica de cada una de estas emociones.

Al igual que en las pantallas anteriores tenemos la columna *Acciones* para **Modificar y Eliminar** la configuración del perfil de cada emoción registrada. 

En caso de no existir ninguna emoción registrada, el sistema desplegará la leyenda **No existen emociones dadas de alta en el sistema**.


###Características Pantalla 12 *Emociones*

Cuando el usuario de `click`en el botón `Agregar Emoción` se desplegará la siguiente pantalla:

+ *Agregar Emoción*

 Pantalla de configuración de **emociones** en donde se detalla la característica de cada una de ellas.

+ *ID Emoción** 

Número serial autoincremental.

**Nombre de la Emoción** 

Cada emoción tiene un nombre y esta será la sección en donde le será asignado.

Ejemplo: Feliz, Sorprendido, Estresado, Cnsado, Soñoliento, Enojado.
 
+ **Descripción**: 

Texto descriptivo de la emoción.

+ *Icono*

El súper administrador deberá seleccionar de su computadora la imagen del icono de la empresa que está creando. Dicha imagen deberá ser de formato JPG o PNG del tamaño especificado en el manual de usuario.

En caso de que el usuario no seleccione un Icono, el sistema mostrará por defecto el de Dreamz.

+ *Ponderación* 

Es el valor que tendrá cada emoción para realizar el cálculo de puntos acumulados por su uso. Dichos puntos serán usados para canjear premios en la sección `Rewarding`que se detalla en la página 17.
 
+ *Emoción Activa* 

Mediante el check box, el Súper Administrador o bien el Usuario Dreamz controlarán el estado de cada emoción,  check box elegido denota Emoción Activa en el sistema y todos los usuarios la podrán ver.  Y viceversa. 

+ *Guardar Emoción* 

Si el usuario hace click en `Guardar Emoción` podrá conservar la configuración realizada y la emoción estará disponible para utilizarse.



## Pantalla 13 KPI  para Sper Administrador, Usuario Dreamz, CEO y Gerente 

*Tipo: Back end, pantalla 13*
 
>Esta pantalla junto con la pantall 10 `Valores` son las que definen mediante su calificación la evaluación general en la compañía de cada usuario. Es el eje de las `X` que mediante el desempeño de cada usuario en el cumplimiento de sus objetivos y prioridades asignará una calificación resumida en color **Verde** para los mejores empleados, **Amarrillo** para los regulares y **Rojo** para los irregulares.

>Los  objetivos de los empleados siempre estarán medidos en trimestres y son   clasificados por categorías, pueden ser personales, por áreas o bien a nivel empresarial.

>Todas las áreas a todos niveles pueden generar sus objetvios, los empleados  unicamente tendrán la opción de agregar más objetivos, pero el Súper Administrador y el Usuario Dreamz podrán agregar categorias, subcategorias y uniad de medida.

>La **categoría** será definida por el perfil de cada empresa.

>La **subcategoria** es la vía de medición  de los objetivos

> El KPI, es el resultado de combinar el cumplimiento de los objetivos y las prioridades que reflejan el desempeño del empleado en el periodo, Un objetivo puede ser trimestral, menor de un trimestre (se integra dentro del Q1) o bien anual Q4.
> 
> La columna **Unidad** detalla la unidad de medida para la interpretación de cada KPI. 
> 
> Ejemplo: en %, moneda, piezas y tiempo.

> El Súper Administrador y Usuario Dreams podrán agregar  **N** categorías, subcategorias, unidad de medidas y objetivos.

###Características Pantalla 13 KPI.

Una vez que los usuarios den `click`en **Agregar Categoría** podrán ingresar a la siguiente pantalla:
   
+ *Agregar Categoria*  

Tipo de KPI a realizar por usuarios.

+ *ID Categoria* 

Número serial autoincremental.

+ *Nombre de la Categoria*

+ *Siguiente* 

El usuario tendrá que hacer `click` en **Siguiente** para conservar la configuración realizada en este apartado. y se desplegará la siguiente pantalla:

 
+ *Agregar Sub Categoria* 

Tipo de subcategoría a la que pertenece la categoría del KPI recién configurado. 

+ *ID Subcategoria* 

Número serial autoincremental.

+ *Seleccione subcategoría* 

Combo box del que se tendrá que seleccionar la subcategoría a programar.

+ *Nombre de la Subcategoria*

Nombre que le será asignado a dicha subcategoría.

+ *Siguiente* 

El usuario tendrá que hacer `click` en **Siguiente** para conservar la configuración realizada en este apartado. y se desplegará la siguiente pantalla:

+ *Agregar Unidad de Medida*  

Unidad de medida bajo la cual será medido cada KPI configurado.

+ *ID Unidad* 

Número serial autoincremental.

+ *Nombre de Unidad* 

Nombre con el que será definida la unidad de medida.

El usuario tendrá que hacer `click` en **Siguiente** para conservar la configuración realizada en este apartado. y se desplegará la siguiente pantalla:


+ *Registrar un avance en KPIS (Todos los usuarios)*

>En esta pantalla **todos los usuarios** podrán ingresar sus datos referentes a resultados empresariales obtenidos en el periodo para que el sistema gráfique sus resultados diarios y genere los acumulados,  respecto a los objetivos planeados y poder definir el semáforo de logros.

+ *Registrar Avance* 

El usuario tendrá que hacer `click` para poder registrar un nuevo avance. y podrá hacerlo en una pantalla light box

El usuario podrá registrar los avances que guste las veces que sea necesario por día.

+ *Ver detalles*

Este botón conducirá al usuario a los detalles de configuración de los KPI.  


+ *Agregar KPI*

El usuario podrá agregar un nuevo KPI.

+ *ID KPI* 

Número serial autoincremental.

+ *Periodo* 

El usuario tendrá que desplegar el combo box para poder seleccionar el o los periodos divididos, en trimestres, en el que se encuentra la operación.

+ *Seleccione Categoría* 

El usuario tendrá que desplegar el combo box para poder seleccionar la categoría, de la que su objetivo es parte.

+ *Seleccione Subcategoría*

 El usuario tendrá que desplegar el combo box para poder seleccionar la subcategoría, de la que su objetivo es parte.

+ *Descripción* 

El usuario ingresará un texto descriptivo del objetivo a cumplir.

+ *Unidad de Medida* 

El usuario tendrá que desplegar el combo box para poder seleccionar la unidad de medida que expresará el avance trimestral del cumplimiento de su objetivo.

+ *Responsable* 

El Administrador Dreamz  tendrá que desplegar el combo box para poder seleccionar el usuario que será el responsable de lograr dicho objetivo.

+ *Tipo de KPI*

Define el tipo de objetivo que el usuario tenga que cumplir, ya sea personal, de área o a nivel empresarial.

+ *KPI Compartido* 

Si el usuario desea compartir el KPI con una o más personas tendrá que seleccionar el check box para que pueda observar la caja de texto  **seleccione usuarios con quien quiera compartir el objetivo**,  una vez haga `click` sobre el nombre de cualquier usuario tendrá la opción de agregarlo en una nueva caja de texto mediante la tecla **Agregar**  y de esta manera podrá compartir sus objetivos con uno o más usuarios.

Si desea dejar de compartir su objetivo con uno o más usuarios, tendrá que seleccionar al usuario y después dar `click` en la tecla **Quitar** para dejar de compartir sus objetivos.

Los usuarios con los que se quieran compartir objetivos **se tienen que poder seleccionar de manera múltiple** para que sea más práctico.

El usuario tendrá que hacer `click` en **Siguiente** para conservar la configuración realizada en este apartado. y se desplegará la siguiente pantalla:


+ *Valor Semáforos para el Trimestre*

Es la ponderación que evaluará el resultado de los usuarios cada trimestre en términos de objetivos y prioridades alcanzadas.
	
+ *Valor Objetivo Trimestral* 

Valor total del objetivo a lograr en unidad de medida que represente el 100%.

+ *Valor Verde Trimestral* 

Rango de resultados desplegables en el combo box, considerados como **menor qué o igual a**  para ser considerados como los mejores de la compañía en el periodo.

+ *Valor Amarillo Trimestral* 

Rango de resultados desplegables en el combo box, considerados como **entre**  para ser considerados como aceptables de la compañía en el periodo.

+ *Valor Rojo Trimestral* 

Resultado condicionado en el combo box, considerado como **menor a**  para ser considerado como deficiente según las metas que la compañía busca en el periodo.

El usuario tendrá que hacer `click` en **Siguiente** para conservar la configuración realizada en este apartado. y se desplegará la siguiente pantalla:


+ *Valor Semáforos Para el Objetivo Diario*

 Valores para objetivos sobre 90 días,  un trimestre, para que se cumplan las condiciones del semáforo en términos de la programación general.

+ *Valor Verde diario* 

Rango de resultados desplegables en el combo box, considerados como **entre**  para ser considerados como aceptables de la compañía en el periodo.

+ *Valor Amarillo diario* 

Rango de resultados desplegables en el combo box, considerados como **entre**  para ser considerados como aceptables de la compañía en el periodo.
 
+ *Valor Rojo diario* 

Resultado condicionado en el combo box, considerado como **menor a**  para ser considerado como deficiente según las metas que la compañía busca en el periodo.

+ *Siguiente* 

Si el usuario hace`click` en el botón **Guardar** podrá grabar la configuración hecha en dicho semáforo y estará habilitada inmediatamente en el sistema.



## Pantalla 14  Sueños  para Súper Administrador y Usuario Dreamz.

*Tipo: Back end, pantalla 14*
 
>La pantalla Sueños estará habilitada para que además del Súper Usuario, el Usuario Dreamz pueda editar su contenido.
>
>Todos los empleados de la organización sin importar el nivel jerárquico, podrán agregar hasta 4 sueños al iniciar el periodo, el objetivo es que la empresa recompense a los empleados ayudándolos a convertir  dichos sueños en realidad por su desempeño empresarial. 

>Los sueños **No son canjeables por puntos** son decisiones de la empresa basadas en las calificación general **Top Grading + KPI **
>
>Solamente se pueden editar 4 veces por periodo, Si el usuario desea cambiar un sueño, el Usuario Dreamz tiendrá que gestionar dicho cambio solamente se permite cambiar 3 veces los sueños por periodo.  
 
### Características Pantalla 14 Sueños  

Debajo de la pantalla principal encontraremos los siguientes tres botones:

1.- `Agregar Categoría`

2.- `Agregar Subcategoría`

3.- `Agregar Sueño`.

Al presionar cada botón, nos desprende una pantalla de configuración que siguiendo el mismo orden del listado anterior tendremos:

1.1 *Agregar Categoría*

Configuración de la Categoría del sueño que el usuario desea realizar.
 
+ * ID Categoría* 

Número serial Autoincremental 

+ *Categoría*
+ 
Rubro del sueño a realizar por el empleado.

+ *Siguiente*

 Si el usuario hace`click` en el botón **Guardar** podrá grabar la configuración hecha en dicha sección y estará habilitada inmediatamente en el sistema.


Al presionar el botón `Subcategoría` tendrá los siguientes campos para su configuración:

+ *ID Subcategoría*

Número serial autoincremental.

+ *Categoría*

 Área de acción del sueño a realizar.

+ *Nombre Subcategoría*

Nombre asignado por el usuario a la subcategoría que pertenece dicho sueño.

+ *Guardar*

 Si el usuario hace`click` en el botón **Guardar** podrá grabar la configuración hecha en dicha sección y estará habilitada inmediatamente en el sistema.

Si el usuario hace `click`en el botón `Agregar Sueño`tendrá la siguiente pantalla de configuración:

+ *ID Sueño*

Número serial autoincremental.

+ *Seleccione Categoría* 

Combo Box que permite la elección de las categorías asignadas a los sueños por 
parte de cada empresa.

+ *Seleccione Subcategoría* 

Combo Box que permite la elección de las subcategorías asignadas a los sueños por parte de cada empresa.

+ *Escriba su sueño*

 Descripción del sueño que desea realizar cada usuario.


+ *Guardar* 

Si el usuario hace`click` en el botón **Guardar** podrá grabar la configuración hecha en dicha sección y estará habilitada inmediatamente en el sistema y sólo podrá realizar tres cambios de sueños por periodo. 




#Pantalla 14 *Prioridades* para Súper Usuario  y Administrador Dreamz.
-----

*Tipo: Back End, pantalla 15.*

> Cuando el Súper Usuario y el Administrador Dreamz ingresen observaran de inmediato la pantalla **Prioridades**, en donde podrán observar las prioridades por periodo configuradas en el sistema, el responsable de cumplirlas y el estatus que guarda en el tiempo. 

>los usuarios podrán registrar avance en la evolución del cumplimiento de sus prioridades en la columna **acciones** al presionar dicho botón se despliega la pantalla explicada en la siguiente sección *características pantalla 14*

> 
>En caso de no existir prioridades registradas aparecerá una leyenda que diga **No existe ninguna prioridad configurada en el sistema**.
>
>El botón `Agregar Prioridad` permite enlazar al usuario a las pantallas configuración general.
 

###Caracteristicas Pantalla 15. *Prioridades*
  
Una ve que el usuario dio `click`en el botón `Agregar Prioridad` el sistema desplegará la siguiente pantalla con los campos de configuración:

+ *Crear Prioridad* 

Pantalla que permite la edición y creación de prioridades en la organización.

+ *ID Prioridad*

Número serial autoincremental 

+ *Periodo* 

Combo Box que mostrará una lista de opciones de tiempo trimestrales para que el usuario pueda configurar a qué periodo de la operación pertenece la prioridad.

+ *Prioridad*

 Descripción de cada prioridad.
 
+ *Responsable* 

Combo Box que tendrá una lista desplegable con los nombres de los empleados para cuando se quiera delegar alguna prioridad.

1.- Unicamente los “jefes” podrán delegar prioridades.

2.- Entre pares **NO**  se pueden delegar prioridades.

3.- Las prioridades creadas por empleados necesitan autorización del jefe inmediato.
 
+ *Estatus* 

Combo Box que describe la situación corriente de la prioridad.  Si ya fue asignada, si está pendiente de asignar o si ya esta autorizada.

+ *Tipo de prioridad* 

Combo Box que describirá el nivel de objetivo de la prioridad,  la lista tendrá cargadas las opciones Personal, Área, y Empresa.

+ *Guardar Prioridad* 

Cuando el usuario haga `click` en dicho botón automáticamente quedará grabada en el sistema la nueva edición realizada.

Cómo lo explicamos en la introducción a la pantalla principal, cuando el usuario quiera registrar un avance en la columna secciones, al dar `click`en el botón `Registrar Avance`se desplegará la siguiente ventana.

+ *Registrar Avance*

 El usuario podrá registrar los logros realizados en el cumplimiento de cada prioridad.

+ *ID Avance*

Número serial autoincremental.

+ *Prioridad* 

Trabajo a realizar en el/los periodo/s que le sean asignado al usuario.

+ *Semana*

 Semana en la que se cargó la información de avance.

+ *Avance* 

Edición del grado de acercamiento a la conclusión de la prioridad asignada.

+ *Guardar Avance* 

Cuando el usuario Dreamz de `click` a dicho botón, automáticamente la prioridad estará guardada en el sistema y en caso de ser delegada será visible a la persona que se le asignó.



# Pantalla 16 Assestments para Súper Administrador y Usuario Dreamz.

*Tipo: Back End, pantalla 16*
 
>En esta pantalla se cargarán los assessments asignados por usuario, definidos  por las evaluaciones que hayan tenido en el periodo.
>
>Al ingrear el Súper Administador y el Usuario Final podrán ver que tipo de assesment se han cargado por usuario y adjunto estará un archivo con los resultados o la descripción de dicho assesment, seguido de una columna que da la opción de eliminarlo en caso de así quererlo.
 


### Características pantalla 16  *Assestments* para Súper Usuario y Usuario Dreamz .

+ *Assestments* 

Pantalla que permite ver las distintas evaluaciones asignadas por empleado.

Cuando el usuario quiere agregar un nuevo assessment deberá dar `click`en el botón *Agregar Assesment* y se desplegará la siguiente pantalla.
 
+ *ID Assessment*

Número serial autoincremental.

+ *Fecha* 

Calendario en dónde se tendrá que seleccionar la fecha en la que se está configurando el assessment.

+ *Archivo*

El Súper Administrador o el Usuario Dreams podrán cargar los archivos que quieran hacer llegar a cada usuario mediante este comando, el archivo tendrá que ser cargado guardado ensu computadora y en los formatos convencionales Word, Excel, Power Point, PDF.

+ *Guardar Assessment* 

Una vez ejecutada la configuración, el usuario tendrá que pulsar el botón `Guardar` para que el sistema guarde los cambios y estén habilitados inmediatamente.

Si no se ha agregado algún Assestment, el sistema mostrará una leyenda que diga **No hay ningún Assestment configurado**  y el usuario tendrá que dar `click` en dicho botón para comenzar el historial de Assestments.




# Pantalla 17 *Rewarding* para Súper Administrador y Usuario Dreamz.

*Tipo: Back end, pantalla 17*


>El sistema *Rewarding* es un estímulo para que los trabajadores puedan canjear puntos generados por su actividad en el sistema por diferentes beneficios.

>Entendiendo que la generación de puntos es función de la actividad en el sistema, el Súper Administrador o el Usuario Dreamz tienen que asignar a cada actividad un valor en puntos para que cuando el usuario cumpla los criterios que completan una actividad pueda obtener dichos puntos y acumularlos a través del tiempo. 
>
>
>En la pantalla *Rewarding* es donde observarán todas las acciones que tienen dadas en alta en la empresa, que son generadoras de puntos, seguida de las **reglas** por cada acción, que se tienen que cumplir para que los puntos sean asignados, el *estatus* que mediante un check box cuando está seleccionado significará que la actividad está **activa** en el sistema y viceversa. Y por último la columna **Valor Puntos** donde dichos usuarios podrán definir cuantos puntos genera una actividad al usuario que la realizó.

> Es importante tomar en cuenta que dicha pantalla podrá tener **N** actividades listadas. 
> 
>   
Al Finalizar esta sección el usuario podrá guardar valores dando `click` al botón **Guardar Valores**. y automáticamente se desplegará la siguiente pantalla.


+ *Catálogo de premios*

>El Súper Usuario y el Usuario Dreamz podrán configurar todo tipo de premios que la organización va a otorgar a todos aquellos usuarios que administren bien el sistema Dreamz generando puntos por el cumplimiento de sus actividades personales y laborales.

>Cuando el usuario se encuentre en esta sección podrá ver el catálogo de premios cargados en el sistema; en la columna **Puntos** podrán asignar el costo por puntos de cada premio para saber cuántos puntos necesita cada empleado generar para obtener dicho premio.
>
>La columna **Disponibles** mostrará el inventario por premio que existe en la compañía.
>
>En la columna **imagen** deberán de cargar un valor gráfico que describa al premio que se ofrece seguido del estatus que tiene en el sistema de Rewarding,*pues algunos premios pueden aplicar para todo un año y otros unicamente ciertos periodos*.
>
>Al final la columna **Acción** otorga la opción de editar dicha configuración o bien eliminarla.
>
Si no existe ningún premio registrado en el sistema aparecerá una leyenda que diga **No se ha registrado ningún premio en el sistema**.

El usuario podrá agregar cuantos premios la organización quiera entregar mediante el botón **Agregar Premios**. y se desplegará la siguiente pantalla:
 

+ *Agregar Premio* 

Configuración de nuevo premio que la compañía otorgará.

+ *ID Premio* 

Número serial autoincremental.

+ *Nombre* 

Nombre del premio a otorgar.

+ *Valor en Puntos* 

Costo en puntos del premio configurado.

+ *Cantidad disponible*

Inventario con el que empieza la empresa a otorgar cada uno de los premios. 
Se descontará automáticamente cada que se entregue uno.

+ *Imagen* 

Imagen JPG que describa gráficamente el premio a otorgar, la imagen tendrá que ser cargada desde la computadora del usuaro de lo contrario marcará error.

+ *Premio Activo* 

Check Box que permite mantener activo o inactivo un premio.

+ *Guardar Premio* 

Cuando el usuario quiera guardar la configuración que ha realizado de acción sobre un premio tendrá que dar `click` para que esté disponible en el apartado de Rewarding.



## Pantalla 18- *Periodo/ Semanas*  para Súper Administrador Usuario Dreamz.

*Tipo: Back End, pantalla 18*

> El Súper Administrador y el Usuario Dreamz observarán la pantalla  ** Periodos / Semanas** en la que podrán definir a partir de qué día la empresa comienza a tomar sus calendarios de operación de manera trimestral.
> 
>La columna **Periodo** muestra el año y el trimestre que estará en curso.
>
>En la columna **DE – A**,  el Súper Administrador o el Usuario Dreamz podrán definir a partir de que día del mes comienza a operar su primer trimestre y en qué día termina.

>La columna  **Acciones** será la cual permita a los usuarios modificar la configuración de cada periodo o bien eliminarlo.
>
> *Cada trimestre constará forzosamente de 13 semanas.*
> 
> En la parte inferior observamos el botón `Agregar Periodo`el cual una vez hecho `click`nos mostrará la siguiente pantalla de configuración: 

### Características pantalla 18 Periodo/Semanas
 
*Agregar periodo*
 
Botón que definirá si el usuario quiere agregar un nuevo periodo al catalogo de actividades de la compañía, en caso de que no exista ningún periodo cargado, el sistema mostrará una leyenda que diga **No existe ningún periodo configurado en el sistema**.
 
+ *ID PERIODO* 

Número serial autoincremental.

+ *Nombre* 

Año y/o trimestre del periodo a configurar.
 
+ *Inicio Periodo* 

El usuario tendrá que seleccionar en el calendario la fecha en la que iniciará el periodo a configurar.

+ *Fin Periodo*

El usuario tendrá que seleccionar en el calendario la fecha en la que finalizará el periodo a configurar.

+ *Periodo Activo* 

Check box que enumera si el periodo está activo o no en el sistema.

+ *Guardar periodo*  

Si el usuario desea guardar los cambios realizados en la configuración del periodo deberá de dar `click` en dicho botón para que esté disponible en el sistema de manera inmediata.


#Pantalla 19  Idiomas para Súper Administrador.
---


>El Súper Administrador **será el único usuario que tenga acceso a esta pantalla** en donde podrá configurar los idiomas en los que estará disponible cada sistema instalado por empresa. 
>
>Los idiomas se cargarán mediante un archivo de etiquetas para que pueda mostrar las traducciones.
>
>Una empresa puede tener uno o más idiomas disponibles en su aplicación.
 

### Caracteristicas pantalla 19 Idiomas: Súper Administrador 

>Al ingresar observará la pantalla **Idiomas**  en donde el Súper Administrador podrá observar los idiomas que tiene dados de alta en su perfil general y los que podrá instalar en las empresas que contraten los servicios de Dreamz.

>En dicha pantalla encontrará el nombre del **idioma** que se ha cargado, su estatus de actividad, y el archivo que contiene las etiquetas de cada idioma.

>La columna **Archivo** incluirá el archivo cargado con la etiqueta de idioma con el que se deseé instalar el sistema.  Cada archivo con la etiqueta de idioma tiene que ser cargado directamente desde la computadora del usuario en un archivo **.PHP**

>La columna **Acción** decide si se mantiene o se elimina dicho idioma de la congifuración general.
>
>El Súper Administrador podrá cargar los idiomas que deseé mediante el botón **Agregar Idioma**. En caso de no existir ningún idioma cargado el sistema mostrará una leyenda que diga **No existe ningún idioma configurado en el sistema** y aparecerá la siguiente pantalla:

###Caracteristicas Pantalla 19 Idiomas.

> Una vez que el usuario haya hecho `click` en el botón `Agregar Idioma` aparecerá la siguiente pantalla para comenzar la configuración.
> 
+ *ID Idioma* 

Número serial autoincremental.

+ *Archivo* 

Campo de valor disponible para adjuntar un archivo de etiquetas de idioma .PHP, y tendrá que ser cargado desde la computadora del Súper Usuario.

+ *Guardar Idioma* 

Si el usuario desea guardar los cambios realizados en la configuración tendrá que seleccionar la opción **Guardar Idioma** para que el sistema este habilitado inmediatamente.



# Pantalla 20 *País*           ... para Súper Administrador.
-----
* Tipo Back End, pantalla 20*

>El Súper Administrador podrá ingresar a esta pantalla y  agregar el país donde el sistema operará. Se pueden integrar **N** países a la configuración general de este perfil.

 
### Características Pantalla 20 País


+ *País* 

El Súper Administrador podrá ver el catálogo de países donde el sistema está instalado.

+ *Estatus* 

Observará el estatus que guarda el sistema si se encuentra activo o inactivo 

+ *Acciones* 

El usuario podrá eliminar el país configurado.


El usuario al hacer `click` en el botón **Agregar País** se desplegará la siguiente pantalla:


+ *Agregar País* 

+ *ID País*

 Número serial autoincremental

+ *País*

País donde operará el sistema.

+ *Guardar País* 
+
Guardar los cambios realizados en la configuración.


En caso de no haber paises cofigurados el sistema mostrará una leyenda que diga **No hay países configurados en el sistema.** 

# Pantalla 21 *Posición / Puesto*      para Super Administrador / Usuario Dreamz
----
*Tipo: Back End, pantalla 21*

>El Súper Administrador y el Usuario Dreamz al ingresar observarán inmediatamente la pantalla **Posición / Puesto** en donde podrán ver las configuraciones realizadas hasta el momento en los distintos niveles de jerarquía que la compañía tenga y en las distintas áreas.

>Como en el resto de las pantallas de configuración back end la sección **Acciones** les permitirá modificar la edición realizada de cada campo o bien eliminarla.

 Sí el Súper administrador desea agregar una nueva posición o un nuevo puesto al sistema tendrá que dar `click`en el botón **Agregar Posición** y se deseplegará la siguiente pantalla:  

###Características pantalla 21 Posición /  Puesto.
    

+ *ID Posición puesto* 

Número serial autoincremental.

+ *Área/Departamento* 

Combo Box que tendrá cargadas todas las áreas y departamentos de la compañía para su selección.

+ *Nombre de Posición* 

Cargo que ocupa el usuario en la empresa.

+ *Guardar País* 

El usuario podrá guardar los cambios realizados en la configuración solamente dando `click` a dicho botón para que estén inmediatamente visibles en el sistema.


#Pantalla 22 Industria  Súper Administrador.
----

>El Súper Administrador podrá configurar **N** industrias en esta pantalla en la que al abrirla encontrará la sección **Industria** que representa el resumen general del tipo de industrias dadas en el sistema. 
>
>El botón **Acciones** ofrece la oportunidad de modificar o eliminar alguna industria programada. 

Si el usuario quiere agregar una nueva industria tendrá que dar `click`en la pantalla **Agregar Industria**.

#### Características Pantalla 22 Industria para Súper Administrador.

*Agregar Industria* 

El Súper Administrador  tendrá que hacer `click` en dicho botón para poder generar una nueva configuración. Si el sistema no tiene  ninguna industria cargada mostrará una leyenda que diga **No se ha cargado ninguna industria en el sistema** y aparecerá el botón para poder comenzar la configuración.

+ *ID Industria** 

Número serial autoincremental. 

+ *Nombre de la Industria* 

Rama industrial a la que pertenece la compañía que está instalando el sistema.

+ *Guardar Industria* 

Si el usuario desea conservar la configuración efectuada deberá de dar `click` en dicho botón para que la industria esté disponible en el sistema.


# Pantalla 23 *Escolaridad*  para Súper Administrador y Usuario Dreamz

*Tipo: Back End, pantalla 23*

>En la pantalla escolaridad, el Súper Administrador y el Usuario Dreamz podrán configurar el grado de escolaridad que tiene cada empleado de la compañía, al igual que las demás pantallas el botón **Acciones** servirá para editar o eliminar las configuraciones realizadas en el sistema.


Si el usuario quiere agregar una nueva escolaridad tendrá que dar `click`en la pantalla **Agregar Escolaridad**. y se desplegará la siguiente pantalla de configuración.

### Características pantalla 23 Escolaridad 

+ *Agregar Escolaridad* 


+ *ID Escolaridad* 

Número serial Autoincremental.

+ *Nombre Escolaridad* 

Titulo del grado escolar del empleado.

+ *Guardar Escolaridad* 

Sí el usuario desea guardar los cambios realizados en la configuración tendrá que hacer `Click` en este botón para que la Escolaridad esté habilitada en el sistema.

Si en el sistema no se ha cargado ninguna **Escolaridad**, se mostrará un mensaje que diga **No se ha cargado ninguna escolaridad en el sistema** seguida del botón **Agregar**.




# Pantalla 24 One Page sección 	para Súper Administrador, Usuario Dreamz y Usuario Final

*Tipo: Back End pantalla 24*

>La pantalla **One Page** es una pantalla de análisis donde podremos determinar ciertos criterios y rangos de búsqueda para tener datos consolidados por periodos y obtener conclusiones, las secciones van de lo general a lo particular desde datos de desempeño empresa, área hasta los del empleado.

> Todos los usuarios al ingresar a la pantalla **One Page** podrán ver la primera sección compuesta por los valores **Empresa** **Fecha** y  **Periodo**  la primera será asignada por el sistema por default, en Fecha y Periodo el usuario tendrá que poner las fechas que quiera consultar.
> 
> El objetivo del check box con el nombre **Copiar último one page**. Es crear el reporte One Page que muestra todo lo que se estableció en el sistema. 

 
+ *Características* 

###### Primera sección One Page 

+ *Empresa* 

Este campo se llenará automáticamente.

+ *Periodo* 

Rango de tiempo que los usuarios quieran observar la configuración establecida en el sistema.

+ *Fecha* 

Días del periodo en los que se deseé observar dicha información. 

+ *Agregar Valores del Trimestre* 

Lista de texto que permite agregar o quitar valores (badges) del periodo a analizar. **La selección de dichos valores tendrá que ser habilitada para múltiple selección y hacer el sistema más amigable**.



###### Segunda sección  One Page 

Los usuarios tendrán que ingresar en la caja de texto **Propósito** el propósito del trimestre de la compañía, del área o del usuario final.
 
+ En el campo **Acciones** los usuarios tendrán que detallar qué acciones lograrán para realizar dicho propósito, se pueden hacer **N** acciones mediante el botón **Agregar**.

+ El campo **Profit/x** será un factor asignado por el Súper Administrador a cada empresa.

+ El *BHAG* es un campo de texto que se explicará de acuerdo a la metodología aplicada para la empresa.



######Pantalla tercera sección One Page.  

 **Targets (3 a 5 años)**

Objetivos a los que se tendrán que guiar dentro de los próximos años.

++ *Nombre* 

El usuario tendrá que asignar un nombre a su objetivo que vaya de 3 a 5 años.

+ *Descripción* 

El usuario describirá el objetivo que va a lograr, y puede agregar **N** número de objetivos mediante el botón **Agregar**.

+ *Sandbox* 

Campo de texto definido por el usuario.

+ *Key Thrusts /Capabilities* 

Campo de texto definido por el usuario.

+ *Brand Promise KPI* 

Indicadores de la promesa de marca.

+ *Brand Promises*  

Cuál es la promesa de marca de la empresa.


+ *Goals 1 year* 

Metas anuales del usuario final, área o compañía. Se podrán agregar **N** metas anuales.

+ *Key Initiatives* 

Iniciativas claves para el logro de la meta. Se podrán agregar **N** iniciativas.

+ *Critical People* 

 Semáforos de rendimientos de personal de las metas logradas.

+ *Critical Process* 

Semáforos de rendimientos de procesos cumplidos en el periodo.

#### Cuarta Sección One Page
 
+ *Agregar objetivos del trimestre de la empresa.*

Caja de texto donde los usuarios podrán seleccionar, qué objetivos trimestrales de la empresa quieren analizar. *La selección de los objetivos deberá de ser habilitada para múltiples selecciones.*

+ *Agregar prioridades del trimestre de la empresa*
 
Caja de texto donde los usuarios podrán seleccionar, qué prioridades trimestrales de la empresa quieren analizar. La selección de las prioridades deberá de ser habilitada para múltiples selecciones.

+ *Critical People*  

Semáforos de rendimientos de personal de las metas logradas

+ *Critical Process* 

Semáforos de rendimientos de procesos cumplidos en e periodo.

 
+ *Tema* 

La empresa decidirá un tema por periodo de operación para tomarlo como base en la compañía.

+ *Deadline* 

Fecha limite de operación.

+ *Número critico* 

Campo numérico que el usuario deberá de establecer.

+ *Celebration*  

Festejo.

+ *Reward* 

Premios logrados en el periodo por el canje de puntos.



###### Quinta Sección One Page

+ *Agregar objetivos del trimestre personales*

Caja de texto habilitada para agregar al reporte los avances de los objetivos personales en el periodo. La selección podrá ser múltiple.

+ *Agregar Prioridades Trimestrales Personales*

Caja de texto habilitada para agregar al reporte los avances de las prioridades 
personales en el periodo. La selección podrá ser múltiple.

+ *Critical People*  

Semáforos de rendimientos de personal de las metas logradas


+ *Critical Process* 

Semáforos de rendimientos de procesos cumplidos en e periodo.

+ *Fuerzas* 

Fortalezas del usuario, podrá agregar **N** fortalezas.

+ *Debilidades* 

Debilidades del usuario, podrá agregar N debilidades.

+ *Tendencias* 

Usuario deberá capturar las tendencias que tiene que seguir en el periodo, podrá agregar **N** tendencias.

+ *Process* 

Procesos que se necesitan para lograr metas.

+ *Make/ Buy* 

Qué procesos necesita el usuario para hacer cosas y comprarlas. Se podrán agregar los que sean necesarios mediante el botón **Agregar**.

+ **Sell** 

Qué procesos necesita el usuario para vender cosas. Se podrán agregar las que sean necesarias mediante el botón **Agregar**.

+ *Recording Keeping* 

Qué necesita el usuario para mantener números altos.  Se podrán agregar los que sean necesarios mediante el botón **Agregar**.

+ *Empelados* 

Qué empleados necesita para lograr dichas metas. Se podrán agregar los que sean necesarios mediante el botón **Agregar.**

+ *Clientes*  

A qué clientes tiene que buscar / conservar para lograr resultados. Se podrán agregar los que sean necesarios mediante el botón **Agregar.**

+ *Colaboradores* 

Personal secundario de utilidad para el logro de metas. Se podrán agregar los que sean necesarios mediante el botón **Agregar**.


# Pantalla 25 Task Manager para  Súper Administrador / Usuario Dremz.

>En esta pantalla el tanto el Súper Administrador como el Usuario Dreamz al ingresar a la pagina se encontrarán con la sección **Task Manager**  en donde podrán observar un resumen completo de las taras generadas en la empresa y el responsable de su cumplimiento.
>
>Los usuarios tendrán la opción de **Filtrar tareas por** mediante el combo box superior con dicho nombre, el cual desplegará una lista con los distintos conceptos de tareas que la empresa quiera programar.
>
>Además para completar el proceso de *filtrado* podrán hacer `click` en el check box  **Mis Tareas** y **Tareas Delegadas** para poder filtrar también la información por dichos conceptos. 

En la parte inferior izquierda podrán **Agregar tareas** al hacer `click`en el botón con dicho nombre y desplegará la pantalla siguiente: 

### Características Task Manager

+ *Agregar Tarea* 

Si el usuario desea agregar una tarea nueva deberá hacer `click` en el botón Agregar Tarea. Si el sistema no tiene ninguna tarea agregada mostrará una leyenda que diga **No se ha cargado ninguna tarea en el sistema**.
           
+ *ID Tarea* 

Número serial autoincremental.

+ *Tarea* 

Descripción de la tarea a realizar.

+ *Prioridad* 

Combo Box  que describirá los valores de prioridades cargados en el sistema para su selección.

+ *Responsable* 

Combo Box que describirá los valores de las personas que se harán responsables del cumplimiento de las tareas; Se tendrán que cargar sus nombres en una lista previa para su selección.

+ *Participantes* 

Se cargarán en dos listas, en las cuales se podrá elegir que usuario/s participarán en la actividad.

+ *Fecha de Vencimiento* 

Calendario desplegable para seleccionar la fecha de vencimiento de tarea asignada.

+ *Estatus* 

Etapa de avance del proceso en el que se encuentra la tarea.

+ *Guardar Tarea*

El usuario al dar `click` en dicho botón podrá guardar los cambios efectuados en la configuración del Task Manager y las tareas serán asignadas de acuerdo a los criterios que eligió de manera inmediata.













