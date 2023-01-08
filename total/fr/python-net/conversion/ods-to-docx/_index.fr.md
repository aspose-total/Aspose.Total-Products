---
title: Convertir ODS en DOCX en utilisant Python
description: Conversion ODS en DOCX dans vos applications Python sans utiliser Microsoft Office 

family: total
platformtag: Python
feature: conversion
informat: ODS
outformat: DOCX
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir ODS en DOCX via Python" h2="Conversion ODS en DOCX dans vos applications Python sans installer Microsoft Excel<sup>&reg;</sup> ou Word" >}}

{{% blocks/products/pf/feature-page-summary %}}

Pour un développeur Python, qui essaie d'ajouter une fonction de conversion ODS en DOCX dans l'application. L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) peut aider à automatiser le processus de conversion. Il s'agit d'un ensemble complet de diverses API traitant différents formats, y compris les fichiers ODS et DOCX.

C'est principalement en deux étapes. Utilisez d'abord l'API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) pour convertir le fichier ODS en HTML. Après cela, en utilisant l'API Word Python [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/), enregistrez le code HTML créé au format Microsoft Word souhaité. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment convertir ODS en DOCX en Python" %}}
- **Étape 1** Ouvrez le fichier ODS source à l'aide de la classe Workbook
- Enregistrez le fichier ODS au format HTML en utilisant la méthode save(file, SaveFormat.HTML) en fournissant le nom du fichier et le chemin du répertoire souhaité
-  **Étape 2** Charger le fichier HTML avec une instance de la classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
-  Appelez la méthode `save` tout en spécifiant le chemin du fichier DOCX de sortie. Ainsi, votre fichier ODS est converti en DOCX au chemin spécifié

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}

- Pour la conversion ODS en DOCX, Python 3.5 ou version ultérieure est requis
- API de référence dans le projet directement depuis PyPI ([Aspose.Cells](https://pypi.org/project/aspose-cells-python/) et [Aspose.Words](https://pypi.org/project/aspose-words/))
-  Ou utilisez les commandes pip suivantes ```pip install aspose-cells-python``` et ```pip install aspose.words```
-  De plus, les systèmes d'exploitation basés sur Microsoft Windows ou Linux (voir plus pour [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation) et [Words](https://docs.aspose.com/words/python-net/system-requirements/)) et pour Linux, vérifiez les exigences supplémentaires pour gcc et libpython et suivez [instructions étape par étape](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Enregistrer ODS en HTML en Python - Étape 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-microsoft-excel-files-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Enregistrer HTML en DOCX en Python - Étape 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "d08d1227e1bbdc5631cd1ccc6ba8dd9a" "convert-html-files-to-word-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/python-net/conversion/ods-to-word/" name="ODS Pour WORD" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/python-net/conversion/ods-to-doc/" name="ODS Pour DOC" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/python-net/conversion/ods-to-docx/" name="ODS Pour DOCX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/python-net/conversion/ods-to-docm/" name="ODS Pour DOCM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/python-net/conversion/ods-to-dot/" name="ODS Pour DOT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/python-net/conversion/ods-to-dotm/" name="ODS Pour DOTM" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/python-net/conversion/ods-to-dotx/" name="ODS Pour DOTX" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/python-net/conversion/ods-to-mobi/" name="ODS Pour MOBI" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/python-net/conversion/ods-to-odt/" name="ODS Pour ODT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/python-net/conversion/ods-to-ott/" name="ODS Pour OTT" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/python-net/conversion/ods-to-rtf/" name="ODS Pour RTF" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/python-net/conversion/ods-to-wordml/" name="ODS Pour WORDML" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}