# Portfolio Docker V0

Ce projet est un portfolio web développé avec React et Vite. Il permet de présenter vos projets GitHub et est conçu pour être facilement déployé sur un NAS grâce à Docker.

## Démarrage local

```bash
npm install
npm run dev
```
Le site sera accessible sur http://localhost:5173

## Démarrage avec Docker

1. Construire l'image Docker :
```bash
docker build -t portfolio-docker .
```
2. Lancer le conteneur :
```bash
docker run -d -p 8080:80 --name portfolio portfolio-docker
```
Le site sera accessible sur http://localhost:8080

## Objectifs
- Présenter vos projets GitHub
- Design moderne et agréable
- Déploiement simple via Docker

## Prochaines étapes
- Ajouter une page d'accueil personnalisée
- Ajouter une page "Projets" qui récupère les repos GitHub
- Dockeriser l'application

---

# Portfolio Docker V0

This project is a web portfolio built with React and Vite. It showcases your GitHub projects and is designed to be easily deployed on a NAS using Docker.

## Local run

```bash
npm install
npm run dev
```
The site will be available at http://localhost:5173

## Run with Docker

1. Build the Docker image:
```bash
docker build -t portfolio-docker .
```
2. Start the container:
```bash
docker run -d -p 8080:80 --name portfolio portfolio-docker
```
The site will be available at http://localhost:8080

## Goals
- Showcase your GitHub projects
- Modern and pleasant design
- Easy deployment with Docker

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
