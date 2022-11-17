---
title: API de C++ para convertir PPT a ODT
description: Exporte PPT a ODT dentro de sus aplicaciones C++

family: total
platformtag: cpp
feature: conversion
informat: PPT
outformat: ODT
otherformats: FLATOPC WORDML TEXT OTT DOCM DOC DOTM DOCX RTF DOTX WORD DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para renderizar PPT a ODT" h2="Exporte PPT a ODT en aplicaciones C++ sin dependencias de Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) es un paquete completo de bibliotecas de automatización de formato de archivo C++. Mediante el uso de las ricas funciones de las API disponibles en el paquete, podemos convertir fácilmente PowerPoint PPT a Word ODT. Para realizar la conversión, primero puede usar la API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para convertir PPT a HTML. Después de eso, al usar la API de procesamiento de textos rica en funciones [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puede convertir el HTML a ODT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir PPT a ODT" %}}
1. Cargue el archivo PPT usando la referencia de clase [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Renderice PPT a HTML usando la función de miembro [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) y configure Html como SaveFormat
3. Cargue el archivo HTML convertido usando la referencia de clase [Odtumento](https://reference.aspose.com/words/cpp/class/aspose.words.odtument)
4. Guarde el odtumento en formato ODT usando la función de miembro [Guardar](https://reference.aspose.com/words/cpp/class/aspose.words.odtument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPT file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppt");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Odtument
System::SharedPtr<Odtument> odt = System::MakeObject<Odtument>(u"htmlOutput.html");
// save odtument in ODT format
odt->Save(u"output.odt"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppt-to-flatopc/" name="PPT A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppt-to-wordml/" name="PPT A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppt-to-text/" name="PPT A TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppt-to-ott/" name="PPT A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppt-to-odtm/" name="PPT A ODTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppt-to-odt/" name="PPT A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppt-to-dotm/" name="PPT A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppt-to-odtx/" name="PPT A ODTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppt-to-rtf/" name="PPT A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppt-to-dotx/" name="PPT A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppt-to-word/" name="PPT A WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppt-to-dot/" name="PPT A DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}