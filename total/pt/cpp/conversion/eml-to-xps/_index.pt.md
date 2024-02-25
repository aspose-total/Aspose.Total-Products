---
title: Exportar EML para XPS via C++
description: API C++ para converter EML para XPS sem usar o Microsoft Word ou Outlook

family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: XPS
otherformats: DOTM PNG TEXT PDF PCL EMF JPEG PS DOTX FLATOPC OTT EPUB DOT DOCM SVG ODT WORDML GIF RTF MD DOCX BMP TIFF DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API C++ para exportar EML para XPS" h2="Transforme EML em XPS dentro do aplicativo C++ sem exigir Microsoft Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Você é um desenvolvedor C++ que deseja adicionar recursos de conversão de e-mail em seus aplicativos? Usando [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) você pode converter o formato de arquivo EML para HTML. Depois disso, usando a API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), você pode exportar HTML para XPS. Ambas as APIs estão no pacote [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C++ para converter EML em XPS" %}}
1. Abra o arquivo EML usando a referência de classe [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message)
2. Converta EML para HTML usando a função de membro [Save](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Carregue o HTML usando a classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Salve o documento no formato XPS usando o método [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) e defina Xps como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total.Cpp``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Xps as save format
doc->Save(u"convertedFile.Xps");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo EML via C++" %}}
Não só você pode converter seu EML para XPS, mas também ler, manipular e analisar o documento EML. Você pode obter informações de assunto, endereço, corpo e destinatários do e-mail usando a classe MapiMessage da API [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/). Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade get_SenderEmlAddress().
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

{{% blocks/products/pf/feature-page-section  h2="API C++ para restringir a edição de formato de arquivo XPS" %}}
Você também pode adicionar recursos de proteção de documentos em seu aplicativo enquanto exporta o documento de EML para XPS. Adicionar proteção ao seu documento é um processo simples, pois tudo o que você precisa fazer é aplicar o método de proteção ao seu documento. Você pode definir o tipo de proteção como ReadOnly para restringir o usuário a editar o documento.
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
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}