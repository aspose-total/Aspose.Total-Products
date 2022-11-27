---
title: Mettre à jour les fichiers Excel à l'aide de Python 

description: Modifiez des documents Microsoft Excel XLSX, XLS, CSV sans installer Microsoft Office dans les applications Python
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Mettre à jour les documents Excel via Python" h2="Modifiez les fichiers Microsoft Excel XLSX, XLS dans les applications Python sans installer Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Il est courant que les organisations mettent à jour leurs données, stockées dans des fichiers Excel tels que les données des étudiants, les dossiers des patients et la liste des articles d'entrepôt, etc. via le logiciel de l'entreprise. L'API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) fournit la fonctionnalité de modification des feuilles de calcul via le logiciel. Les programmeurs peuvent améliorer le logiciel avec les capacités de modification en intégrant l'API et en écrivant quelques lignes de code. L'API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) qui fait partie du package [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) facilite ce processus de modification. Vous trouverez ci-dessous le processus de mise à jour du document Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Mettre à jour des documents Excel à l'aide de Python" %}}

L'API [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) fournit la classe Workbook qui gère le chargement des feuilles de calcul Excel. Le processus est simple. Créez l'objet de classe [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) en fournissant le fichier source comme paramètre. Utilisez la méthode [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets) pour accéder à la feuille de travail pertinente en fournissant son index. appelez la méthode [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells) pour modifier le contenu de la cellule accédée et invoquez enfin la méthode save() pour enregistrer le document.

{{% blocks/products/pf/feature-page-code h3="Python - Mettre à jour les documents Excel" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Mise à jour">}}