---
title: Update XLT File using C++
description: Modify XLT document in C++ applications without using Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Update XLT File via C++" h2="Modify XLT spreadsheets via your C++ based applications without installing Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

For a programmer, who is trying to update XLT files within C++ application, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API can help to automate the updating process. It's a full package of different C++ libraries dealing multiple formats including Microsoft Excel documents. [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API that is part of [Aspose.Total for C++](https://products.aspose.com/total/cpp/) package makes this modifying process easy. Process of updating the XLT document is simple by firstly accessing the sheet and then update cell value in excel using C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="How to Update XLT File in C++" %}}

- Load the XLT file using [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Access of relevant [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) using GetIWorksheets()->GetObjectByIndex(0) and relevant cell using GetICells()->GetObjectByIndex
- Insert new data in the accessed cell using PutValue method
- Save the file as .xlt file using Save method by passing the file with path as the parameter

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Modification Requirements" %}}

- For XLT modification, following [system requirements](https://docs.aspose.com/cells/cpp/system-requirements/) for Windows and Linux systems 
- Install from command line as ```nuget install Aspose.Total.Cpp```
- Or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Total.Cpp```
- Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://releases.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Code - Update XLT File in C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/feature-page-wrap >}}