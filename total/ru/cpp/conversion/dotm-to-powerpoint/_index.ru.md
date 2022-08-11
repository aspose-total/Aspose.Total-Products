---
title: Преобразование DOTM в POWERPOINT через C++
description: Экспортируйте DOTM в POWERPOINT в свои приложения C++ без использования Microsoft Word of PowerPoint.
url: /ru/cpp/conversion/dotm-to-powerpoint/
family: total
platformtag: cpp
feature: conversion
informat: DOTM
outformat: PPTX
otherformats: PPSX PPSM PPT POTX POT PPTX PPTM PPS POTM ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для преобразования DOTM в POWERPOINT" h2="Экспортируйте DOTM в POWERPOINT в приложениях C++ без использования Microsoft Word&reg; или PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) состоит из мощных API-интерфейсов для автоматизации файлов, которые позволяют автоматизировать преобразование DOTM в POWERPOINT при использовании двух API-интерфейсов. Загрузите свой DOTM с помощью [Aspose.Words для C++](https://products.aspose.com/words/cpp/) и преобразуйте его в HTML, затем загрузите HTML с помощью C++ API для обработки PowerPoint [Aspose.Slides для C++]( https://products.aspose.com/slides/cpp/), чтобы создать новую презентацию и сохранить ее как POWERPOINT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование DOTM в POWERPOINT на C++" %}}
1. Откройте файл DOTM, используя ссылку на класс [Dotmument](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument).
2. Преобразуйте DOTM в HTML с помощью функции-члена [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotmument#save_stdbasicostream_saveoptions).
3. Инициализируйте новый объект [Презентация](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Добавьте AutoShape на слайд и добавьте в него AddTextFrame.
5. Загрузите содержимое HTML и запишите его в файл презентации.
6. Сохраните документ в формате POWERPOINT с помощью метода [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) и установите Powerpoint как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOTM file with an instance of Dotmument
Dotmument dotmument = new Dotmument("template.dotm");
System::SharedPtr<Dotmument> dotm = System::MakeObject<Dotmument>(u"sourceFile.dotm");
// save the dotmument in HTML file format
dotm->Save(u"HtmlOutput.HTML");
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
// save presentation as Pptx
pres->Save(output.pptx, Aspose::Slides::Export::SaveFormat::Pptx);                  
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Загрузить защищенный паролем документ DOTM через C++" %}}
Помимо преобразования документов, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API позволяет разработчикам C++ использовать множество функций для работы с документами. Если ваш формат файла Microsoft Word DOTM защищен паролем, вы все равно можете открыть его с помощью API. Чтобы загрузить зашифрованный документ, вы можете использовать специальную перегрузку конструктора, которая принимает объект [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Этот объект содержит свойство Password, которое определяет строку пароля.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected dotmument, the password is passed to the dotmument's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"dotmPassword");
// load the dotmument from the local file system by filename:
SharedPtr<Dotmument> dotm = MakeObject<Dotmument>(u"Encrypted.dotm", options);
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Добавить комментарии в документ POWERPOINT через C++" %}}
При сохранении DOTM в формате POWERPOINT вы также можете использовать [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), чтобы добавить дополнительные функции в документ POWERPOINT. Например, вы можете добавлять комментарии в свою презентацию. Комментарии к слайдам презентации связаны с конкретным автором. Класс Presentation содержит коллекцию авторов в ICommentAuthorCollection, которые отвечают за добавление комментариев к слайдам. Для каждого автора в ICommentCollection есть коллекция комментариев.
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
// save presentation as Pptx
pres->Save(output.pptx, Aspose::Slides::Export::SaveFormat::Pptx);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-ppsx/" name="DOTM К PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-ppsm/" name="DOTM К PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-ppt/" name="DOTM К PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-potx/" name="DOTM К POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-pot/" name="DOTM К POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-pptx/" name="DOTM К PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-pptm/" name="DOTM К PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-pps/" name="DOTM К PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-potm/" name="DOTM К POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/cpp/conversion/dotm-to-powerpoint/" name="DOTM К POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}