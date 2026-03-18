# 📘 Jour 7 — Gestion des accès avec groupes (RBAC)

## 🎯 Objectif

Mettre en place une gestion des accès via des groupes plutôt que des utilisateurs individuels.

---

## 🧱 Étapes réalisées

### 👥 Création d’un groupe

* Nom : **grp-storage-readers**
* Type : **Sécurité**

📸 Voir : `group.png`

---

### ➕ Ajout d’un utilisateur au groupe

* Utilisateur : **labuser01**

📸 Voir : `group-members.png`

---

### 🔐 Attribution d’un rôle au groupe

* Ressource : **stlab04timothe**
* Rôle : **Lecteur des données Blob du stockage**

📸 Voir : `group-role.png`

---

## ✅ Résultat

Le groupe dispose d’un accès en lecture au stockage, et tous les membres héritent automatiquement de ces permissions.

---

## 🧠 Bonnes pratiques

* ✔️ Utiliser des groupes pour gérer les accès
* ✔️ Éviter les attributions directes aux utilisateurs
* ✔️ Centraliser la gestion des permissions

---

## 🚀 Conclusion

Ce modèle correspond aux standards utilisés en entreprise pour gérer les accès de manière scalable et sécurisée.
