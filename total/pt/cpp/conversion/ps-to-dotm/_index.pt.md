---
title: API C++ para exportar PS para DOTM
description: Converta PS para DOTM em aplicativos C++.

family: total
platformtag: cpp
feature: conversion
informat: PS
outformat: DOTM
otherformats: RTF OTT WORDML FLATOPC XAMLFLOW DOTX MHTML MARKDOWN PCL DOT DOCM ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para exportar PS para DOTM" h2="Renderize PS para DOTM em aplicativos C++ sem exigir nenhum aplicativo de terceiros" >}}

{{% blocks/products/pf/feature-page-summary %}}
As bibliotecas de automação de formato de arquivo [Aspose.Total for C++](https://products.aspose.com/total/cpp/) permitem que o desenvolvedor C++ converta PS para DOTM em duas etapas simples. Em primeiro lugar, você pode usar a API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) para converter o formato de arquivo PS para DOC. Em segundo lugar, usando a API avançada de processamento de documentos do Word [Aspose.Words for C++](https://products.aspose.com/words/cpp/), você pode exportar DOC para DOTM. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para renderizar PS para DOTM" %}}
1. Abra o arquivo PS usando a referência de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Converta PS para DOC usando a função de membro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01)
3. Carregue o arquivo DOC usando a referência de classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) da API Aspose.Words
4. Salve o documento no formato DOTM usando a função de membro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load PS file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.ps");
// save PS as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Dotm
wordDoc->Save(u"output.Dotm");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Alterar senha do documento PS via C++" %}}
No processo de renderização de PS para DOTM, você pode abrir um PS protegido por senha e também alterar sua senha. Para alterar a senha de um arquivo PS, você deve saber a senha do proprietário desse documento. Você pode carregar um documento PDF protegido por senha com [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) especificando sua senha de proprietário e usando o método ChangePasswords para alterar a senha.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing PS Document
auto doc = MakeObject<Document>(L"input.ps", L"owner");
// change password of PS Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de arquivos DOTM via C++" %}}
Você também pode restringir a edição de arquivos DOTM usando a API [Aspose.Words for C++](https://products.aspose.com/words/cpp/). Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. A API permite que você controle a maneira como restringe o conteúdo usando o parâmetro de enumeração [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype). O exemplo de código a seguir demonstra como restringir a edição em um documento para que seja possível editar apenas em campos de formulário.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Dotm");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}