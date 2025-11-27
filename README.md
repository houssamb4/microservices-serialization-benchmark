# **microservices-serialization-benchmark**
Un TP Node.js comparant **JSON**, **XML** et **Protocol Buffers** à travers la sérialisation, la taille des fichiers et des tests de performance simples.  
Conçu pour le cours **« Architecture des microservices : Conception, Déploiement et Orchestration »**.

---

## 📘 Objectif du TP

Ce projet a pour but de comprendre les différences entre plusieurs formats de sérialisation utilisés dans les architectures distribuées, notamment dans les microservices :

- **JSON** : simple, lisible, très utilisé dans les API REST  
- **XML** : plus verbeux, structuré, utilisé dans des systèmes hérités  
- **Protocol Buffers (Protobuf)** : binaire, compact, utilisé par **gRPC**

L'objectif principal est d’illustrer pourquoi les systèmes modernes privilégient **Protobuf**, notamment pour ses performances et sa faible empreinte mémoire.

---

## 🧪 Ce que vous allez apprendre

- Créer une liste d’employés en JavaScript  
- Sérialiser ces données en **JSON**, **XML** et **Protobuf**  
- Sauvegarder les sérialisations dans des fichiers  
- Comparer la taille des fichiers  
- Observer les différences de performance entre les formats  
- Comprendre pourquoi gRPC utilise Protobuf

---

## 📦 Prérequis

- **Node.js 14+**  
- Connaissances de base en JavaScript / Node.js  
- Notion d’objet JSON  
- Un éditeur de code (VS Code, WebStorm, etc.)
