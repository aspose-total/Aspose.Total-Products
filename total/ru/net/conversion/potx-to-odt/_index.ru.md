---
title: Преобразование POTX в ODT через C# .NET или с помощью бесплатного онлайн-конвертера
url_ignore: /ru/net/conversion/potx-to-odt/ 
description: Преобразование документов PowerPoint potx в файлы документов Word с помощью C#. Преобразование нескольких файлов в ASP.NET или других приложениях .NET.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/i18n/upper-banner h1="Преобразование POTX в ODT с помощью C# или онлайн" h2="Создавайте приложения для преобразования документов Microsoft PowerPoint POTX Presentation в Word ODT на платформах .NET Framework, .NET Core, Windows Azure, Mono или Xamarin." logoImageSrc="/total/images/aspose_total-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="ODT" pfName="Aspose.Total" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="POTX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Total " subTitlepfName="for .NET" >}}
{{% blocks/products/pf/agp/content h2="Как преобразовать POTX в ODT с помощью C#" %}}

 Чтобы автоматизировать процесс пакетного преобразования любой презентации PowerPoint potx в файлы документов Word, мы будем использовать [Aspose.Slides for .NET](https://products.aspose.com/slides/net) и [Aspose.Words for .NET](https://products.aspose.com/words/net) API. Первый — это API для работы с презентациями PowerPoint, который позволяет создавать или изменять слайды Microsoft PowerPoint. Принимая во внимание, что последний представляет собой API обработки текстов для обработки или управления документами Microsoft Word. Оба API являются частью пакета [Aspose.Total for .NET](https://products.aspose.com/total/net). Вы можете напрямую [скачать](https://releases.aspose.com) из Nuget или использовать следующие команды из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда консоли диспетчера пакетов" offSpacer="true" %}}

```cs
PM> Install-Package Aspose.Total

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги по преобразованию POTX в ODT через С#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Total позволяет разработчикам легко загружать и конвертировать файлы POTX в ODT всего за несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Добавить ссылку на Aspose.Slides for .NET и Aspose.Words for .NET
1. Загрузите презентацию PowerPoint POTX с помощью класса [Aspose.Slides.Presentation](https://reference.aspose.com/slides/net/aspose.slides/presentation).
1. Сохраните документ в объект [MemoryStream](https://docs.microsoft.com/en-us/dotnet/api/system.io.memorystream?view=net-5.0).
1. Создайте [Aspose.Words.Document](https://reference.aspose.com/words/net/aspose.words/document) и инициализируйте его с помощью объекта MemoryStream.
1. Сохраните документ, используя [Aspose.Words.Document.Save("output.odt", SaveFormat.Odt)](https://reference.aspose.com/words/net/aspose.words.document/save/methods/3 )

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Total for .NET поддерживается во всех основных операционных системах. Просто убедитесь, что у вас есть следующие предпосылки. 

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows или совместимая ОС с платформами .NET Framework, .NET Core, Windows Azure, Mono или Xamarin.
-  Среда разработки, такая как Microsoft Visual Studio.
-  Aspose.Slides for .NET и Aspose.Words for .NET DLL, на которые есть ссылки в вашем проекте.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="В этом примере кода показано, как преобразовать POTX в ODT с помощью C#." offSpacer="" %}}

```cs// Загрузите POTX-файл Microsoft PowerPoint
Aspose.Slides.Presentation potx = new Aspose.Slides.Presentation("source.potx");

var stream = new MemoryStream();

potx.Save(stream, Aspose.Slides.Export.SaveFormat.Html);
stream.Flush();
stream.Seek(0, SeekOrigin.Begin);
// stream.Position = 0;

// Загружаем содержимое презентации в документ Word
var odt = new Aspose.Words.Document(stream);
      
// Сохраняем документ Word ODT
odt.Save("output.odt", Aspose.Words.SaveFormat.Odt);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class="demobox tc col-md-12 padding-0" align="center">
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Онлайн-конвертер POTX в ODT</h3>

<iframe title="Онлайн-инструмент от odt до potx долларов" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=odt&from=potx" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>


<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Бесплатное приложение для преобразования POTX в ODT" sectionDescription="Посмотрите наши живые демонстрации для [преобразования POTX в ODT](https://products.aspose.app/slides/conversion/) со следующими преимуществами." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Не нужно ничего скачивать или настраивать." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Нет необходимости писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите файл POTX и нажмите кнопку «Конвертировать»." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы сразу же получите ссылку для скачивания результирующего файла ODT." >}}

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
                          <span itemprop="name"><b>Как я могу конвертировать POTX в ODT онлайн?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Онлайн-приложение для преобразования POTX интегрировано выше. Чтобы использовать приложение, вы можете добавить свой файл POTX, перетащив его в указанную область или щелкнув внутри области, чтобы импортировать файл. После добавления файла нажмите кнопку «Преобразовать», чтобы начать процесс преобразования. После завершения преобразования POTX в ODT вы можете загрузить только что преобразованный файл одним щелчком мыши, и он будет доступен в формате ODT.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Сколько времени занимает конвертация POTX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">этот онлайн-конвертер работает быстро, но скорость преобразования POTX в ODT в основном зависит от размера конвертируемого файла POTX. Небольшие файлы POTX можно преобразовать в формат ODT за считанные секунды. Кроме того, если вы интегрировали код преобразования POTX в ODT в приложение .NET, скорость преобразования будет зависеть от того, насколько хорошо вы оптимизировали свое приложение для процесса преобразования.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Безопасно ли конвертировать POTX в ODT с помощью бесплатного конвертера Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Конечно! Как только процесс преобразования POTX в ODT будет завершен, ссылка для скачивания преобразованного файла ODT будет мгновенно доступна. Все загруженные файлы, включая файлы POTX, удаляются из системы через 24 часа, а ссылки для скачивания перестают функционировать по истечении этого периода времени. Онлайн-конвертер обеспечивает безопасность и конфиденциальность ваших файлов, а встроенное приложение доступно бесплатно для целей тестирования. Это позволяет пользователям проверить результат, прежде чем интегрировать код в свои проекты.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Какой браузер я должен использовать для преобразования POTX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Вы можете использовать любой современный веб-браузер, такой как Google Chrome, Firefox, Opera или Safari, для преобразования файлов POTX в ODT онлайн. Однако, если вы создаете настольное приложение, рекомендуется использовать Aspose.Total POTX Conversion API для плавного и беспрепятственного процесса преобразования.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}