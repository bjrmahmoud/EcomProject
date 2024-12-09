
# 🌟 Projet de Gestion de Microservices  

Ce projet implémente un système complet avec une architecture **microservices** et une interface utilisateur développée en **Angular** pour gérer 🧑‍💼 les clients, 🛍️ les produits, et 📦 les commandes.  

---

## 🛠️ Partie Backend  
### Fonctionnalités  
1. **📋 Customer-Service** : Gestion des clients.  
2. **📦 Inventory-Service** : Gestion des produits.  
3. **🧾 Billing-Service** : Gestion des factures et commandes.  
4. **🚪 Gateway-Service** : Passerelle basée sur Spring Cloud Gateway.  
5. **🌐 Eureka Discovery Service** : Annuaire pour enregistrer et découvrir les microservices.  
6. **📑 Configuration-Service** : Centralisation des configurations.  

---

### 📚 Technologies utilisées  
- **🚀 Spring Boot** : Framework principal pour le développement des microservices.  
- **🗄️ Spring Data JPA** : Gestion des bases de données relationnelles.  
- **🌐 Spring Data REST** : Exposition des entités en tant qu'API RESTful.  
- **🛢️ H2 Database** : Base de données en mémoire pour les tests.  
- **🌩️ Spring Cloud** : Modules pour Eureka, Gateway et OpenFeign.  
- **✍️ Lombok** : Réduction du boilerplate dans le code.  
- **📊 Spring Boot Actuator** : Monitoring et gestion des microservices.  

---

### 🖼️ Démonstration Backend  
Chaque microservice expose des fonctionnalités via des endpoints RESTful.  

#### Customer-Service  
- **API pour les clients** :  
  - Liste des clients : [http://localhost:8081/customers](http://localhost:8081/customers)  
  - Liste des clients avec projection : [http://localhost:8081/customers?projection=fullCustomer](http://localhost:8081/customers?projection=fullCustomer)  

#### Inventory-Service  
- **API pour les produits** :  
  - Liste des produits : [http://localhost:8082/products](http://localhost:8082/products)  

#### Billing-Service  
- **API pour les commandes** :  
  - Liste des commandes : [http://localhost:8083/bills](http://localhost:8083/bills)  

#### Spring Cloud Gateway  
- Accès aux microservices via la Gateway :  
  - Clients : [http://localhost:8088/customers](http://localhost:8088/customers)  
  - Produits : [http://localhost:8088/products](http://localhost:8088/products)  

---

### 🖥️ Screenshots Backend  
- **📋 Customer-Service** :  
  ![Capture d'écran Customer-Service](./screens/customers-backend.png)  

- **📦 Inventory-Service** :  
  ![Capture d'écran Inventory-Service](./screens/products-backend.png)  

- **🧾 Billing-Service** :  
  ![Capture d'écran Billing-Service](./screens/orders-backend.png)  

---

## 🌟 Partie Frontend  

L'interface utilisateur est développée avec **Angular** pour offrir une expérience utilisateur fluide et intuitive.  

---

### Fonctionnalités  
1. **Gestion des clients** : Affichage de la liste des clients, ajout, modification et suppression.  
2. **Gestion des produits** : Affichage de la liste des produits, ajout, modification et suppression.  
3. **Gestion des commandes** : Affichage des factures et des détails des commandes.  

---

### 📚 Technologies utilisées  
- **🅰️ Angular** : Framework pour le frontend.  
- **📦 Bootstrap** : Design responsive et moderne.  
- **🔗 Axios** : Communication avec les API REST du backend.  

---

### 🖼️ Démonstration Frontend  

#### Customers  
Interface utilisateur pour gérer les clients :  
![Capture d'écran Customers](./screens/customers-frontend.png)  

#### Products  
Interface utilisateur pour gérer les produits :  
![Capture d'écran Products](./screens/products-frontend.png)  

#### Orders  
Interface utilisateur pour gérer les commandes :  
![Capture d'écran Orders](./screens/orders-frontend.png)  

---

## 🚀 Lancement du Projet  
### Backend  
1. **Clonez** le projet depuis le dépôt. 🧩  
2. Assurez-vous que les dépendances Maven/Gradle sont installées. 📦  
3. Lancez chaque microservice avec `mvn spring-boot:run`. 🏃‍♂️  
4. Accédez à l'interface **Eureka** à l'adresse [localhost:8761](http://localhost:8761). 🌐  

### Frontend  
1. Accédez au dossier Angular : `cd frontend`.  
2. Installez les dépendances : `npm install`.  
3. Lancez l'application : `ng serve`.  
4. Accédez à l'interface utilisateur : [http://localhost:4200](http://localhost:4200).  

---

## ✍️ Auteur  
Réalisé par **Mahmoud Boujir**.  
