---
title: C++-API zum Exportieren von SVG nach DOTM
description: Konvertieren Sie SVG in DOTM innerhalb von C++-Anwendungen.

family: total
platformtag: cpp
feature: conversion
informat: SVG
outformat: DOTM
otherformats: DOCM MHTML MARKDOWN PS FLATOPC DOTX ODT XAMLFLOW WORDML OTT DOT RTF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++-API zum Exportieren von SVG nach DOTM" h2="Rendern Sie SVG in DOTM innerhalb von C++-Anwendungen, ohne dass eine Anwendung eines Drittanbieters erforderlich ist" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/)-Dateiformat-Automatisierungsbibliotheken ermöglichen es C++-Entwicklern, SVG in zwei einfachen Schritten in DOTM zu konvertieren. Erstens können Sie die API [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) verwenden, um das SVG-Dateiformat in DOC zu konvertieren. Zweitens können Sie durch Verwendung der erweiterten Word-Dokumentverarbeitungs-API [Aspose.Words for C++](https://products.aspose.com/words/cpp/) DOC nach DOTM exportieren. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Rendern von SVG in DOTM" %}}
1. Öffnen Sie die SVG-Datei mit der Klassenreferenz [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document).
2. Konvertieren Sie SVG in DOC, indem Sie die Member-Funktion [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) verwenden
3. Laden Sie die DOC-Datei mithilfe der [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)-Klassenreferenz der Aspose.Words-API
4. Speichern Sie das Dokument mit der Member-Funktion [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) im DOTM-Format
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load SVG file with an instance of Document class reference
auto doc = MakeObject<Document>(u"sourceFile.svg");
// save SVG as a DOC 
doc->Save(u"DocOutput.doc", SaveFormat::Doc); 
// load DOC with an instance of Document
System::SharedPtr<Document> wordDoc = System::MakeObject<Document>(u"DocOutput.doc");
// save document as Dotm
wordDoc->Save(u"output.Dotm");  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ändern Sie das Passwort des SVG-Dokuments über C++" %}}
Beim Rendern von SVG in DOTM können Sie ein passwortgeschütztes SVG öffnen und auch sein Passwort ändern. Um das Passwort einer SVG-Datei zu ändern, müssen Sie das Besitzerpasswort dieses Dokuments kennen. Sie können ein passwortgeschütztes PDF-Dokument mit [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) laden, indem Sie das Besitzerpasswort angeben und das Passwort mit der ChangePasswords-Methode ändern.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing SVG Document
auto doc = MakeObject<Document>(L"input.svg", L"owner");
// change password of SVG Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Beschränken Sie die Bearbeitung von DOTM-Dateien über C++" %}}
Sie können die Bearbeitung von DOTM-Dateien auch mithilfe der [Aspose.Words for C++](https://products.aspose.com/words/cpp/)-API einschränken. Manchmal müssen Sie möglicherweise die Möglichkeit zum Bearbeiten eines Dokuments einschränken und nur bestimmte Aktionen damit zulassen. Mit der API können Sie steuern, wie Sie den Inhalt mithilfe des Aufzählungsparameters [ProtectionType](https://reference.aspose.com/words/cpp/namespace/aspose.words#protectiontype) einschränken. Das folgende Codebeispiel zeigt, wie Sie die Bearbeitung in einem Dokument einschränken, sodass nur die Bearbeitung in Formularfeldern möglich ist.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load Doc with an instance of Document
auto doc = System::MakeObject<Document>("input.doc");
// document protection only works when document protection is turned and only editing in form fields is allowed.
doc->Protect(ProtectionType::AllowOnlyFormFields, u"password");
// save the protected document.
doc->Save(u"Protected.Dotm");  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}