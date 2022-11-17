---
title: API C++ para exportar EPUB para GIF
description: Converta EPUB para GIF em aplicativos C++.

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: GIF
otherformats: DOT MARKDOWN OTT DOTX DOTM MHTML ODT PCL WORDML XAMLFLOW PS FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para exportar EPUB para GIF" h2="Renderize EPUB para GIF em aplicativos C++ sem exigir nenhum aplicativo de terceiros" >}}

{{% blocks/products/pf/feature-page-summary %}}
As bibliotecas de automação de formato de arquivo [Aspose.Total for C++](https://products.aspose.com/total/cpp/) permitem que o desenvolvedor C++ converta EPUB para GIF em duas etapas simples. Em primeiro lugar, você pode usar a API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) para converter o formato de arquivo EPUB para DOC. Em segundo lugar, usando a API avançada de processamento de documentos do Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), você pode exportar DOC para GIF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para renderizar EPUB para GIF" %}}
1. Abra o arquivo EPUB usando a referência de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Converta EPUB para DOC usando a função de membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Carregue o arquivo DOC usando a referência de classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) da API Aspose.Words
4. Salve o documento no formato GIF usando a função de membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load EPUB file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.epub");
// save EPUB as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Gif
wordDoc->Save(u"output.Gif");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Alterar senha do documento EPUB via C++" %}}
No processo de renderização de EPUB para GIF, você pode abrir um EPUB protegido por senha e também alterar sua senha. Para alterar a senha de um arquivo EPUB, você deve saber a senha do proprietário desse documento. Você pode carregar um documento PDF protegido por senha com [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) especificando sua senha de proprietário e usando o método ChangePasswords para alterar a senha.
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/epub-to-dot/" name="EPUB Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/epub-to-markdown/" name="EPUB Para MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/epub-to-ott/" name="EPUB Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/epub-to-dotx/" name="EPUB Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/epub-to-dotm/" name="EPUB Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/epub-to-mhtml/" name="EPUB Para MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/epub-to-odt/" name="EPUB Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/epub-to-pcl/" name="EPUB Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/epub-to-wordml/" name="EPUB Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/epub-to-xamlflow/" name="EPUB Para XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/epub-to-ps/" name="EPUB Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/epub-to-flatopc/" name="EPUB Para FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}