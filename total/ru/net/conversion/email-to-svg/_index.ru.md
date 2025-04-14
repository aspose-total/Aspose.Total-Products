---
title: C# API для экспорта EMAIL в SVG
description: Преобразование EMAIL в SVG без использования Microsoft Word или Outlook на .NET
url_ignore: /ru/net/conversion/email-to-svg/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: SVG
otherformats: PCL TIFF DOCX FLATOPC DOTX DOTM DOC MD XPS PS ODT RTF EPUB DOT SVG OTT TEXT GIF DOCM PDF WORDML EMF JPEG PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт EMAIL в SVG через .NET" h2=".NET API для преобразования электронной почты в SVG в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования EMAIL в SVG в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Email for .NET](https://products.aspose.com/email/net/), вы можете преобразовать формат файла EMAIL в HTML. После этого, используя [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в SVG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования EMAIL в SVG" %}}
1. Откройте файл EMAIL с помощью класса [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Преобразуйте EMAIL в HTML, используя метод [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате SVG с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Svg в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.svg", SaveFormat.Svg); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл EMAIL через .NET" %}}
Перед преобразованием EMAIL в SVG, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ EMAIL, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) класса [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов SVG через .NET" %}}
При сохранении документа из EMAIL в SVG вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.svg", SaveFormat.Svg);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла EMAIL в SVG: примеры использования" %}}
Файлы email используются для хранения текстовых сообщений, что делает их идеальным вариантом для создания персонализированных коммуникаций и newsletters. Однако при работе с визуальными контентами изображения, такие как SVG (Scalable Vector Graphics), становятся необходимостью для эффективной коммуникации и брендинга.

Преобразование файлов email в форматы SVG позволяет раскрыть полную функциональность вашей визуальной коммуникации и возможностей брендинга. Это преобразование позволяет:

**Использования:**  

*   **Брендинг и логотипы**: Преобразовать шаблоны email для создания масштабируемых, векторных логотипов и активов бренда, которые сохраняют одинакимость во всех средах.  
*   **Инфографики и визуализации данных**: Использовать SVG для визуализации данных, создания интерактивных инфографиков и представления сложной информации в ясной и краткой форме.  
*   **Дизайн для веба и мобильных устройств**: Преобразовать email newsletters для создания адаптивных, векторных дизайнов для веба и мобильных устройств, которые плавно переходят между разными размерами экранов и устройств.  
*   **Социальные сети и материалы маркетинга**: Использовать SVG для создания масштабируемых иконок социальных сетей, графических элементов и материалов рекламы, сохраняющих одинакимость бренда на разных платформах.  
*   **Электронная коммерция и онлайн-магазины**: Преобразовать шаблоны email для создания интерактивных, векторных изображений продуктов, имитирующих 3D-produkты и показывающих детали продукта.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}