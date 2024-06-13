# Student Management Platform

## Overview
The Student Management Platform is a Spring Boot service designed to manage students and masters. It provides CRUD operations for both entities, enforces role-based access control using Spring Security, and includes various integrations and optimizations such as Azure Kubernetes Service (AKS), Caffeine Cache, and rate limiting. The project follows a facade-based code organization for better maintainability and scalability.

## Features

 #### CRUD Operations: Create, Read, Update, Delete operations for students and masters.
 #### Many-to-Many Relationship: Students can be associated with multiple masters and vice versa.
 #### Role-Based Access Control: Secure the application using Spring Security roles.
 #### Azure AKS Integration: Deploy and manage the application using Azure Kubernetes Service.
 #### Caching: Optimize performance with Caffeine Cache.
 #### Rate Limiting: Protect the service from excessive requests.
 #### Facade Pattern: Organized codebase for better structure and readability.
 

 ## Technologies Used
    - Java 17
    - Spring Boot
    - Spring Security
    - Spring Data JPA
    - Azure Kubernetes Service (AKS)
    - Caffeine Cache
    - Rate Limiting Libraries (e.g., Bucket4j)
    - Facade Design Pattern
    - Getting Started


## Prerequisites
    - Java 17
    - Maven 3.8.6 and above
    - Docker
    - Azure account with AKS setup
