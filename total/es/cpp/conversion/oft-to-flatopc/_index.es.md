---
title: Exportar OFT a FLATOPC a través de C++
description: API de C++ para convertir OFT a FLATOPC sin usar Microsoft Word o Outlook
url: /es/cpp/conversion/oft-to-flatopc/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: FLATOPC
otherformats: DOCX DOCM PNG BMP DOTM PS EPUB TIFF ODT EMF DOC JPEG OTT RTF SVG MD PCL XPS PDF DOT TEXT GIF WORDML DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para exportar OFT a FLATOPC" h2="Transforme OFT a FLATOPC dentro de la aplicación C++ sin necesidad de Microsoft Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
¿Es usted un desarrollador de C++ que busca agregar funciones de conversión de correo electrónico dentro de sus aplicaciones? Usando [Aspose.Oft para C++](https://products.aspose.com/oft/cpp/) puede convertir el formato de archivo de OFT a HTML. Después de eso, al usar la API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puede exportar HTML a FLATOPC. Ambas API se incluyen en el paquete [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir OFT a FLATOPC" %}}
1. Abra el archivo OFT usando la referencia de clase [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message)
2. Convierta OFT a HTML usando la función miembro [Guardar](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Guarde el documento en formato FLATOPC usando el método [Guardar](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) y configure Flatopc como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing FlatOpc as save format
doc->Save(u"convertedFile.FlatOpc");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizar archivo OFT a través de C++" %}}
No solo puede convertir su OFT a FLATOPC, sino que también puede leer, manipular y analizar documentos de OFT. Puede obtener información sobre el asunto, la dirección, el cuerpo y los destinatarios del correo electrónico utilizando la clase MapiMessage de [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) API. Por ejemplo, puede buscar un correo electrónico de remitente específico para la conversión utilizando la propiedad get_SenderOftAddress().
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

{{% blocks/products/pf/feature-page-section  h2="API de C++ para restringir la edición del formato de archivo FLATOPC" %}}
También puede agregar funciones de protección de documentos en su aplicación mientras exporta el documento de OFT a FLATOPC. Agregar protección a su documento es un proceso simple, ya que todo lo que necesita hacer es aplicar el método de protección a su documento. Puede establecer el tipo de protección en Solo lectura para restringir que el usuario edite el documento.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.FlatOpc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-docx/" name="OFT A DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-docm/" name="OFT A DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-png/" name="OFT A PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-flatopc/" name="OFT A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-dotm/" name="OFT A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-ps/" name="OFT A PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-epub/" name="OFT A EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-tiff/" name="OFT A TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-odt/" name="OFT A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-emf/" name="OFT A EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-doc/" name="OFT A DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-jpeg/" name="OFT A JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-ott/" name="OFT A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-rtf/" name="OFT A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-svg/" name="OFT A SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-md/" name="OFT A MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-pcl/" name="OFT A PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-xps/" name="OFT A XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-pdf/" name="OFT A PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-dot/" name="OFT A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-text/" name="OFT A TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-gif/" name="OFT A GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-wordml/" name="OFT A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/oft-to-dotx/" name="OFT A DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}