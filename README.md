Trabajo-con-LaTex
=================

Aplicaciones exitosas en terminos de usuario de Context-Aware 
\documentclass[12pt,a4paper,spanish]{report} %%%Esto indica el tipo de documento.
%Va a ser de tipo (report), el tamaño es a4, la lengua castellano (spanish)y la fuente de tipo "paper"%%%
\usepackage{babel} %%%Incluimos el paquete Babel
%que sirve para separar correctamente
%las palabras de multitud de idiomas%%%
\usepackage[latin1]{inputenc}%%%Este paquete permite poner acentos directamente%%%
\usepackage{indentfirst}%%%Espaciado de
%primera línea de cada párrafo%%%
\usepackage[pdflatex]{graphicx}%%%para poder insertar imagenes
\author{NOMBRE: Pedro Manuel Gómez Cano \\\\DNI: 23293223-L \\\\ASIGNATURA:Tecnología específica de la ingeniería informática}%%%para %poner el autor del documento y aprovecho para poner mi DNI y la asignatura.Pongo las barras \\ para que no salga todo seguido y salta a %la linea siguiente
\title{{\bfseries Aplicaciones exitosas  en términos de usuarios de context-aware.}}%%%pongo el titulo y bfseries para ponerle negrita
\date{10 de mayo de 2012}%%%para poner la fecha de creacion del documento, si no se pone pone por defecto la del dia de creacion.

\begin{document}%%%Empieza del documento
\maketitle

\chapter{{\bfseries Introducción y motivación  } }%%%chapter es para que vaya enumerando el texto por capitulos este es el primero y lo pongo en negrita.


 
Las nuevas generaciones de dispositivos móviles poseen una capacidad de cómputo cada vez mayor. Hoy en día es común ver teléfonos celulares que pueden quitar fotos, grabar video, reproducir músicas y correr programas hechos por terceros. La interconexión de distintos dispositivos forma una red en la cual existe gran cantidad de información que puede ser aprovechada.

La forma en que interactúa el usuario con el sistema está cambiando. El usuario está dejando el ambiente virtual del tradicional escritorio de trabajo para interactuar con un gran número de dispositivos y lo hace de manera transparente. Una nueva generación donde se integra capacidad de cómputo a los objetos de todos los días, para aumentar su funcionalidad y transformar su uso de manera más conveniente para las personas.

La disponibilidad cada vez mayor de capacidad de cómputo permitirá que la
computación sea invisible ubicando sistemas embebidos en nuestro ambiente de tal forma que los utilicemos sin siquiera pensar en ello, a esto se conoce como computación ubicua.

La información en el ambiente físico y electrónico crea un contexto para la interacción entre humanos y servicios computacionales. Se define contexto como cualquier información que caracteriza a una situación entre usuario, aplicación y el ambiente que los rodea. Un sistema que es capaz de extraer, interpretar y usar información contextual y adaptar su comportamiento de acuerdo a ella se conoce como una aplicación “Context-Aware”.

Cuando nosotros los humanos interactuamos con otras personas y los ambientes que nos rodean, creamos implícitamente una información actual de la situación. Podemos intuitivamente deducir e interpretar el contexto de la situación actual y reaccionar de la manera apropiada. Por ejemplo, una persona discutiendo con otra automáticamente observa el gesto y el tono de voz de quién habla y reacciona apropiadamente.

Las computadoras no son buenas como los humanos en deducir la información del ambiente y en usar eso para interactuar. Estas no pueden fácilmente adquirir información de manera transparente ya que el ambiente es altamente dinámico y complejo y ésta debe ser adquirida, filtrada, fusionada y finalmente interpretada. Esto es un desafío para la interacción humano-computadora. Por ejemplo, sería bueno si uno pudiese obtener servicios de información de acuerdo a su actual actividad y lugar donde se encuentre, como si estamos en un estadio se pueda obtener la información de los jugadores o verificar el tráfico alrededor del estadio. Existen diferentes maneras de como la información del contexto puede ser usada para hacer sistemas y aplicaciones mas fácil de usar, flexible y adaptable.
El uso de información de contexto es especialmente importante en ambientes móviles, donde la interacción, ejecución y el uso necesita cambios rápidos.


\chapter{{\bfseries Context-Aware}}%%%este es el capitulo 2 y en negrita.

\section{{\bfseries Concepto}}%%%"section" es para dividirlo en secciones el segundo capitulo.

Contexto es cualquier información que puede ser usado para caracterizar la situación de una entidad. Una entidad es una persona, lugar u objeto que es considerado relevante para la interacción entre un usuario y una aplicación, incluyendo el usuario y la aplicación. 
Los tres aspectos importantes del contexto son: dónde estás, con quién estás y qué recursos están cerca. Contexto es más que posición del usuario, porque otras cosas de interés son también móviles y cambiantes. Contexto incluye iluminación, nivel de ruido, conectividad de red,
los costes de comunicación, ancho de banda de comunicación, y también la situación social. Casi cualquier información disponible en el tiempo de la interacción puede ser vista como información del contexto. 
\\\\Algunos ejemplos son:
\\\\ {\bfseries Identidad.}
\\ {\bfseries Información espacial:} lugar, orientación, velocidad y aceleración.
\\ {\bfseries Información temporal:} hora del día, fecha, y estación del año.
\\ {\bfseries Información ambiental:} temperatura, calidad del aire, y nivel de iluminación o ruido.
\\ {\bfseries Situación social:} con quién estas, y personas que están cercas.
\\ {\bfseries Recurso que están cerca:} dispositivos accesibles, y hosts.
\\ {\bfseries Recursos disponibles:} batería, pantalla, red, y ancho de banda.
\\ {\bfseries Medidas fisiológicas:} presión de sangre, respiración, actividad muscular y tono de voz.
\\ {\bfseries Actividad:} hablando, leyendo, caminando, y corriendo.
\\ {\bfseries Calendario y agendas.}

\begin{figure}%%% Vamos a insertar una imagen
    \begin{center}%%%para que este centrada
        \includegraphics{imagen1}%%%incluye la imagen, que tiene que estar en el mismo directorio donde este el archivo.txt
        \caption{Enfoque de Context-Aware}%%%descripcion de la figura      
        \label{marcador_figura}
    \end{center}
\end{figure}

La definición de contexto no hace distinción entre la información adquirida manualmente y aquella adquirida de forma automática. En un ambiente ideal el contexto debería de ser adquirido automáticamente. Sin embargo, en el mundo real, mucha información contextual no puede ser obtenida automáticamente y los usuarios deben de proveerla manualmente. 
La información contextual esta relacionada a una interacción y la manera de cómo es obtenida no debe de cambiar el modo en el que se la utiliza.
Awareness, genéricamente, dentro de computación ubicua significa tener en cuenta cierta información para sacar provecho, ejemplo:

\\{\bfseries Location aware:} utiliza información de localización de usuario para filtración de servicios o adaptación de los mismos.
\\{\bfseries Power aware:} tiene en cuenta el nivel de batería para optimizar su consumo en términos de acciones realizadas internamente.
\\{\bfseries Contex-awareness:} hacer uso del contexto del usuario.

Un sistema es context-aware si puede extraer, interpretar y usar la información del contexto y adaptar a su funcionalidad al actual contexto en uso. Computación Context-Aware es un campo que recibe mucha atención en investigación y desarrollo. 

Los sistemas de context-aware pueden ser:

\\{\bfseries • Sistema Adaptativo:} estos aprenden las preferencias de sus usuarios y los ajustan.
\\{\bfseries • Sistema de respuesta:} estos anticipan las necesidades del usuario en un ambiente cambiante.
\\{\bfseries • Sistema Proactivo:} estos son orientados a objetivo, capaz de tomar iniciativa, no solo de reaccionar al ambiente.
\\{\bfseries • Sistema Autónomas:} estos pueden actuar independientemente sin interferencia humana.

\chapter{{\bfseries Aplicaciones exitosas a nivel de usuario.}}%%%nuevo capitulo

\section{{\bfseries Active Badge System.}}%%%seccion 1 del nuevo capitulo.

Una de las principales aplicaciones con context-aware es El Active Badge System( sistema de tarjetas de activo).
La insignia activo fue concebido, diseñado y prototipos entre 1989 y 1992 considerada como la primera de las aplicaciones contex-aware. En su forma original, la insignia de una transmisión única de cinco bits de código cada quince segundos. Las sucesivas versiones se han ampliado el tamaño de la funcionalidad y el espacio de direcciones de la placa.
 La versión actual de la placa incorpora un microprocesador pequeño, ofreciendo una comunicación bidireccional, y una dirección de 48 bits. 
En varias ocasiones Andy Hopper , Roy Want, Andy Harter , Blackie Tom, Picar Marcos, Gilmurray Damián, y Bennett Frazer, han hecho una contribución al desarrollo de la placa y el software de apoyo. 
El sistema de Placa activa proporciona un medio para localizar los individuos dentro de un edificio mediante la determinación de la localización de su Placa activa. Este pequeño dispositivo usado por el personal transmite una única señal infrarroja cada 10 segundos. Cada oficina dentro de un edificio está equipado con uno o más sensores en red que detectan estas transmisiones. La ubicación de la placa (y por tanto su portador) puede así ser determinada sobre la base de la información proporcionada por estos sensores. 

\begin{figure}%%%incluimos otra figura
    \begin{center}
        \includegraphics[width=0.7\textwidth]{imagen2}%%%como quedaba muy grande he tenido que reducirla al 70% con width=0.7/textwidth
        \caption{ Ejemplo de utilizacion en un hospital}      
        \label{marcador_figura}
    \end{center}
\end{figure}


Más de 1500 tarjetas y 2000 sensores están desplegados en toda una serie de universidades europeas, incluida la Universidad de Kent , el Imperial College de Londres , la Universidad de Lancaster , y la Universidad de Twente, Países Bajos . En los EE.UU., Xerox PARC , DEC research laboratories , Bellcore y MIT Media Lab han recibido sistemas activos Badge. 
El mayor sistema único se encuentra en el Laboratorio de Cómputo de la Universidad de Cambridge , donde más de 200 escudos y 300 sensores son de uso diario. La información sobre la ubicación de los individuos también se intercambian entre estos sitios en su caso. 
Este Servicio de Comunicación Global ofrece una forma de determinar los medios más adecuados para ponerse en contacto con un individuo. 

\section{{\bfseries Stick-e Documents.}}

Otro de los grandes exitos es Stick-e Documents ya que fue uno de los primeros pasos que se dieron hacia la creación de frameworks para aplicaciones Context-Aware fueron los Stick-e Documents de Brown .Se trata de una metáfora creada para aplicaciones Context-Aware en forma de notas que muestran mensajes dadas unas ciertas condiciones de localización de usuarios. 
En los inicios de estos sistemas, el objetivo de la mayoría de aplicaciones era presentar información cuando se dieran ciertas condiciones relacionadas con la posición de usuarios u algún otro tipo de contexto dentro de un entorno. Cada Stick-e Document consta del propio contenido o mensaje, y del contexto relacionado. En un ejemplo, cuando un usuario lleva consigo una PDA que usa algún medio de localización, se consigue tener una localización constante. Así, el propio usuario utilizando su PDA puede dejar un mensaje en la localización donde se encuentra en ese momento o en cualquier otro punto. Cuando pase una vez más por ese lugar el Stick-e note es mostrado con el mensaje. Es una forma electrónica de dejar Post-its a lo largo de determinados lugares.

Además, estos mensajes pueden dispararse no sólo bajo condiciones de localización, sino cuando se cumpla alguna otra condición de contexto. Las condiciones posibles según los Stick-e Documents pueden basarse en:

\\{\bfseries · Localización:} que puede ser el emplazamiento de una nota en un lugar.
\\{\bfseries · Proximidad a otros objetos o personas:} Cuando se detecte la presencia próxima de un elemento señalado, puede dispararse el Stick-e Document.
\\{\bfseries · Estados críticos:} En el momento en que ciertos sensores detecten un valor que se sale del rango aceptado, puede mostrarse un mensaje.
\\{\bfseries · Estados del computador o dispositivo:} Condiciones como entrar en una carpeta o  abrir cierto archivo pueden ser condiciones para mostrar mensajes.
\\{\bfseries · Compañeros imaginarios:} Brown los llama Spirits y representan objetos o gente que no existe realmente o que no lleva ningún dispositivo de localización que el sistema pueda percibir. Al no poder ser detectados, sería el usuario el que manualmente indicase que está próximo a un Spirit. Los mensajes pueden dejarse ligados a un Spirit para que aparezcan todos juntos al indicar que el compañero imaginario está próximo.
\\{\bfseries · Tiempo:} Los mensajes pueden mostrarse a una determinada hora. Este es el tipo de mensaje más comúnmente extendido.

Estas condiciones incluso pueden combinarse para crear condiciones más completas. Por ejemplo podrían combinarse condiciones de proximidad a una persona y localización.
Brown hace referencia a un Stick-e Document como un conjunto de Stick-e Notes y define una Note como mensaje con su contexto y condiciones. Un Stick-e Document sería entonces un conjunto de Notes. De esa forma, todo el conjunto de Stick-e notes que se dejan en un Spirit, compone un Stick-e Document.
El contexto puede ser tanto un menaje de texto, como una página HTML o un programa que ha de ser ejecutado:
Cuando en una nota se refiere a contexto, en realidad se hace referencia a las condiciones de activación de la Stick-e Note.
Este framework ayuda a realizar aplicaciones Context-Aware, principalmente definiendo una metáfora de triggers que se accionan bajo condiciones. Sin embargo no provee de componentes explícitos para solucionar problemas como la heterogeneidad del contexto, la necesidad de abstracción del medio físico de los sensores, etc. Las reglas que se especifican como condiciones representan los primeros pasos de una reacción hacia el contexto, aunque son insuficientes para aplicaciones con una necesidad más compleja y contexto de más alto nivel.
Este marco de aplicaciones tampoco proporciona ningún componente que se encargue de la creación de contexto de alto nivel ni el razonamiento sobre él. Además, el ámbito del contexto es muy limitado.
Todos los inconvenientes relatados anteriormente se deben principalmente a que se trata de una herramienta que apareció en los orígenes de las aplicaciones Context-Aware, cuando las definiciones de contexto y Context-Aware tenían unos límites muy cerrados. A pesar de estas limitaciones, los Stick-e Documents consiguen hacer una generalización eficiente en un framework y lo más importante: el propio concepto de Post-it electrónico aún hoy sigue siendo referencia para aplicaciones modernas.

\section{{\bfseries Serendipity.}}

Otra aplicación es Serendipity , que analiza los patrones de cercanía entre personas para analizar compatibilidades y gente que no se conoce pero se debería conocer. Analizando a través de Bluetooth quién y en qué momento del día está en cada lugar.  Se despliegan balizas Bluetooth que recogen qué teléfonos están cerca de ellas y envían la información a servidores que analizan los datos.  
Estos datos son después contrastados para analizar varias características de cada usuario: dónde suele pasar ciertos momentos del día, qué personas hay junto a él y cómo se relacionan con él. El tiempo de permanencia juntos los autores lo toman como un factor crucial, así como el lugar en el que se da la situación. Información de cercanía alrededor de una máquina de café no tiene el mismo significado que información de cercanía en una mesa de cafetería. 

Con hechos como estos, Serendipity calcula las relaciones interpersonales y la gente que podría o debería conocerse entre ella. 

\begin{figure}
    \begin{center}
        \includegraphics{imagen3}
        \caption{Análisis realizado a un individuo en Serendipity acerca de la cercanía con un amigo (a) y un compañero de oficina (b) .}      
        \label{marcador_figura}
    \end{center}
\end{figure}

Análisis realizado a un individuo en Serendipity acerca de la cercanía con un amigo (a) y un compañero de oficina (b) .

Esta aplicación tiene según los autores tres usos principales: 

\\{\bfseries • Empresa:} Analizar las relaciones sociales dentro de una empresa para, entre otros, poder averiguar la comunicación entre las personas de  una organización y poder situar cerca de las que más necesidad tienen de comunicarse entre ellas. 
\\{\bfseries • Citas:} Analizar compatibilidades entre diferentes personas para poner en común gente que podría ser sentimentalmente compatible. 
\\{\bfseries • Conferencias:} Analizar intereses similares entre asistentes a conferencias para poner en común gente con los mismos objetivos de investigación y que podrían colaborar juntos en proyectos.

\chapter{{\bfseries Conclusión.}}

La computación Contex-aware  es muy interesante de investigar ya que es muy amplio y se puede introducir en todos los ámbitos de nuestro entorno, pero aun quedan muchos problemas por resolver, por ejemplo, como hacer para que el ordenador tenga un sentido común para diferenciar entre situaciones similares y mejorar las limitaciones que nos da todavía los sensores de reconocimiento. Lo que demuestra, que hemos avanzado bastante en esta rama de al informática, pero esto es solo el comienzo.

\end{document}%%%finalizamos el documento.

