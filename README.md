# java-spring-boot-crud-api

## Spring Boot 3 & PostgreSQL: Software Engineer Management API 🚀

Dieses Projekt ist eine RESTful API, die ich im Rahmen meines **Java II** Studiums entwickle. Es dient dazu, meine Java-Grundlagen zu festigen und moderne Frameworks wie **Spring Boot 3** sowie die Containerisierung mit **Docker** in der Praxis anzuwenden.

## 📚 Hintergrund & Lernziele
Ich folge dem Tutorial von **Amigoscode**: [Spring Boot Tutorial for Beginners 2025](https://www.youtube.com/watch?v=Cw0J6jYJtzw).

**Im Fokus stehen:**
* **Java II Vertiefung:** Anwendung von Generics (JPA), Streams und modernem Exception Handling.
* **Spring Boot 3:** Dependency Injection, Bean Management und REST-Controller.
* **Datenpersistenz:** Arbeiten mit **Spring Data JPA** und Hibernate.
* **Infrastruktur:** Datenbank-Setup (PostgreSQL) mittels Docker Compose.

## 🛠 Technologien
* **Java 21** (LTS)
* **Spring Boot 3.4+**
* **Spring Data JPA** (Hibernate)
* **Maven** (Dependency Management)
* **PostgreSQL** (Datenbank)
* **Docker & Docker Compose**
* **IntelliJ IDEA** (HTTP Client für API-Tests)

## 🏗 Architektur
Die Anwendung folgt einer sauberen Schichtenarchitektur, um Wartbarkeit und Testbarkeit zu gewährleisten:

1.  **Controller-Layer:** Definiert die REST-Endpunkte und verarbeitet HTTP-Requests.
2.  **Service-Layer:** Beinhaltet die Geschäftslogik (Java II Fokus).
3.  **Data-Access-Layer (Repository):** Abstrahiert den Datenbankzugriff über JPA Interfaces.
4.  **Database:** PostgreSQL Container, verwaltet über Docker.

