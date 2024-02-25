---
title: Exportieren Sie E-MAIL über C++ nach FLATOPC
description: C++-API zum Konvertieren von E-MAIL in FLATOPC, ohne Microsoft Word oder Outlook zu verwenden

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: FLATOPC
otherformats: DOTX TIFF XPS JPEG OTT EMF TEXT DOC SVG GIF EPUB PDF ODT DOCX DOTM PNG PCL RTF BMP DOT PS MD DOCM WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++-API zum Exportieren von E-MAIL nach FLATOPC" h2="Wandeln Sie E-MAIL in FLATOPC innerhalb einer C++-Anwendung um, ohne Microsoft Word oder Outlook zu benötigen" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sind Sie ein C++-Entwickler, der E-Mail-Konvertierungsfunktionen in Ihre Anwendungen integrieren möchte? Mit [Aspose.Msg for C++](https://products.aspose.com/msg/cpp/) können Sie das MSG-Dateiformat in HTML konvertieren. Danach können Sie mithilfe der [Aspose.Words for C++](https://products.aspose.com/words/cpp/)-API HTML in FLATOPC exportieren. Beide APIs befinden sich im Paket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Konvertieren von E-MAIL in FLATOPC" %}}
1. Öffnen Sie die MSG-Datei mit der Klassenreferenz [MailMessage](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message).
2. Konvertieren Sie E-MAIL in HTML, indem Sie die Member-Funktion [Save](https://reference.aspose.com/msg/cpp/class/aspose.msg.mail_message#a7e7c6b50c8db5a8bcc6934db02b4a786) verwenden
3. Laden Sie HTML mithilfe der Klasse [Dokument](https://reference.aspose.com/words/cpp/class/aspose.words.document).
4. Speichern Sie das Dokument mit der Methode [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) im FLATOPC-Format und legen Sie Flatopc als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load the MSG file to be converted
System::SharedPtr<MailMessage> msg = MailMessage::Load(u"sourceFile.msg");
// save MSG as a HTML 
msg->Save(u"HtmlOutput.html", SaveOptions::get_DefaultHtml());  
// load HTML with an instance of Document
System::SharedPtr<Document> doc = System::MakeObject<Document>(u"HtmlOutput.html");
// call save method while passing FlatOpc as save format
doc->Save(u"convertedFile.FlatOpc");
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analysieren Sie die E-MAIL-Datei über C++" %}}
Sie können nicht nur Ihre E-MAIL in FLATOPC konvertieren, sondern auch E-MAIL-Dokumente lesen, manipulieren und parsen. Sie können Betreff, Adresse, Text und Empfängerinformationen der E-Mail abrufen, indem Sie die MapiMessage-Klasse der [Aspose.Msg for C++](https://products.aspose.com/msg/cpp/)-API verwenden. Beispielsweise können Sie mithilfe der Eigenschaft get_SenderMsgAddress() nach einer bestimmten Absender-E-Mail für die Konvertierung suchen.
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

{{% blocks/products/pf/feature-page-section  h2="C++-API zum Einschränken der Bearbeitung des FLATOPC-Dateiformats" %}}
Sie können Ihrer App auch Dokumentschutzfunktionen hinzufügen, während Sie das Dokument von E-MAIL nach FLATOPC exportieren. Das Hinzufügen von Schutz zu Ihrem Dokument ist ein einfacher Vorgang, da Sie lediglich die Schutzmethode auf Ihr Dokument anwenden müssen. Sie können den Schutztyp auf ReadOnly setzen, um den Benutzer auf die Bearbeitung des Dokuments einzuschränken.
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
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}