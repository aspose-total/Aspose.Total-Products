---
title: Преобразование TXT в PPS через C++
description: Экспортируйте TXT в PPS в свои приложения C++ без использования Microsoft Word of PowerPoint.
url: /ru/cpp/conversion/txt-to-pps/
family: total
platformtag: cpp
feature: conversion
informat: TXT
outformat: PPS
otherformats: PPSX PPSM ODP POTX POTM PPTM PPT POWERPOINT PPTX POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для преобразования TXT в PPS" h2="Экспортируйте TXT в PPS в приложениях C++ без использования Microsoft Word&reg; или PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) состоит из мощных API-интерфейсов для автоматизации файлов, которые позволяют автоматизировать преобразование TXT в PPS при использовании двух API-интерфейсов. Загрузите свой TXT с помощью [Aspose.Words for C++](https://products.aspose.com/words/cpp/) и преобразуйте его в HTML, затем загрузите HTML с помощью C++ API для обработки PowerPoint [Aspose.Slides for C++]( https://products.aspose.com/slides/cpp/), чтобы создать новую презентацию и сохранить ее как PPS. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование TXT в PPS на C++" %}}
1. Откройте файл TXT, используя ссылку на класс [Txtument](https://reference.aspose.com/words/cpp/class/aspose.words.txtument).
2. Преобразуйте TXT в HTML с помощью функции-члена [Save](https://reference.aspose.com/words/cpp/class/aspose.words.txtument#save_stdbasicostream_saveoptions).
3. Инициализируйте новый объект [Презентация](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Добавьте AutoShape на слайд и добавьте в него AddTextFrame.
5. Загрузите содержимое HTML и запишите его в файл презентации.
6. Сохраните документ в формате PPS с помощью метода [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) и установите Pps как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load TXT file with an instance of Txtument
Txtument txtument = new Txtument("template.txt");
System::SharedPtr<Txtument> txt = System::MakeObject<Txtument>(u"sourceFile.txt");
// save the txtument in HTML file format
txt->Save(u"HtmlOutput.HTML");
// load the desired the presentation
SharedPtr<Presentation> pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ISlide> sld = pres->get_Slides()->idx_get(0);
// add an AutoShape of Rectangle type
SharedPtr<IAutoShape>  ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10, 10, 700, 500);
// reset default fill color
ashp->get_FillFormat()->set_FillType(FillType::NoFill);
// add TextFrame to the Rectangle
ashp->AddTextFrame(u" ");
// access the text frame
SharedPtr<ITextFrame>  txtFrame = ashp->get_TextFrame();
// get Paragraphs collection
SharedPtr<Aspose::Slides::IParagraphCollection>ParaCollection = txtFrame->get_Paragraphs();
// clear all paragraphs in added text frame
ParaCollection->Clear();
// load the HTML file using stream reader
SharedPtr<System::IO::StreamReader>  tr = MakeObject<System::IO::StreamReader>(HtmlOutput.HTML);
// add text from HTML stream reader in text frame
ParaCollection->AddFromHtml(tr->ReadToEnd());
// save presentation as Pps
pres->Save(output.pps, Aspose::Slides::Export::SaveFormat::Pps);                  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Загрузить защищенный паролем документ TXT через C++" %}}
Помимо преобразования документов, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API позволяет разработчикам C++ использовать множество функций для работы с документами. Если ваш формат файла Microsoft Word TXT защищен паролем, вы все равно можете открыть его с помощью API. Чтобы загрузить зашифрованный документ, вы можете использовать специальную перегрузку конструктора, которая принимает объект [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Этот объект содержит свойство Password, которое определяет строку пароля.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected txtument, the password is passed to the txtument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"txtPassword");
// load the txtument from the local file system by filename:
SharedPtr<Txtument> txt = MakeObject<Txtument>(u"Encrypted.txt", options);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Добавить комментарии в документ PPS через C++" %}}
При сохранении TXT в формате PPS вы также можете использовать [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), чтобы добавить дополнительные функции в документ PPS. Например, вы можете добавлять комментарии в свою презентацию. Комментарии к слайдам презентации связаны с конкретным автором. Класс Presentation содержит коллекцию авторов в ICommentAuthorCollection, которые отвечают за добавление комментариев к слайдам. Для каждого автора в ICommentCollection есть коллекция комментариев.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// instantiate Presentation class
SharedPtr<Presentation>pres = MakeObject<Presentation>();
// access first slide
SharedPtr<ILayoutSlide>layout = pres->get_LayoutSlides()->idx_get(0);
// add empty slide
pres->get_Slides()->AddEmptySlide(layout);
// adding Author
SharedPtr<ICommentAuthor> author = pres->get_CommentAuthors()->AddAuthor(u"John Doe", u"MF");
// set position of comments
System::Drawing::PointF point = System::Drawing::PointF(0.2f, 0.2f);
// add slide comment for an author on slide 1
author->get_Comments()->AddComment(u"Hello John, this is a slide comment", pres->get_Slides()->idx_get(1), point, DateTime::get_Now());
// access ISlide 1
SharedPtr<ISlide> slide = pres->get_Slides()->idx_get(0);
// save presentation as Pps
pres->Save(output.pps, Aspose::Slides::Export::SaveFormat::Pps);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/txt-to-ppsx/" name="TXT К PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/txt-to-ppsm/" name="TXT К PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/txt-to-pps/" name="TXT К PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/txt-to-potx/" name="TXT К POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/txt-to-potm/" name="TXT К POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/txt-to-pptm/" name="TXT К PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/txt-to-ppt/" name="TXT К PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/txt-to-powerpoint/" name="TXT К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/txt-to-pptx/" name="TXT К PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/txt-to-pot/" name="TXT К POT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}