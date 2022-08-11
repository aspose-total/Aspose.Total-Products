---
title: C++ API do konwersji XPS na PPS
description: Konwertuj XPS na PPS za pomocą C++ bez użycia Microsoft Word lub Adobe Acrobat Reader
url: /pl/cpp/conversion/xps-to-pps/
family: total
platformtag: cpp
feature: conversion
informat: XPS
outformat: PPS
otherformats: PPSM OTP POTX XAML POTM POT ODP POWERPOINT SWF PPTM PPSX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderuj XPS do PPS w aplikacjach C++" h2="Konwertuj XPS na PPS w swoich aplikacjach C++ bez użycia Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Czy jesteś programistą C++, który chce dodać funkcję konwersji XPS do PPS w swoich aplikacjach C++? Możesz to zrobić w dwóch prostych krokach. Możesz wyeksportować XPS do PPTX, używając [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Po drugie, używając [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), możesz przekonwertować PPTX na PPS. Oba interfejsy API są objęte pakietem [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API do eksportu XPS do PPS" %}}
1. Otwórz plik XPS, korzystając z odwołania do klasy [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Konwertuj XPS na PPTX za pomocą funkcji metody [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6)
3. Załaduj dokument PPTX, korzystając z odwołania do klasy [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Zapisz dokument w formacie PPS za pomocą funkcji członkowskiej [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) i ustaw `Pps` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania dotyczące konwersji" %}}
Zainstaluj z wiersza poleceń jako ```nuget install Aspose.Total.Cpp``` lub za pomocą konsoli Menedżera pakietów programu Visual Studio za pomocą ```Install-Package Aspose.Total.Cpp```.

Możesz też pobrać instalator MSI lub biblioteki DLL offline w pliku ZIP ze strony [downloads](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load XPS file with an instance of Document class
auto doc = MakeObject<Document>(u"template.xps");
// save XPS as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Pps format
prs->Save(u"output.pps", Aspose::Slides::Export::SaveFormat::Pps);  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Zmień hasło dokumentu XPS za pomocą C++" %}}
W procesie renderowania XPS do PPS możesz otworzyć XPS chroniony hasłem, a także zmienić jego hasło. Aby zmienić hasło do pliku XPS, musisz znać hasło właściciela tego dokumentu. Możesz załadować dokument PDF chroniony hasłem za pomocą [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), określając hasło właściciela i używając metody ChangePasswords, aby zmienić hasło.
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

{{% blocks/products/pf/feature-page-section  h2="Dodaj obrazy z sieci w pliku PPS za pomocą C++" %}}
Po przekonwertowaniu XPS na PPS możesz również dodać obrazy z Internetu do dokumentu wyjściowego. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) obsługuje operacje na obrazach w tych popularnych formatach: JPEG, PNG, BMP, GIF i innych. Do slajdu w prezentacji można dodać jeden lub kilka obrazów z komputera. Ten przykładowy kod w C++ pokazuje, jak dodać obraz do pliku PPS
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
{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-ppsm/" name="XPS Do PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-otp/" name="XPS Do OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-potx/" name="XPS Do POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-xaml/" name="XPS Do XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-potm/" name="XPS Do POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-pot/" name="XPS Do POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-pps/" name="XPS Do PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-powerpoint/" name="XPS Do POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-swf/" name="XPS Do SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-pptm/" name="XPS Do PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-ppsx/" name="XPS Do PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/pl/cpp/conversion/xps-to-ppt/" name="XPS Do PPT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}