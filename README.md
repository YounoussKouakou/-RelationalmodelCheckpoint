# 🏨 Projet de Gestion Hôtelière

## 📘 Description

Ce projet a pour objectif de modéliser un système de gestion hôtelière structuré autour de plusieurs entités telles que les hôtels, les chambres, les employés, les types et les catégories. Il permet de représenter de façon claire la structure de l’établissement, l’organisation des chambres, et la hiérarchie du personnel.

---

## 🧱 Modèle Logique des Données (MLD)

### 📌 Tables et attributs

#### 🔹 `Type`
Contient les types généraux attribués aux hôtels et chambres.

```sql
Type(
    Type_Id INT PRIMARY KEY,
    Type_Name VARCHAR(50)
);
