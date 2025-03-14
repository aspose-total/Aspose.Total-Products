---
title: Convertir CGM en TXT via l'API C#
description: API C# pour convertir un fichier CGM en TXT sans utiliser Microsoft Excel ou Adobe Reader
url_ignore: /fr/net/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLSM XLTX FODS TSV XLT XLSB XLAM MD XLTM ODS TXT EXCEL
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API C# pour rendre CGM en TXT" h2="Exporter le fichier CGM au format TXT via C# sans utiliser Microsoft<sup>&reg;</sup> Excel ou Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
En utilisant [Aspose.Total for .NET](https://products.aspose.com/total/net/), vous pouvez facilement convertir un fichier CGM en TXT dans n'importe quelle application .NET, C#, ASP.NET et VB.NET. Tout d'abord, en utilisant [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), vous pouvez exporter CGM vers XLSX. Après cela, en utilisant l'API de programmation de feuille de calcul [Aspose.Cells for .NET](https://products.aspose.com/cells/net/), vous pouvez convertir XLSX en TXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET pour convertir CGM en TXT" %}}
1. Ouvrez le fichier CGM à l'aide de la classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Convertir CGM en XLSX en utilisant la méthode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Chargez le document XLSX en utilisant la classe [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook)
4. Enregistrez le document au format TXT à l'aide de la méthode [Save](https://reference.aspose.com/cells/net/aspose.cells.workbook/save/methods/4) et définissez `Txt` comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel.cs" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir CGM protégé en TXT via C#" %}}
Si votre document CGM est protégé par un mot de passe, vous ne pouvez pas le convertir en TXT sans le mot de passe. À l'aide de l'API, vous pouvez d'abord ouvrir le document protégé à l'aide d'un mot de passe valide et le convertir ensuite. Pour ouvrir le fichier chiffré, vous pouvez initialiser une nouvelle instance de la classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) et transmettre le nom de fichier et le mot de passe comme arguments.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-password-protected-pdf-to-excel.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir un fichier CGM en TXT avec filigrane via C#" %}}
Lors de la conversion du fichier CGM en TXT, vous pouvez également ajouter un filigrane au format de votre fichier TXT de sortie. Pour ajouter un filigrane, vous pouvez créer un nouvel objet Workbook et ouvrir le document XLSX converti, sélectionner Worksheet via son index, créer une Shape et utiliser sa fonction AddTextEffect. Après cela, vous pouvez enregistrer votre document XLSX au format TXT avec filigrane. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "0739adc8c301dc024f48b96d37b23dd7" "convert-pdf-to-excel-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformation d'un fichier CGM en TXT par programmation : cas d'utilisation" %}}
CGM (Metafile des Grapheurs Informatiques) est utilisé pour stocker les informations graphiques vectorielles, ce qui en fait idéal pour créer des graphics statiques et des illustrations fixes. Cependant, lorsqu'on travaille avec des données dynamiques, des éditeurs de texte comme Notepad deviennent essentiels pour la manipulation textuelle et la documentation.

La conversion des fichiers CGM en formats de texte plain sont nécessaires pour débloquer pleinement vos capacités d'édition textuelle. Cette conversion permet :

Utilisations :

*   Documentation des données : Convertir les fichiers CGM afin de créer une documentation readable par l'homme, facilitant ainsi la compréhension et la partage des informations graphiques.
*   Manipulation du texte : Utiliser Notepad pour éditer et manipuler les données de texte extraïtes des fichiers CGM, rendant les tâches d'édition textuelle basiques possibles.
*   Création d'art ASCII : Convertir les fichiers CGM afin de créer de l'art ASCII, créant des représentations simples, texte-basedes graphics pour des buts artistiques ou décoratifs.
*   Import des données de graphique dans d'autres outils : Utiliser la conversion en format de texte pour importer les informations graphiques dans d'autres éditeurs de texte ou logiciels de traitement du texte, enrichissant ainsi vos capacités de manipulation textuelle.
*   Rappel et débogage de base : Convertir les fichiers CGM afin de créer des rapports de base et des journaux de débogage, aidant dans l'identification des erreurs et problèmes au cours du processus de développement.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}