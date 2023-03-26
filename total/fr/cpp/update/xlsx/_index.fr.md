---
title: Mettre à jour le fichier XLSX à l'aide de C++
description: Modifier le document XLSX dans les applications C++ sans utiliser Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Mettre à jour le fichier XLSX via C++" h2="Modifiez les feuilles de calcul XLSX via vos applications basées sur C++ sans installer Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Pour un programmeur qui essaie de mettre à jour des fichiers XLSX dans une application C++, L'API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) peut aider à automatiser le processus de mise à jour. Il s'agit d'un ensemble complet de différentes bibliothèques C++ traitant plusieurs formats, y compris les documents Microsoft Excel. L'API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) qui fait partie du package [Aspose.Total for C++](https://products.aspose.com/total/cpp/) facilite ce processus de modification. Le processus de mise à jour du document XLSX est simple en accédant d'abord à la feuille, puis en mettant à jour la valeur de la cellule dans Excel à l'aide de C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Comment mettre à jour le fichier XLSX en C++" %}}

- Charger le fichier XLSX en utilisant [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Accès au [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) pertinent à l'aide de GetIWorksheets()->GetObjectByIndex(0) et à la cellule pertinente à l'aide de GetICells()->GetObjectByIndex
- Insérer de nouvelles données dans la cellule consultée à l'aide de la méthode PutValue
- Enregistrez le fichier en tant que fichier .xlsx à l'aide de la méthode Save en transmettant le fichier avec le chemin comme paramètre

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de modification" %}}

- Pour la modification XLSX, suivre [Configuration requise](https://docs.aspose.com/cells/cpp/system-requirements/) pour les systèmes Windows et Linux 
- Installer à partir de la ligne de commande en tant que ```nuget install Aspose.Total.Cpp```
- Ou via Package Manager Console de Visual Studio avec ```Install-Package Aspose.Total.Cpp```
- Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [Téléchargements](https://releases.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Code - Mettre à jour le fichier XLSX en C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}