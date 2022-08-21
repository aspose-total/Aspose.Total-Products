---
title: Exportar EML para PNG via C++
description: API C++ para converter EML para PNG sem usar o Microsoft Word ou Outlook
url: /pt/cpp/conversion/eml-to-png/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: PNG
otherformats: DOTM XPS PS FLATOPC PCL SVG DOT TIFF BMP PDF EPUB OTT DOCM MD GIF EMF RTF DOC WORDML TEXT DOTX DOCX JPEG ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para exportar EML para PNG" h2="Transforme EML em PNG dentro do aplicativo C++ sem exigir Microsoft Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você é um desenvolvedor C++ que deseja adicionar recursos de conversão de e-mail em seus aplicativos? Usando [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) você pode converter o formato de arquivo EML para HTML. Depois disso, usando a API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), você pode exportar HTML para PNG. Ambas as APIs estão no pacote [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para converter EML em PNG" %}}
1. Abra o arquivo EML usando a referência de classe [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message)
2. Converta EML para HTML usando a função de membro [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Carregue o HTML usando a classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Salve o documento no formato PNG usando o método [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) e defina Png como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Png as save format
doc->Save(u"convertedFile.Png");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo EML via C++" %}}
Não só você pode converter seu EML para PNG, mas também ler, manipular e analisar o documento EML. Você pode obter informações de assunto, endereço, corpo e destinatários do e-mail usando a classe MapiMessage da API [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/). Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade get_SenderEmlAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.eml");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="API C++ para restringir a edição de formato de arquivo PNG" %}}
Você também pode adicionar recursos de proteção de documentos em seu aplicativo enquanto exporta o documento de EML para PNG. Adicionar proteção ao seu documento é um processo simples, pois tudo o que você precisa fazer é aplicar o método de proteção ao seu documento. Você pode definir o tipo de proteção como ReadOnly para restringir o usuário a editar o documento.
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-dotm/" name="EML Para DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-xps/" name="EML Para XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-ps/" name="EML Para PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-flatopc/" name="EML Para FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-pcl/" name="EML Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-svg/" name="EML Para SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-dot/" name="EML Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-tiff/" name="EML Para TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-png/" name="EML Para PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-pdf/" name="EML Para PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-epub/" name="EML Para EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-ott/" name="EML Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-docm/" name="EML Para DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-md/" name="EML Para MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-gif/" name="EML Para GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-emf/" name="EML Para EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-rtf/" name="EML Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-doc/" name="EML Para DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-wordml/" name="EML Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-text/" name="EML Para TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-dotx/" name="EML Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-docx/" name="EML Para DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-jpeg/" name="EML Para JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pt/cpp/conversion/eml-to-odt/" name="EML Para ODT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}