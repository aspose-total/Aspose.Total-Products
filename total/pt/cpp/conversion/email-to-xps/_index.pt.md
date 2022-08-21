---
title: Exportar EMAIL para XPS via C++
description: API C++ para converter EMAIL para XPS sem usar o Microsoft Word ou Outlook
url: /pt/cpp/conversion/email-to-xps/
family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: XPS
otherformats: TIFF TEXT PS ODT OTT WORDML SVG RTF JPEG MD DOCX DOCM EPUB PNG DOTM PCL DOT EMF FLATOPC DOC GIF DOTX BMP PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para exportar EMAIL para XPS" h2="Transforme EMAIL em XPS dentro do aplicativo C++ sem exigir Microsoft Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você é um desenvolvedor C++ que deseja adicionar recursos de conversão de e-mail em seus aplicativos? Usando [Aspose.Email for C++](https://products.aspose.com/email/cpp/) você pode converter o formato de arquivo EMAIL para HTML. Depois disso, usando a API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), você pode exportar HTML para XPS. Ambas as APIs estão no pacote [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para converter EMAIL em XPS" %}}
1. Abra o arquivo EMAIL usando a referência de classe [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message)
2. Converta EMAIL para HTML usando a função de membro [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Carregue o HTML usando a classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Salve o documento no formato XPS usando o método [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) e defina Xps como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMAIL file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save EMAIL as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Xps as save format
doc->Save(u"convertedFile.Xps");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo EMAIL via C++" %}}
Não só você pode converter seu EMAIL para XPS, mas também ler, manipular e analisar o documento EMAIL. Você pode obter informações de assunto, endereço, corpo e destinatários do e-mail usando a classe MapiMessage da API [Aspose.Email for C++](https://products.aspose.com/email/cpp/). Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade get_SenderEmailAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.msg");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmailAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="API C++ para restringir a edição de formato de arquivo XPS" %}}
Você também pode adicionar recursos de proteção de documentos em seu aplicativo enquanto exporta o documento de EMAIL para XPS. Adicionar proteção ao seu documento é um processo simples, pois tudo o que você precisa fazer é aplicar o método de proteção ao seu documento. Você pode definir o tipo de proteção como ReadOnly para restringir o usuário a editar o documento.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Xps");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Outras conversões compatíveis" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-tiff/" name="MSG Para TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-text/" name="MSG Para TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-ps/" name="MSG Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-odt/" name="MSG Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-ott/" name="MSG Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-wordml/" name="MSG Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-svg/" name="MSG Para SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-rtf/" name="MSG Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-jpeg/" name="MSG Para JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-md/" name="MSG Para MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-docx/" name="MSG Para DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-docm/" name="MSG Para DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-epub/" name="MSG Para EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-png/" name="MSG Para PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-dotm/" name="MSG Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-pcl/" name="MSG Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-dot/" name="MSG Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-emf/" name="MSG Para EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-flatopc/" name="MSG Para FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-doc/" name="MSG Para DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-gif/" name="MSG Para GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-dotx/" name="MSG Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-xps/" name="MSG Para XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/msg-to-pdf/" name="MSG Para PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}