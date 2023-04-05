# certificacion

README
•	Descripción del proyecto
 
* El proyecto es un blog de noticias sobre libros, donde las personas recomiendan libros a través de sus publicaciones, si el usuario no se encuentra registrado no podrá agregar comentarios, solo ver los últimos libros publicados y sus distintas secciones como: libros infantiles, libros de arte y todos aquellas categorías que se quieran desplegar, una vez registrado el usuario podra subir imágenes de libros, una breve descripción y la imagen y titulo correspondiente al libro, de esto cualquier usuario registrado podrá comentar o dar noticias sobre las publicaciones de cualquier libro y categoría. 
*El proyecto para ser ejecutado en forma local, debe crear la base de datos blog_libros, anexarse un archivo con los datos de las tablas para ser ejecutadas en pg admin y crear la base de datos para su uso, respaldo de la base de datos también se anexa.
*Credenciales de pruebas: usuarios registrados que pueden logearse con los siguientes datos
1 usuario: andres
correo: andres2122@gmail.com
clave: 65432
2 usuario: carlos
correo: carito23@gmail.com
clave: 3456
3 usuario: maria
correo: mari43@gmail.com
clave: 87654
*Tecnologías utilizadas
-cors: v. 2.8.5: este mecanismo o política de seguridad me permite controlar las peticiones HTTP asíncronas que se pueden realizar desde un navegador a un servidor con un dominio diferente de la página cargada originalmente, lo instale para el desarrollo del proyecto.
 -express v. 4.18.2: Este framework backend gratuito y de código abierto para Node.js. gracias a sus herramientas y a la versatilidad de su uso, Su enfoque minimalista, su alta escalabilidad, su velocidad y su rendimiento general son sólo algunas de las razones por las cuales me permitió el desarrollo del proyecto y que lo pueda dejar escalable para agregar nuevos módulos en el futuro.
  -express-fileupload v:1.4.0: En node existen librerías excelentes para subir archivos tales como Multer y Express-fileupload, en este proyecto utilize express-fileupload porque ya había desarrollados proyectos usándolo y se me facilito mas subir las fotos con esta librería.
   -express-handlebars v. 7.0.4: Existen diversos motores de plantillas que podría haber usado en Node, pero me gusta Handlebars por su sencillez. No tienes necesidad de usar otro lenguaje, como ocurre con Jade, y eso lo veo una ventaja, sobre todo cuando quieres hacer un código limpio y de calidad, pero no quieres invertir tiempo en aprender nada nuevo, me facilito hacer varias vistas crear el navbar para todo el proyecto sin necesidad de estar cargándolo en cada página, desarrollar el footer y el navbar por separado y llamarlo en todas las paginas en cuanto a sencillez y robustes por eso fue mi elección.
   -jsonwebtoken v: 9.0.0: me permitió dar seguridad en uso del login ya que el mismo se define un mecanismo para poder propagar entre dos partes, y de forma segura, la identidad de un determinado usuario, además con una serie de claims o privilegios. Estos privilegios están codificados en objetos de tipo JSON, que se incrustan dentro de del payload o cuerpo de un mensaje que va firmado digitalmente.
-moment v. 2.29.4: Esta librería la utilize para manejar todo lo referente a fechas, sus formatos hacer peticiones con now() y  almacenar las fechas correctamente y en un formato estandar a lo largo del proyecto 
 -pg v. 8.10.0:  La use para conectar Node JSo a la base de datos fácilmente a través del paquete pg. que lo instalo en el editor de código de visual studio.
-Boosptra: Se utilizo el el uso de botones, navbar o barra de navegación, creación de formularios.
Visual Studio Code: y por su puestoe el editor potente que lo use como base para el desarrollo de la aplicacion y su gran parte por las extensiones que posee me permitieron personalizar y agregar funcionalidad adicional de forma modular y aislada. 
*me falto colocar la opción de like, de hecho cargue una table like en la base de datos que era: tabla like con los atributos de un id, y un campo nombre like o dislike y un número que era para llevar la cantidad de likes o dislikes, también en la base de datos en la tabla comentarios la clave foranea hacia referencia a esta tabla like sabía que la base de datos estaba bien pero cuando hacia las consultas y los llenados de los likes se me cracheaba la aplicación por eso lo quite de la base de datos y deje solamente la parte funcional para que no me afectara el funcionamiento de los demás items, por tema de tiempo no logre su implementación.




*datos del alumno:
Pedro Emilio Navarro Casanova
rut: 25.963.657-4

*repositorio en git hub:
https://github.com/pedrinchixx/certificacion.git

