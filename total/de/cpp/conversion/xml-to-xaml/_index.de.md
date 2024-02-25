---
title: C++-API zum Konvertieren von XML in XAML
description: Konvertieren Sie XML über C++ in XAML, ohne Microsoft Word oder Adobe Acrobat Reader zu verwenden

family: total
platformtag: cpp
feature: conversion
informat: XML
outformat: XAML
otherformats: PPS ODP POWERPOINT PPSX OTP PPT PPSM SWF POTX POT POTM PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie XML in XAML innerhalb von C++-Anwendungen" h2="Konvertieren Sie XML in XAML innerhalb Ihrer C++-Anwendungen, ohne Microsoft<sup>&reg;</sup> PowerPoint zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sind Sie ein C++-Entwickler, der XML-zu-XAML-Konvertierungsfunktionen in Ihre C++-Anwendungen integrieren möchte? Sie können es in zwei einfachen Schritten tun. Sie können XML in PPTX exportieren, indem Sie [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) verwenden. Zweitens können Sie mit [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) PPTX in XAML konvertieren. Beide APIs befinden sich im Paket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Exportieren von XML nach XAML" %}}
1. Öffnen Sie die XML-Datei mit der Klassenreferenz [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document).
2. Konvertieren Sie XML in PPTX, indem Sie die Methodenfunktion [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) verwenden
3. Laden Sie das PPTX-Dokument mithilfe der Klassenreferenz [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation).
4. Speichern Sie das Dokument im XAML-Format mit der Member-Funktion [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) und legen Sie „Xaml“ als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XML file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xml");
// save XML as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Xaml format
prs->Save(u"output.xaml", Aspose::Slides::Export::SaveFormat::Xaml);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ändern Sie das Passwort des XML-Dokuments über C++" %}}
Beim Rendern von XML zu XAML können Sie ein passwortgeschütztes XML öffnen und auch sein Passwort ändern. Um das Passwort einer XML-Datei zu ändern, müssen Sie das Besitzerpasswort dieses Dokuments kennen. Sie können ein passwortgeschütztes PDF-Dokument mit [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) laden, indem Sie das Besitzerpasswort angeben und das Passwort mit der ChangePasswords-Methode ändern.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XML Document
auto doc = MakeObject<Document>(L"input.xml", L"owner");
// change password of XML Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Fügen Sie Bilder aus dem Web in einer XAML-Datei über C++ hinzu" %}}
Nach der Konvertierung von XML in XAML können Sie Ihrem Ausgabedokument auch Bilder aus dem Internet hinzufügen. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) unterstützt Operationen mit Bildern in diesen gängigen Formaten: JPEG, PNG, BMP, GIF und andere. Sie können einer Folie in einer Präsentation ein oder mehrere Bilder auf Ihrem Computer hinzufügen. Dieser Beispielcode in C++ zeigt Ihnen, wie Sie einer XAML-Datei ein Bild hinzufügen
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a XAML file
auto pres = System::MakeObject<Presentation>("output.xaml");
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
pres->Save(u"updated.xaml", SaveFormat::Xaml);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}