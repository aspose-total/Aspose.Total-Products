---
title: Converter DOC para PPSM via C++
description: Exporte DOC para PPSM em seus aplicativos C++ sem usar o Microsoft Word do PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: DOC
outformat: PPSM
otherformats: POWERPOINT POTX ODP POTM POT PPS PPTM PPSX PPTX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para converter DOC em PPSM" h2="Exporte DOC para PPSM em seus aplicativos C++ sem usar o Microsoft Word&reg; ou PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) consiste em poderosas APIs de automação de arquivos que permitem automatizar a conversão de DOC para PPSM usando duas de suas APIs. Carregue seu DOC usando [Aspose.Words for C++](https://products.aspose.com/words/cpp/) e converta-o em HTML, depois carregue o HTML via API C++ de manipulação do PowerPoint [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para criar uma nova apresentação e salvá-la como PPSM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversão de DOC para PPSM em C++" %}}
1. Abra o arquivo DOC usando a referência de classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
2. Converta DOC para HTML usando a função de membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stdbasicostream_saveoptions)
3. Inicialize um novo objeto [Apresentação](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Adicione uma AutoForma em seu slide e adicione AddTextFrame nele
5. Carregue o conteúdo HTML e escreva-o em seu arquivo de apresentação
6. Salve o documento no formato PPSM usando o método [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) e defina Ppsm como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOC file with an instance of Document
Document document = new Document("template.doc");
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"sourceFile.doc");
// save the document in HTML file format
doc->Save(u"HtmlOutput.HTML");
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
// save presentation as Ppsm
pres->Save(output.ppsm, Aspose::Slides::Export::SaveFormat::Ppsm);                  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Carregar documento DOC protegido por senha via C++" %}}
Além da conversão de documentos, a API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) permite vários recursos de manipulação de documentos para desenvolvedores de C++. Caso seu formato de arquivo DOC do Microsoft Word seja protegido por senha, você ainda pode abri-lo usando a API. Para carregar o documento criptografado, você pode usar uma sobrecarga de construtor especial, que aceita um objeto [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Este objeto contém a propriedade Password, que especifica a string de senha.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected document, the password is passed to the document's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docPassword");
// load the document from the local file system by filename:
SharedPtr<Document> doc = MakeObject<Document>(u"Encrypted.doc", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Adicionar comentários no documento PPSM via C++" %}}
Ao salvar o DOC como PPSM, você também pode usar o [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) para adicionar mais recursos ao seu documento PPSM. Por exemplo, você pode adicionar comentários em sua apresentação. O comentário do slide da apresentação está associado a um autor específico. A classe Presentation contém a coleção de autores em ICommentAuthorCollection que são responsáveis por adicionar comentários ao slide. Para cada autor, há uma coleção de comentários em ICommentCollection.
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
// save presentation as Ppsm
pres->Save(output.ppsm, Aspose::Slides::Export::SaveFormat::Ppsm);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/doc-to-powerpoint/" name="DOC Para POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/doc-to-potx/" name="DOC Para POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/doc-to-ppsm/" name="DOC Para PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/doc-to-potm/" name="DOC Para POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/doc-to-pot/" name="DOC Para POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/doc-to-pps/" name="DOC Para PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/doc-to-pptm/" name="DOC Para PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/doc-to-ppsx/" name="DOC Para PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/doc-to-pptx/" name="DOC Para PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/doc-to-ppt/" name="DOC Para PPT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}