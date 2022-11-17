---
title: Exportieren Sie E-MAIL über C++ nach PDF
description: C++-API zum Konvertieren von E-MAIL in PDF, ohne Microsoft Word oder Outlook zu verwenden

family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: PDF
otherformats: PCL BMP EMF MD GIF OTT DOTX PNG PS EPUB DOT DOCM FLATOPC DOCX SVG DOTM TEXT RTF ODT WORDML XPS JPEG TIFF DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++-API zum Exportieren von E-MAIL nach PDF" h2="Wandeln Sie E-MAIL in PDF innerhalb einer C++-Anwendung um, ohne Microsoft Word oder Outlook zu benötigen" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sind Sie ein C++-Entwickler, der E-Mail-Konvertierungsfunktionen in Ihre Anwendungen integrieren möchte? Mit [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/) können Sie das OFT-Dateiformat in HTML konvertieren. Danach können Sie mithilfe der [Aspose.Words for C++](https://products.aspose.com/words/cpp/)-API HTML in PDF exportieren. Beide APIs befinden sich im Paket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Konvertieren von E-MAIL in PDF" %}}
1. Öffnen Sie die OFT-Datei mit der Klassenreferenz [MailMessage](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message).
2. Konvertieren Sie E-MAIL in HTML, indem Sie die Member-Funktion [Save](https://reference.aspose.com/oft/cpp/class/aspose.oft.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) verwenden
3. Laden Sie HTML mithilfe der Klasse [Dokument](https://reference.aspose.com/words/cpp/class/aspose.words.document).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) im PDF-Format und legen Sie Pdf als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the OFT file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.oft");
// save OFT as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Pdf as save format
doc->Save(u"convertedFile.Pdf");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysieren Sie die E-MAIL-Datei über C++" %}}
Sie können nicht nur Ihre E-MAIL in PDF konvertieren, sondern auch E-MAIL-Dokumente lesen, manipulieren und parsen. Sie können Betreff, Adresse, Text und Empfängerinformationen der E-Mail abrufen, indem Sie die MapiMessage-Klasse der [Aspose.Oft for C++](https://products.aspose.com/oft/cpp/)-API verwenden. Beispielsweise können Sie mithilfe der Eigenschaft get_SenderOftAddress() nach einer bestimmten Absender-E-Mail für die Konvertierung suchen.
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

{{% blocks/products/pf/feature-page-section  h2="C++-API zum Einschränken der Bearbeitung des PDF-Dateiformats" %}}
Sie können Ihrer App auch Dokumentschutzfunktionen hinzufügen, während Sie das Dokument von E-MAIL nach PDF exportieren. Das Hinzufügen von Schutz zu Ihrem Dokument ist ein einfacher Vorgang, da Sie lediglich die Schutzmethode auf Ihr Dokument anwenden müssen. Sie können den Schutztyp auf ReadOnly setzen, um den Benutzer auf die Bearbeitung des Dokuments einzuschränken.
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
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-pcl/" name="OFT Zu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-pdf/" name="OFT Zu PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-emf/" name="OFT Zu EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-md/" name="OFT Zu MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-gif/" name="OFT Zu GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-ott/" name="OFT Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-dotx/" name="OFT Zu DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-png/" name="OFT Zu PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-ps/" name="OFT Zu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-epub/" name="OFT Zu EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-dot/" name="OFT Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-docm/" name="OFT Zu DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-flatopc/" name="OFT Zu FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-docx/" name="OFT Zu DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-svg/" name="OFT Zu SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-dotm/" name="OFT Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-text/" name="OFT Zu TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-rtf/" name="OFT Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-odt/" name="OFT Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-wordml/" name="OFT Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-xps/" name="OFT Zu XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-jpeg/" name="OFT Zu JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-tiff/" name="OFT Zu TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/oft-to-doc/" name="OFT Zu DOC" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}