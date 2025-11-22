# gRPC Bank Service

[![Java](https://img.shields.io/badge/Java-21-blue)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.3.3-green)](https://spring.io/projects/spring-boot)
[![gRPC](https://img.shields.io/badge/gRPC-1.65.0-brightgreen)](https://grpc.io/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

---

## Description

**gRPC Bank Service** est un microservice bancaire développé avec **Spring Boot 3** et **gRPC**.  
Il permet de réaliser des opérations de conversion de devises et de démontrer tous les modes de communication gRPC :

- Unary RPC  
- Client Streaming  
- Server Streaming  
- Bidirectional Streaming  

Le projet inclut la génération automatique des stubs Java à partir d’un fichier `.proto`.

---

## Fonctionnalités

- **Conversion de devises (Unary RPC)** : Convertit USD ↔ TND.  
- **Client Streaming** : Somme des montants envoyés par le client.  
- **Server Streaming** : Génère des taux aléatoires périodiquement.  
- **Bidirectional Streaming** : Calculs en temps réel pour chaque montant envoyé.  
- **ProtoBuf** : Génération automatique du code gRPC via `protobuf-maven-plugin`.  

---

## Technologies utilisées

- Java 21  
- Spring Boot 3.3.3  
- gRPC Java 1.65.0  
- Protocol Buffers 3.25.0  
- Maven  

---



