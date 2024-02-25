---
title: C++-API zum Konvertieren von EPUB in PPS
description: Konvertieren Sie EPUB über C++ in PPS, ohne Microsoft Word oder Adobe Acrobat Reader zu verwenden

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: PPS
otherformats: POTX ODP PPSX PPT PPSM POTM XAML POWERPOINT PPTM SWF OTP POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie EPUB in PPS innerhalb von C++-Anwendungen" h2="Konvertieren Sie EPUB in PPS innerhalb Ihrer C++-Anwendungen, ohne Microsoft<sup>&reg;</sup> PowerPoint zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sind Sie ein C++-Entwickler, der EPUB-zu-PPS-Konvertierungsfunktionen in Ihre C++-Anwendungen integrieren möchte? Sie können es in zwei einfachen Schritten tun. Sie können EPUB in PPTX exportieren, indem Sie [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) verwenden. Zweitens können Sie mit [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) PPTX in PPS konvertieren. Beide APIs befinden sich im Paket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Exportieren von EPUB nach PPS" %}}
1. Öffnen Sie die EPUB-Datei mit der Klassenreferenz [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document).
2. Konvertieren Sie EPUB in PPTX, indem Sie die Methodenfunktion [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) verwenden
3. Laden Sie das PPTX-Dokument mithilfe der Klassenreferenz [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation).
4. Speichern Sie das Dokument im PPS-Format mit der Member-Funktion [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) und legen Sie „Pps“ als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load EPUB file with an instance of Document class
auto doc = MakeObject<Document>(u"template.epub");
// save EPUB as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Pps format
prs->Save(u"output.pps", Aspose::Slides::Export::SaveFormat::Pps);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ändern Sie das Passwort des EPUB-Dokuments über C++" %}}
Beim Rendern von EPUB zu PPS können Sie ein passwortgeschütztes EPUB öffnen und auch sein Passwort ändern. Um das Passwort einer EPUB-Datei zu ändern, müssen Sie das Besitzerpasswort dieses Dokuments kennen. Sie können ein passwortgeschütztes PDF-Dokument mit [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) laden, indem Sie das Besitzerpasswort angeben und das Passwort mit der ChangePasswords-Methode ändern.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing EPUB Document
auto doc = MakeObject<Document>(L"input.epub", L"owner");
// change password of EPUB Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Fügen Sie Bilder aus dem Web in einer PPS-Datei über C++ hinzu" %}}
Nach der Konvertierung von EPUB in PPS können Sie Ihrem Ausgabedokument auch Bilder aus dem Internet hinzufügen. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) unterstützt Operationen mit Bildern in diesen gängigen Formaten: JPEG, PNG, BMP, GIF und andere. Sie können einer Folie in einer Präsentation ein oder mehrere Bilder auf Ihrem Computer hinzufügen. Dieser Beispielcode in C++ zeigt Ihnen, wie Sie einer PPS-Datei ein Bild hinzufügen
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPS file
auto pres = System::MakeObject<Presentation>("output.pps");
// get slide
auto slide = pres->get_Slides()->idx_get(0);
// initialize Web Client    
auto webClient = System::MakeObject<WebClient>();
// get image data
auto imageData = webClient->DownloadData(System::MakeObject<Uri>(u"[REPLACE WITH URL]"));
// add image
auto image = pres->get_Images()->AddImage(imageData);
// add picture frame
slide->get_Shapes()->AddPictureFrame(ShapeType::Rectangle, 10.0f, 10.0f, 100.0f, 100.0f, image);
// save updated file
pres->Save(u"updated.pps", SaveFormat::Pps);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}