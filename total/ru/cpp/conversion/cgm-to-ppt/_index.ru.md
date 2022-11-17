---
title: C++ API для преобразования CGM в PPT
description: Преобразование CGM в PPT через C++ без использования Microsoft Word или Adobe Acrobat Reader.

family: total
platformtag: cpp
feature: conversion
informat: CGM
outformat: PPT
otherformats: PPSX PPSM PPS POTM POWERPOINT POT POTX PPTM SWF XAML ODP OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Рендеринг CGM в PPT в приложениях C++" h2="Преобразование CGM в PPT в приложениях C++ без использования Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы разработчик C++ и хотите добавить функцию преобразования CGM в PPT в свои приложения C++? Вы можете сделать это в два простых шага. Вы можете экспортировать CGM в PPTX с помощью [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/). Во-вторых, с помощью [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) вы можете конвертировать PPTX в PPT. Оба API входят в пакет [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++ API для экспорта CGM в PPT" %}}
1. Откройте файл CGM, используя ссылку на класс [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document).
2. Преобразуйте CGM в PPTX, используя функцию метода [Сохранить](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a0184df207563187be7df37b8dbe443f6).
3. Загрузите документ PPTX, используя ссылку на класс [Presentation](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation).
4. Сохраните документ в формате PPT с помощью функции-члена [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) и установите `Ppt` как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load CGM file with an instance of Document class
auto doc = MakeObject<Document>(u"template.cgm");
// save CGM as PPTX format 
doc->Save(u"PptxOutput.pptx", SaveFormat::Pptx);
// instantiate a Presentation object that represents a PPTX file
SharedPtr<Presentation> prs = MakeObject<Presentation>(u"PptxOutput.pptx");
// save the presentation as Ppt format
prs->Save(u"output.ppt", Aspose::Slides::Export::SaveFormat::Ppt);  
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Изменить пароль документа CGM через C++" %}}
В процессе рендеринга CGM в PPT вы можете открыть защищенный паролем CGM, а также изменить его пароль. Чтобы изменить пароль файла CGM, вы должны знать пароль владельца этого документа. Вы можете загрузить PDF-документ, защищенный паролем, с помощью [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), указав пароль его владельца и используя метод ChangePasswords для изменения пароля.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load an existing CGM Document
auto doc = MakeObject<Document>(L"input.cgm", L"owner");
// change password of CGM Document
doc->ChangePasswords(L"owner", L"newuser", L"newuser");
// save the document
doc->Save(L"output.Doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Добавить изображения из Интернета в файл PPT через С++" %}}
После преобразования CGM в PPT вы также можете добавлять изображения из Интернета в выходной документ. [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/) поддерживает работу с изображениями в таких популярных форматах: JPEG, PNG, BMP, GIF и других. Вы можете добавить одно или несколько изображений со своего компьютера на слайд в презентации. В этом примере кода на C++ показано, как добавить изображение в файл PPT.
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
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-ppsx/" name="CGM К PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-ppsm/" name="CGM К PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-pps/" name="CGM К PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-potm/" name="CGM К POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-powerpoint/" name="CGM К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-pot/" name="CGM К POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-potx/" name="CGM К POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-pptm/" name="CGM К PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-swf/" name="CGM К SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-xaml/" name="CGM К XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-ppt/" name="CGM К PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/cgm-to-otp/" name="CGM К OTP" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}