# MicroService FastAPI


![Microservice](https://img.shields.io/badge/Microservice-red)
![FastAPI](https://img.shields.io/badge/FastAPI-green)
![Docker](https://img.shields.io/badge/Docker-blue)
![Version](https://img.shields.io/badge/version-1.5.2--Beta-yellow)

Focus Microservice Generator is a powerful VS Code extension designed to streamline the creation, management, and deployment of FastAPI microservices. This extension helps developers efficiently handle microservices with Docker.

## Features

### Commands

- **Create MicroService**: Quickly scaffold a new FastAPI microservice.
- **Focus**: Easily navigate and open relevant files for a specific microservice.
- **Deploy in Docker**: Start and manage microservices in Docker containers.
- **Update Docker Containers**: Effortlessly update and restart Docker containers.
- **Show Docker Logs**: View real-time logs from Docker containers.
- **Restart Docker Containers**: Restart all Docker containers.
- **Stop Docker Containers**: Stop all Docker containers.

## Quick Start

### Installation

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X)
3. Search for `MicroService FastAPI`
4. Click Install

### Creating a Microservice

1. Open the command palette (Ctrl+Shift+P)
2. Type `MicroService: Create MicroService`
3. Follow the prompts to create a new microservice
<br>

![Create Microservice Demo](https://raw.githubusercontent.com/Abder-Rahmane/image-microservice/main/assets/create-microservice-demo.gif)

### Deploying a Microservice

1. Open the command palette (Ctrl+Shift+P)
2. Type `MicroService: Deploy in Docker`
3. Wait for the containers to start and view the logs
<br>

![Deploy in Docker Demo](https://raw.githubusercontent.com/Abder-Rahmane/image-microservice/main/assets/deploy-docker-demo.gif)

### Working on a Microservice

1. Open the command palette (Ctrl+Shift+P)
2. Type `MicroService: Focus`
3. Select the microservice you want to focus on

### Additional Commands

- **Update Docker Containers**: Use `Ctrl+Alt+U` to update and restart Docker containers.
- **Restart Docker Containers**: Use `Ctrl+Alt+R` to restart all Docker containers.
- **Stop Docker Containers**: Use `Ctrl+Alt+X` to stop all Docker containers.
- **Show Docker Logs**: Use `Ctrl+Alt+L` to view real-time logs from Docker containers.

## Micro Service  Structure

```plaintext
<rootPath>
└── microservices
    └── example
        ├── app
        │   ├── __init__.py
        │   ├── main.py
        │   ├── core
        │   │   ├── __init__.py
        │   │   ├── config.py
        │   │   └── security.py
        │   ├── api
        │   │   ├── __init__.py
        │   │   └── v1
        │   │       ├── __init__.py
        │   │       └── endpoints
        │   │           ├── __init__.py
        │   │           ├── example_endpoint.py
        │   │           └── auth.py
        │   ├── models
        │   │   ├── __init__.py
        │   │   ├── example.py
        │   │   └── user_model.py
        │   ├── schemas
        │   │   ├── __init__.py
        │   │   ├── example.py
        │   │   └── user_schema.py
        │   ├── crud
        │   │   ├── __init__.py
        │   │   ├── example.py
        │   │   └── user_crud.py
        │   ├── db
        │   │   ├── __init__.py
        │   │   ├── base.py
        │   │   └── session.py
        │   ├── auth
        │   │   ├── __init__.py
        │   │   ├── jwt.py
        │   │   └── oauth2.py
        │   ├── tests
        │   │   ├── __init__.py
        │   │   ├── test_example.py
        │   │   └── test_auth.py
        ├── alembic
        │   ├── env.py
        │   ├── script.py.mako
        │   └── versions
        ├── scripts
        │   └── init_db.py
        ├── .env
        ├── .gitignore
        ├── requirements.txt
        ├── Dockerfile
        └── README.md
```

## Credits

Created by [MAGROUD Abderrahmane](https://www.linkedin.com/in/abder-rahmane-magroud/)
<br><br>
Hey developers! 🚀 Ready to take your microservices game to the next level? With this extension, creating and managing FastAPI microservices is as easy as pie. Remember, you can quickly focus on any microservice, restart Docker containers, and view logs in real-time. Enjoy coding, and don't forget to have fun while you're at it! 😄
<br><br>
For any feedback or suggestions, feel free to [contact us](mailto:reprend_05_cursif@icloud.com).


## License

[MIT](LICENSE)
