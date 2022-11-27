---
title: Mettre à jour les fichiers Excel à l'aide de C++ 

description: Modifiez des documents Microsoft Excel XLSX, XLS, CSV sans installer Microsoft Office avec des applications basées sur C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Mettre à jour les documents Excel via C++" h2="Modifiez les fichiers Microsoft Excel XLSX, XLS dans les applications basées sur C++ sans installer Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Il est courant que l'organisation mette à jour ses données, stockées dans des fichiers Excel tels que les données des étudiants, les dossiers des patients et la liste des articles d'entrepôt, etc. via le logiciel de l'entreprise. L'API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) fournit la fonctionnalité de modification des feuilles de calcul à l'aide du logiciel. Les programmeurs peuvent améliorer le logiciel avec les capacités de modification en écrivant simplement quelques lignes de code API. L'API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) qui fait partie du package [Aspose.Total for C++](https://products.aspose.com/total/cpp/) facilite ce processus de modification. Vous trouverez ci-dessous le processus de mise à jour du document Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Mettre à jour des documents Excel à l'aide de C++" %}}

À l'aide de l'API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), chargez le document source à l'aide de [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8). Accédez au [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) à l'aide de GetIWorksheets()->GetObjectByIndex(0) et à la cellule requise à l'aide de GetICells()->GetObjectByIndex. En utilisant la méthode PutValue, modifiez le contenu de la cellule accédée. Invoquez enfin la méthode save() pour enregistrer le document.

{{% blocks/products/pf/feature-page-code h3="Code C++ - Mettre à jour les documents Excel" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Mise à jour">}}