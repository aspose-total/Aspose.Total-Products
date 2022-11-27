---
title: Actualizar archivos de Excel usando C++ 

description: Edite documentos de Microsoft Excel XLSX, XLS, CSV sin instalar Microsoft Office con aplicaciones basadas en C++.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Actualizar documentos de Excel a través de C++" h2="Modifique archivos Microsoft Excel XLSX, XLS dentro de aplicaciones basadas en C++ sin instalar Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
Es común que la organización actualice sus datos, almacenados en archivos de Excel, como datos de estudiantes, registros de pacientes y lista de artículos del almacén, etc. a través del software de la empresa. [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API proporciona la funcionalidad de modificar las hojas de cálculo utilizando el software. Los programadores pueden mejorar el software con las capacidades de modificación simplemente escribiendo unas pocas líneas de código API. La API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) que forma parte del paquete [Aspose.Total for C++](https://products.aspose.com/total/cpp/) facilita este proceso de modificación. A continuación se muestra el proceso de actualización del documento Excel.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Actualizar documentos de Excel usando C++" %}}

Con la API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), cargue el documento de origen con [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8). Acceda al [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) usando GetIWorksheets()->GetObjectByIndex(0) y la celda requerida usando GetICells()->GetObjectByIndex. Usando el método PutValue, modifique el contenido en la celda a la que se accede. Por último, invoque el método save() para guardar el documento.

{{% blocks/products/pf/feature-page-code h3="Código C++ - Actualizar documentos de Excel" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Actualizar">}}