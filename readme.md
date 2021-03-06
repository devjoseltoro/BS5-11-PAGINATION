[![](captura.png)](captura.png "Captura de Pantalla")

# Bootstrap 5 | Pagination

📒 Paginación básica

    📝Si tiene un sitio web con muchas páginas, es posible que desee agregar algún tipo de paginación a cada página.

    📝Para crear una paginación básica, agregue la clase .pagination a un elemento <ul>. Luego agregue el .page-item a cada elemento <li> y una clase .page-link a cada enlace dentro de <li>:
    
        <ul class="pagination">
            <li class="page-item"><a class="page-link" href="#">Previous</a></li>
            <li class="page-item"><a class="page-link" href="#">1</a></li>
            <li class="page-item"><a class="page-link" href="#">2</a></li>
            <li class="page-item"><a class="page-link" href="#">3</a></li>
            <li class="page-item"><a class="page-link" href="#">Next</a></li>
        </ul>

📒 Estado activo

    📝La clase .active se usa para "resaltar" la página actual:

        <ul class="pagination">
            <li class="page-item"><a class="page-link" href="#">Previous</a></li>
            <li class="page-item"><a class="page-link" href="#">1</a></li>
            <li class="page-item active"><a class="page-link" href="#">2</a></li>
            <li class="page-item"><a class="page-link" href="#">3</a></li>
            <li class="page-item"><a class="page-link" href="#">Next</a></li>
        </ul>

📒 Estado deshabilitado

    📝La clase .disabled se usa para enlaces en los que no se puede hacer clic:

    <ul class="pagination">
        <li class="page-item disabled"><a class="page-link" href="#">Previous</a></li>
        <li class="page-item"><a class="page-link" href="#">1</a></li>
        <li class="page-item"><a class="page-link" href="#">2</a></li>
        <li class="page-item"><a class="page-link" href="#">3</a></li>
        <li class="page-item"><a class="page-link" href="#">Next</a></li>
    </ul>

📒 Tamaño de paginación

    📝Los bloques de paginación también se pueden dimensionar a un tamaño más grande o más pequeño:

    📝Agregue la clase .pagination-lg para bloques más grandes o .pagination-sm para bloques más pequeños:

        <ul class="pagination pagination-lg">
            <li class="page-item"><a class="page-link" href="#">Previous</a></li>
            <li class="page-item"><a class="page-link" href="#">1</a></li>
            <li class="page-item"><a class="page-link" href="#">2</a></li>
            <li class="page-item"><a class="page-link" href="#">3</a></li>
            <li class="page-item"><a class="page-link" href="#">Next</a></li>
        </ul>

        <ul class="pagination pagination-sm">
            <li class="page-item"><a class="page-link" href="#">Previous</a></li>
            <li class="page-item"><a class="page-link" href="#">1</a></li>
            <li class="page-item"><a class="page-link" href="#">2</a></li>
            <li class="page-item"><a class="page-link" href="#">3</a></li>
            <li class="page-item"><a class="page-link" href="#">Next</a></li>
        </ul>

📒 Alineación de paginación

    📝Use clases de utilidad para cambiar la alineación de la paginación:

        <!-- Predeterminada (alineada a la izquierda) -->
        <ul class="pagination" style="margin:20px 0">
            <li class="page-item">...</li>
        </ul>

        <!-- Alineado al centro -->
        <ul class="pagination justify-content-center" style="margin:20px 0">
            <li class="page-item">...</li>
        </ul>

        <!-- Alineada a la derecha -->
        <ul class="pagination justify-content-end" style="margin:20px 0">
            <li class="page-item">...</li>
        </ul>

📒 Breadcrumbs (Migas de pan)

    📝Otra forma de paginación son las migas de pan: Photos / Summer 2017 / Italy / Rome

    📝Las clases .breadcrumb y .breadcrumb-item indican la ubicación de la página actual dentro de una jerarquía de navegación:

    <ul class="breadcrumb">
        <li class="breadcrumb-item"><a href="#">Photos</a></li>
        <li class="breadcrumb-item"><a href="#">Summer 2017</a></li>
        <li class="breadcrumb-item"><a href="#">Italy</a></li>
        <li class="breadcrumb-item active">Rome</li>
    </ul>

Redes sociales:

- https://instagram.com/dev.joseltoro
- https://facebook.com/devjoseltoro
- https://tiktok.com/@dev.joseltoro
- https://dev.to/joseltoro
- https://code.dcoder.tech/profile/joseltoro
- https://joseltoro.blogspot.com/
- https://joseltoro.gumroad.com/