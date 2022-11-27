---
title: Mettre à jour les fichiers Excel à l'aide de .NET 

description: Modifiez des documents Microsoft Excel XLSX, XLS, CSV sans installer Microsoft Office avec des applications basées sur C# .NET.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Mettre à jour les documents Excel via .NET" h2="Modifiez les fichiers Microsoft Excel XLSX, XLS dans les applications basées sur .NET sans installer Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Il est courant que l'organisation mette à jour ses données, stockées dans des fichiers Excel tels que les données des étudiants, les dossiers des patients et la liste des articles d'entrepôt, etc. via le logiciel de l'entreprise. L'API [Aspose.Total for .NET](https://products.aspose.com/total/net/) fournit la fonctionnalité de modification des feuilles de calcul à l'aide du logiciel. Les programmeurs peuvent améliorer le logiciel avec les capacités de modification en écrivant simplement quelques lignes de code API. L'API [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) qui fait partie du package [Aspose.Total for .NET](https://products.aspose.com/total/net/) facilite ce processus de modification. Vous trouverez ci-dessous le processus de mise à jour du document Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Mettre à jour des documents Excel à l'aide de .NET" %}}

L'API [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) fournit la classe Workbook qui gère le chargement des feuilles de calcul Excel. Le processus est simple. Créez l'objet [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) en fournissant le fichier source en paramètre. Accédez à la feuille de travail pertinente en fournissant son index à l'aide de la méthode [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/). Utilisez la méthode [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/) pour modifier le contenu de la cellule accédée et enfin appelez la méthode save() pour enregistrer le document.

{{% blocks/products/pf/feature-page-code h3="Code .NET - Mettre à jour les documents Excel" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Mise à jour">}}