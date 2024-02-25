---
title: Exportar EMAIL a PDF a través de C++
description: API de C++ para convertir EMAIL a PDF sin usar Microsoft Word o Outlook

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: PDF
otherformats: DOCX TIFF DOTM PNG MD SVG GIF DOTX OTT PCL PS FLATOPC EMF EPUB TEXT DOT DOC RTF DOCM ODT XPS JPEG WORDML BMP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para exportar EMAIL a PDF" h2="Transforme EMAIL a PDF dentro de la aplicación C++ sin necesidad de Microsoft Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
¿Es usted un desarrollador de C++ que busca agregar funciones de conversión de correo electrónico dentro de sus aplicaciones? Usando [Aspose.Email for C++](https://products.aspose.com/email/cpp/) puede convertir el formato de archivo de EMAIL a HTML. Después de eso, al usar la API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puede exportar HTML a PDF. Ambas API se incluyen en el paquete [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir EMAIL a PDF" %}}
1. Abra el archivo EMAIL usando la referencia de clase [MailMessage](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message)
2. Convierta EMAIL a HTML usando la función miembro [Save](https://reference.aspose.com/email/cpp/class/aspose.email.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Guarde el documento en formato PDF usando el método [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) y configure Pdf como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMAIL file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save EMAIL as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Pdf as save format
doc->Save(u"convertedFile.Pdf");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizar archivo EMAIL a través de C++" %}}
No solo puede convertir su EMAIL a PDF, sino que también puede leer, manipular y analizar documentos de EMAIL. Puede obtener información sobre el asunto, la dirección, el cuerpo y los destinatarios del correo electrónico utilizando la clase MapiMessage de [Aspose.Email for C++](https://products.aspose.com/email/cpp/) API. Por ejemplo, puede buscar un correo electrónico de remitente específico para la conversión utilizando la propiedad get_SenderEmailAddress().
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

{{% blocks/products/pf/feature-page-section  h2="API de C++ para restringir la edición del formato de archivo PDF" %}}
También puede agregar funciones de protección de documentos en su aplicación mientras exporta el documento de EMAIL a PDF. Agregar protección a su documento es un proceso simple, ya que todo lo que necesita hacer es aplicar el método de protección a su documento. Puede establecer el tipo de protección en Solo lectura para restringir que el usuario edite el documento.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Pdf");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}