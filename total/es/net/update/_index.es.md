---
title: Actualizar archivos de Excel usando .NET 

description: Edite documentos de Microsoft Excel XLSX, XLS, CSV sin instalar Microsoft Office con aplicaciones basadas en C# .NET.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Actualizar documentos de Excel a través de .NET" h2="Modifique archivos Microsoft Excel XLSX, XLS dentro de aplicaciones basadas en .NET sin instalar Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Es común que la organización actualice sus datos, almacenados en archivos de Excel, como datos de estudiantes, registros de pacientes y lista de artículos del almacén, etc. a través del software de la empresa. [Aspose.Total for .NET](https://products.aspose.com/total/net/) API proporciona la funcionalidad de modificar las hojas de cálculo utilizando el software. Los programadores pueden mejorar el software con las capacidades de modificación simplemente escribiendo unas pocas líneas de código API. La API [Aspose.Cells for .NET](https://products.aspose.com/cells/net/) que forma parte del paquete [Aspose.Total for .NET](https://products.aspose.com/total/net/) facilita este proceso de modificación. A continuación se muestra el proceso de actualización del documento Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Actualizar documentos de Excel usando .NET" %}}

[Aspose.Cells for .NET](https://products.aspose.com/cells/net/) API proporciona la clase Workbook que maneja la carga de hojas de cálculo de Excel. El proceso es simple. Cree el objeto [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/) proporcionando el archivo fuente como parámetro. Acceda a la hoja de trabajo correspondiente proporcionando su índice utilizando el método [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/). Utilice el método [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/) para modificar el contenido de la celda a la que se accede y, finalmente, llame al método save() para guardar el documento.

{{% blocks/products/pf/feature-page-code h3="Código .NET - Actualización de documentos de Excel" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Actualizar">}}