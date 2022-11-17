---
title: Exportar OFT para IMAGE via C++
description: API C++ para converter OFT para IMAGE sem usar o Microsoft Word ou Outlook

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: PNG
otherformats: BMP TEXT MD TIFF WORDML PCL EMF JPEG EPUB DOTX PNG DOT RTF OTT DOC GIF XPS SVG ODT DOCX DOTM FLATOPC DOCM PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para exportar OFT para IMAGE" h2="Transforme OFT em IMAGE dentro do aplicativo C++ sem exigir Microsoft Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você é um desenvolvedor C++ que deseja adicionar recursos de conversão de e-mail em seus aplicativos? Usando [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) você pode converter o formato de arquivo OFT para HTML. Depois disso, usando a API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), você pode exportar HTML para IMAGE. Ambas as APIs estão no pacote [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para converter OFT em IMAGE" %}}
1. Abra o arquivo OFT usando a referência de classe [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message)
2. Converta OFT para HTML usando a função de membro [Save](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Carregue o HTML usando a classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Salve o documento no formato IMAGE usando o método [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) e defina Image como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Png as save format
doc->Save(u"convertedFile.Png");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo OFT via C++" %}}
Não só você pode converter seu OFT para IMAGE, mas também ler, manipular e analisar o documento OFT. Você pode obter informações de assunto, endereço, corpo e destinatários do e-mail usando a classe MapiMessage da API [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/). Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade get_SenderOftAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.oft");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderOftAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="API C++ para restringir a edição de formato de arquivo IMAGE" %}}
Você também pode adicionar recursos de proteção de documentos em seu aplicativo enquanto exporta o documento de OFT para IMAGE. Adicionar proteção ao seu documento é um processo simples, pois tudo o que você precisa fazer é aplicar o método de proteção ao seu documento. Você pode definir o tipo de proteção como ReadOnly para restringir o usuário a editar o documento.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Png");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-image/" name="OFT Para IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-text/" name="OFT Para TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-md/" name="OFT Para MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-tiff/" name="OFT Para TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-wordml/" name="OFT Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-pcl/" name="OFT Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-emf/" name="OFT Para EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-jpeg/" name="OFT Para JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-epub/" name="OFT Para EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-dotx/" name="OFT Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-png/" name="OFT Para PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-dot/" name="OFT Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-rtf/" name="OFT Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-ott/" name="OFT Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-doc/" name="OFT Para DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-gif/" name="OFT Para GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-xps/" name="OFT Para XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-svg/" name="OFT Para SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-odt/" name="OFT Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-docx/" name="OFT Para DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-dotm/" name="OFT Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-flatopc/" name="OFT Para FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-docm/" name="OFT Para DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/oft-to-pdf/" name="OFT Para PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}