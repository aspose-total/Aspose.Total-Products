---
title: API C++ para exportar PDF para PS
description: Converta PDF para PS em aplicativos C++.
url: /pt/cpp/conversion/pdf-to-ps/
family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: PS
otherformats: MHTML DOCM MARKDOWN WORDML DOTM XAMLFLOW OTT DOT ODT PCL RTF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para exportar PDF para PS" h2="Renderize PDF para PS em aplicativos C++ sem exigir nenhum aplicativo de terceiros" >}}

{{% blocks/products/pf/feature-page-summary %}}
As bibliotecas de automação de formato de arquivo [Aspose.Total for C++](https://products.aspose.com/total/cpp/) permitem que o desenvolvedor C++ converta PDF para PS em duas etapas simples. Em primeiro lugar, você pode usar a API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) para converter o formato de arquivo PDF para DOC. Em segundo lugar, usando a API avançada de processamento de documentos do Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), você pode exportar DOC para PS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para renderizar PDF para PS" %}}
1. Abra o arquivo PDF usando a referência de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Converta PDF para DOC usando a função de membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Carregue o arquivo DOC usando a referência de classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) da API Aspose.Words
4. Salve o documento no formato PS usando a função de membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
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
// save document as Ps
wordDoc->Save(u"output.Ps");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Alterar senha do documento PDF via C++" %}}
No processo de renderização de PDF para PS, você pode abrir um PDF protegido por senha e também alterar sua senha. Para alterar a senha de um arquivo PDF, você deve saber a senha do proprietário desse documento. Você pode carregar um documento PDF protegido por senha com [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) especificando sua senha de proprietário e usando o método ChangePasswords para alterar a senha.
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

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de arquivos PS via C++" %}}
Você também pode restringir a edição de arquivos PS usando a API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. A API permite que você controle a maneira como restringe o conteúdo usando o parâmetro de enumeração [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). O exemplo de código a seguir demonstra como restringir a edição em um documento para que seja possível editar apenas em campos de formulário.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Ps");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-mhtml/" name="PDF Para MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-ps/" name="PDF Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-markdown/" name="PDF Para MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-wordml/" name="PDF Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-dotm/" name="PDF Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-xamlflow/" name="PDF Para XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-ott/" name="PDF Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-dot/" name="PDF Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-odt/" name="PDF Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-pcl/" name="PDF Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-rtf/" name="PDF Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pdf-to-flatopc/" name="PDF Para FLATOPC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}