---
title: Mettre à jour les fichiers Excel à l'aide de Java 

description: Modifiez les documents Microsoft Excel XLSX, XLS, CSV sans installer Microsoft Office dans les applications basées sur Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Mettre à jour des documents Excel via Java" h2="Modifiez les fichiers Microsoft Excel XLSX, XLS dans les applications basées sur Java sans installer Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Il est courant que l'organisation mette à jour ses données, stockées dans des fichiers Excel tels que les données des étudiants, les dossiers des patients et la liste des articles d'entrepôt, etc. via le logiciel de l'entreprise. L'API [Aspose.Total for Java](https://products.aspose.com/total/java/) fournit la fonctionnalité de modification des feuilles de calcul à l'aide de leur propre logiciel. Les programmeurs peuvent améliorer le logiciel avec les capacités de modification en écrivant simplement quelques lignes de code API. L'API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) qui fait partie du package [Aspose.Total for Java](https://products.aspose.com/total/java/) facilite ce processus de modification. Vous trouverez ci-dessous le processus de mise à jour du document Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Mettre à jour des documents Excel à l'aide de Java" %}}

L'API [Aspose.Cells for Java](https://products.aspose.com/cells/java/) fournit la classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) qui gère le chargement des feuilles de calcul Excel. Le processus est simple. Créez l'objet de classe Workbook en fournissant le fichier source comme paramètre. Accédez à la feuille de calcul et à la cellule pertinentes à l'aide de la méthode [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int)). Utilisez la méthode [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value) pour modifier le contenu de la cellule accédée et enfin appelez la méthode save() pour enregistrer le document.

{{% blocks/products/pf/feature-page-code h3="Code Java - Mettre à jour les documents Excel" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Mise à jour">}}