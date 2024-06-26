---
title: Convertir EXCEL en POTM en utilisant Python
description: Conversion EXCEL en POTM dans vos applications Python sans utiliser Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: EXCEL
outformat: POTM
otherformats: PowerPoint PPT PPTX PPS POT PPSX PPTM PPSM POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir EXCEL en POTM via Python" h2="Conversion EXCEL en POTM dans vos applications Python sans installer Microsoft Excel<sup>&reg;</sup> ou PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Pour un développeur Python qui essaie d'ajouter une fonction de conversion EXCEL en POTM dans l'application, L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) peut aider à automatiser le processus de conversion. C'est un package complet de diverses API traitant différents formats, y compris les fichiers EXCEL et POTM.

C'est principalement en deux étapes. Utilisez d'abord l'API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) pour convertir le fichier EXCEL en PDF. Après cela, en utilisant l'API PowerPoint Python [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/), enregistrez le PDF créé au format Microsoft PowerPoint souhaité.. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment convertir EXCEL en POTM en Python" %}}
- **Étape 1** Utiliser l'instance de classe Workbook pour ouvrir le fichier EXCEL source 
- Enregistrez le fichier EXCEL au format PDF en utilisant la méthode save en fournissant le nom du fichier et le chemin du répertoire souhaité
-  **Étape 2** Charger le fichier PDF en utilisant la classe [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Appelez la méthode [save](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) tout en spécifiant le chemin du fichier POTM de sortie. Ainsi, votre fichier EXCEL est converti en POTM au chemin spécifié

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}

- Pour la conversion EXCEL en POTM, Python 3.5 ou version ultérieure est requis
- API de référence dans le projet directement depuis PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) et [Aspose.Slides](https://pypi.org/project/Aspose.Slides/))
-  Ou utilisez les commandes pip suivantes ```pip install aspose-cells-python``` et ```pip install aspose.slides```
-  De plus, OS basé sur Microsoft Windows ou Linux (voir plus pour [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) et [Slides](https://docs.aspose.com/slides/python-net/system-requirements/))
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Enregistrer EXCEL au format PDF en Python - Étape 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "convert-microsoft-excel-file-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Enregistrer le PDF au format POTM en Python - Étape 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "43edf3ae7660cdd4ba7a7ee82816e7ac" "pdf-documents-to-powerpoint-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}