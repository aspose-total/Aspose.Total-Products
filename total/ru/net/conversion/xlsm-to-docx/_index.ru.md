---
title: Преобразование XLSM в DOCX с помощью .NET 
description: Преобразование XLSM в DOCX на платформах .NET Framework, .NET Core, Mono или Xamarin. или онлайн. Быстро протестируйте бесплатный онлайн-конвертер XLSM в DOCX, прежде чем интегрировать код. или с помощью бесплатного онлайн-конвертера
url_ignore: /ru/net/conversion/xlsm-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLSM
outformat: DOCX
otherformats: PPTX WORD DOC POWERPOINT
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="Преобразование XLSM в DOCX через C# или онлайн-приложение" h2="Экспорт Excel<sup>&reg;</sup> XLSM в DOCX на платформах .NET Framework, .NET Core, Mono или Xamarin.">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Преобразование XLSM в DOCX на .NET" %}}
1. Откройте файл XLSM, используя класс [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
2. Преобразуйте XLSM в PDF и установите для параметра SaveFormat значение Auto.
3. Загрузите преобразованный файл PDF с помощью класса [Документ](https://reference.aspose.com/pdf/net/aspose.pdf/document).
4. Сохраните документ в формате DOCX с помощью метода [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) и установите DocX как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.com/total/net).(https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Код .NET C# для преобразования XLSM в DOCX" gistPath="" %}}

```cs// load the XLSM file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsm");
// save XLSM as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOCX format
document.Save("output.docx", SaveFormat.DocX); 
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Бесплатный онлайн-конвертер XLSM в DOCX</h3>

<iframe title="Онлайн-инструмент от docx до xlsm долларов" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xlsm" id="child-iframe" width="80%"></iframe>

</div></div>
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
                          <span itemprop="name"><b>Как я могу конвертировать XLSM в DOCX онлайн?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Онлайн-приложение для преобразования XLSM интегрировано выше. Чтобы начать процесс преобразования, вы можете либо перетащить файл XLSM, либо щелкнуть внутри обозначенной области, чтобы импортировать документ. Затем нажмите кнопку «Конвертировать», чтобы начать преобразование XLSM в DOCX. После завершения процесса вы можете легко загрузить преобразованный файл одним щелчком мыши, получив желаемый результат в формате DOCX.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Сколько времени занимает конвертация XLSM?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Скорость этого онлайн-конвертера высокая, но в первую очередь она зависит от размера файла XLSM. Если у вас есть небольшой файл XLSM, его можно преобразовать в DOCX всего за несколько секунд. Кроме того, если вы интегрировали код преобразования в свое приложение .NET, скорость процесса преобразования зависит от того, насколько хорошо вы оптимизировали свое приложение.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Безопасно ли конвертировать XLSM в DOCX с помощью бесплатного конвертера Aspose.Total?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Конечно! После завершения процесса преобразования XLSM в DOCX сразу создается ссылка для скачивания файлов DOCX. Мы уделяем первостепенное внимание безопасности ваших файлов, поэтому все загруженные файлы удаляются через 24 часа, а ссылки для скачивания перестают работать по истечении этого периода. Вы можете быть уверены, что ваши файлы в безопасности в процессе преобразования, включая файлы XLSM. Вышеупомянутое бесплатное приложение предназначено для тестирования и позволяет проверить результат перед интеграцией кода.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Какой браузер я должен использовать для преобразования XLSM?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">У вас есть возможность использовать любой современный веб-браузер для онлайн-преобразования XLSM в DOCX, например, Google Chrome, Firefox, Opera, Safari. Однако, если вы создаете настольное приложение, вы можете легко интегрировать API Aspose.Total XLSM Conversion.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}