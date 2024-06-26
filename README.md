# 💊 AppMedicFront

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)

## 🎉 Welcome

Welcome to the **AppMedic** project, an application designed to report essential medicines in case of supply difficulties.

Here is the link to the Backend project: [AppMedicBack](https://github.com/paulpp78/AppMedicBack)

## 📋 Prerequisites

Make sure Node.js and npm are installed on your machine.

## 📦 Install Dependencies

Install npm dependencies by running:

```bash
npm install
```

## 🚀 Development Server

To start the development server, run:

```bash
ng serve
```

Then navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## 🛠️ Code Generation

To generate a new component, run:

```bash
ng generate component component-name
```

You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## 🔨 Build

To build the project, run:

```bash
ng build
```

The build artifacts will be stored in the `serverGo/app-medic` directory.

## ✅ Running Unit Tests

To execute the unit tests via [Karma](https://karma-runner.github.io), run:

```bash
ng test
```

## 🌐 Running End-to-End Tests

To execute the end-to-end tests via a platform of your choice, run:

```bash
ng e2e
```

To use this command, you need to first add a package that implements end-to-end testing capabilities.

## 💡 Additional Help

For more help on the Angular CLI, use `ng help` or check out the [Angular CLI Overview and Command Reference](https://angular.io/cli).

## 🌍 Deployment

### Docker

A `Dockerfile` is included in this project. To build and run the Docker container, use the following commands:

To build the Docker image:

```bash
docker build -t appmedicfront .
```

To run the Docker container:

```bash
docker run -p 443:443 appmedicfront
```

### Go Server

In the `serverGo` folder, there is a `server.go` file that allows you to launch a web server in Go. To start this server, ensure Go is installed, then run:

```bash
go run serverGo/server.go
```
