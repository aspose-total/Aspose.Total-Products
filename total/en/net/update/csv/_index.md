---
title: Update CSV File using .NET
description: Modify CSV documents in C# VB.NET applications without using Microsoft Excel.
family: total
platformtag: .NET
feature: update
informat: CSV
semantic: true
page_type: generated_detail
hero:
  h1: Update CSV File via .NET
  h2: Modify CSV spreadsheet via your .NET based applications without installing Microsoft Office<sup>&reg;</sup>.
sections:
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: markdown
      markdown: For a developer, who is trying to update CSV files via .NET application. [Aspose.Total for .NET](https://products.aspose.com/total/net/) API can help to automate the updating process. It's a full package of various .NET APIs dealing different formats including Microsoft Excel files. [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API that is part of [Aspose.Total for .NET](https://products.aspose.com/total/net/) package makes this modifying process easy. Below is the process of updating the CSV document.
      role: summary
- layout: columns
  columns:
  - width: 6
    blocks:
    - type: steps
      role: api
      title: How to Update CSV File in .NET
      items:
      - Create new [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) class object having the source CSV file as parameter
      - Access of relevant Worksheet and relevant cell using [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/) method
      - Insert new data in the accessed cell using [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/) method
      - Save the file as .csv file using save() method by passing the file with path as the parameter
  - width: 6
    blocks:
    - type: markdown
      title: Modification Requirements
      markdown: "- For CSV modification, Microsoft Windows or a compatible OS with .NET, .NET Core, Mono or Xamarin Platforms\n- Development environment like Microsoft Visual Studio \n- Install from command line as ```nuget install Aspose.Cells``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.Cells```\n- Alternatively, get the offline MSI installer or all DLLs in a ZIP file from [Downloads](https://releases.aspose.com/cells/net)"
- layout: columns
  columns:
  - width: 12
    blocks:
    - type: code
      title: Code - Update CSV File in .NET
      gist:
        user: aspose-com-gists
        id: 800f8b626c3129d4682bc58338b93ecc
        file: update-excel-file-using-net.cs
- type: autogen_total
manual_review: true
---
{{< blocks/products/pf/agp/about-autogen-total >}}
