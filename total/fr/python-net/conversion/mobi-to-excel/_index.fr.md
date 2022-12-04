---
title: Convertir MOBI en EXCEL en utilisant Python
description: Conversion MOBI en EXCEL dans vos applications Python sans utiliser Microsoft Word ou Excel 

family: total
platformtag: Python
feature: conversion
informat: MOBI
outformat: EXCEL
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir MOBI en EXCEL via Python" h2="Conversion MOBI en EXCEL dans vos applications Python sans installer Microsoft Word<sup>&reg;</sup> ou Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Pour un développeur Python, qui essaie d'ajouter une fonction de conversion MOBI en EXCEL dans l'application. L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) peut aider à automatiser le processus de conversion. Il s'agit d'un ensemble complet de diverses API traitant de différents formats.

C'est principalement en deux étapes. Utilisez d'abord l'API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) pour convertir le fichier MOBI en HTML. Après cela, en utilisant l'API Excel Python [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/), enregistrez le code HTML créé au format Microsoft Excel souhaité. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment convertir MOBI en EXCEL en Python" %}}
- **Étape 1** Ouvrez le fichier MOBI source à l'aide de la classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Enregistrez le fichier MOBI au format HTML en utilisant la méthode [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) en fournissant le nom du fichier et le chemin du répertoire souhaité
-  **Étape 2** Charger le fichier HTML avec une instance de la classe Workbook avec file et LoadOptions comme paramètres
-  Appelez la méthode `save` tout en spécifiant le chemin du fichier EXCEL de sortie. Ainsi, votre fichier MOBI est converti en EXCEL au chemin spécifié

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}

- Pour la conversion MOBI en EXCEL, Python 3.5 ou version ultérieure est requis
- API de référence dans le projet directement depuis PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) et [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Ou utilisez les commandes pip suivantes ```pip install aspose.words``` et ```pip install aspose-cells-python``` 
-  De plus, les systèmes d'exploitation basés sur Microsoft Windows ou Linux (voir plus pour [Words](https://docs.aspose.com/words/python-net/system-requirements/) et [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) et pour Linux, vérifiez les exigences supplémentaires pour gcc et libpython et suivez [instructions étape par étape](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Enregistrer MOBI en HTML en Python - Étape 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Enregistrer HTML en EXCEL en Python - Étape 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}