# REST API

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les verbes HTTP ✔️
  - POST
  - GET
  - DELETE
  - PUT
- les statuts HTTP ✔️
  - success 200, 201 ...
  - erreurs serveurs 500, 501 ...
  - erreur client 400, 401...  
    liste complète https://developer.mozilla.org/fr/docs/Web/HTTP/Status
- les endpoints ✔️
  url , routes vers lesquelles , nos requêtes http vont aller chercher / demander une action auprès du serveur / backend
- CORS ✔️
  Cross Origin Resource Sharing
- la nomenclature recommandée pour les routes ✔️

## 💻 J'utilise

### Un exemple personnel commenté ✔️

```import express from "express";
import WilderService from "../services/Wilder.service";
import WilderEntity from "../entity/Wilder.entity";
import { IWilderUpdateKey } from "../services/services";

const router = express.Router();

//plus haut dans l'app, dans le fichier index.js le middleware appelle notre route initié par /wilder :
// app.use("/wilder", WilderRoutes);
// le endpoint complet pour récupérer un étudiant est "/wilder/find/:id"

router.get("/find/:id", async (req, res) => {
  const { id } = req.params;
  try {
    const wilder = await new WilderService().findById(id);
    res.status(200).json(wilder);
  } catch (err) {
    res.status(400).json({ success: false, message: err.message });
  }
});

```

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️

```

```
