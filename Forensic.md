- La informática forense es la ciencia de adquirir, preservar, obtener y presentar datos que han sido procesados electronicamente y guardados en soportes informáticos. Se trata de una practica cada vez mas habitual debido al uso que actualmente todos realizamos uso de las nuevas tecnologías, y que permite resolver casos policiales o judiciales. 
- Tanto las fuerzas y cuerpos de seguridad del Estado como los peritos informaticos forenses utilizan herramientas y procedimientos especificos para la recoleccion de informacion de dispositivos que van desde computadoras o telefonos moviles hasta servidores de correo electronico, por ejemplo.
- Aunque un delito no sea informatico, si que hay pruebas digitales, y puesto que todas las actividades que se realizan con un dispositivo (de forma manual o automatica) dejan una prueba, es posible que la misma sea analizada junto con el resto de pruebas de un caso.
- Son procedimientos y tecnicas forenses que son utilizados con fines investigativos, en su mayoria criminales.

## Conocimientos necesarios para trabajar en informatica forense

1. Redes. El conocimiento de como se realizan las comunicaciones es vital al moment de querer deshilvanar como sucedio un delito en entornos digitales.
2. Linux. Muchas de las herramientas forenses estan basadas en entornos [[UNIX]], sobre todo las gratuitas.
3. Seguridad informatica. El conocimiento sobre seguridad informatica es muchas veces sumamente util en forense, ya que permite descubrir el modus operandi de un ciberdelincuente, como pudo lograr realizar el delito.
4. Legales. Tener como nocion sobre aspectos legales en base a cada pais es util para saber asociar un supuesto crimen con lo que seria realmente un delito para la ley.
5. Cibercrimen y evidencia digital. La metodologia al momento de recolectar evidencia e identificar lo que se considera un  cibercrimen en el ambito legal, implica una capacitacion especifica sobre ello.
6. Actualizacion permanente. Como todo lo relacionado a la tecnologia, nos obliga a estar a la vanguardia de las nuevas tecnologias y todo lo nuevo que haya para aprender.


## Objetivos de la informatica forense
En caso de que se haya producido una brecha de seguridad, estos son los objetivos esenciales del uso de la **computacion forense**:
1. Ayuda a recuperar, analizar y preservar la computadora y los materiales relacionados de tal manera que ayuda a la agencia de investigacion a presentarlos como evidencia en un tribunal de justicia.
2. Ayuda a postular el motivo detras del crimen y la identidad del principal culpable.
3. Diseñar procedimientos en una presunta escena del crimen que ayudan a garantizar que la evidencia digital obtenida no este corrupta.
4. Adquisicion y duplicacion de datos: recuperacion de archivos eliminados y particiones eliminadas de medios digitales para extraer la evidencia y validarlos
5. Ayuda a identificar...


## Perito Informático
Los **peritos informáticos** son los profesionales que se encargan de dar soporte a particulares, empresas u organizaciones a la hora de presentar pruebas tecnológicas ante un tribunal. Ellos son quien se encargan de analizar la veracidad de dichos pruebas y de exponerlas de forma clara y sencilla para que puedan ser comprendidas por las partes interesadas,  un juez por ejemplo.


## Evidencia digital
- Informacion o datos, almacenados o transmitidos en forma binaria que pueden ser confiados como evidencia.
- **Principios** 
	- Relevancia
	- Confiabilidad: obtenida con un metodo cientifico
	- Suficiencia: los indicios que obtenemos tiene que ser importantes para dar por valida  la evidencia digital.


## Otros aspectos de la evidencia digital
- Estamos hablando de evidencia que sera presentada en un juicio.
- Por lo mismo existe lo que se llama cadena de custodia.
- La obtención de información del dispositivo se debe poder replicar, y jamas trabajar sobre el original (copia forense).
- Hay casos especiales en los que en dispositivos móviles se trabaja sobre los originales y se modifica la evidencia.
- Física: pendrive, discos duros
- Lógica: documentos, archivos, fotos, archivos video, logs, bases de datos.


## Caracteristicas de la evidencia digital
1. Volatil. Facil de perderse por completo
2. Anonima. Muy dificil de atar una evidencia digital a una persona fisica que lo haya ...


## Copia Forense
- Es una replica exacta bit a bit (a dispositivos de almacenamiento)
- Importante: antes de empezar a trabajar o realizar una investigacion, se debe hacer la copia forense, ya que en el proceso de evaluacion, otra persona debe llegar a los mismos resultados que nosotros replicando los pasos que hagamos.
**Copia de evidencia digital**
Copia de la evidencia ...


## Contraperitaje
La idea es botar evidencias por parte de la contraparte al hacer su propio peritaje, por mala praxis, o simplemente se demuestra que el otro perito estaba equivocado.


## Cadena de custodia
- Proceso que define como se debe preservar la ED, desde que es identificada hasta que es depositadahasta su lugar de custodia. Debe estar planificado y normado. Al recibier un elemento debemos ...


## Errores tipicos en la manipulacion de computadoras
- Apagar la computadora
- Desconectar la usb
- No realizar copia forense
- Memoria volatil: memoria que al apagarse la computadora se apaga, podria eliminarse evidencia (contraseñas, datos de navegacion, cookies)


## [[HASH]]
- Es una cadena de texto 
- Un hash es la huella digital de un archivo
- Las funciones hash son irreversibles
- Su salida es de tamaño fijo
- Brinda la posibilidad de verificar que la evidencia digital no haya sido modificada.


## Fases para manejo de evidencia digital
**Identificacion**
Proceso que implica la busqueda, el reconocimiento y la documentacion de posibles evidencias digitales.
**Adquisicion**
Proceso de creacion de una copia de datos dentro de un conjunto definido.
**Recoleccion**
Proceso de recoleccion de los elementos fisicos que contienen evidencia digital potencial.
**Preservacion**
Proceso para mantener y salvaguardar la integridad y/o condicion original de la evidencia digital potencial


## Metodologia de Investigacion
- El EDRM esta diseñado para servir..
- Gobierno de la informacion. Esta es la primera etapa del EDRM y esta destinada a indicar los sistemas nativos en los que viven los datos. Eso puede incluir el servidor de correo electronico, un sistema de chat/mensajeria, bases de datos comerciales, documentos electronicos y otras formas de informacion digital.
- Identificacion: buscar fuentes de informacion para determinar exactamente que datos son y como deben administrarse. Hardware, software, resposables, donde, como, credenciales, storage.
- Preservacion: Aislarlos para que sean legalmente defendibles, razonables, amplios, pero a medida, auditables y repetibles. 


## Recoleccion
- Validar herramientas, licenciamiento valido, hash ejecutable.
- Preparar la estacion de trabajo forense.
- Preparar los dispositivos de almacenamiento mediante formateado a bajo nivel (puestos a cero).
- Dead Collection. Imagen forense, clonado bit a bit. Bloqueo contra escritura por hard o soft. No hacerlo es un error muy grave e irreversible porque se alteraria la evidencia. Caine por ejemplo viene configurado para permitir montar discos en modo solo escritura.
- Live collection. Por ejemplo si es una campañia que su servidor no se puede apagar. Tambien al e...

## Herramientas para adquisicion de imagenes
- Dd (http)...


## E



Recursos
- [Politica de ciberseguridad en El Salvador](https://consulta.innovacion.gob.sv/system/documents/attachments/000/000/003/original/0e8a02f53673daa587b66691b1770faeb1e71c8a.pdf)
- [Ciberseguridad y privacidad de los datos](https://www.hlb.com.sv/ciberseguridad-y-privacidad-de-los-datos/)
- [Glosario del cibercrimen](https://intel471.com/glossary)
- 