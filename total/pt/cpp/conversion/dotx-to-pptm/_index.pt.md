---
title: Converter DOTX para PPTM via C++
description: Exporte DOTX para PPTM em seus aplicativos C++ sem usar o Microsoft Word do PowerPoint
url: /pt/cpp/conversion/dotx-to-pptm/
family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: PPTM
otherformats: PPSM POWERPOINT PPTX PPT ODP POT POTM POTX PPS PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para converter DOTX em PPTM" h2="Exporte DOTX para PPTM em seus aplicativos C++ sem usar o Microsoft Word&reg; ou PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) consiste em poderosas APIs de automação de arquivos que permitem automatizar a conversão de DOTX para PPTM usando duas de suas APIs. Carregue seu DOTX usando [Aspose.Words for C++](https://products.aspose.com/words/cpp/) e converta-o em HTML, depois carregue o HTML via API C++ de manipulação do PowerPoint [Aspose.Slides for C++]( https://products.aspose.com/slides/cpp/) para criar uma nova apresentação e salvá-la como PPTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversão de DOTX para PPTM em C++" %}}
1. Abra o arquivo DOTX usando a referência de classe [Dotxument](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument)
2. Converta DOTX para HTML usando a função de membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_stdbasicostream_saveoptions)
3. Inicialize um novo objeto [Apresentação](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Adicione uma AutoForma em seu slide e adicione AddTextFrame nele
5. Carregue o conteúdo HTML e escreva-o em seu arquivo de apresentação
6. Salve o dotxumento no formato PPTM usando o método [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e defina Pptm como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOTX file with an instance of Dotxument
Dotxument dotxument = new Dotxument("template.dotx");
System::SharedPtr<Dotxument> dotx = System::MakeObject<Dotxument>(u"sourceFile.dotx");
// save the dotxument in HTML file format
dotx->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);                  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Carregar dotxumento DOTX protegido por senha via C++" %}}
Além da conversão de dotxumentos, a API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) permite vários recursos de manipulação de dotxumentos para desenvolvedores de C++. Caso seu formato de arquivo DOTX do Microsoft Word seja protegido por senha, você ainda pode abri-lo usando a API. Para carregar o dotxumento criptografado, você pode usar uma sobrecarga de construtor especial, que aceita um objeto [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Este objeto contém a propriedade Password, que especifica a string de senha.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected dotxument, the password is passed to the dotxument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"dotxPassword");
// load the dotxument from the local file system by filename:
SharedPtr<Dotxument> dotx = MakeObject<Dotxument>(u"Encrypted.dotx", options);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Adicionar comentários no dotxumento PPTM via C++" %}}
Ao salvar o DOTX como PPTM, você também pode usar o [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para adicionar mais recursos ao seu dotxumento PPTM. Por exemplo, você pode adicionar comentários em sua apresentação. O comentário do slide da apresentação está associado a um autor específico. A classe Presentation contém a coleção de autores em ICommentAuthorCollection que são responsáveis por adicionar comentários ao slide. Para cada autor, há uma coleção de comentários em ICommentCollection.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Pptm
pres->Save(output.pptm, Aspose::Slides::Export::SaveFormat::Pptm);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/dotx-to-ppsm/" name="DOTX Para PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/dotx-to-powerpoint/" name="DOTX Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/dotx-to-pptx/" name="DOTX Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/dotx-to-ppt/" name="DOTX Para PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/dotx-to-pptm/" name="DOTX Para PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/dotx-to-pot/" name="DOTX Para POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/dotx-to-potm/" name="DOTX Para POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/dotx-to-potx/" name="DOTX Para POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/dotx-to-pps/" name="DOTX Para PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/dotx-to-ppsx/" name="DOTX Para PPSX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}