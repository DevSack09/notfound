# NotFound

Proyecto web desarrollado en PHP utilizando XAMPP, diseñado para gestionar y mostrar páginas de error personalizadas (404 Not Found) en aplicaciones web.

## Características

- Página de error 404 personalizada y responsiva.
- Fácil integración con proyectos existentes en XAMPP.
- Código modular y fácil de mantener.
- Compatible con PHP 7.x y 8.x.

## Requisitos

- [XAMPP](https://www.apachefriends.org/) instalado.
- PHP 7.0 o superior.
- Navegador web moderno.

## Instalación

1. Clona o descarga este repositorio en la carpeta `htdocs` de XAMPP:
   ```bash
   git clone https://github.com/DevSack09/notfound
   ```
2. Asegúrate de que el directorio sea accesible desde `http://localhost/notfound`.

3. Configura el archivo `.htaccess` para redirigir los errores 404:
   ```
   ErrorDocument 404 /notfound/404.php
   ```

## Uso

- Accede a una ruta inexistente en tu proyecto para ver la página de error personalizada.
- Personaliza el archivo `404.php` según tus necesidades.

## Estructura del Proyecto

```
notfound/
├── 404.php
├── .htaccess
├── assets/
│   └── styles.css
└── README.md
```

## Personalización

- Modifica `404.php` para cambiar el mensaje o el diseño.
- Edita `assets/styles.css` para adaptar los estilos visuales.

## Licencia

Este proyecto está bajo la licencia MIT.

## Autor

- [Tu Nombre](https://github.com/DevSack09/)
