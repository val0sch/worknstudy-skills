# Titre de la compétence

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'état (_state_) pour contrôler l'affichage d'un composant ✔️
  const[state, setState]= useState()
- les composants enfants et les _props_ qu'on leur passe ✔️
  Dans le return de composant Parent on stock le composant enfant dans une div par exemple et on lui envoit les props:
  <div className="composant-enfant"><ChildrenComponent state={state}/></div>
- le déclenchement d'instructions en fonction des actions de l'utilisateur ✔️
  Avec des fonctions telles que OnSubmit(), OnClick() ou handleChange()
- le déclenchement d'instructions en fonction de l'étape du cycle de vie du composant ou du changement de valeur de ses props ✔️
  Avec un useEffect, et son tableau de dépendance qui reload le composant lorsque l'état stocké dans le taleau de dépendances est modifié
- l'usage d'un reducer (_useReducer_) pour gérer un état composé dans un composant ❌ / ✔️
  A revoir
- l'état stocké dans un composant avec un _context provider_ et accessible dans ses descendants via `useContext` ✔️
  Permet de faire hériter les props à tous les composants souhaités via un context provider sans avoir à se soucier de les passer forcément du parent à l'enfant.

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

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
