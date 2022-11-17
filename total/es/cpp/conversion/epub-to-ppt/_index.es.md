---
title: API de C++ para convertir EPUB a PPT
description: Convierta EPUB a PPT a través de C++ sin usar Microsoft Word o Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: PPT
otherformats: PPSX PPTM SWF POTX PPS ODP POTM POT XAML POWERPOINT PPSM OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar EPUB a PPT dentro de aplicaciones C++" h2="Convierta EPUB a PPT dentro de sus aplicaciones C++ sin usar Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
¿Es usted un desarrollador de C++ que busca agregar para integrar la función de conversión de EPUB a PPT dentro de sus aplicaciones de C++? Puedes hacerlo en dos sencillos pasos. Puede exportar EPUB a PPTX mediante [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). En segundo lugar, al usar [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), puede convertir PPTX a PPT. Ambas API se incluyen en el paquete [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para exportar EPUB a PPT" %}}
1. Abra el archivo EPUB usando la referencia de clase [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Convierta EPUB a PPTX usando la función de método [Guardar](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Cargue el documento PPTX utilizando la referencia de clase [Presentación](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Guarde el documento en formato PPT usando la función miembro [Guardar](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) y configure `Ppt` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load EPUB file with an instance of Document class
auto doc = MakeObject<Document>(u"template.epub");
// save EPUB as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Cambiar la contraseña del documento EPUB a través de C++" %}}
En el proceso de convertir EPUB a PPT, puede abrir un EPUB protegido con contraseña y también cambiar su contraseña. Para cambiar la contraseña de un archivo EPUB, debe conocer la contraseña del propietario de ese documento. Puede cargar un documento PDF protegido con contraseña con [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) especificando su contraseña de propietario y usando el método ChangePasswords para cambiar la contraseña.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing EPUB Document
auto doc = MakeObject<Document>(L"input.epub", L"owner");
// change password of EPUB Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Agregue imágenes desde la web en un archivo PPT a través de C++" %}}
Después de convertir EPUB a PPT, también puede agregar imágenes de la web a su documento de salida. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) admite operaciones con imágenes en estos formatos populares: JPEG, PNG, BMP, GIF y otros. Puede agregar una o varias imágenes en su computadora a una diapositiva en una presentación. Este código de muestra en C++ le muestra cómo agregar una imagen a un archivo PPT
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPT file
auto pres = System::MakeObject<Presentation>("output.ppt");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/epub-to-ppsx/" name="EPUB A PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/epub-to-pptm/" name="EPUB A PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/epub-to-swf/" name="EPUB A SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/epub-to-potx/" name="EPUB A POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/epub-to-pps/" name="EPUB A PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/epub-to-ppt/" name="EPUB A PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/epub-to-potm/" name="EPUB A POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/epub-to-pot/" name="EPUB A POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/epub-to-xaml/" name="EPUB A XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/epub-to-powerpoint/" name="EPUB A POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/epub-to-ppsm/" name="EPUB A PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/epub-to-otp/" name="EPUB A OTP" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}