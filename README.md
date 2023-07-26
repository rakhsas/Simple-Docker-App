
# Docker Hello World with Nginx


simple Dockerfile to build an NGINX container that serves a "Hello, World!" HTML page. Run the container and access the page in your web browser.


## Run Locally

Clone the project

```bash
  git clone https://github.com/rakhsas/Simple-Docker-App.git
```

Go to the project directory

```bash
  cd Simple-Docker-App
```

Install Docker for Windows

```bash
  1 -> Download Docker Desktop for Windows
  2 -> Enable WSL 2
  3 -> Restart your system for the changes to take effect
  4 -> Launch Docker Desktop from the Start menu, and navigate to Settings > General
  5 -> Ensure the Use WSL 2 based engine check box is enabled
  6 -> Select Apply & Restart
```

Start the App

```bash
    docker-compose -f ./src/docker-compose.yml up -d

```


## HTTP TEST

```bash
  http://localhost
```

## HTTPS TEST

```bash
  https://localhost
```
