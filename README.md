# QualityTest

Aplicación web demostrativa para practicar pruebas de calidad de software con Selenium IDE.

## Publicar en GitHub Pages
1. Crea un repositorio público en GitHub, por ejemplo `qualitytest`.
2. Sube el archivo `index.html` a la raíz del repositorio.
3. Entra a **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`, y guarda.
6. Espera la publicación. GitHub mostrará la URL de tu página.

## Acceso de demostración
- Correo: `admin@qualitytest.com`
- Contraseña: `Admin123`

## Funciones
- Inicio y cierre de sesión simulado.
- Registro, edición, búsqueda, filtro y eliminación de usuarios.
- Registro, edición, búsqueda, filtro y eliminación de productos.
- Validación de campos obligatorios, correo duplicado, código duplicado, precio y stock.
- Dashboard con indicadores.
- Exportación CSV.
- Persistencia de datos mediante `localStorage`.

## Consideraciones
Es un prototipo académico de frontend. La autenticación no es segura y no existe un servidor ni una base de datos compartida. Los datos se guardan solamente en el navegador y dispositivo donde se utiliza la aplicación. No utilizar información personal real.

## Ideas para Selenium IDE
1. Login con credenciales correctas.
2. Login con contraseña incorrecta.
3. Intentar iniciar sesión con campos vacíos.
4. Navegar entre las secciones.
5. Registrar un usuario válido.
6. Intentar registrar un correo duplicado.
7. Buscar un usuario por nombre.
8. Filtrar usuarios por rol.
9. Editar un usuario.
10. Eliminar un usuario.
11. Registrar un producto válido.
12. Intentar guardar un producto con precio cero.
13. Intentar registrar un código duplicado.
14. Filtrar productos con stock bajo.
15. Buscar un producto por código.
16. Editar y eliminar un producto.
17. Exportar el inventario a CSV.
18. Cerrar sesión y verificar que regrese al login.

Los escenarios no funcionales de rendimiento, seguridad real, accesibilidad formal y compatibilidad requieren herramientas y procedimientos adicionales; esta aplicación no los certifica automáticamente.
