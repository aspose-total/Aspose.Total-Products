---
title: Преобразование OTT в PPTM через C# .NET или с помощью бесплатного онлайн-конвертера
url_ignore: /ru/net/conversion/ott-to-pptm/ 
description: Преобразование документов Word ott в файлы PowerPoint pptm с помощью C#. Преобразование нескольких файлов в ASP.NET или других приложениях .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование OTT в PPTM с помощью C# или онлайн" h2="Создавайте приложения преобразования Microsoft Word OTT в PowerPoint PPTM на платформах .NET Framework, .NET Core, Windows Azure, Mono или Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PPTM" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="OTT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Как преобразовать OTT в PPTM с помощью C#" %}}

Чтобы автоматизировать процесс пакетного преобразования любых файлов Word ott в формат презентации PowerPoint pptm, мы будем использовать [Aspose.Words for .NET](https://products.aspose.com/words/net) и [Aspose.Slides for .NET](https://products.aspose.com/slides/net) API. Первый представляет собой API обработки текстов для обработки или управления документами Microsoft Word. Принимая во внимание, что последний представляет собой API для управления презентациями, который позволяет создавать или изменять слайды Microsoft PowerPoint. Оба API являются частью пакета [Aspose.Total for .NET](https://products.aspose.com/total/net). Вы можете напрямую [скачать](https://releases.aspose.com) из Nuget или использовать следующие команды из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда консоли диспетчера пакетов" offSpacer="true" %}}

```cs
PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги по преобразованию OTT в PPTM через C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Total позволяет разработчикам легко загружать и конвертировать файлы OTT в PPTM всего за несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Добавить ссылку на Aspose.Total for .NET
1. Загрузите файл DOCM, используя класс [Aspose.Words.Document](https://reference.aspose.com/words/net/aspose.words/document)
1. Сохраните документ OTT в HTML.
1. Создайте объект [Aspose.Slides.Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation)
1. Импорт содержимого HTML в текстовом фрейме любой формы слайда внутри презентации.
1. Сохраните документ, используя [Aspose.Slides.Presentation.Save("output.pptm", SaveFormat.Pptm)](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5 )

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.Total for .NET поддерживается во всех основных операционных системах. Просто убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС с платформами .NET Framework, .NET Core, Windows Azure, Mono или Xamarin.
-  Среда разработки, такая как Microsoft Visual Studio.
-  Aspose.Words for .NET &amp; Aspose.Slides for .NET DLL или Aspose.Total for .NET DLL, на которые ссылается ваш проект.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="В этом примере кода показано, как преобразовать OTT в PPTM с помощью C#." offSpacer="" %}}

```cs// Загрузите одностраничный файл Microsoft Word OTT
Aspose.Words.Document ott = new Aspose.Words.Document("sourceWordFile.ott");

// Сохраняем файл OTT в HTML
ott.Save("filepath\\test.html", SaveFormat.Html);

// Чтобы преобразовать многостраничные документы OTT, экспортируйте каждую страницу в HTML отдельно, используя Aspose.Words, а затем используйте приведенный ниже код для преобразования в PPTM.

using (Presentation pptm = new Presentation()){

	// Доступ к первому слайду презентации по умолчанию
	ISlide slide = pres.Slides[0];

	// Добавление автофигуры для размещения содержимого HTML
	// Отрегулируйте его по своему усмотрению
	IAutoShape ashape = slide.Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, pres.SlideSize.Size.Width - 20, pres.SlideSize.Size.Height - 10);

	ashape.FillFormat.FillType = FillType.NoFill;

	// Добавляем текстовую рамку к фигуре
	ashape.AddTextFrame("");

	// Очистка всех абзацев в добавленном текстовом фрейме
	ashape.TextFrame.Paragraphs.Clear();

	// Загрузка HTML-файла с помощью потокового считывателя
	TextReader tr = new StreamReader("filepath\\test.html");

	// Добавление текста из программы чтения потока HTML в текстовом фрейме
	ashape.TextFrame.Paragraphs.AddFromHtml(tr.ReadToEnd());

	// Сохраняем презентацию PPTM
	pptm.Save("filepath\\pres.pptm", Aspose.Slides.Export.SaveFormat.Pptm);
}

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class="demobox tc col-md-12 padding-0" align="center">
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Онлайн-конвертер OTT в PPTM</h3>

<iframe title="Онлайн-инструмент от pptm до ott долларов" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=pptm&from=ott" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Бесплатное приложение для преобразования OTT в PPTM" sectionDescription="Посмотрите наши живые демонстрации для [преобразования OTT в PPTM](https://products.aspose.app/words/conversion/word-to-pptm) со следующими преимуществами." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл OTT и нажмите кнопку «Конвертировать»." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы сразу же получите ссылку для скачивания результирующего OTT-файла." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

Aspose.Total for .NET — это полный пакет API для работы с документами. API легко интегрируются в любое приложение на основе .NET для управления Microsoft Word, Excel, PowerPoint, Outlook, PDF, изображениями, штрих-кодами и более чем 100 другими форматами. Программисты могут легко использовать их для создания, изменения, рендеринга, печати и преобразования между наиболее популярными форматами файлов в любых приложениях .NET, C#, ASP.NET и VB.NET без необходимости использования какого-либо другого программного обеспечения.

    {{% /blocks/products/pf/agp/content %}}
{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

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
                          <span itemprop="name"><b>Как я могу конвертировать OTT в PPTM онлайн?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Онлайн-приложение для преобразования OTT интегрировано выше. Чтобы использовать это приложение, вы можете добавить свой файл OTT, перетащив его в обозначенную белую область или щелкнув внутри области, чтобы импортировать документ. Затем нажмите кнопку «Преобразовать», чтобы начать процесс преобразования. После завершения преобразования OTT в PPTM вы можете загрузить только что преобразованный файл одним щелчком мыши, и он будет доступен вам в виде файла PPTM.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Сколько времени занимает конвертация OTT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Этот онлайн-конвертер работает быстро, но в первую очередь зависит от размера конвертируемого файла OTT. Для небольших файлов OTT преобразование в PPTM может быть выполнено за считанные секунды. Однако если вы интегрировали код преобразования в приложение .NET, скорость преобразования будет зависеть от того, насколько хорошо ваше приложение оптимизировано для процесса преобразования.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Безопасно ли конвертировать OTT в PPTM с помощью бесплатного конвертера Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Конечно! Как только преобразование OTT в PPTM будет завершено, ссылка для скачивания только что преобразованного файла PPTM будет доступна мгновенно. Это также обеспечивает безопасность процесса преобразования, так как все загруженные файлы, включая файлы OTT, полностью защищены и будут удалены из системы через 24 часа. Кроме того, по истечении этого периода ссылки для скачивания перестанут работать, что обеспечит конфиденциальность и защиту ваших файлов. Интегрированное приложение является бесплатным для использования и предназначено для целей тестирования, чтобы пользователи могли оценить результаты, прежде чем интегрировать код в свои проекты.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Какой браузер я должен использовать для преобразования OTT?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Вы можете использовать любой современный веб-браузер, такой как Google Chrome, Firefox, Opera или Safari, для онлайн-преобразования OTT в PPTM. Однако, если вы разрабатываете настольное приложение, рекомендуется использовать Aspose.Total OTT Conversion API для плавной и эффективной обработки.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}