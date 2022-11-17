---
title: Exportar EMLX a DOCM a través de C++
description: API de C++ para convertir EMLX a DOCM sin usar Microsoft Word o Outlook

family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: DOCM
otherformats: WORDML GIF DOCX MD TEXT RTF BMP DOTM SVG FLATOPC EMF ODT OTT JPEG XPS PNG TIFF DOTX PS EPUB PCL DOC PDF DOT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para exportar EMLX a DOCM" h2="Transforme EMLX a DOCM dentro de la aplicación C++ sin necesidad de Microsoft Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
¿Es usted un desarrollador de C++ que busca agregar funciones de conversión de correo electrónico dentro de sus aplicaciones? Usando [Aspose.Emlx para C++](https://products.aspose.com/emlx/cpp/) puede convertir el formato de archivo de EMLX a HTML. Después de eso, al usar la API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puede exportar HTML a DOCM. Ambas API se incluyen en el paquete [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir EMLX a DOCM" %}}
1. Abra el archivo EMLX usando la referencia de clase [MailMessage](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message)
2. Convierta EMLX a HTML usando la función miembro [Guardar](https://reference.aspose.com/emlx/cpp/class/aspose.emlx.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Guarde el documento en formato DOCM usando el método [Guardar](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) y configure Docm como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EMLX file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.emlx");
// save EMLX as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Docm as save format
doc->Save(u"convertedFile.Docm");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizar archivo EMLX a través de C++" %}}
No solo puede convertir su EMLX a DOCM, sino que también puede leer, manipular y analizar documentos de EMLX. Puede obtener información sobre el asunto, la dirección, el cuerpo y los destinatarios del correo electrónico utilizando la clase MapiMessage de [Aspose.Emlx for C++](https://products.aspose.com/emlx/cpp/) API. Por ejemplo, puede buscar un correo electrónico de remitente específico para la conversión utilizando la propiedad get_SenderEmlxAddress().
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.emlx");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderEmlxAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="API de C++ para restringir la edición del formato de archivo DOCM" %}}
También puede agregar funciones de protección de documentos en su aplicación mientras exporta el documento de EMLX a DOCM. Agregar protección a su documento es un proceso simple, ya que todo lo que necesita hacer es aplicar el método de protección a su documento. Puede establecer el tipo de protección en Solo lectura para restringir que el usuario edite el documento.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Docm");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-wordml/" name="EMLX A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-gif/" name="EMLX A GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-docx/" name="EMLX A DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-md/" name="EMLX A MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-text/" name="EMLX A TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-rtf/" name="EMLX A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-docm/" name="EMLX A DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-dotm/" name="EMLX A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-svg/" name="EMLX A SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-flatopc/" name="EMLX A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-emf/" name="EMLX A EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-odt/" name="EMLX A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-ott/" name="EMLX A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-jpeg/" name="EMLX A JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-xps/" name="EMLX A XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-png/" name="EMLX A PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-tiff/" name="EMLX A TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-dotx/" name="EMLX A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-ps/" name="EMLX A PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-epub/" name="EMLX A EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-pcl/" name="EMLX A PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-doc/" name="EMLX A DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-pdf/" name="EMLX A PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/emlx-to-dot/" name="EMLX A DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}