# TechstarterToDo-API Skeleton

Es gibt zwei Varianten die API zu entwicklen, docker oder nodejs basierend.

## docker-based
Bitte stellen Sie sicher folgende Komponenten installiert zu haben:
* docker
* docker-compose

Anschließend kann mittels
```
docker-compose up
```
direkt in diesem Verzeichnis gearbeitet werden.

## node-based
Bitte stellen Sie sicher folgende Komponenten installiert zu haben:
* nodejs (Version 14)
* npm
* nodemon (`npm install nodemon`)

Anschließend kann mittels
```
npm install
npx nodemon app.js
```
direkt in diesem Verzeichnis gearbeitet werden.

## Benutzung

Die API ist lokal auf dem Port 5000 erreichbar: http://localhost:5000

## Implementierung

Die Implementierung erfolgt ausschließlich in der `app.js`. In dieser Datei sind alle notwendigen TODOs
beschrieben. Nutzen Sie die Dokumentation unter https://docs.api.techstarter.dev/ für genauere Informationen.

## express-prometheus-middleware

{
  "name": "express-prometheus-middleware",
  "version": "1.2.0",
  "description": "RED/USE metrics for express applications",
  "keywords": [
    "express",
    "prometheus",
    "metrics",
    "monit"
  ],
  "main": "src/index.js",
  "files": [
    "src/"
  ],
  "repository": "https://github.com/joao-fontenele/express-prometheus-middleware.git",
  "author": "João Paulo Fontenele Brito <jpfb@icomp.ufam.edu.br>",
  "license": "MIT",
  "private": false,
  "scripts": {
    "lint": "eslint . && echo '✔  Your .js files look good.'",
    "release": "standard-version"
  }