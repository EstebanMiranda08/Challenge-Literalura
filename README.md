# Challenge Literalura

<br></br>
:clipboard:<h1>Descripción:</h1>
<p>Este proyecto es una aplicación llamada Literatura, creada como parte de un desafío de Alura Latam.
Su objetivo es consultar libros en línea usando una base de datos pública llamada Gutendex y guardar la información en una base de datos propia.</p>

<br></br>
:wrench:<h1>Funcionalidad:</h1>
Cuando se inicia, aparece un menú con distintas opciones, entre ellas:

- Buscar un libro por su título (aunque no se escriba completo, el sistema busca coincidencias).
- Ver la lista de libros guardados.
- Ver los autores registrados.
- Consultar qué autores estaban vivos en cierto año.
- Buscar libros según el idioma (escribiendo un código de 2 letras, por ejemplo: "es" para español o "en" para inglés).

- Cada vez que se busca un libro, sus datos (título, autor e idioma) se guardan automáticamente en la base de datos.
- Luego, esa información se puede volver a consultar sin necesidad de buscarla otra vez en línea.
- Si se intenta guardar un libro repetido, el sistema no lo permite.
<br></br>

- `Validaciones:`
- Si se elige una opción incorrecta del menú, aparece un aviso.
- Se pueden consultar varios libros del mismo autor.
- Todo queda registrado para acceder más rápido en el futuro.

:computer:<h1>Tecnologías utilizadas:</h1>
- `Java`
- `API Gutendex`
- `Base de Datos PostgreSQL`
