---
title: C# API для экспорта EMAIL в BMP
description: Преобразование EMAIL в BMP без использования Microsoft Word или Outlook на .NET
url_ignore: /ru/net/conversion/email-to-bmp/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: BMP
otherformats: PCL PDF DOT FLATOPC JPEG PNG RTF TIFF DOCM PS GIF XPS ODT DOCX DOC WORDML SVG EPUB MD EMF DOTM OTT DOTX TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт EMAIL в BMP через .NET" h2=".NET API для преобразования электронной почты в BMP в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования EMAIL в BMP в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Email for .NET](https://products.aspose.com/email/net/), вы можете преобразовать формат файла EMAIL в HTML. После этого, используя [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в BMP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования EMAIL в BMP" %}}
1. Откройте файл EMAIL с помощью класса [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Преобразуйте EMAIL в HTML, используя метод [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате BMP с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Bmp в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл EMAIL через .NET" %}}
Перед преобразованием EMAIL в BMP, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ EMAIL, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) класса [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов BMP через .NET" %}}
При сохранении документа из EMAIL в BMP вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.bmp", SaveFormat.Bmp);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла EMAIL в BMP: примеры использования" %}}
Файлы email используются для хранения текстовой информации, что делает их идеальным вариантом для создания профессиональных коммуникаций и переписки. Однако при работе с визуальной информацией, такие изображения, как BMP, становятся необходимостью для добавления возможностей мультимедийных.

Преобразование файлов email в форматы BMP необходимо для раскрытия полной возможностей вашего мультимедийного потенциала. Это преобразование позволяет вам:

* События приглашения: Преобразовать файлы email в привлекательные приглашения на события, украшенные графикой и изображениями.
* Представление товаров в интернет-магазине: Использовать BMP для добавления высококачественных изображений товаров в email-письма в онлайн-магазинах, улучшая опыт покупателя и стимулируя продажи.
* Рекламационные кампании: Преобразовать файлы email для включения привлекательных баннеров и изображений в рекламационных кампаниях, увеличивая вовлеченность и коэффициент преобразования.
* Персонализированные сообщения: Использовать BMP для добавления персонализированных изображений и графических элементов в email-письма, создавая более личный и запомнившийся опыт получателей.
* Дизайн новостей: Преобразовать файлы email для создания привлекательных новостных письмов с изображениями и контентом мультимедийным, сохраняя подписчиков заинтересованными и информированными.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}