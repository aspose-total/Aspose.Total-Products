---
title: Mettre à jour le fichier XLT à l'aide de Python
description: Modifiez le document XLT dans les applications Python sans utiliser Microsoft Excel. 

family: total
platformtag: Python
feature: update
informat: XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Mettre à jour le fichier XLT via Python" h2="Modifiez les feuilles de calcul XLT via vos applications Python sans installer Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pour un développeur, qui essaie de mettre à jour des fichiers XLT via l'application Python ? L'API [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) peut aider à automatiser le processus de mise à jour. Il s'agit d'un ensemble complet de diverses API traitant différents formats, y compris les fichiers Microsoft Excel. L'API ASPOSE.CELL qui fait partie du package [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) facilite ce processus de modification. Vous trouverez ci-dessous le processus de mise à jour du document XLT.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment mettre à jour le fichier XLT en Python" %}}

- Créer un nouvel objet de classe [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook) ayant le fichier XLT source comme paramètre
- Accès à la feuille de calcul pertinente à l'aide de la méthode [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)
- Insérer de nouvelles données dans la cellule consultée à l'aide de la méthode [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)
- Enregistrez le fichier en tant que fichier .xlt en utilisant la méthode save () en passant le fichier avec le chemin comme paramètre

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de modification" %}}

- Pour la modification XLT, référencez les API dans le projet directement depuis PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells/))
- Ou utilisez la commande pip suivante ```pip install aspose.cells``` 
- De plus, téléchargez le package API à partir de la section [Téléchargements](https://releases.aspose.com/cells/python-java)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Code - Mettre à jour le fichier XLT en Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}