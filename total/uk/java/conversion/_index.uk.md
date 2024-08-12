---
title: Перетворення формату файлу через Java 
url_ignore: /java/conversion/
description: Перетворюйте Microsoft Office Word, Excel, PowerPoint, Outlook, PDF, HTML, 3D-зображення, діаграми, відеоформати та інші інші формати за допомогою лише кількох рядків коду Java.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Перетворення формату файлу через Java" h2="Конвертуйте документи Microsoft Office, PDF, зображення, HTML та багато інших файлів без використання будь-якого іншого програмного забезпечення." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Повна бібліотека Java](https://products.aspose.com/total/java/) пришвидшує розробку рішень для роботи з документами з нуля або покращує існуючі додатки для легкого керування документами.  API не лише створює, редагує та конвертує документи Microsoft Office, але й обробляє PDF, HTML, зображення TIFF, JPG, PNG, BMP та SVG, файли електронної пошти, формати відео, 3D, CAD та багато іншого.  Це набір API рішень для керування документами та маніпуляцій без будь-яких програмних залежностей у будь-яких програмах Java J2SE, J2EE, J2ME. Програмісти можуть легко створювати, оновлювати, рендерити, друкувати та конвертувати між найпопулярнішими форматами в будь-яких програмах на основі Java.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Перетворення Word в Excel" %}}
Total API підтримує не лише взаємне перетворення форматів Microsoft Word, але й перетворення Word у Excel, PDF, HTML, зображення, EPUB, Markdown і XPS.  Процес перетворення простий. Розглянемо випадок перетворення **Word to Excel**.  Завантажте файл Microsoft Word за допомогою класу [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) і перетворіть **WORD на HTML** за допомогою методу [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)).  Потім відкрийте перетворений HTML-документ за допомогою класу [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) і збережіть документ у форматі XLSX за допомогою методу [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).
 Розробники також можуть конвертувати [Word в PDF](https://products.aspose.com/words/java/conversion/word-to-pdf/).


{{% blocks/products/pf/feature-page-code h3="Перетворення Java Word в Excel" %}}

{{< gist "aspose-com-gists" "519819eaf54003f5ba524be783483c1e" "convert-word-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="word-to-csv word-to-json word-to-powerpoint" >}}


{{% blocks/products/pf/feature-page-section  h2="Перетворення PDF на зображення" %}}
API підтримує конвертацію PDF у зображення, такі як JPEG2000, EMZ, WMZ, TGA, PSD, DXF, WMF, SVGZ, APNG, DICOM, Powerpoint, Excel та інші формати.  Для перетворення PDF у зображення розглянемо зображення JPG як цільовий файл.  Процес полягає в завантаженні PDF-файлу за допомогою класу Document, ініціалізації об’єкта [JpegDevice class](https://reference.aspose.com/pdf/java/aspose.pdf.devices/jpegdevice) і рендерингу PDF у JPEG за допомогою методу [Process](https://reference.aspose.com/pdf/java/aspose.pdf.devices.pagedevice/process/methods/1)
Завантажте файл JPEG за допомогою класу [Image](https://reference.aspose.com/imaging/java/aspose.imaging/image) і, нарешті, викличте метод Save.

{{% blocks/products/pf/feature-page-code h3="Перетворення Java PDF на зображення" %}}

{{< gist "aspose-com-gists" "a0abf986a98e2b1f1e86127b1a4449bd" "convert-pdf-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-csv pdf-to-txt pdf-to-markdown" >}}

{{% blocks/products/pf/feature-page-section  h2="Перетворення PowerPoint на файли Excel" %}}

Для перетворення файлів Microsoft PowerPoint у різні файли, включаючи Excel Word, MHTML, відповідні підпорядковані API, пов’язані з основним API Aspose.Total для Java. Процес перетворення файлів PowerPoint на документ Excel, завантаження файлу PowerPoint за допомогою класу [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) і перетворення **PowerPoint на HTML** за допомогою методу [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-). Потім завантажте перетворений HTML-документ за допомогою класу [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) і збережіть документ у форматі EXCEL за допомогою методу [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).  Також наведено код для перетворення **PowerPoint у Word**.

{{% blocks/products/pf/feature-page-code h3="Перетворення Java PowerPoint в Excel" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Перетворення Java PowerPoint у Word" %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-doc powerpoint-to-docx powerpoint-to-xlsx" >}}