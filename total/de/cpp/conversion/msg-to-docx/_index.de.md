---
title: Exportieren Sie E-MAIL über C++ nach DOCX
description: C++-API zum Konvertieren von E-MAIL in DOCX, ohne Microsoft Word oder Outlook zu verwenden

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: DOCX
otherformats: SVG RTF PNG BMP DOT DOCM DOTM WORDML TIFF PS TEXT EPUB EMF PCL OTT ODT GIF PDF FLATOPC MD JPEG DOC XPS DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++-API zum Exportieren von E-MAIL nach DOCX" h2="Wandeln Sie E-MAIL in DOCX innerhalb einer C++-Anwendung um, ohne Microsoft Word oder Outlook zu benötigen" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sind Sie ein C++-Entwickler, der E-Mail-Konvertierungsfunktionen in Ihre Anwendungen integrieren möchte? Mit [Aspose.Msg for C++](https://products.aspose.com/msg/cpp/) können Sie das MSG-Dateiformat in HTML konvertieren. Danach können Sie mithilfe der [Aspose.Words for C++](https://products.aspose.com/words/cpp/)-API HTML in DOCX exportieren. Beide APIs befinden sich im Paket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Konvertieren von E-MAIL in DOCX" %}}
1. Öffnen Sie die MSG-Datei mit der Klassenreferenz [MailMessage](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message).
2. Konvertieren Sie E-MAIL in HTML, indem Sie die Member-Funktion [Save](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) verwenden
3. Laden Sie HTML mithilfe der Klasse [Dokument](https://reference.aspose.com/words/cpp/class/aspose.words.document).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) im DOCX-Format und legen Sie Docx als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the MSG file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save MSG as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing Docx as save format
doc->Save(u"convertedFile.Docx");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysieren Sie die E-MAIL-Datei über C++" %}}
Sie können nicht nur Ihre E-MAIL in DOCX konvertieren, sondern auch E-MAIL-Dokumente lesen, manipulieren und parsen. Sie können Betreff, Adresse, Text und Empfängerinformationen der E-Mail abrufen, indem Sie die MapiMessage-Klasse der [Aspose.Msg for C++](https://products.aspose.com/msg/cpp/)-API verwenden. Beispielsweise können Sie mithilfe der Eigenschaft get_SenderMsgAddress() nach einer bestimmten Absender-E-Mail für die Konvertierung suchen.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create an instance of MapiMessage from file
System::SharedPtr<MapiMessage> msg = MapiMessage::FromFile(dataDir + L"message.msg");
// get subject
System::Console::WriteLine(System::String(L"Subject:") + msg->get_Subject());
// get from address
System::Console::WriteLine(System::String(L"From:") + msg->get_SenderMsgAddress());
// get body
System::Console::WriteLine(System::String(L"Body") + msg->get_Body());
// get recipients information
System::Console::WriteLine(System::String(L"Recipient: ") + msg->get_Recipients());
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="C++-API zum Einschränken der Bearbeitung des DOCX-Dateiformats" %}}
Sie können Ihrer App auch Dokumentschutzfunktionen hinzufügen, während Sie das Dokument von E-MAIL nach DOCX exportieren. Das Hinzufügen von Schutz zu Ihrem Dokument ist ein einfacher Vorgang, da Sie lediglich die Schutzmethode auf Ihr Dokument anwenden müssen. Sie können den Schutztyp auf ReadOnly setzen, um den Benutzer auf die Bearbeitung des Dokuments einzuschränken.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// create a new document and protect it with a password.
auto doc = System::MakeObject<Document>();
// apply Document Protection.
doc->Protect(ProtectionType::ReadOnly, u"password");
// save the document.
doc->Save(u"DocumentProtection.PasswordProtection.Docx");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-svg/" name="MSG Zu SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-rtf/" name="MSG Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-png/" name="MSG Zu PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-docx/" name="MSG Zu DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-dot/" name="MSG Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-docm/" name="MSG Zu DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-dotm/" name="MSG Zu DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-wordml/" name="MSG Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-tiff/" name="MSG Zu TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-ps/" name="MSG Zu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-text/" name="MSG Zu TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-epub/" name="MSG Zu EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-emf/" name="MSG Zu EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-pcl/" name="MSG Zu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-ott/" name="MSG Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-odt/" name="MSG Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-gif/" name="MSG Zu GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-pdf/" name="MSG Zu PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-flatopc/" name="MSG Zu FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-md/" name="MSG Zu MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-jpeg/" name="MSG Zu JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-doc/" name="MSG Zu DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-xps/" name="MSG Zu XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/msg-to-dotx/" name="MSG Zu DOTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}