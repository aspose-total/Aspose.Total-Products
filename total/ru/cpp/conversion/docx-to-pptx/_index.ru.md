---
title: Преобразование DOCX в PPTX через C++ или с помощью бесплатного онлайн-конвертера
description: Экспортируйте DOCX в PPTX в свои приложения C++ без использования Microsoft Word of PowerPoint. или онлайн. Быстро протестируйте бесплатный онлайн-конвертер DOCX в PPTX, прежде чем интегрировать код.

family: total
platformtag: cpp
feature: conversion
informat: DOCX
outformat: PPTX
otherformats: POTX PPTM POT PPSX PPS PPT PPSM POTM POWERPOINT ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++ API для преобразования DOCX в PPTX или онлайн-приложение" h2="Экспортируйте DOCX в PPTX в приложениях C++ без использования Microsoft Word&reg; или PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for C++](https://products.aspose.com/total/cpp/) состоит из мощных API-интерфейсов для автоматизации файлов, которые позволяют автоматизировать преобразование DOCX в PPTX при использовании двух API-интерфейсов. Загрузите свой DOCX с помощью [Aspose.Words for C++](https://products.aspose.com/words/cpp/) и преобразуйте его в HTML, затем загрузите HTML с помощью C++ API для обработки PowerPoint [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), чтобы создать новую презентацию и сохранить ее как PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование DOCX в PPTX на C++" %}}
1. Откройте файл DOCX, используя ссылку на класс [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document).
2. Преобразуйте DOCX в HTML с помощью функции-члена [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stdbasicostream_saveoptions).
3. Инициализируйте новый объект [Презентация](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Добавьте AutoShape на слайд и добавьте в него AddTextFrame.
5. Загрузите содержимое HTML и запишите его в файл презентации.
6. Сохраните документ в формате PPTX с помощью метода [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e) и установите Pptx как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Установите из командной строки как ```nuget install Aspose.Total.Cpp``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total.Cpp```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP-файле из [загрузки](https://releases.aspose.comtotal/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```cpp
// load DOCX file with an instance of Document
Document document = new Document("template.docx");
System::SharedPtr<Document> docx = System::MakeObject<Document>(u"sourceFile.docx");
// save the document in HTML file format
docx->Save(u"HtmlOutput.HTML");
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

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Бесплатный онлайн-конвертер DOCX в PPTX</h3>

<iframe title="Онлайн-инструмент от pptx до docx долларов" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pptx&from=docx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>

{{% blocks/products/pf/feature-page-section  h2="Загрузить защищенный паролем документ DOCX через C++" %}}
Помимо преобразования документов, [Aspose.Words for C++](https://products.aspose.com/words/cpp/) API позволяет разработчикам C++ использовать множество функций для работы с документами. Если ваш формат файла Microsoft Word DOCX защищен паролем, вы все равно можете открыть его с помощью API. Чтобы загрузить зашифрованный документ, вы можете использовать специальную перегрузку конструктора, которая принимает объект [LoadOptions](https://reference.aspose.com/words/cpp/class/aspose.words.loading.load_options). Этот объект содержит свойство Password, которое определяет строку пароля.
{{% blocks/products/pf/feature-page-code %}}

```cpp
// when loading password protected document, the password is passed to the document's constructor using a LoadOptions object.
auto options = MakeObject<LoadOptions>(u"docxPassword");
// load thDocumentnt from the local fiDocument by filename:
SharedPtr<Docxument> docx = MakeObject<Docxument>(u"Encrypted.docx", options);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Добавить комментарии в документ PPTX через C++" %}}
При сохранении DOCX в формате PPTX вы также можете использовать [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), чтобы добавить дополнительные функции в документ PPTX. Например, вы можете добавлять комментарии в свою презентацию. Комментарии к слайдам презентации связаны с конкретным автором. Класс Presentation содержит коллекцию авторов в ICommentAuthorCollection, которые отвечают за добавление комментариев к слайдам. Для каждого автора в ICommentCollection есть коллекция комментариев.
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
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Часто задаваемые вопросы</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Как я могу конвертировать DOCX в PPTX онлайн?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Вы можете найти онлайн-приложение для преобразования DOCX выше. Чтобы начать процесс преобразования, вы можете добавить файл DOCX, перетащив его или щелкнув внутри белой области, чтобы импортировать документ. После того, как вы добавили файл, вы можете просто нажать кнопку «Конвертировать». После завершения преобразования DOCX в PPTX вы можете загрузить преобразованный файл одним щелчком мыши.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Сколько времени занимает конвертация DOCX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Скорость этого онлайн-конвертера во многом зависит от размера конвертируемого DOCX-файла. Небольшие файлы DOCX можно преобразовать в PPTX всего за несколько секунд. Если вы используете код преобразования в приложении C++, скорость преобразования будет зависеть от того, насколько хорошо вы оптимизировали свое приложение.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Безопасно ли конвертировать DOCX в PPTX с помощью бесплатного конвертера Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Конечно! После того, как ваш файл DOCX будет преобразован в PPTX с помощью нашего онлайн-конвертера, ссылка для скачивания файла PPTX будет немедленно доступна. Мы серьезно относимся к безопасности и конфиденциальности загруженных вами файлов и удаляем их через 24 часа после завершения процесса преобразования. Будьте уверены, никто не получит доступ к вашим файлам. Наш процесс преобразования, включая преобразование DOCX, полностью безопасен. Мы предоставляем бесплатное приложение для целей тестирования, чтобы вы могли проверить результаты перед интеграцией кода.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Какой браузер я должен использовать для преобразования DOCX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Для онлайн-конвертации DOCX вы можете использовать любой современный браузер, такой как Google Chrome, Firefox, Opera или Safari. Однако, если вы разрабатываете настольное приложение, рекомендуется использовать Aspose.Total DOCX Conversion API для бесперебойной работы.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}