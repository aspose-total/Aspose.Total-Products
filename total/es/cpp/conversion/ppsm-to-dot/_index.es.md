---
title: API de C++ para convertir PPSM a DOT
description: Exporte PPSM a DOT dentro de sus aplicaciones C++

family: total
platformtag: cpp
feature: conversion
informat: PPSM
outformat: DOT
otherformats: DOC FLATOPC TEXT DOTX DOTM ODT DOCM WORD RTF OTT DOCX WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para renderizar PPSM a DOT" h2="Exporte PPSM a DOT en aplicaciones C++ sin dependencias de Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) es un paquete completo de bibliotecas de automatización de formato de archivo C++. Mediante el uso de las ricas funciones de las API disponibles en el paquete, podemos convertir fácilmente PowerPoint PPSM a Word DOT. Para realizar la conversión, primero puede usar la API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para convertir PPSM a HTML. Después de eso, al usar la API de procesamiento de textos rica en funciones [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puede convertir el HTML a DOT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir PPSM a DOT" %}}
1. Cargue el archivo PPSM usando la referencia de clase [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Renderice PPSM a HTML usando la función de miembro [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) y configure Html como SaveFormat
3. Cargue el archivo HTML convertido usando la referencia de clase [Dotumento](https://reference.aspose.com/words/cpp/class/aspose.words.dotument)
4. Guarde el dotumento en formato DOT usando la función de miembro [Guardar](https://reference.aspose.com/words/cpp/class/aspose.words.dotument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPSM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.ppsm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Dotument
System::SharedPtr<Dotument> dot = System::MakeObject<Dotument>(u"htmlOutput.html");
// save dotument in DOT format
dot->Save(u"output.dot"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppsm-to-dot/" name="PPSM A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppsm-to-flatopc/" name="PPSM A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppsm-to-text/" name="PPSM A TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppsm-to-dotx/" name="PPSM A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppsm-to-dotm/" name="PPSM A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppsm-to-odt/" name="PPSM A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppsm-to-dotm/" name="PPSM A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppsm-to-word/" name="PPSM A WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppsm-to-rtf/" name="PPSM A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppsm-to-ott/" name="PPSM A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppsm-to-dotx/" name="PPSM A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ppsm-to-wordml/" name="PPSM A WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}