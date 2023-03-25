---
title: Actualizar archivo XLT usando C++
description: Modifique el documento XLT en aplicaciones C++ sin usar Microsoft Excel.
family: total
platformtag: C++
feature: update
informat: XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Actualizar archivo XLT a través de C++" h2="Modifique hojas de cálculo XLT a través de sus aplicaciones basadas en C++ sin instalar Microsoft Office<sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}

Para un programador que intenta actualizar archivos XLT dentro de la aplicación C++, La API [Aspose.Total for C++](https://products.aspose.com/total/cpp/) puede ayudar a automatizar el proceso de actualización. Es un paquete completo de diferentes bibliotecas de C++ que manejan múltiples formatos, incluidos documentos de Microsoft Excel. La API [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) que forma parte del paquete [Aspose.Total for C++](https://products.aspose.com/total/cpp/) facilita este proceso de modificación. El proceso de actualización del documento XLT es simple al acceder primero a la hoja y luego actualizar el valor de la celda en Excel usando C++.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Cómo actualizar el archivo XLT en C++" %}}

- Cargue el archivo XLT usando [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Acceso a [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) relevante usando GetIWorksheets()->GetObjectByIndex(0) y celda relevante usando GetICells()->GetObjectByIndex
- Inserte nuevos datos en la celda a la que accedió usando el método PutValue
- Guarde el archivo como archivo .xlt usando el método Guardar pasando el archivo con la ruta como parámetro

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de modificación" %}}

- Para la modificación de XLT, siguiendo [Requisitos del sistema](https://docs.aspose.com/cells/cpp/system-requirements/) para sistemas Windows y Linux 
- Instalar desde la línea de comandos como ```nuget install Aspose.Total.Cpp```
- O a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```
- Alternativamente, obtenga el instalador MSI fuera de línea o las DLL en un archivo ZIP de [Descargas](https://releases.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Código - Actualizar archivo XLT en C++" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}