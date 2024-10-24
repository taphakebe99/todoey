# Todoey ✓

## Objectif

L'objectif de ce tutoriel est de m'apprendre à gérer l'état dans Flutter. Je vais explorer différentes options d'architecture Flutter et me familiariser avec le package Provider, recommandé officiellement, pour gérer l'état de mon application.

## Ce que je vais créer

Je vais développer une application de liste de tâches (todolist) qui me permettra de suivre toutes mes tâches facilement.

## Ce que je vais apprendre

- **Comprendre ce qu'est l'état et pourquoi il est important de le gérer**  
  Je vais découvrir pourquoi la gestion de l'état est essentielle dans le développement d'applications modernes.

- **Comprendre la différence entre l'état éphémère (local) et l'état global (app state)**  
  Je vais apprendre comment certains états ne concernent qu'un widget particulier, tandis que d'autres doivent être accessibles dans toute l'application.

- **Découvrir les limites de l'utilisation de `setState()`**  
  J'explorerai pourquoi `setState()`, bien qu'utile, n'est pas toujours la meilleure solution pour gérer l'état dans les applications plus complexes.

- **Apprendre le concept de "Prop Drilling"**  
  Je vais comprendre ce problème qui se pose lorsqu'on doit passer des données d'un widget parent à un widget enfant éloigné dans la hiérarchie des widgets.

- **Examiner différentes façons populaires de gérer l'état dans les projets Flutter**  
  Je vais découvrir plusieurs solutions de gestion d'état et leurs avantages, afin de choisir la meilleure approche pour chaque situation.

- **Utiliser le `ListView.builder`**  
  J'apprendrai à créer des listes dynamiques et performantes avec cet outil.

- **Utiliser le widget `BottomSheet` de Flutter**  
  Je vais apprendre à créer une feuille de fond pour les interactions utilisateur, comme l'ajout d'une nouvelle tâche.

- **Apprendre à élever l'état ("lift state up") pour le rendre accessible aux widgets enfants**  
  Je vais comprendre comment déplacer l'état vers un niveau supérieur pour le rendre accessible aux widgets inférieurs.

- **Découvrir les motifs de conception (design patterns) et leur utilité**  
  Je vais voir comment certains motifs de conception peuvent simplifier la gestion de l'état et rendre le code plus facile à maintenir.

- **Comprendre le fonctionnement du package Provider et l'utiliser pour gérer l'état de l'application**  
  Le package Provider m'aidera à mettre en œuvre une gestion d'état plus efficace en évitant les limitations de `setState()`.

---

Avec ce tutoriel, je serai capable de créer une application de gestion de tâches fonctionnelle tout en maîtrisant les bases de la gestion de l'état dans Flutter.
