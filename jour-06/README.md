# Jour 6 — Monitoring Azure

## 🎯 Objectif

Comprendre les bases du monitoring Azure avec Azure Monitor.

---

## 🧠 Ce que j’ai appris

Azure Monitor repose sur trois éléments principaux :

### 📊 Metrics

Les métriques permettent de surveiller en temps réel l’activité d’une ressource.
J’ai observé les transactions de mon compte de stockage après avoir effectué plusieurs uploads/suppressions.

### 📜 Logs

Les journaux nécessitent :

* un espace de travail Log Analytics
* l’activation des paramètres de diagnostic

J’ai appris que les logs ne sont pas instantanés et peuvent mettre quelques minutes à apparaître.

### 🚨 Alerts

Les alertes permettent d’être notifié automatiquement selon des conditions définies.
J’ai créé une alerte basée sur le nombre de transactions.

---

## 📸 Captures

### Metrics

![metrics](./metrics.png)

### Diagnostic settings

![diagnostic](./diagnostic-settings.png)

### Alert rule

![alert](./alert-rule.png)

---

## ✅ Conclusion

Cette session m’a permis de comprendre comment surveiller efficacement une ressource Azure avec :

* les métriques
* les journaux
* les alertes

Ces éléments sont essentiels pour l’exploitation en environnement professionnel.
