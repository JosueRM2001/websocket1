# WebSocket
Este es un proyecto que fue desarrollado con javascript en una arquitectura WebSocket.

## Descripción
Este proyecto muestra una página en la cual dará la bienvenida. 
Es un programa sencillo para mostrar cómo funciona un programa en el lenguaje de programación con un estilo de arquitectura.

## Tecnologías Utilizadas
**Contiene lo Siguiente**
- Visual Studio Code (version mas actual)
- Docker
- JavaScript
- WebSocket

## Requerimientos para el Desarrollo
- **Docker Desktop** (si lo quieres correr en un contenedor)
- **Visual Studio Code** (opcional, pero recomendado)
- **JavaScript**(requerido y recomendado)
- **La extensión JavaScript para Visual Studio Code** (para mejorar el soporte y el resaltado de sintaxis).
- **GitHub Desktop** (si quieres clonar y usar el proyecto)
  
  ```bash
  https://www.docker.com/products/docker-desktop/
  ```
  
- **Docker hub** (si quieres clonar y usar el proyecto)
  
  ```bash
  https://hub.docker.com/layers/erickjrm/programwebsocket/latest/images/sha256-4c0f5b6c780a8705c6b4b36ce5169ffe12897479611cf24a3497787f13a974af?context=repo
  ```

## Intruciciones para ejecutar el proyecto
## Pasos para ejecutar
**Paso #1**
  **Clonar este repositorio**
Si aún no ha clonado el repositorio, puede hacerlo con el siguiente link:

 ```bash
https://github.com/JosueRM2001/websocket1.git
 ```
**Paso #2**
  **Construya la imagen de Docker**

Ejecuta el siguiente comando, que generará la imagen:

```bash
docker pull erickjrm/programwebsocket:latest
```

**Paso #3**
**Ejecute el contenedor Docker:**

Luego ejecuta el siguiente comando, que genera el contenedor y el puerto.

```bash
docker run -d -p 8080:80 --name websocket erickjrm/programwebsocket:latest
```

**Paso #4**

Abre Docker Desktop para ver si la imagen se creó correctamente y envíala a ejecutar para verla.

**Paso #5**

**Accede a la aplicación**: Si está ejecutándose, puedes acceder a la aplicación navegando a la

siguiente url en tu navegador web:

```bash
https://localhost:8080
```
