---
title: Convertir DOCX en MHTML en Python
description: Format d'archive Web DOCX vers mhtml et conversion de fichiers HtmlFixed dans vos applications Python sans utiliser Microsoft Word 

family: total
platformtag: Python
feature: conversion
informat: DOCX
outformat: MHTML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir DOCX en MHTML en utilisant Python" h2="Conversion DOCX en MHTML, HtmlFixed et HTML dans vos applications Python sans installer Microsoft Word<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pour un développeur Python, qui essaie d'ajouter une fonctionnalité de conversion DOCX vers MHTML (format d'archive Web) ou HtmlFixed signifie vouloir enregistrer le document au format HTML en utilisant des éléments absolument positionnés dans l'application. L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) peut aider à automatiser le processus de conversion. Il s'agit d'un ensemble complet de diverses API traitant de différents formats. 

Nous utilisons l'API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) qui fait partie du package [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) pour ajouter la fonction de conversion DOCX en MHTML. Si le fichier DOCX est simple, il ne s'agit que de deux lignes de code. Chargez le fichier DOCX et appelez la méthode save avec le chemin de fichier approprié avec l'énumération SaveFormat en tant que MHTML ou HTML_FIXED. Mais dans le cas où il est nécessaire de restaurer le modèle de document aussi proche de celui d'origine, il est nécessaire d'enregistrer des informations supplémentaires dans le document résultant, appelées informations aller-retour.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment Convertir DOCX en MHTML en Python" %}}
- Charger le fichier DOCX source à l'aide de la classe [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Créez l'instance de [HtmlSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/htmlsaveoptions/)
- Définissez export_roundtrip_information sur True
- Spécifiez [SaveFormat](https://reference.aspose.com/words/python-net/aspose.words/saveformat/) comme MHTML
- Appelez la méthode `save` tout en spécifiant le chemin du fichier de sortie et SaveFormat comme paramètres. Ainsi, votre fichier DOCX est converti en MHTML au chemin spécifié.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}

- Pour la conversion du format DOCX vers MHTML ou HtmlFixed, Python 3.5 ou version ultérieure est requis
- API de référence dans le projet directement depuis PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/))
- Ou utilisez les commandes pip suivantes ```pip install aspose.words```
- De plus, les systèmes d'exploitation basés sur Microsoft Windows ou Linux (voir plus pour [Words](https://docs.aspose.com/words/python-net/system-requirements/)) et pour Linux vérifient les exigences supplémentaires pour gcc et libpython et suivent les instructions étape par étape [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Enregistrer DOCX en MHTML en Python - Simple" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-simple-microsoft-word-documents-to-mhtml-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Conversion DOCX en MHTML en Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "word-files-to-mhtml-conversion-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}