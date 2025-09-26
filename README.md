# 💳 BesLoan  

Plateforme de **gestion de prêts privés** développée en **architecture microservices**.  
Elle permet aux utilisateurs de :  
✅ Soumettre des demandes de prêt  
✅ Consulter leur portefeuille  
✅ Effectuer des remboursements sécurisés avec **authentification JWT**  

---

## 📖 Vue d'ensemble  

**BesLoan** est un système complet de gestion de prêts privés, conçu avec une architecture moderne basée sur les microservices.  
Cette plateforme garantit une gestion **sécurisée, efficace et flexible** des :  
- demandes de prêt,  
- remboursements,  
- authentifications des utilisateurs.  

---

## 🚀 Fonctionnalités principales  

- 🔐 **Authentification sécurisée** avec JWT  
- 📝 **Soumission de demandes** de prêt avec validation métier rigoureuse  
- 📊 **Suivi en temps réel** du portefeuille de prêts  
- 💰 **Remboursements flexibles** (partiels ou totaux)  
- ✅ **Validation automatique** des critères d'éligibilité  

---

## 🏗️ Architecture technique  

### 📦 Microservices développés  
- **BesLoan** – Gestion principale  
- **Auth Service** 🔑 – Inscriptions et connexions  
- **Loan Service** 📝 – Traitement des demandes & suivi  
- **Payment Service** 💸 – Gestion des remboursements & transactions  
- **Gateway API** 🌐 – Point d'entrée unifié avec **documentation Swagger**  

### ⚙️ Technologies utilisées  
| Domaine            | Technologies |
|--------------------|--------------|
| Backend            | Node.js, Express.js |
| Base de données    | PostgreSQL / MongoDB |
| Authentification   | JWT (JSON Web Tokens) |
| Validation         | express-validator |
| Documentation API  | Swagger / OpenAPI |
| Architecture       | Microservices |

---

## 🧩 Défis techniques relevés  

- 🔄 Gestion des transactions pour la **cohérence des données** lors des remboursements  
- 📏 Validation métier complexe (**montant max, revenu minimum, prêts actifs**)  
- 🔐 Sécurisation des endpoints avec **middleware JWT**  
- 📚 Documentation complète et interactive via **Swagger**  

---

## 📌 Règles métier implémentées  

- 💵 **Montant maximum** : 5000$ par prêt  
- 📉 **Revenu mensuel minimum** : 1200$  
- 🔄 **Maximum 3 prêts actifs** par utilisateur  
- ⏳ **Validation des dates d'échéance**  

---

## 📜 Documentation  
👉 La documentation complète de l’API est disponible via **Swagger** après déploiement.  

---
