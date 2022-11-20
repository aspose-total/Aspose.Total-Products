---
title: Actualizar archivo XLTX usando C++
description: Modifique el documento XLTX en aplicaciones C++ sin usar Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Actualizar archivo XLTX a través de C++" h2="Modifique hojas de cálculo XLTX a través de sus aplicaciones basadas en C++ sin instalar Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Para un programador que intenta actualizar archivos XLTX dentro de la aplicación C++, La API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) puede ayudar a automatizar el proceso de actualización. Es un paquete completo de diferentes bibliotecas de C++ que manejan múltiples formatos, incluidos documentos de Microsoft Excel. La API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) que forma parte del paquete [Aspose.Total for C++](https://products.aspose.com/total/cpp/) facilita este proceso de modificación. El proceso de actualización del documento XLTX es simple al acceder primero a la hoja y luego actualizar el valor de la celda en Excel usando C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo actualizar el archivo XLTX en C++" %}}

- Cargue el archivo XLTX usando [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Acceso a [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) relevante usando GetIWorksheets()->GetObjectByIndex(0) y celda relevante usando GetICells()->GetObjectByIndex
- Inserte nuevos datos en la celda a la que accedió usando el método PutValue
- Guarde el archivo como archivo .xltx usando el método Guardar pasando el archivo con la ruta como parámetro

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de modificación" %}}

- Para la modificación de XLTX, siguiendo [Requisitos del sistema](https://docs.aspose.com/cells/cpp/system-requirements/) para sistemas Windows y Linux 
- Instalar desde la línea de comandos como ```nuget install Aspose.Total.Cpp```
- O a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```
- Alternativamente, obtenga el instalador MSI fuera de línea o las DLL en un archivo ZIP de [Descargas](https://downloads.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código - Actualizar archivo XLTX en C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de modificación" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/update/xls/" name="Actualizar XLS Expediente" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/update/xlsx/" name="Actualizar XLSX Expediente" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/update/csv/" name="Actualizar CSV Expediente" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/update/xlsb/" name="Actualizar XLSB Expediente" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/update/xlsm/" name="Modificar XLSM Expediente" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/update/xlt/" name="Actualizar XLT Expediente" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/update/xltx/" name="Actualizar XLTX Expediente" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/update/xltm/" name="Actualizar XLTM Expediente" description="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/update/tsv/" name="Actualizar TSV Expediente" description="" >}}
{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}