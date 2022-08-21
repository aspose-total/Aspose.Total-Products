---
title: API C++ para exportar PDF para GIF
description: Converta PDF para GIF em aplicativos C++.
url: /pt/cpp/conversion/pdf-to-gif/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: GIF
otherformats: DOT PCL XAMLFLOW MHTML WORDML ODT RTF MARKDOWN DOTM DOTX OTT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para exportar PDF para GIF" h2="Renderize PDF para GIF em aplicativos C++ sem exigir nenhum aplicativo de terceiros" >}}

{{% blocks/products/pf/feature-page-summary %}}
As bibliotecas de automação de formato de arquivo [Aspose.Total for C++](https://products.aspose.com/total/cpp/) permitem que o desenvolvedor C++ converta PDF para GIF em duas etapas simples. Em primeiro lugar, você pode usar a API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) para converter o formato de arquivo PDF para DOC. Em segundo lugar, usando a API avançada de processamento de documentos do Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), você pode exportar DOC para GIF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para renderizar PDF para GIF" %}}
1. Abra o arquivo PDF usando a referência de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Converta PDF para DOC usando a função de membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Carregue o arquivo DOC usando a referência de classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) da API Aspose.Words
4. Salve o documento no formato GIF usando a função de membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PDF file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.pdf");
// save PDF as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Gif
wordDoc->Save(u"output.Gif");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Alterar senha do documento PDF via C++" %}}
No processo de renderização de PDF para GIF, você pode abrir um PDF protegido por senha e também alterar sua senha. Para alterar a senha de um arquivo PDF, você deve saber a senha do proprietário desse documento. Você pode carregar um documento PDF protegido por senha com [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) especificando sua senha de proprietário e usando o método ChangePasswords para alterar a senha.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PDF Document
auto doc = MakeObject<Document>(L"input.pdf", L"owner");
// change password of PDF Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de arquivos GIF via C++" %}}
Você também pode restringir a edição de arquivos GIF usando a API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. A API permite que você controle a maneira como restringe o conteúdo usando o parâmetro de enumeração [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). O exemplo de código a seguir demonstra como restringir a edição em um documento para que seja possível editar apenas em campos de formulário.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Gif");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-dot/" name="PDF Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-pcl/" name="PDF Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-xamlflow/" name="PDF Para XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-mhtml/" name="PDF Para MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-wordml/" name="PDF Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-odt/" name="PDF Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-rtf/" name="PDF Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-markdown/" name="PDF Para MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-dotm/" name="PDF Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-dotx/" name="PDF Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-ott/" name="PDF Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-gif/" name="PDF Para GIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}