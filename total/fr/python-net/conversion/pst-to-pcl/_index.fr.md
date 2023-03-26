---
title: Convertir PST en PCL en Python
description: Enregistrez PST au format PCL dans vos applications Python sans utiliser Microsoft Outlook ou Word 

family: total
platformtag: Python
feature: conversion
informat: PST
outformat: PCL
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convertir PST en PCL en utilisant Python" h2="Conversion PST en PCL dans vos applications Python sans installer Microsoft Word<sup>&reg;</sup> ou Outlook." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pour un développeur Python, qui essaie d'ajouter une fonctionnalité de conversion PST en PCL dans l'application ? L'API [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) peut aider à automatiser le processus de conversion. Il s'agit d'un ensemble complet de diverses API traitant différents formats, notamment les formats Email, Images et Microsoft Word. Les API [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) et [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) qui font partie du package [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) facilitent cette conversion à l'aide de Python. C'est un processus en deux étapes, d'abord charger Email et le rendre en HTML via [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/). Ensuite, chargez le HTML converti en utilisant [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) et enregistrez-le au format PCL.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment convertir PST en PCL en Python" %}}

- Ouvrez le fichier PST source à l'aide de la classe MailMessage.load
- Appelez la méthode `save` tout en spécifiant le chemin du fichier HTML de sortie et les options d'enregistrement HTML pertinentes en tant que paramètre. Ainsi, votre fichier PST est converti en HTML au chemin spécifié
- Chargez maintenant le fichier HTML enregistré à l'aide de [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)
- Appelez la méthode save avec le chemin de fichier approprié. Donc finalement le PST est converti

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}

- Pour la conversion PST en PCL, Python 3.5 ou version ultérieure est requis
- API de référence dans le projet directement depuis PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) et [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- Ou utilisez la commande pip suivante ```pip install aspose.words``` et ```pip install Aspose.Email-for-Python-via-NET``` 
- De plus, les systèmes d'exploitation basés sur Microsoft Windows ou Linux (voir plus pour [Words](https://docs.aspose.com/words/python-net/system-requirements/) et [Email](https://docs.aspose.com/email/python-net/system-requirements/)) et pour Linux, vérifiez les exigences supplémentaires pour gcc et libpython et suivez les instructions étape par étape [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Enregistrer PST en PCL en Python" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}