---
title: C++ API для преобразования EPUB в PPSX
description: Преобразование EPUB в PPSX через C++ без использования Microsoft Word или Adobe Acrobat Reader.

family: total
platformtag: cpp
feature: conversion
informat: EPUB
outformat: PPSX
otherformats: PPS ODP POT POTM POTX PPSM SWF OTP POWERPOINT PPTM XAML PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Рендеринг EPUB в PPSX в приложениях C++" h2="Преобразование EPUB в PPSX в приложениях C++ без использования Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы разработчик C++ и хотите добавить функцию преобразования EPUB в PPSX в свои приложения C++? Вы можете сделать это в два простых шага. Вы можете экспортировать EPUB в PPTX с помощью [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Во-вторых, с помощью [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) вы можете конвертировать PPTX в PPSX. Оба API входят в пакет [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для экспорта EPUB в PPSX" %}}
1. Откройте файл EPUB, используя ссылку на класс [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document).
2. Преобразуйте EPUB в PPTX, используя функцию метода [Сохранить](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6).
3. Загрузите документ PPTX, используя ссылку на класс [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation).
4. Сохраните документ в формате PPSX с помощью функции-члена [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) и установите `Ppsx` как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load EPUB file with an instance of Document class
auto doc = MakeObject<Document>(u"template.epub");
// save EPUB as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppsx format
prs->Save(u"output.ppsx", Aspose::Slides::Export::SaveFormat::Ppsx);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Изменить пароль документа EPUB через C++" %}}
В процессе рендеринга EPUB в PPSX вы можете открыть защищенный паролем EPUB, а также изменить его пароль. Чтобы изменить пароль файла EPUB, вы должны знать пароль владельца этого документа. Вы можете загрузить PDF-документ, защищенный паролем, с помощью [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), указав пароль его владельца и используя метод ChangePasswords для изменения пароля.
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

{{% blocks/products/pf/feature-page-section  h2="Добавить изображения из Интернета в файл PPSX через С++" %}}
После преобразования EPUB в PPSX вы также можете добавлять изображения из Интернета в выходной документ. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) поддерживает работу с изображениями в таких популярных форматах: JPEG, PNG, BMP, GIF и других. Вы можете добавить одно или несколько изображений со своего компьютера на слайд в презентации. В этом примере кода на C++ показано, как добавить изображение в файл PPSX.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate a Presentation object that represents a PPSX file
auto pres = System::MakeObject<Presentation>("output.ppsx");
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
pres->Save(u"updated.ppsx", SaveFormat::Ppsx);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/epub-to-pps/" name="EPUB К PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/epub-to-ppsx/" name="EPUB К PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/epub-to-pot/" name="EPUB К POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/epub-to-potm/" name="EPUB К POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/epub-to-potx/" name="EPUB К POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/epub-to-ppsm/" name="EPUB К PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/epub-to-swf/" name="EPUB К SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/epub-to-otp/" name="EPUB К OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/epub-to-powerpoint/" name="EPUB К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/epub-to-pptm/" name="EPUB К PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/epub-to-xaml/" name="EPUB К XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/epub-to-ppt/" name="EPUB К PPT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}