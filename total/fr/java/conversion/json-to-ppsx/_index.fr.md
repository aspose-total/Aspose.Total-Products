---
title: Convertir le format JSON en PPSX via Java
description: Analyser JSON en PPSX en Java sans utiliser Microsoft PowerPoint
url_ignore: /fr/java/conversion/json-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPSX
otherformats: PPT POTM PPTM PPS PPSX POT POWERPOINT OTP POTX PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convertir le format JSON en PPSX via Java" h2="API Java pour analyser le format JSON en PPSX sans utiliser Microsoft<sup>&reg;</sup> PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Java](https://products.aspose.com/total/java/), vous pouvez convertir le format JSON en PPSX dans n'importe quelle application Java en deux étapes simples. Tout d'abord, en utilisant [Aspose.Cells for Java](https://products.aspose.com/cells/java/), vous pouvez analyser JSON en PPTX. Après cela, en utilisant [Aspose.Slides for Java](https://products.aspose.com/slides/java/), vous pouvez convertir PPTX en PPSX.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le format JSON en PPSX via Java" %}}
1. Créez un nouvel objet [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) et ouvrez le fichier JSON
2. Enregistrez JSON en tant que PPTX en utilisant [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) méthode
3. Chargez le document PPTX en utilisant la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Enregistrez le document au format PPSX à l'aide de la méthode [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et incluez des bibliothèques dans votre pom.xml.

Vous pouvez également obtenir un fichier ZIP à partir de [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
De plus, l'API vous permet d'analyser JSON en PPSX avec des options de mise en page spécifiées. Afin de spécifier les options de mise en page, vous pouvez utiliser la classe [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Il vous permet de traiter un tableau comme un tableau, d'ignorer les valeurs nulles, d'ignorer le titre du tableau, d'ignorer le titre de l'objet, de convertir une chaîne en nombre ou en date, de définir le format de date et de nombre et de définir le style du titre. Toutes ces options vous permettent de présenter vos données selon vos besoins. L'extrait de code suivant vous montre comment définir les options de mise en page.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Définir la mise en page et convertir le format JSON en PPSX via Java" %}}
À l'aide de l'API, vous pouvez également convertir JSON en PPSX avec filigrane. Afin d'ajouter un filigrane à votre document PPSX, vous pouvez d'abord analyser JSON en PPTX et y ajouter un filigrane. Pour ajouter un filigrane, chargez le fichier PPTX nouvellement créé à l'aide de la classe [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation), parcourez toutes les diapositives, ajoutez du texte en utilisant addTextFrame, définissez toutes les options pertinentes comme la couleur, fillType et plus et pouvez enregistrer le document sur PPSX. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}