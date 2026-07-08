# DESIGN IV - Maquette pédagogique à PWM configurable

## Description

Ce dépôt contient les travaux réalisés dans le cadre du projet de Design IV visant à développer une plateforme pédagogique basée sur la carte d'onduleur Toshiba RD220.

Le dépôt comprend les simulation et les commandes PLECS pour les quatre configurations (dévolteur, survolteur, pont en H et onduleur triphasé) ainsi que les commandes Arduino pour les 3 premiers montages. Il contient également les documents des interfaces PCB RT-Box-TOSHIBA et Arduino-TOSHIBA, ainsi que la documentation sur la portion matérielle du projet.

---

## Structure du dépôt

```
docs/
    Rapport, présentation, documentation

hardware/
    Schémas Altium, PCB, boîtier et composantes matérielles

commandes Arduino/
    commandes et code de référence Arduino

simulations et commandes PLECS/
    Simulations et commandes PLECS

resources/
    Documentation du fabricant, fiches techniques, références
```

---

## Utilisation

Avant de commencer une nouvelle tâche :

1. Mettre le dépôt local à jour.
2. Créer une branche à partir de `main`.
3. Effectuer les modifications.
4. Valider les changements (`commit`).
5. Envoyer la branche sur GitHub (`push`).
6. Fusionner dans `main` via une Pull Request ou après validation de l'équipe.

---

## Aide-mémoire Git

### Cloner le dépôt

```bash
git clone https://github.com/PhilippeGRLX/DESIGN-IV---Maquette-pedagogique-a-PWM-configurable.git
```

### Se mettre à jour

```bash
git checkout main
git pull
```

### Créer une nouvelle branche

```bash
git checkout -b nom-de-la-branche
```

### Enregistrer les modifications

```bash
git add .
git commit -m "Description des modifications"
```

### Envoyer la branche

```bash
git push -u origin nom-de-la-branche
```

### Revenir sur `main`

```bash
git checkout main
```