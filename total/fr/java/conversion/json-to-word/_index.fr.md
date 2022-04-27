---
title: Convertir le format JSON en WORD via Java
description: Analyser JSON en WORD en Java sans utiliser Microsoft Word
url: /fr/java/conversion/json-to-word/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOC
otherformats: EPUB PCL WORDML WORD RTF MOBI DOT ODT PS FLATOPC DOTX OTT DOCM DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir le format JSON en WORD via Java" h2="API Java sur site pour analyser JSON vers WORD sans utiliser Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total pour Java](https://products.aspose.com/total/java/), vous pouvez convertir JSON en WORD dans vos applications Java en deux étapes. Tout d'abord, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez analyser JSON en PDF. Dans la deuxième étape, vous pouvez convertir un PDF en WORD en utilisant l'API de traitement de texte [Aspose.Words pour Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le format JSON en WORD via Java" %}}
1. Créez un nouvel objet [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) et lisez les données JSON valides à partir du fichier
2. Importez le fichier JSON dans la feuille de calcul à l'aide de la classe [JsonUtility](https://apireference.aspose.com/cells/java/com.aspose.cells/JsonUtility) et [Save](https://apireference.aspose.com/ cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) au format PDF
3. Chargez le document PDF en utilisant la classe [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document)
4. Enregistrez le document au format WORD en utilisant [Save](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions )) méthode
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
De plus, l'API vous permet de définir des options de mise en page pour votre JSON lors de l'analyse de JSON vers WORD à l'aide de [JsonLayoutOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Il vous permet de traiter Array comme une table, d'ignorer les valeurs nulles, d'ignorer le titre du tableau, d'ignorer le titre de l'objet, de convertir une chaîne en nombre ou en date, de définir le format de la date et du nombre et de définir le style du titre. Toutes ces options vous permettent de présenter vos données selon vos besoins. L'extrait de code suivant vous montre comment définir les options de mise en page.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Définir la mise en page et convertir le format JSON en WORD via Java" %}}
À l'aide de l'API, vous pouvez également analyser JSON en WORD avec filigrane. Afin d'ajouter un filigrane à votre document WORD, vous pouvez d'abord convertir le fichier JSON en PDF et y ajouter un filigrane. Pour ajouter un filigrane, chargez le fichier PDF nouvellement créé à l'aide de la classe [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document), créez une instance de TextWatermarkOptions et définissez ses propriétés, appelez la méthode Watermark.setText et transmettez le texte et l'objet du filigrane de TextWatermarkOptions. Après avoir ajouté le filigrane, vous pouvez enregistrer le document sur WORD. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Autres options de conversion" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-flatopc/" name="JSON Pour FLAPourPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-docm/" name="JSON Pour DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-word/" name="JSON Pour WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-wordml/" name="JSON Pour WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-odt/" name="JSON Pour ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-rtf/" name="JSON Pour RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-doc/" name="JSON Pour DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-mobi/" name="JSON Pour MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-ott/" name="JSON Pour OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-dotx/" name="JSON Pour DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-pcl/" name="JSON Pour PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-dot/" name="JSON Pour DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-epub/" name="JSON Pour EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/json-to-ps/" name="JSON Pour PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}