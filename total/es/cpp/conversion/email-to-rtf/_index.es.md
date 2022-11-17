---
title: Exportar EMAIL a RTF a través de C++
description: API de C++ para convertir EMAIL a RTF sin usar Microsoft Word o Outlook

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: RTF
otherformats: DOTX PS WORDML DOCX GIF EPUB DOT JPEG OTT ODT FLATOPC TIFF DOCM DOC BMP PNG DOTM PCL TEXT XPS SVG MD EMF PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para exportar EMAIL a RTF" h2="Transforme EMAIL a RTF dentro de la aplicación C++ sin necesidad de Microsoft Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
¿Es usted un desarrollador de C++ que busca agregar funciones de conversión de correo electrónico dentro de sus aplicaciones? Usando [Aspose.Email for C++](https://products.aspose.com/email/cpp/) puede convertir el formato de archivo de EMAIL a HTML. Después de eso, al usar la API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puede exportar HTML a RTF. Ambas API se incluyen en el paquete [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir EMAIL a RTF" %}}
1. Abra el archivo EMAIL usando la referencia de clase [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message)
2. Convierta EMAIL a HTML usando la función miembro [Guardar](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Guarde el documento en formato RTF usando el método [Guardar](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) y configure Rtf como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMAIL file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save EMAIL as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Rtf as save format
doc->Save(u"convertedFile.Rtf");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizar archivo EMAIL a través de C++" %}}
No solo puede convertir su EMAIL a RTF, sino que también puede leer, manipular y analizar documentos de EMAIL. Puede obtener información sobre el asunto, la dirección, el cuerpo y los destinatarios del correo electrónico utilizando la clase MapiMessage de [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API. Por ejemplo, puede buscar un correo electrónico de remitente específico para la conversión utilizando la propiedad get_SenderEmailAddress().
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

{{% blocks/products/pf/feature-page-section  h2="API de C++ para restringir la edición del formato de archivo RTF" %}}
También puede agregar funciones de protección de documentos en su aplicación mientras exporta el documento de EMAIL a RTF. Agregar protección a su documento es un proceso simple, ya que todo lo que necesita hacer es aplicar el método de protección a su documento. Puede establecer el tipo de protección en Solo lectura para restringir que el usuario edite el documento.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Rtf");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-dotx/" name="MSG A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-ps/" name="MSG A PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-wordml/" name="MSG A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-docx/" name="MSG A DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-gif/" name="MSG A GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-epub/" name="MSG A EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-dot/" name="MSG A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-jpeg/" name="MSG A JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-ott/" name="MSG A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-odt/" name="MSG A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-flatopc/" name="MSG A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-tiff/" name="MSG A TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-docm/" name="MSG A DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-doc/" name="MSG A DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-rtf/" name="MSG A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-png/" name="MSG A PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-dotm/" name="MSG A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-pcl/" name="MSG A PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-text/" name="MSG A TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-xps/" name="MSG A XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-svg/" name="MSG A SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-md/" name="MSG A MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-emf/" name="MSG A EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/msg-to-pdf/" name="MSG A PDF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}