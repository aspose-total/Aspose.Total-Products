---
title: C# API для экспорта EML в PNG
description: Преобразование EML в PNG без использования Microsoft Word или Outlook на .NET
url_ignore: /ru/net/conversion/eml-to-png/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PNG
otherformats: EPUB TIFF MD EMF ODT PDF DOTX JPEG PCL DOCX FLATOPC PS DOT DOCM TEXT WORDML OTT RTF GIF SVG XPS DOC DOTM PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт EML в PNG через .NET" h2=".NET API для преобразования электронной почты в PNG в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования EML в PNG в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Email for .NET](https://products.aspose.com/email/net/), вы можете преобразовать формат файла EML в HTML. После этого, используя [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в PNG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования EML в PNG" %}}
1. Откройте файл EML с помощью класса [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage).
2. Преобразуйте EML в HTML, используя метод [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате PNG с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Png в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл EML через .NET" %}}
Перед преобразованием EML в PNG, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ EML, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) класса [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов PNG через .NET" %}}
При сохранении документа из EML в PNG вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла EML в PNG: примеры использования" %}}
Файлы EML (Electronic Mail) используются для хранения текстовой информации по электронной почте, что делает их идеальным выбором для отправки и приёма сообщений. Однако при работе с визуальными контентами, такие как изображения PNG, становятся необходимыми для отображения графических элементов и иллюстраций.

Преобразование файлов EML в формат PNG позволяет раскрыть полные возможности отображения вашей визуальной содержимой. Это позволяет:

**Использования:**  

*   **Графические изображения для социальных сетей**: Преобразовать файлы EML в привлекательные графические изображения для социальных сетей, рекламу и материалы по продвижу.

*   **Кампании по email-рассылке**: Использовать PNG для визуализации кампаний по email-рассылке, оптимизировать дизайны и измерять метрики взаимодействия.

*   **Графические элементы на веб-страницах**: Преобразовать файлы EML в интерактивные графические элементы для веб-страниц, имитировать пользовательские опыт и проверять концепции дизайна.

*   **Иллюстрации для блогов**: Использовать PNG для визуализации иллюстраций в блогах, создавая интересный контент для читателей.

*   **Материалы для презентаций**: Преобразовать файлы EML в профессиональные материалы для презентаций, эффективно отображать данные, диаграммы и графики.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}