---
title: API C++ para converter CGM em POWERPOINT
description: Converta CGM para POWERPOINT via C++ sem usar o Microsoft Word ou Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: PPT
otherformats: OTP POTX ODP POT PPT XAML SWF PPSM PPS PPSX PPTM POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar CGM para POWERPOINT em aplicativos C++" h2="Converta CGM para POWERPOINT em seus aplicativos C++ sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você é um desenvolvedor C++ que deseja adicionar para integrar o recurso de conversão CGM para POWERPOINT dentro de seus aplicativos C++? Você pode fazer isso em duas etapas simples. Você pode exportar CGM para PPTX usando [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Em segundo lugar, usando [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), você pode converter PPTX para POWERPOINT. Ambas as APIs estão no pacote [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para exportar CGM para POWERPOINT" %}}
1. Abra o arquivo CGM usando a referência de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Converta CGM para PPTX usando a função do método [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Carregue o documento PPTX usando a referência de classe [Apresentação](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Salve o documento no formato POWERPOINT usando a função de membro [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e defina "Powerpoint" como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load CGM file with an instance of Document class
auto doc = MakeObject<Document>(u"template.cgm");
// save CGM as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Alterar senha do documento CGM via C++" %}}
No processo de renderização de CGM para POWERPOINT, você pode abrir um CGM protegido por senha e também alterar sua senha. Para alterar a senha de um arquivo CGM, você deve saber a senha do proprietário desse documento. Você pode carregar um documento PDF protegido por senha com [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) especificando sua senha de proprietário e usando o método ChangePasswords para alterar a senha.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing CGM Document
auto doc = MakeObject<Document>(L"input.cgm", L"owner");
// change password of CGM Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Adicionar imagens da Web no arquivo POWERPOINT via C++" %}}
Depois de converter CGM para POWERPOINT, você também pode adicionar imagens da web ao seu documento de saída. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) suporta operações com imagens nestes formatos populares: JPEG, PNG, BMP, GIF e outros. Você pode adicionar uma ou várias imagens em seu computador em um slide em uma apresentação. Este código de exemplo em C++ mostra como adicionar uma imagem a um arquivo POWERPOINT
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a POWERPOINT file
auto pres = System::MakeObject<Presentation>("output.powerpoint");
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
pres->Save(u"updated.powerpoint", SaveFormat::Ppt);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/cgm-to-otp/" name="CGM Para OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/cgm-to-potx/" name="CGM Para POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/cgm-to-powerpoint/" name="CGM Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/cgm-to-pot/" name="CGM Para POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/cgm-to-ppt/" name="CGM Para PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/cgm-to-xaml/" name="CGM Para XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/cgm-to-swf/" name="CGM Para SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/cgm-to-ppsm/" name="CGM Para PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/cgm-to-pps/" name="CGM Para PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/cgm-to-ppsx/" name="CGM Para PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/cgm-to-pptm/" name="CGM Para PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/cgm-to-potm/" name="CGM Para POTM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}