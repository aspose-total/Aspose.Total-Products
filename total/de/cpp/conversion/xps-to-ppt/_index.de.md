---
title: C++-API zum Konvertieren von XPS in PPT
description: Konvertieren Sie XPS über C++ in PPT, ohne Microsoft Word oder Adobe Acrobat Reader zu verwenden

family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: PPT
otherformats: PPSX SWF PPSM POTM POT XAML PPS POWERPOINT OTP POTX PPTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Rendern Sie XPS in PPT innerhalb von C++-Anwendungen" h2="Konvertieren Sie XPS in PPT innerhalb Ihrer C++-Anwendungen, ohne Microsoft<sup>&reg;</sup> PowerPoint zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
Sind Sie ein C++-Entwickler, der XPS-zu-PPT-Konvertierungsfunktionen in Ihre C++-Anwendungen integrieren möchte? Sie können es in zwei einfachen Schritten tun. Sie können XPS in PPTX exportieren, indem Sie [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) verwenden. Zweitens können Sie mit [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) PPTX in PPT konvertieren. Beide APIs befinden sich im Paket [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++-API zum Exportieren von XPS nach PPT" %}}
1. Öffnen Sie die XPS-Datei mit der Klassenreferenz [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document).
2. Konvertieren Sie XPS in PPTX, indem Sie die Methodenfunktion [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6) verwenden
3. Laden Sie das PPTX-Dokument mithilfe der Klassenreferenz [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation).
4. Speichern Sie das Dokument im PPT-Format mit der Member-Funktion [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) und legen Sie „Ppt“ als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://downloads.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XPS file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xps");
// save XPS as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Ändern Sie das Passwort des XPS-Dokuments über C++" %}}
Beim Rendern von XPS zu PPT können Sie ein passwortgeschütztes XPS öffnen und auch sein Passwort ändern. Um das Passwort einer XPS-Datei zu ändern, müssen Sie das Besitzerpasswort dieses Dokuments kennen. Sie können ein passwortgeschütztes PDF-Dokument mit [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) laden, indem Sie das Besitzerpasswort angeben und das Passwort mit der ChangePasswords-Methode ändern.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing XPS Document
auto doc = MakeObject<Document>(L"input.xps", L"owner");
// change password of XPS Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Fügen Sie Bilder aus dem Web in einer PPT-Datei über C++ hinzu" %}}
Nach der Konvertierung von XPS in PPT können Sie Ihrem Ausgabedokument auch Bilder aus dem Internet hinzufügen. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) unterstützt Operationen mit Bildern in diesen gängigen Formaten: JPEG, PNG, BMP, GIF und andere. Sie können einer Folie in einer Präsentation ein oder mehrere Bilder auf Ihrem Computer hinzufügen. Dieser Beispielcode in C++ zeigt Ihnen, wie Sie einer PPT-Datei ein Bild hinzufügen
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPT file
auto pres = System::MakeObject<Presentation>("output.ppt");
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
pres->Save(u"updated.ppt", SaveFormat::Ppt);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Konvertierungen" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xps-to-ppsx/" name="XPS Zu PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xps-to-swf/" name="XPS Zu SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xps-to-ppsm/" name="XPS Zu PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xps-to-potm/" name="XPS Zu POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xps-to-pot/" name="XPS Zu POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xps-to-xaml/" name="XPS Zu XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xps-to-pps/" name="XPS Zu PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xps-to-powerpoint/" name="XPS Zu POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xps-to-otp/" name="XPS Zu OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xps-to-potx/" name="XPS Zu POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xps-to-pptm/" name="XPS Zu PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/cpp/conversion/xps-to-ppt/" name="XPS Zu PPT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}