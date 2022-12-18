---
title: Convertir PPSX en XLS en utilisant Python
description: Conversion PPSX en XLS dans vos applications Python sans utiliser Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: PPSX
outformat: XLS
otherformats: Excel XLS XLSX XLSB XLTX XLTM XLSM CSV TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir PPSX en XLS via Python" h2="Conversion PPSX en XLS dans vos applications Python sans installer Microsoft PowerPoint<sup>&reg;</sup> ou Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Pour un développeur Python, qui essaie d'ajouter une fonction de conversion PPSX en XLS dans l'application. L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) peut aider à automatiser le processus de conversion. Il s'agit d'un ensemble complet de diverses API traitant différents formats, y compris les fichiers PPSX et XLS.

C'est principalement en deux étapes. Utilisez d'abord l'API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) pour convertir le fichier PPSX en HTML. Après cela, en utilisant l'API Excel Python [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), enregistrez le code HTML créé au format Microsoft Excel souhaité. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment convertir PPSX en XLS en Python" %}}
- **Étape 1** Utiliser l'instance de classe [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) pour ouvrir le fichier PPSX source 
- Enregistrez le fichier PPSX au format HTML en utilisant la méthode [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) en fournissant le nom du fichier et le chemin du répertoire souhaité
-  **Étape 2** Charger le fichier HTML avec une instance de la classe Workbook
-  Appelez la méthode `save` tout en spécifiant le chemin du fichier XLS de sortie. Ainsi, votre fichier PPSX est converti en XLS au chemin spécifié

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}

- Pour la conversion PPSX en XLS, Python 3.5 ou version ultérieure est requis
- API de référence dans le projet directement depuis PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) et [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Ou utilisez les commandes pip suivantes ```pip install aspose.slides``` et ```pip install aspose-cells-python```
-  De plus, OS basé sur Microsoft Windows ou Linux (voir plus pour [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) et [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Enregistrer PPSX en HTML en Python - Étape 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "convert-microsoft-powerpoint-presentations-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Enregistrer HTML en XLS en Python - Étape 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "8eed2122b5524f1c19cc184cea1399cf" "html-documents-to-excel-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}