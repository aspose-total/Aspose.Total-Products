---
title: API Java pour rendre CGM en TXT
description: Exportez CGM vers TXT via l'API Java sans utiliser Microsoft Excel ou Adobe Reader
url_ignore: /fr/java/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLAM FODS XLTM ODS MD DIF EXCEL TXT XLTX XLT SXC XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exporter CGM vers TXT via Java" h2="Convertissez le fichier CGM en TXT en utilisant l'API Java sur site dans toutes les applications Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for Java](https://products.aspose.com/total/java/), vous pouvez intégrer la fonction de conversion CGM vers TXT dans vos applications Java en deux étapes. Tout d'abord, en utilisant [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), vous pouvez rendre CGM en XLSX. Dans la deuxième étape, vous pouvez convertir XLSX en TXT à l'aide de l'API de programmation de feuille de calcul [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convertir le fichier CGM en TXT via Java" %}}
1. Ouvrez le fichier CGM à l'aide de la classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Convertissez CGM en XLSX en utilisant [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) méthode
3. Chargez le document XLSX à l'aide de la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Enregistrez le document au format TXT en utilisant [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. Méthode SaveOptions))
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Vous pouvez facilement utiliser Aspose.Total pour Java directement à partir d'un projet basé sur [Maven](https://releases.aspose.com/total/java/) et inclure [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) et [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) dans votre pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Exigences de conversion" %}}
Si votre document CGM est protégé par un mot de passe, vous ne pouvez pas le convertir en TXT sans le mot de passe. À l'aide de l'API, vous pouvez d'abord ouvrir le document protégé à l'aide d'un mot de passe valide et le convertir ensuite. Afin d'ouvrir le fichier crypté, vous pouvez initialiser une nouvelle instance du [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) classe et transmettez le nom de fichier et le mot de passe comme arguments.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convertir CGM protégé en TXT via Java" %}}
Lors de la conversion du fichier CGM en TXT, vous pouvez également ajouter un filigrane au format de votre fichier TXT de sortie. Pour ajouter un filigrane, créez un nouveau classeur pour ouvrir le fichier XLSX converti. Sélectionnez Feuille de calcul via son index, créez une forme et utilisez sa fonction addTextEffect, définissez les couleurs, la transparence, etc. Après cela, vous pouvez enregistrer votre document XLSX au format TXT avec filigrane. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/agp/feature-section >}}
```
Converting **Fichiers Computer Graphics Metafile (CGM)** en format **TXT (Texte brut)** est précieux pour extraire, documenter et traiter les informations graphiques vectorielles sous une forme légère et lisible par l'homme. Dans les **pipelines de traitement de données alimentés par Java**, cette conversion permet de transformer les diagrammes CGM en représentations textuelles pour le journalisation, le stockage des métadonnées ou l'analyse en aval. En capturant les éléments descriptifs des fichiers CGM en TXT, les organisations peuvent simplifier l'intégration avec d'autres systèmes, permettre une recherche et un indexation rapides, et assurer une compatibilité à long terme.



{{% blocks/products/pf/agp/feature-section-col title="Cas d'utilisation clés" %}}

- **Journalisation basée sur le texte des diagrammes**  
  Stockez les informations des diagrammes CGM sous forme de texte brut pour des raisons d'audit, de débogage ou d'archivage.

- **Extraction des descriptions graphiques vectorielles**  
  Convertissez les structures CGM en TXT pour l'analyse syntaxique, l'indexation de recherche ou l'intégration avec des outils d'analyse.

- **Documentation des métadonnées d'ingénierie**  
  Documentez les données d'ingénierie liées aux CGM dans des fichiers TXT pour une référence rapide et un stockage léger.


{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Scénarios d'automatisation" %}}

- **Bibliothèques d'E/S Java pour la conversion**  
  Utilisez les API de manipulation de fichiers Java standard ainsi que des analyseurs CGM pour extraire et écrire le contenu dans des fichiers TXT.

- **Services de surveillance de fichiers**  
  Automatisez la conversion de CGM en TXT en surveillant les répertoires avec le `WatchService` Java pour les nouveaux événements de fichiers.

- **Travaux de conversion par lots**  
  Traitez de grands volumes de fichiers CGM dans des tâches Java planifiées, exportant des représentations textuelles pour l'archivage ou l'analyse.

- **Exportateurs de texte brut dans les pipelines ETL**  
  Intégrez l'analyse des CGM et l'exportation en TXT dans des workflows d'extraction-transformation-chargement basés sur Java pour le traitement de données structurées.
```
{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}