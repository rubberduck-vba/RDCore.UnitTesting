# RDCore.UnitTesting
<sup>_This document is available in [English](./README.md)_</sup>

![VIVAT CUCUMIS](./assets/vivat-cucumis-stonecore.png)

RDCore.UnitTesting est l'extension de tests unitaires de la plateforme [RDCore](https://github.com/rubberduck-vba/RDCore), pour le code RD-VBA. Elle est en construction et fournira :

| Partie | Rôle |
|---|---|
| **Modules et méthodes de test** | Des annotations font d'un module standard un module de test et de ses procédures des tests, avec leurs méthodes d'initialisation et de nettoyage. L'extension les trouve et signale un test qui ne peut pas s'exécuter. |
| **`Assert`** | L'objet avec lequel un test vérifie ses résultats : `Assert.AreEqual`, `Assert.IsTrue`, `Assert.Fail` et les autres membres de l'`Assert` du Rubberduck legacy. |
| **Lignes de données** | Les annotations `@TestCase` exécutent une méthode de test une fois par ligne d'arguments, chaque ligne avec son propre résultat. |
| **`rdc test`** | Exécute les tests d'un espace de travail à partir de la ligne de commande, affiche chaque résultat et se termine avec un code qu'une compilation peut vérifier. |

L'extension s'exécute dans la plateforme RDCore, à côté de son serveur de langage. Elle se compile avec le paquet [RDCore.SDK](https://github.com/rubberduck-vba/RDCore.SDK) de NuGet.

## État du projet

RDCore.UnitTesting est en développement **pré-alpha**. Le référentiel ne contient aucun code, et aucun paquet n'est publié. L'extension a besoin de la plateforme RDCore pour s'exécuter.

## Licence

RDCore.UnitTesting est distribué sous la licence **MIT** : voir [LICENSE](LICENSE) et [NOTICE.md](NOTICE.md).

## Contributions

- Individus : ouvertes, sous le [CLA de RDCore](https://github.com/rubberduck-vba/RDCore/blob/main/CLA.md). Une seule signature couvre tous les référentiels de RDCore.
- Entreprises : prévues.

## Voir aussi

- [RDCore](https://github.com/rubberduck-vba/RDCore) : la plateforme, son _runtime_ et son serveur de langage
- [RDCore.SDK](https://github.com/rubberduck-vba/RDCore.SDK) : le modèle du langage et l'infrastructure commune sur lesquels reposent chaque composant et chaque extension de RDCore

<hr/>
<h6 align='center'>V I V A T ❤️ C U C U M I S ™</h6>
<p align='center' style='font-size:8pt;'>
<small>© Copyright <strong>9562-7303 Québec inc.</strong> (2026)<br/><em>Seul, &quot;Rubberduck&quot; est utilisé pour fins de référence au projet open-source legacy <strong>utilisé publiquement ainsi depuis 2015</strong> et sans lien ni affiliation avec tout tiers détenteur d'une marque semblable dans quelque juridiction que ce soit.<br/>&quot;Rubberduck VBA&quot;, &quot;RDCore&quot; et &quot;VIVAT CUCUMIS&quot; sont des marques de commerce revendiquées par 9562-7303 Québec inc. (en attente); Toutes les marques appartiennent à leur détenteur respectif.<br/>RDCore.UnitTesting n'est pas un produit de Microsoft et n'est pas affilié à Microsoft, ni directement, ni indirectement.</em><br/><br/><em>If used alone, &quot;Rubberduck&quot; is used as a reference to the legacy open-source project <strong>the same way it has been used publicly since 2015</strong> and without any links or affiliation with any third-party trademark holders of a similar trademark in any jurisdiction.<br/>&quot;Rubberduck VBA&quot;, &quot;RDCore&quot; and &quot;VIVAT CUCUMIS&quot; are trademarks claimed by 9562-7303 Québec inc. (pending). All trademarks belong to their respective owners.<br/>RDCore.UnitTesting is not a Microsoft product and is not affiliated with Microsoft, directly or indirectly.</em></small>
</p>
