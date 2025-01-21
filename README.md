LiterAlura 📚✨

LiterAlura es una aplicación de consola desarrollada en Java con Spring Boot y PostgreSQL, que permite consultar libros de dominio público en distintos idiomas. Para ello, se conecta a la API de Gutenberg, obteniendo información detallada y almacenándola en una base de datos. Este proyecto forma parte del "Challenge One" dentro del programa Alura ONE (Oracle Next Education). 🚀
📖 Funcionamiento

Al iniciar la aplicación, se muestra un menú interactivo con varias opciones:

    🔍 Buscar libros: Obtiene información desde la API de Gutenberg y la guarda en la base de datos.
    📚 Ver libros guardados: Muestra los libros almacenados previamente.
    ✍ Explorar autores: Lista los autores registrados en la base de datos.
    📅 Filtrar autores por año: Permite buscar autores según su año de nacimiento.
    🌍 Filtrar libros por idioma: Muestra libros según su idioma original.

⚙️ Cómo usar la aplicación

    Descargar o clonar el repositorio.
    Abrir el proyecto en IntelliJ IDEA o un IDE compatible con Java y Spring Boot.
    Configurar el archivo application.properties con los datos de conexión a PostgreSQL.
    Ejecutar la clase LiterAluraApplication.

    Importante: Se necesita una instancia activa de PostgreSQL, ya que la base de datos y sus tablas se crearán automáticamente al ejecutar la aplicación.


Autor: Agustin Puebla
