---
title: Перетворення формату файлу за допомогою C#  

description: Перетворюйте Microsoft Word, Excel, PowerPoint, Outlook, PDF, HTML, 3D-зображення, діаграми, відеоформати та багато інших популярних файлів за допомогою лише кількох рядків коду C#.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Перетворення формату файлу за допомогою C#  .NET" h2="Перетворюйте файли Microsoft Office, PDF, зображення, HTML та інші формати без використання будь-якого іншого програмного забезпечення." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Повна бібліотека .NET](https://products.aspose.com/total/net/) пришвидшує розробку рішень для керування документами з нуля або покращує існуючі програми для легкої роботи з документами.  API не тільки керує документами Microsoft Office, але й обробляє PDF, HTML, зображення TIFF, JPG, PNG, BMP і SVG, файли електронної пошти, формати відео, формати даних ГІС та багато іншого.  Це повний набір API рішень для управління документами та маніпулюванням без будь-яких програмних залежностей.    Програмісти можуть легко створювати, оновлювати, відтворювати, друкувати та конвертувати між найпопулярнішими форматами в будь-якій програмі на основі .NET.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Перетворення Word на PDF" %}}
Total API підтримує не лише взаємне перетворення форматів Microsoft Word, але й перетворення Word у PDF, HTML, зображення, EPUB, Markdown і XPS.  Процес перетворення простий.  Завантажте документ через клас Document і просто викличте метод Save with target format.  Це так просто. Розробники можуть перевірити [результат перетворення](https://products.aspose.com/words/net/conversion/word-to-pdf/) перед інтеграцією коду **Word to PDF**


{{% blocks/products/pf/feature-page-code h3="C# - перетворення Word у PDF" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-word-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-excel word-to-json word-to-ods" >}}


{{% blocks/products/pf/feature-page-section  h2="Перетворення PDF на зображення" %}}
API підтримує перетворення PDF в зображення, Powerpoint, Excel та інші формати. Для перетворення PDF у зображення розглянемо зображення JPG як цільовий файл. Процес полягає в завантаженні PDF-файлу за допомогою класу Document, ініціалізації об’єкта [JpegDevice class](https://reference.aspose.com/pdf/net/aspose.pdf.devices/jpegdevice) і рендерингу PDF у JPEG за допомогою методу [Process](https://reference.aspose.com/pdf/net/aspose.pdf.devices.pagedevice/process/methods/1)
Завантажте файл JPEG за допомогою класу [Image](https://reference.aspose.com/imaging/net/aspose.imaging/image) і, нарешті, викличте метод Save.

{{% blocks/products/pf/feature-page-code h3="C# - перетворення PDF на зображення" %}}

{{< gist "aspose-com-gists" "2f2f0deee186feb29f805d4b26625caf" "convert-pdf-to-image.cs" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt" >}}

{{% blocks/products/pf/feature-page-section  h2="Перетворення Excel на Word і PowerPoint" %}}

Для перетворення форматів Microsoft Excel у різні файли, включаючи Word і PowerPoint, відповідні допоміжні API, пов’язані з основним API Aspose.Total для .NET. Процес перетворення файлів Excel у документ Word, завантажте файл EXCEL за допомогою класу [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook) і спочатку конвертуйте EXCEL у PDF і встановіть для SaveFormat значення Auto.  Потім завантажте перетворений PDF-файл за допомогою класу Document, викличте метод Save і встановіть Doc, Docx як SaveFormat. Також наведено код для перетворення Microsoft **Excel у Powerpoint**.

{{% blocks/products/pf/feature-page-code h3="C# - перетворення JSON на Excel" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-word.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# – перетворення Excel у JSON" %}}

{{< gist "aspose-com-gists" "73f7662392c88a80941c930db836cd58" "convert-excel-to-powerpoint.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="excel-to-doc excel-to-docx excel-to-pptx" >}}