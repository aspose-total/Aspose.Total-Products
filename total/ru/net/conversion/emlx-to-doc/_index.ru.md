---
title: C# API для экспорта EMLX в DOC
description: Преобразование EMLX в DOC без использования Microsoft Word или Outlook на .NET
url_ignore: /ru/net/conversion/emlx-to-doc/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: DOC
otherformats: PDF TEXT PS EMF OTT DOCM SVG DOCX DOTM MD DOT EPUB WORDML DOC FLATOPC XPS PCL JPEG ODT PNG GIF RTF DOTX TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт EMLX в DOC через .NET" h2=".NET API для преобразования электронной почты в DOC в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования EMLX в DOC в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Email for .NET](https://products.aspose.com/email/net/), вы можете преобразовать формат файла EMLX в HTML. После этого, используя [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в DOC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования EMLX в DOC" %}}
1. Откройте файл EMLX с помощью класса [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Преобразуйте EMLX в HTML, используя метод [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате DOC с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Doc в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл EMLX через .NET" %}}
Перед преобразованием EMLX в DOC, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ EMLX, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) класса [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов DOC через .NET" %}}
При сохранении документа из EMLX в DOC вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.doc", SaveFormat.Doc);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла EMLX в DOC: примеры использования" %}}
Файлы EMFX (Enhансированный Фреймворк Метаданных) используются для хранения информации о метадатах, что делает их идеальным инструментом для создания структурированных записей данных и баз данных. Однако при работе с динамическими содержимыми Microsoft Office документы становятся незаменимыми в управлении документами и сотрудничестве.

Преобразование файлов EMFX в форматы Word позволяет раскрыть полную функциональность возможностей управления документами и сотрудничества. Это преобразование позволяет:

**Использования:**

*   **Отзыв и утверждение документов**: Преобразовать файлы EMFX для отзыва и утверждения документов, обеспечивая соответствие регуляциям и стандартам.
*   **Управление содержимым**: Использовать Word для управления большими объемами информации, включая статьи, отчеты и презентации, что упрощает поиск и доступ к необходимой информации.
*   **Сотрудничество и процессуальные потоки**: Преобразовать файлы EMFX для facilitation сотрудничества между командами, позволяя реальному комментированию, отслеживанию изменений и обеспечению точности документов.
*   **Поиск и извлечение**: Использовать Word для поиска и извлечения конкретных документов, что ускоряет процесс поиска информации и увеличивает продуктивность.
*   **Управление версиями и контроль**: Преобразовать файлы EMFX для поддержки нескольких версий документов, что упрощает управление версиями и отслеживание истории изменений.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}