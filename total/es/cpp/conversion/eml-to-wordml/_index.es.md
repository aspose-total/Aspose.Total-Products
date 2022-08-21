---
title: Exportar EML a WORDML a través de C++
description: API de C++ para convertir EML a WORDML sin usar Microsoft Word o Outlook
url: /es/cpp/conversion/eml-to-wordml/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: WORDML
otherformats: PS ODT TEXT OTT DOCX DOT DOC FLATOPC RTF EPUB PCL DOCM GIF XPS DOTX PNG TIFF PDF MD DOTM EMF SVG BMP JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="API de C++ para exportar EML a WORDML" h2="Transforme EML a WORDML dentro de la aplicación C++ sin necesidad de Microsoft Word o Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
¿Es usted un desarrollador de C++ que busca agregar funciones de conversión de correo electrónico dentro de sus aplicaciones? Usando [Aspose.Eml para C++](https://products.aspose.com/eml/cpp/) puede convertir el formato de archivo de EML a HTML. Después de eso, al usar la API [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puede exportar HTML a WORDML. Ambas API se incluyen en el paquete [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir EML a WORDML" %}}
1. Abra el archivo EML usando la referencia de clase [MailMessage](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message)
2. Convierta EML a HTML usando la función miembro [Guardar](https://reference.aspose.com/eml/cpp/class/aspose.eml.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786)
3. Cargue HTML usando la clase [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Guarde el documento en formato WORDML usando el método [Guardar](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) y configure Wordml como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the EML file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.eml");
// save EML as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing WordML as save format
doc->Save(u"convertedFile.WordML");
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analizar archivo EML a través de C++" %}}
No solo puede convertir su EML a WORDML, sino que también puede leer, manipular y analizar documentos de EML. Puede obtener información sobre el asunto, la dirección, el cuerpo y los destinatarios del correo electrónico utilizando la clase MapiMessage de [Aspose.Eml for C++](https://products.aspose.com/eml/cpp/) API. Por ejemplo, puede buscar un correo electrónico de remitente específico para la conversión utilizando la propiedad get_SenderEmlAddress().
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

{{% blocks/products/pf/feature-page-section  h2="API de C++ para restringir la edición del formato de archivo WORDML" %}}
También puede agregar funciones de protección de documentos en su aplicación mientras exporta el documento de EML a WORDML. Agregar protección a su documento es un proceso simple, ya que todo lo que necesita hacer es aplicar el método de protección a su documento. Puede establecer el tipo de protección en Solo lectura para restringir que el usuario edite el documento.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.WordML");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-ps/" name="EML A PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-odt/" name="EML A ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-text/" name="EML A TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-ott/" name="EML A OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-docx/" name="EML A DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-dot/" name="EML A DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-doc/" name="EML A DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-flatopc/" name="EML A FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-rtf/" name="EML A RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-epub/" name="EML A EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-pcl/" name="EML A PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-docm/" name="EML A DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-gif/" name="EML A GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-xps/" name="EML A XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-dotx/" name="EML A DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-png/" name="EML A PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-tiff/" name="EML A TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-pdf/" name="EML A PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-md/" name="EML A MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-dotm/" name="EML A DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-emf/" name="EML A EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-svg/" name="EML A SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-wordml/" name="EML A WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/eml-to-jpeg/" name="EML A JPEG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}