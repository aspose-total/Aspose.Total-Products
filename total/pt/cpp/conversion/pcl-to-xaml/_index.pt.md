---
title: API C++ para converter PCL em XAML
description: Converta PCL para XAML via C++ sem usar o Microsoft Word ou Adobe Acrobat Reader

family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: XAML
otherformats: PPT PPS POTX SWF PPSM ODP PPSX PPTM POTM POWERPOINT POT OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar PCL para XAML em aplicativos C++" h2="Converta PCL para XAML em seus aplicativos C++ sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você é um desenvolvedor C++ que deseja adicionar para integrar o recurso de conversão PCL para XAML dentro de seus aplicativos C++? Você pode fazer isso em duas etapas simples. Você pode exportar PCL para PPTX usando [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Em segundo lugar, usando [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), você pode converter PPTX para XAML. Ambas as APIs estão no pacote [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para exportar PCL para XAML" %}}
1. Abra o arquivo PCL usando a referência de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Converta PCL para PPTX usando a função do método [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Carregue o documento PPTX usando a referência de classe [Apresentação](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Salve o documento no formato XAML usando a função de membro [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e defina "Xaml" como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PCL file with an instance of Document class
auto doc = MakeObject<Document>(u"template.pcl");
// save PCL as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Xaml format
prs->Save(u"output.xaml", Aspose::Slides::Export::SaveFormat::Xaml);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Alterar senha do documento PCL via C++" %}}
No processo de renderização de PCL para XAML, você pode abrir um PCL protegido por senha e também alterar sua senha. Para alterar a senha de um arquivo PCL, você deve saber a senha do proprietário desse documento. Você pode carregar um documento PDF protegido por senha com [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) especificando sua senha de proprietário e usando o método ChangePasswords para alterar a senha.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PCL Document
auto doc = MakeObject<Document>(L"input.pcl", L"owner");
// change password of PCL Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Adicionar imagens da Web no arquivo XAML via C++" %}}
Depois de converter PCL para XAML, você também pode adicionar imagens da web ao seu documento de saída. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) suporta operações com imagens nestes formatos populares: JPEG, PNG, BMP, GIF e outros. Você pode adicionar uma ou várias imagens em seu computador em um slide em uma apresentação. Este código de exemplo em C++ mostra como adicionar uma imagem a um arquivo XAML
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a XAML file
auto pres = System::MakeObject<Presentation>("output.xaml");
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
pres->Save(u"updated.xaml", SaveFormat::Xaml);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-ppt/" name="PCL Para PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-pps/" name="PCL Para PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-potx/" name="PCL Para POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-swf/" name="PCL Para SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-ppsm/" name="PCL Para PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-xaml/" name="PCL Para XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-ppsx/" name="PCL Para PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-pptm/" name="PCL Para PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-potm/" name="PCL Para POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-powerpoint/" name="PCL Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-pot/" name="PCL Para POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-otp/" name="PCL Para OTP" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}