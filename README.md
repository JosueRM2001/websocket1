# WebSocket
This is a project that was developed with javascript on a WebSocket architecture.

## Description
This project displays a welcome page.
It is a simple program to show how a program works in the programming language with an architecture style.

## Technologies Used
**Contains the Following**
- Visual Studio Code (most current version)
- Docker
- JavaScript
- WebSocket

## Development Requirements
- **Docker Desktop** (if you want to run it in a container)
- **Visual Studio Code** (optional, but recommended)
- **JavaScript** (required and recommended)
- **The JavaScript extension for Visual Studio Code** (for improved support and syntax highlighting).
- **GitHub Desktop** (if you want to clone and use the project)

```bash
https://www.docker.com/products/docker-desktop/
```

- **Docker hub** (if you want to clone and use the project)

```bash
https://hub.docker.com/layers/erickjrm/programwebsocket/latest/images/sha256-4c0f5b6c780a8705c6b4b36ce5169ffe12897479611cf24a3497787f13a974af?context=repo
```

## Instructions to run the project
## Steps to run
**Step #1**
**Clone this repository**
If you have not yet cloned the repository, you can do so with the following link:

```bash
https://github.com/JosueRM2001/websocket1.git
```
**Step #2**
**Build the Docker Image**

Run the following command, which will build the image:

```bash
docker pull erickjrm/programwebsocket:latest
```

**Step #3**
**Run the Docker container:**

Then run the following command, which builds the container and port.

```bash
docker run -d -p 8080:80 --name websocket erickjrm/programwebsocket:latest
```

**Step #4**

Open Docker Desktop to see if the image was built successfully and send it to run to view.

**Step #5**

**Access the application**: If it is running, you can access the application by navigating to the

following url in your web browser:

```bash
https://localhost:8080
```
