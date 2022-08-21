---
title: API C++ para exportar PCL para FLATOPC
description: Converta PCL para FLATOPC em aplicativos C++.
url: /pt/cpp/conversion/pcl-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: PCL
outformat: FLATOPC
otherformats: DOTM ODT XAMLFLOW DOCM DOTX MARKDOWN MHTML WORDML OTT DOT PS RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para exportar PCL para FLATOPC" h2="Renderize PCL para FLATOPC em aplicativos C++ sem exigir nenhum aplicativo de terceiros" >}}

{{% blocks/products/pf/feature-page-summary %}}
As bibliotecas de automação de formato de arquivo [Aspose.Total for C++](https://products.aspose.com/total/cpp/) permitem que o desenvolvedor C++ converta PCL para FLATOPC em duas etapas simples. Em primeiro lugar, você pode usar a API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) para converter o formato de arquivo PCL para DOC. Em segundo lugar, usando a API avançada de processamento de documentos do Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), você pode exportar DOC para FLATOPC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para renderizar PCL para FLATOPC" %}}
1. Abra o arquivo PCL usando a referência de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Converta PCL para DOC usando a função de membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Carregue o arquivo DOC usando a referência de classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) da API Aspose.Words
4. Salve o documento no formato FLATOPC usando a função de membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PCL file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.pcl");
// save PCL as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as FlatOpc
wordDoc->Save(u"output.FlatOpc");  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Alterar senha do documento PCL via C++" %}}
No processo de renderização de PCL para FLATOPC, você pode abrir um PCL protegido por senha e também alterar sua senha. Para alterar a senha de um arquivo PCL, você deve saber a senha do proprietário desse documento. Você pode carregar um documento PDF protegido por senha com [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) especificando sua senha de proprietário e usando o método ChangePasswords para alterar a senha.
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

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de arquivos FLATOPC via C++" %}}
Você também pode restringir a edição de arquivos FLATOPC usando a API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. A API permite que você controle a maneira como restringe o conteúdo usando o parâmetro de enumeração [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). O exemplo de código a seguir demonstra como restringir a edição em um documento para que seja possível editar apenas em campos de formulário.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.FlatOpc");  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-dotm/" name="PCL Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-odt/" name="PCL Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-xamlflow/" name="PCL Para XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-flatopc/" name="PCL Para FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-dotx/" name="PCL Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-markdown/" name="PCL Para MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-mhtml/" name="PCL Para MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-wordml/" name="PCL Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-ott/" name="PCL Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-dot/" name="PCL Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-ps/" name="PCL Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/pcl-to-rtf/" name="PCL Para RTF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}