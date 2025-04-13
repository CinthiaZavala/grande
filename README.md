
# Nombre del Proyecto

## Descripción

Este proyecto es una aplicación que utiliza la API de Google Maps para mostrar un mapa interactivo. Los usuarios pueden hacer clic en el mapa, y el sistema mostrará un marcador en la ubicación seleccionada junto con el nombre del lugar (obtenido mediante geocodificación inversa). Esta aplicación fue construida con React y la librería `@react-google-maps/api` para interactuar con los mapas de Google.

## Tecnologías utilizadas

- **React**: Librería de JavaScript para construir la interfaz de usuario.
- **Google Maps API**: Para mostrar el mapa interactivo y obtener información de ubicaciones.
- **@react-google-maps/api**: Librería para facilitar la integración de Google Maps con React.

## Instrucciones para correrlo localmente

1. **Clona este repositorio** a tu máquina local:

   ```bash
   git clone https://github.com/usuario/nombre-del-proyecto.git
   ```

2. **Accede a la carpeta del proyecto**:

   ```bash
   cd nombre-del-proyecto
   ```

3. **Instala las dependencias** del proyecto:

   Si estás utilizando `npm`:

   ```bash
   npm install
   ```

   Si prefieres `yarn`:

   ```bash
   yarn install
   ```

4. **Configura las variables de entorno**:

   Crea un archivo `.env` en la raíz del proyecto y agrega tu **Google Maps API Key**. El archivo `.env` debe tener este formato:

   ```
   REACT_APP_GOOGLE_MAPS_API_KEY=tu_api_key_aqui
   ```

5. **Corre la aplicación**:

   Para iniciar el servidor de desarrollo, usa:

   Si estás usando `npm`:

   ```bash
   npm start
   ```

   O si usas `yarn`:

   ```bash
   yarn start
   ```

   Esto abrirá la aplicación en tu navegador, generalmente en `http://localhost:3000`.

6. **Listo!** Ahora puedes interactuar con el mapa y ver cómo funciona el proyecto.

## Notas

- Asegúrate de tener una clave API de Google Maps válida. Si no tienes una, puedes obtenerla desde [Google Cloud Console](https://console.cloud.google.com/).
- Si tienes algún problema con la clave API, revisa los permisos y habilita las APIs necesarias en tu proyecto de Google Cloud.
