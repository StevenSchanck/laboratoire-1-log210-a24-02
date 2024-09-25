# Plan d'itération 1

## Étapes jalons


| Étape jalon          | Date       |
| :------------------- | :--------- |
| Début de l'itération | 2024/09/25 |
| Démo (séance 5)      | 2024/10/09 |
| Fin de l'itération   | 2024/10/09 |

## Objectifs clés


- Établir les outils de développement sur le poste de chaque coéquipier (Git, GitHub, VS Code)
- Faire l'implémentation et les tests de CU01a - Ajouter cours (1 point)
- Faire l'implémentation et les tests de CU01b - Récupérer un cours (1 point)
- Faire l'implémentation et les tests de CU01c - Retirer un cours (0.5 point)
- Faire l'implémentation et les tests de U1 - Facteurs humains itération 1 (1 point)

## Affectations d'éléments de travail

Les éléments de travail suivants seront abordés dans cette itération:

| Nom / Description                | Priorité | [Taille estimée (points)](#commentEstimer "Comment estimer?") | Assigné à (nom) | Documents de référence |
| -------------------------------- | -------: | --------------------------: | --------------- | ---------------------- |
| CU01a                            | 1        | 11                           | Steven, Carine, Maksym           | Énoncé de laboratoire #1, exigences client (les sous-points héritent)  |
| &nbsp;-Conception                           |        |    2                        | Steven, Carine          |   |
|  &nbsp;-Implémentation                           |         |              5              | Maksym          |   | 
| &nbsp;-Tests                          |         |  4                          | Maksym          |   |
| CU01b                            | 1        |  9                         | Steven, Carine, Maksym          | Énoncé de laboratoire #1, exigences client (les sous-points héritent)   | 
| &nbsp;-Conception                           |         |  2                          | Steven, Carine            |   | 
|  &nbsp;-Implémentation                           |         |          4                | Maksym         |   | 
| &nbsp;-Tests                          |         |     3                      | Maksym          |   |
| CU01c                            | 3        | 9                             | Steven, Carine, Chris-Emmanuel          |    Énoncé de laboratoire #1, exigences client (les sous-points héritent)                    |
| &nbsp; -Conception                           |         |    2                       | Steven, Carine            |   |
|  &nbsp; -Implémentation                           |         |                     4       | Chris-Emmanuel          |   | 
| &nbsp; -Tests                          |         |    3                        | Chris-Emmanuel          |   |
| U1                            | 2        | 5                            |  Chris-Emmanuel          |    Énoncé de laboratoire #1, exigences client                    |
|  &nbsp;&nbsp;-Implémentation                           |         |        5                    | Chris-Emmanuel           |   | 
| Rapport                            | 2        | 5                            |  Carine, Steven Maksym, Chris-Emmanuel          |    Énoncé de laboratoire #1, exigences client                    |




## Problèmes

| Problème                                                                                             | Notes |
| ---------------------------------------------------------------------------------------------------- | ----- |
| Sans Objet                                    | -----      |


## Critères d'évaluation

- 70% des cas de test passent.
- Démonstration des fonctionnalités CU01 (CU01a, CU01b, CU01c) et U1 pas à pas avec l'auxiliaire d'enseignement a reçu une réponse favorable.

## Évaluation

> Utiliser cette section pour la saisie et la communication des résultats et les actions des évaluations, qui sont généralement faites à la fin de chaque itération. Si vous ne le faites pas, l'équipe ne peut pas être en mesure d'améliorer la façon dont elle développe des logiciels.
> **Note:** cette section est complétée seulement après l'évaluation faite par l'auxiliaire d'enseignement, lors de la démo en lab.

<!-- GitHub ne supporte pas les tables sans en-tête: https://stackoverflow.com/a/17543474/1168342 -->
| Résumé | |
| ------------------------------------- | ------------------------------------------------------------------------ |
| Cible d'évaluation                    | Itération <!-- *Cela pourrait être toute l'itération ou simplement un composant spécifique* -->                            |
| Date d'évaluation  |   2024/10/09 |
| Participants       | **Coéquipiers** : Carine, Chris-Emmanuel, Maksym, Steven <br> **auxiliaire d'enseignement** : Guillaume Langlois |
| État du projet     | 🔴 (il y a rien de fait encore) <!-- 🔴🟠🟢 *Rouge, Orange, ou Vert.* --> |

### Questions d'évaluation
Regardez votre diagramme TPLANT et répondez aux questions suivantes?
1. Est-ce qu'il y a un décalage de représentation?
  - Est-ce que tous les noms de classe ont un rapport avec le domaine?
2. Est-ce que l'architecture en couche est respectée?
   - Est-ce que les contrôleurs GRASP sont bien identifiés?
   - Est-ce que les paramètres des opérations système sont tous de type primitif ou sont des objets de paramètres de type primitif?
   - Est-ce que vous avez un fichier de route par contrôleur?
3. Évaluer votre conception par rapport aux GRASP "forte cohésion" et "faible couplage"
   - Avez-vous des classes qui sont couplées avec "beaucoup" d'autres classes?
   - Avez-vous des classes qui ont beaucoup de responsabilités (d'opérations)?
     - Faite surtout attention aux responsabilités que vous avez données à vos contrôleurs.
4. Y a-t-il des problèmes de Code smell à identifier avec l'aide de TPLANT
   1. Mysterious name relié au décalage des représentations ou pas
      1. Identifier le renommage (réusinage) éventuel de classe et/ou méthodes
   2. Large class (cohésion)
      1. Proposer d'appliquer le réusinage Extract class / GRAPS fabrication pure 
   3. Trop de paramètres (4+)
      1. Proposer d'appliquer le réusinage Objet de paramètre
   
### Évaluation par rapport aux objectifs

> Documentez si vous avez abordé les objectifs précisés dans le plan d'itération. *(on reprend les objectifs)*

- Résoudre les problèmes de la dernière itération soulevés par l'auxiliaire d'enseignement.
  - La rétroaction de l'auxiliaire d'enseignement a été positive. Bon travail l'équipe!
- Présenter une démonstration technique.
  - Le CU06 a été convaincant pour l'auxiliaire d'enseignement, mais il a trouvé que les tests pour le CU07 n'étaient pas assez étoffés. On doit corriger ça à la prochaine itération si on veut que le CU07 compte pour l'implémentation finale.

### Éléments de travail: prévus vs réalisés

> Résumez si tous les éléments de travail prévus dans l'itération ont été abordés, et des éléments de travail qui ont été reportés ou ajoutés.

Tous les éléments ont été complétés, mais il faut étoffer les tests du CU07:

- CU07 - test et implémentation assignés à Hélène

### Évaluation par rapport aux résultats selon les critères d'évaluation

> Documentez si vous avez satisfait les critères d'évaluation précisés dans le plan d'itération. Cela pourrait inclure des informations telles que «&nbsp;Démo pour le département X a été bien accueilli, avec quelques préoccupations soulevées autour de la convivialité&nbsp;», ou, «&nbsp;495 cas de tests ont été automatisés avec un taux de réussite de 98&nbsp;%. 9 cas de test ont été reportés parce que les éléments de travail correspondants ont été reportés.&nbsp;»

La solution a répondu à tous les critères, mais attention: il faut rajouter des cas de tests.

## Autres préoccupations et écarts

> Documentez d'autres domaines qui ont été évalués, tels que la finance ou un type de programme, ainsi que la rétroaction des intervenants qui n'a pas été saisie ailleurs

Nous avons discuté avec plusieurs professeurs pour comprendre le flux de travail de construction des devoirs à faire en ligne (CU06).

## Évaluation du travail d'équipe

> Évaluez la contribution de chaque membre de l'équipe au projet durant l'itération. Pour vous aider, utilisez `gitinspector` (voir les notes du cours). Toutefois, tenez aussi compte des éléments qui ne peuvent être évalués par l'outil (apprentissage, connaissances préalables, etc.)

Selon les statistiques générées par `gitinspector` Pierre et Jérémie font 90 % de la programmation et les deux autres membres doivent contribuer plus. Voir le script contribution.sh dans le répertoire scripts du projet.

Nous devons trouver un autre moyen de faire les commits (peut-être avec des branches et PR), car il y avait trop de merges difficiles de la documentation.

### Retrait d'un membre de l'équipe pour contribution non significative

- C'est ici que vous mettez le nom de la personne ainsi que les raisons du retrait. Cette section doit nécessairement inclure une liste d'objectifs que cette personne doit respecter pour pouvoir s'assurer de faire partie de l'itération suivante. 


---

<a name="commentPlanifier">Comment planifier une itération selon le
    processus unifié :</a>
    <https://etsmtl365-my.sharepoint.com/:w:/g/personal/christopher_fuhrman_etsmtl_ca/EWVA3MlzFHdElIMlduUvg6oBSAlrgHO7hjM2J93D1LGPSg?e=kCbXch>

<a name="commentEstimer">Comment estimer la taille :</a>
    <https://etsmtl365-my.sharepoint.com/:w:/g/personal/christopher_fuhrman_etsmtl_ca/EaEe2fDK94RAkfWthKX1pr4B7KBgbD9BW4UMrzwtQzOrkg?e=XMf4IK>
