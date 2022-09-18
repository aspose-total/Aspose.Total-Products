---
title: Convertir DOCX en PPSM en Python
description: Conversion DOCX en PPSM dans vos applications Python sans utiliser Microsoft Word ou PowerPoint 
url: /fr/python-net/conversion/docx-to-ppsm/
family: total
platformtag: Python
feature: conversion
informat: DOCX
outformat: PPSM
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir DOCX en PPSM en utilisant Python" h2="Conversion DOCX en PPSM dans vos applications Python sans installer Microsoft Word<sup>&reg;</sup> ou PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}

Pour un développeur Python, qui essaie d'ajouter une fonctionnalité de conversion DOCX en PPSM dans l'application ? L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) peut aider à automatiser le processus de conversion. Il s'agit d'un ensemble complet de diverses API traitant de différents formats. Alors **Comment convertir DOCX en PPSM en Python ?**

C'est principalement en deux étapes. Utilisez d'abord l'API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) pour convertir le fichier DOCX en PDF. Après cela, en utilisant l'API PowerPoint Python [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/), enregistrez le PDF créé dans la présentation au format PPSM. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir DOCX en PPSM en Python" %}}
- **Étape 1** Ouvrez le fichier DOCX source à l'aide de la classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Enregistrez le fichier DOCX au format PDF en utilisant la méthode [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) en fournissant le nom du fichier et le chemin du répertoire souhaité.
-  **Étape 2** Charger le fichier PDF avec une instance de la classe [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/)
-  Appelez la méthode `save` tout en spécifiant le chemin du fichier de sortie et SaveFormat.PPSM comme paramètres. Ainsi, votre fichier DOCX est converti en PPSM au chemin spécifié.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}

- Pour la conversion DOCX en PPSM, Python 3.5 ou version ultérieure est requis
- API de référence dans le projet directement à partir de PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) et [Aspose.Words](https://pypi.org/project/aspose-words/)) ou
- Utilisez les commandes pip suivantes ```pip install aspose.slides``` et ```pip install aspose.words```. En outre,
- Système d'exploitation basé sur Microsoft Windows ou Linux (voir plus pour [Slides](https://docs.aspose.com/slides/python-net/system-requirements/) et [Words](https://docs.aspose.com/words/python-net/system-requirements/)) et pour Linux, vérifiez les exigences supplémentaires pour gcc et libpython et suivez les instructions étape par étape [INSTALL](https://docs.aspose.com/words/python-net/installation/).
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Enregistrer DOCX au format PDF en Python - Étape 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Enregistrer le PDF au format PPSM en Python - Étape 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}