
# Proyecto Final del Curso de Asincronismo con Javascript

En este curso usamos una plantilla web y realizamos una modificacion para insertar mediante innerHTML la informacion obtenida de una API de Youtube que trae los ultimos videos de un canal de Youtube, esta API la obtuvimos de la plataforma [RapidAPI].

## Deploy

Realizamos la configuracion en el repositorio de Github para que se realice el deploy en Github Pages, los paso a seguir son:

- Instalar en el proyecto gh-pages. 

    ```
    npm install gh-pages --save-dev
    ```
- Agregar el archivo package.json

    ```
    "deploy-gh-pages": "gh-pages -d src"
    ```

- Ejecutar

    ```
    npm run deploy-gh-pages
    ```







[RapidAPI]: <https://rapidapi.com/ytdlfree/api/youtube-v31/>
