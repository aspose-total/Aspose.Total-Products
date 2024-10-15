---
title: Онлайн-конвертация PCL в SWF или разработка приложения на основе Java для конвертации файлов PCL
description: Бесплатное онлайн-приложение для конвертации файлов PCL в SWF. Код библиотеки конвертации Java для документов PCL. 

family: total
platformtag: Java
feature: conversion
informat: PCL
outformat: SWF
otherformats: PPSM PPS XAML POWERPOINT PPT PPSX PPTM OTP SWF POT POTX POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Онлайн-приложение для преобразования PCL в SWF и код Java для преобразования файлов PCL" h2="Разработать мощное приложение для преобразования и экспорта PCL на основе Java. Конвертируйте один или несколько файлов PCL в SWF и другие форматы с помощью API автоматизации Java. Бесплатно конвертируйте файлы PCL онлайн через приложение с мгновенной загрузкой." >}}


{{< blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<iframe title="Бесплатное онлайн-приложение для конвертации PCL в SWF" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.k8s.dynabic.com/?to=swf&from=pcl" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Конвертируйте файлы PCL в SWF онлайн с помощью приложения" %}}

1. Загрузите файлы PCL для конвертации
1. Подождите несколько секунд или больше в зависимости от размера PCL
1. Следите за строкой состояния загрузки.
1. Нажмите кнопку «Конвертировать».
1. PCL будет преобразован в документ SWF
1. Загрузите преобразованный файл SWF

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Преобразование PCL в SWF с помощью Java Automation API" %}}


1. Откройте файл PCL, используя класс [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
2. Преобразуйте PCL в PPTX, используя метод [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-).
3. Загрузите документ PPTX с помощью класса [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
4. Сохраните документ в формате SWF с помощью метода [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) и установите ` SWF` как SaveFormat



{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Код Java для преобразования PCL в SWF" offSpacer="" %}}


```java
// load PCL file with an instance of Document class
Document document = new Document("template.pcl");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);   
```



{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-summary %}}

Еще несколько случаев сохранения PCL в SWF с другими функциями, такими как Требования к конвертации, Открыть зашифрованный файл PCL через Java.

{{% blocks/products/pf/feature-page-code %}}


```java
// open PCL document
Document doc = new Document("input.pcl", "Your@Password");
// save PCL as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```


{{% /blocks/products/pf/feature-page-code %}}
{{% blocks/products/pf/feature-page-code %}}


```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);    
```


{{% /blocks/products/pf/feature-page-code %}}


{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-summary %}}

<h2>Разработать приложение для преобразования файлов PCL с использованием Java</h2>

Необходимо разработать программное приложение на базе Java для простого сохранения и экспорта файлов PCL в документ SWF? С помощью [Aspose.Total for Java](https://products.aspose.com/total/ru/java/) любой разработчик Java может интегрировать вышеуказанный код API для программирования приложения для преобразования в различные форматы, включая Microsoft Word (DOC, DOCX), Excel (XLS, XLSX), Powerpoint (PPT, PPTX), PDF, файлы электронной почты, изображения (JPG, PNG, BMP, GIF) и другие форматы. Мощная библиотека Java для преобразования документов, поддерживает множество популярных форматов, включая формат PCL. Экспортируя и преобразуя документы в другие форматы, программисты могут использовать дочерние API Aspose.Total for Java, включая [Aspose.Words for Java](https://products.aspose.com/words/ru/java/), [Aspose.Cells for Java](https://products.aspose.com/cells/ru/java/), [Aspose.Slides for Java](https://products.aspose.com/slides/ru/java/), [Aspose.PDF for Java](https://products.aspose.com/pdf/ru/java/), [Aspose.Imaging for Java](https://products.aspose.com/imaging/ru/java/) и другие.<br /><br />

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PCL Библиотека преобразования для Java" %}}

Существуют альтернативные варианты интеграции Aspose.Total for Java в вашу систему. Пожалуйста, выберите тот вариант, который соответствует вашим потребностям, и следуйте пошаговым инструкциям:<br /><br />

- Используйте Aspose.Total for Java непосредственно из проекта на базе Maven и включите соответствующий дочерний API в pom.xml.
- Кроме того, можно получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Сохранение PCL в SWF Требования к приложению" %}}

Любая операционная система, поддерживающая Java Runtime Environment (JRE), может запустить Aspose.Total for Java. Ниже перечислены большинство (но не все) поддерживаемых операционных систем. <br /><br />
- Майкрософт Виндоус
- Linux: Ubuntu, OpenSUSE, CentOS и другие
- macOS: 10.9 (Mavericks) и более поздние версии
- Мобильные устройства: Android, iOS

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}