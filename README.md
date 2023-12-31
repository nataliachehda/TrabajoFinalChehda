# Trabajo Final React - Natalia Chehda

## Tienda Online de Juguetes, Ropa, Decoración y Amigurumis

Este es un proyecto de una tienda online desarrollada con React Vite, donde podrás encontrar una amplia selección de juguetes, ropa, decoración y amigurumis hechos por abuelos con mucho amor. El objetivo de este proyecto es ofrecer productos de alta calidad, cuidadosamente elaborados y llenos de cariño.

## Tecnologías utilizadas
- Vite
- React
- React Router
- Firebase

## Descripción

La tienda online de juguetes, ropa, decoración y amigurumis es un espacio virtual donde los abuelos comparten su talento y dedicación para crear productos únicos y especiales. Cada artículo ha sido elaborado a mano con materiales de calidad y siguiendo técnicas tradicionales.

## Características

- Amplia selección de productos hechos a mano por abuelos.
- Categorías de productos: juguetes, ropa, decoración y amigurumis.
- Detalles de cada producto, incluyendo nombre, descripción, precio y disponibilidad.
- Gestión de stock por encargo.
- Interfaz de usuario intuitiva y fácil de usar.
- Diseño responsivo para adaptarse a diferentes dispositivos.

## Requisitos Previos

Para ejecutar este proyecto en tu entorno local, debes tener instalado lo siguiente:

- Node.js
- npm (Administrador de paquetes de Node.js)

## Instalación

1. Clona este repositorio en tu máquina local o descárgalo como archivo ZIP.
`bash git clone <URL del repositorio>`
2. Navega hasta el directorio del proyecto.
`cd <directorio del proyecto>`
3. Instala las dependencias del proyecto.
`npm install`
4. Inicia la aplicación.
`npm run dev`
5. Abre tu navegador web y accede a http://localhost:5173/ para ver la tienda online en funcionamiento.

## Configuración de Firebase

Para utilizar Firebase en esta aplicación, debes seguir los siguientes pasos:
1. Crea una cuenta en Firebase y crea un nuevo proyecto.
2. En la sección "Authentication" de Firebase, habilita el proveedor de 3. autenticación de correo electrónico y contraseña.
3. En la sección "Firestore" de Firebase, crea una nueva base de datos y configura las reglas de seguridad para permitir lectura/escritura solamente a usuarios autenticados.
4. En la sección "Project settings" de Firebase, haz clic en "Add app" y sigue las instrucciones para agregar una nueva aplicación web.
5. Copia las credenciales de Firebase y configura las variables de entorno en el archivo .env de tu proyecto.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para obtener más información.
