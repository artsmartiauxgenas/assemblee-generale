---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Assemblée Générale 2025-26
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# duration of the presentation
duration: 35min
---

# Assemblée Générale 2025-26

Arts Martiaux Genas

<div @click="$slidev.nav.next" class="mt-12 py-1" hover:bg="white op-10">
  <carbon:arrow-right />
</div>

<div class="abs-br m-6 text-xl">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="slidev-icon-btn">
    <carbon:edit />
  </button>
  <a href="https://github.com/artsmartiauxgenas/assemblee-generale" target="_blank" class="slidev-icon-btn">
    <carbon:logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: two-cols
layoutClass: gap-16
transition: fade-out
---

# Assemblée Générale 2025-26
Arts Martiaux Genas

<br/>
<br/>

> 📅 6 nov. 2025 20h30  
> 📍 Salle Le Genêt, Genas

::right::

**2024-25**
- Rapport moral 🗳️
- Rapport d'activités
- Rapport financier 🗳️

**2025-26**
- Budget prévisionnel 🗳️
- Aperçu de la saison
- Projets et événements

**Renouvellement du CA** 🗳️

**Questions diverses**

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
transition: fade-out
---
# Rapport moral

- Bon déroulement de la saison 2024–25.
- Stabilité du nombre d’adhérents.
- Bon esprit général au sein des sections et du Bureau.

<br/>

## Faits marquants 🎉

<br/>

- L'approbation des nouveaux statuts.
- Le renouvellement du Bureau.

<br/>
<br/>

## 🗳️ Vote du rapport moral

---
layout: two-cols
layoutClass: gap-16
---

# Rapport d'activités

**83 adhérents**, dont **70 % de Genassiens**.

| Âge / Section | Body-Fight / MMA | Karaté |
| ------------: | :--------------: | :----: |
| 5-7 ans       |   -              |   10   |
| 8-13 ans      |   -              |   33   |
| Ados/Adultes  |   23             |   16   |
| **Total**     | **23**           | **60** |

::right::

6 cours hebdomadaires assurés sur 10 créneaux

Stages et événements organisés :  
- 2024-10-13 Stage Grappling
- 2024-12-13 Soirée de Noël (Karaté)
- 2025-01-18 Stage Karaté JP Lavorato
- 2025-04-11 Lecture et dédicace _L’appel du Karaté_
- 2025-05-10 Stage Karaté Mike Julie
- 2025-05-15 Stage Christian CLAUSE (9e dan)
- 2025-06-28 Passage de grade et fin de saison

Participation extérieure :  
- 2024-09-07 Forum des Associations
- 2025-04-06 Interclubs St-Jeannais
- 2025-04-18 Fête du Kata

---
layout: two-cols-header
layoutClass: gap-2
transition: slide-up
---
# Rapport financier
Budget prévisionnel 2024-25

**Résultat : + 3 130,00 €**

::left::

| **Recettes**  | Code | Montant |
| :------------ | :--: | ------: |
| Cotisations adhérents	         | 756 |    17 535,00 €   |
| Recettes événements	           | 706 |     2 000,00 €   |
| <br/><br/><br/>                |     |                  |
| **Total Recettes**             |     |  **19 535,00 €** |

::right::

| **Dépenses**  | Code | Montant |
| :------------ | :--: | ------: |
| Rémunération des intervenants	 | 621 |     10 600,00 €  |
| Achats de matériel	           | 606 |      2 483,00 €  |
| Assurance	                     | 616 |      1 200,00 €  |
| Licences sportives	           | 628 |      2 122,00 €  |
| **Total Dépenses**	           | 	   |  **16 405,00 €** |

---
layout: two-cols-header
layoutClass: gap-2
---

# Rapport financier
Bilan 2024-25

**Résultat : + 4 134,16 €** (bilan 2023-24 : + 797, 00 €)
<br/>
<br/>
Aides indirectes de la ville de Genas : <span v-mark.circle.orange="1">**+ 5 592,00 €**</span>

::left::

| **Recettes** | Code | Montant |
| :----------- | :--: | ------: |
| Cotisations adhérents	         | 756 |    17 707,58 €   |
| Recettes événements	           | 706 |     3 000,58 €   |
| Contributions financières	     | 755 |       909,28 €   |
| <br/>                          |     |                  |
| **Total Recettes**             |     |  **21 617,44 €** |

::right::

| **Dépenses** | Code | Montant |
| :----------- | :--: | ------: |
| Rémunération des intervenants	 | 621 |    13 701,27 €   |
| Achats de matériel	           | 606 |       163,00 €   |
| Assurance	(+ frais)            | 6xx |     1 889,01 €   |
| Licences sportives	           | 628 |     2 270,00 €   |
| **Total Dépenses**    	       | 	   |  **17 483,28 €** |

---
layout: center
transition: fade-out
---

## 🗳️ Vote du rapport financier 2024-25

---
layout: two-cols-header
layoutClass: gap-2
---

# Budget prévisionnel
Saison 2025-26

::left::

| **Recettes**  | Code | Montant |
| :------------ | :--: | ------: |
| Cotisations adhérents	         | 706  |    22 500,00 €   |
| Stages, événements	           | 707  |     2 000,00 €   |
| Subventions                    | 740  |         0,00 €   |
| Partenariats / mécénat         | 754  |         0,00 €   |
| <br/><br/><br/>                |      |                  |
| **Total Recettes**             |      |  **22 500,00 €** |

::right::

| **Dépenses**  | Code | Montant |
| :------------ | :--: | ------: |
| Rémunération des intervenants	 | 6xx  |     14 000,00 €  |
| Achats de matériel	           | 601  |      1 300,00 €  |
| Publicité, communication       | 601  |      1 000,00 €  |
| Evénements                     | 6257 |      1 800,00 €  |
| Assurance	                     | 616  |      1 200,00 €  |
| Licences fédérales             | 647  |      3 200,00 €  |
| **Total Dépenses**	           | 	    |  **22 500,00 €** |

---
layout: center
transition: fade-out
---

## 🗳️ Vote du budget prévisionnel 2025-26

---
layout: two-cols-header
layoutClass: gap-16
---

# Aperçu de la saison 2025-26

::left::

| Section | Membres |
| :------ | :-----: |
| Karaté 5-7 ans      | 16 |
| Karaté 8-13 ans     | 32 |
| Karaté Ados/Adultes | 13 |
| Karaté Self-Défense | 15 |
| Body-Fight          | 10 |
| MMA                 |  9 |

::right::

| Répartitions |         |
| :----------- | :-----: |
| Membres      | **95**  |
| Genassiens   | **72 (76 %)** |
| M / F        | 57 / 38 |

---
transition: slide-up
---

# Projets 2025-26

- Changement de nom de l'association (suite aux nouveaux statuts) ✔
- Refonte de l'identité visuelle et du site internet : artsmartiauxgenas.fr ✔
- Mise en place des calendriers partagés ✔
- Création d'une section _Karaté Santé_ ❌
  - Trop peu de personnes inscrites à cette section pour la maintenir sur l'année.  
  Communication aux membres impactés le 05/10/2025. 
- Organisation de la communication Facebook et Instagram 👷‍♂️
- Commandes de casquettes et t-shirts 🔥
- Commandes d'écussons 🔥

---
transition: fade-out
---

# Evénements 2025-26

- 2025-09-06 Forum des Associations ✔
- 2025-11-06 AG 👷‍♂️
- 2025-11-20 Stage Jean-Louis Morel (8e dan) - salle 1 ou 4 Genas 🔥
- début décembre Fête de Noël 🎅
- 2025-12-08 Stage partenariat avec les Epides
- 2026-01-07 Stage Jean-Pierre Lavorato (10e dan) - dojo Genas 🔥
- 2026-03-21 Stage enfants/adultes Mike Julie (7e dan) - dojo Genas 🔥
- avril 2026 Projet de stage sport arts martiaux
- 2026-05-28 Stage Christian Clause (9e dan) - salle 1 ou 4 Genas 🔥
- 2025-06-21 Fin de saison

Participations : 
- 2025-11-30 Stage Mike Julie + Philippe Corneloup + Stéphane Marie

---
transition: fade-out
---

# Renouvellement du CA

## Mandats du CA

- Geoffrey Petri — Président (2022–2025)
- Cyrille Protiere — Secrétaire (2025–2028)
- Dragos Mocanu — Trésorier (2025–2028)
- Laurent Galin (2024–2027)

## 📣 Appel à volontaires pour intégrer le CA

<br/>

## 🗳️ Vote pour le renouvellement de Président

---
layout: cover
transition: fade-out
---
# ⁉️ Questions diverses

---
layout: cover
---
# ⌛️ Fin de session
## Assemblée Générale 2025-26
### Arts Martiaux Genas
Merci à tous
