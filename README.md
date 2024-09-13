GuitarraWeb - Tienda de Guitarras
Bienvenido a GuitarraWeb, una página web para la venta de guitarras, desarrollada como proyecto de aprendizaje utilizando React y Vite. Este proyecto incorpora funcionalidades como un carrito de compras persistente (utilizando localStorage), manejo de estados con useState y efectos con useEffect.

🖥️ Despliegue
El proyecto está desplegado en Netlify y puedes verlo aquí: https://guitarraweb.netlify.app

🚀 Características
Catálogo de guitarras: Cada guitarra muestra su imagen, nombre, precio e ID único.
Carrito de compras:
Añade guitarras al carrito de compras al pulsar el botón "Añadir al carrito".
El carrito muestra el total acumulado del precio de las guitarras seleccionadas.
El carrito se puede mantener entre recargas de la página gracias a localStorage.
Gestión del carrito:
Incremento y decremento de cantidad: Puedes ajustar la cantidad de cada guitarra en el carrito (hasta un máximo de 5 unidades por producto).
Eliminar guitarras: Posibilidad de eliminar una guitarra específica o vaciar el carrito por completo con un solo clic.
📦 Tecnologías utilizadas
React: Librería de JavaScript para construir interfaces de usuario.
Hooks: Utilización de useState y useEffect para manejar el estado y los ciclos de vida de los componentes.
Vite: Herramienta rápida de desarrollo para crear aplicaciones de React.
localStorage: Almacenamiento local para mantener los datos del carrito incluso después de recargar la página.
Netlify: Plataforma utilizada para el despliegue y hosting de la aplicación.
🛠️ Estructura del proyecto
bash
Copiar código
/src
  ├── components
  │   ├── Guitarra.js          # Componente para mostrar información de cada guitarra
  │   └── Header.js            # Componente que contiene el carrito de compras
  ├── App.js                   # Componente principal de la aplicación
  ├── index.js                 # Punto de entrada de la aplicación
  └── styles.css               # Estilos de la aplicación
🧩 Funcionalidades principales
Componente Guitarra
Este componente es responsable de mostrar la información básica de cada guitarra, incluyendo:

Imagen
Nombre
Precio
ID único
Botón de "Añadir al carrito", que agrega la guitarra al carrito y actualiza el total.
Componente Header
El Header contiene el carrito de compras, que incluye:

Lista de guitarras seleccionadas.
Total del carrito.
Opciones para incrementar o reducir la cantidad de cada guitarra (hasta un máximo de 5).
Botón para vaciar el carrito completamente.
Botón "X" para eliminar guitarras individuales del carrito.
🚧 Instalación y ejecución local
Si deseas clonar y ejecutar este proyecto en tu máquina local, sigue estos pasos:

Clona este repositorio:
bash
Copiar código
git clone https://github.com/tu-usuario/guitarraweb.git
Accede al directorio del proyecto:
bash
Copiar código
cd guitarraweb
Instala las dependencias:
bash
Copiar código
npm install
Inicia el servidor de desarrollo:
bash
Copiar código
npm run dev
El proyecto estará disponible en http://localhost:3000.

📚 Aprendizaje
Este proyecto fue creado con el objetivo de aprender y practicar las siguientes tecnologías y conceptos:

React Hooks: useState para manejar el estado del carrito, y useEffect para interactuar con el localStorage.
Vite: Configuración rápida de entornos de desarrollo para React.
localStorage: Persistencia de datos entre recargas de la página.
Componentización: Separación de funcionalidades en componentes reutilizables.
🚀 Próximas mejoras
Algunas ideas para futuras mejoras:

Autenticación de usuario: Permitir a los usuarios registrarse y mantener su carrito guardado en una cuenta personal.
Filtrado y búsqueda: Agregar un sistema de filtrado de guitarras por precio, marca, etc.
Pasarela de pago: Integrar un sistema de pago para hacer la compra real.
