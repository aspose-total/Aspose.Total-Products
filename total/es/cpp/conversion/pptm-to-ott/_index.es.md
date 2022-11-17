---
title: API de C++ para convertir PPTM a OTT
description: Exporte PPTM a OTT dentro de sus aplicaciones C++

family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: OTT
otherformats: DOTM WORDML WORD DOT DOCX ODT RTF DOTX DOCM TEXT DOC FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para renderizar PPTM a OTT" h2="Exporte PPTM a OTT en aplicaciones C++ sin dependencias de Microsoft PowerPoint o Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) es un paquete completo de bibliotecas de automatización de formato de archivo C++. Mediante el uso de las ricas funciones de las API disponibles en el paquete, podemos convertir fácilmente PowerPoint PPTM a Word OTT. Para realizar la conversión, primero puede usar la API [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para convertir PPTM a HTML. Después de eso, al usar la API de procesamiento de textos rica en funciones [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puede convertir el HTML a OTT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir PPTM a OTT" %}}
1. Cargue el archivo PPTM usando la referencia de clase [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
2. Renderice PPTM a HTML usando la función de miembro [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) y configure Html como SaveFormat
3. Cargue el archivo HTML convertido usando la referencia de clase [Ottumento](https://reference.aspose.com/words/cpp/class/aspose.words.ottument)
4. Guarde el ottumento en formato OTT usando la función de miembro [Guardar](https://reference.aspose.com/words/cpp/class/aspose.words.ottument#save_string)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// Load PPTM file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"input.pptm");
// Save presentation in HTML format.
prs->Save(u"htmlOutput.html", Aspose::Slides::Export::SaveFormat::Html);
// load HTML with an instance of Ottument
System::SharedPtr<Ottument> ott = System::MakeObject<Ottument>(u"htmlOutput.html");
// save ottument in OTT format
ott->Save(u"output.ott"); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pptm-to-dotm/" name="PPTM A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pptm-to-wordml/" name="PPTM A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pptm-to-word/" name="PPTM A WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pptm-to-dot/" name="PPTM A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pptm-to-ottx/" name="PPTM A OTTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pptm-to-odt/" name="PPTM A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pptm-to-rtf/" name="PPTM A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pptm-to-dotx/" name="PPTM A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pptm-to-ottm/" name="PPTM A OTTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pptm-to-text/" name="PPTM A TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pptm-to-ott/" name="PPTM A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pptm-to-flatopc/" name="PPTM A FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}