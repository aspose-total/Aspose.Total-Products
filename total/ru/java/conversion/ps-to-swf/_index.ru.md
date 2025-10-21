---
title: Преобразование PS в SWF через Java API
description: Java API для преобразования PS в SWF без использования Microsoft Word
url_ignore: /ru/java/conversion/ps-to-swf/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: SWF
otherformats: XAML POTX PPT PPSM SWF PPTM POWERPOINT POT PPS PPSX POTM OTP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API для экспорта PS в SWF" h2="Экспорт PS в SWF через локальный Java API без использования Microsoft<sup>&reg;</sup> PowerPoint или Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Java](https://products.aspose.com/total/java/), вы можете легко преобразовать PS в SWF в любом приложении Java J2SE, J2EE, J2ME. Во-первых, используя [Aspose.PDF для Java](https://products.aspose.com/pdf/java/), вы можете экспортировать PS в PPTX. После этого, используя [Aspose.Slides for Java](https://products.aspose.com/slides/java/) API обработки PowerPoint, вы можете конвертировать PPTX в SWF.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API для преобразования PS в SWF" %}}
1. Откройте файл PS, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте PS в PPTX, используя метод [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-).
3. Загрузите документ PPTX с помощью класса [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
4. Сохраните документ в формате SWF с помощью метода [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) и установите ` SWF` как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите [Aspose.PDF для Java](https://docs.aspose.com/pdf/java/installation/) и [Aspose.Slides для Java](https://docs.aspose.com/slides/java/installation/) в вашем pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
При загрузке формата файла PS ваш документ может быть защищен паролем. [Aspose.PDF для Java](https://products.aspose.com/pdf/java/) также позволяет открывать зашифрованные документы. Чтобы открыть зашифрованный файл, вы можете инициализировать новый экземпляр [Документа](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) и передать имя файла и пароль в качестве аргументов.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open PS document
Document doc = new Document("input.ps", "Your@Password");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Открыть зашифрованный файл PS через Java" %}}
После преобразования PS в SWF вы также можете добавить предопределенный тип представления для своей презентации. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) предоставляет возможность установить тип представления для сгенерированной презентации, когда она открывается в PowerPoint через [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Свойство [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) используется для установки типа представления с помощью [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType). 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

Преобразование файлов PS (PostScript) в SWF (Shockwave Flash) позволяет превратить статическое содержимое PostScript в интерактивные веб-анимации. Это идеально подходит для создания легких анимированных графических изображений, образовательных модулей и интерактивных презентаций на основе макетов PS.

{{% blocks/products/pf/agp/feature-section-col title="Основные сценарии использования" %}}

* Преобразование диаграмм на основе PS в интерактивные веб-анимации.
* Встраивание графиков и визуальных элементов PostScript в образовательные платформы.
* Преобразование маркетинговых брошюр из PS в веб-анимации.
* Создание интерактивных учебных пособий и демонстраций с использованием выходных данных SWF.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Сценарии автоматизации" %}}

* Пакетное преобразование PS в SWF для веб-публикаций.
* Интеграция в LMS или образовательные порталы для автоматизированного создания анимаций.
* Плановое преобразование отчетов PS в интерактивное веб-содержимое.
* Использование искусственного интеллекта для рендеринга сложных макетов PS в анимации SWF.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}