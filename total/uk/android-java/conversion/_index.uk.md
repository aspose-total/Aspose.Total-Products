---
title: Перетворення документів через Android API  

description: Перетворюйте формати Word, Excel, PowerPoint, HTML, PDF і Image за допомогою Android API перетворення.  Android конвертує Office docx, xlsx, pptx у PDF.  
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Перетворення документів за допомогою Android API" h2="Перетворюйте Microsoft Office Word, Excel, PowerPoint, PDF, зображення та різні інші формати за допомогою Aspose.Total для Android через Java." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) надає рішення для перетворення документів і керування програмами Android, не покладаючись на будь-яке інше програмне забезпечення.  Програмісти можуть легко автоматизувати рішення для керування документами та маніпуляції, інтегруючи API у нові розроблені додатки або в існуючі додатки.  Завдяки інтеграції API програміст може легко додавати функції для створення, редагування або конвертації документів різного формату в програмі.  PDF Converter API в Android обробляє випадки перетворення Office DOCX, XLSX, PPTX у PDF або навпаки.  Крім того, кілька випадків, які API розглядає, перелічені нижче, і кілька посилань, наданих для відповідних випадків перетворення.  

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Перетворення PDF на CSV" %}}
Total Android API підтримує конвертацію PDF у Excel XLSX і CSV.  Це двоетапний процес. Задіяно два Total API [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) і [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/).  Процес полягає в тому, що ви можете спочатку конвертувати PDF у формат Excel XLSX, а потім XLSX у CSV.  Більш детально, Завантажте PDF-файл за допомогою класу [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) і відтворіть у XLSX за допомогою методу [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-).  Далі завантажте відтворений документ XLSX за допомогою класу [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) і викликайте метод [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)).

{{% blocks/products/pf/feature-page-code h3="Android - перетворення PDF в Excel" %}}

{{< gist "aspose-com-gists" "216c598605624ff6264b8db912df1c50" "convert-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint potm-to-rtf powerpoint-to-docx ppt-to-docx pptx-to-odt potm-to-docx email-to-docx email-to-word eml-to-pdf emlx-to-bmp emlx-to-image msg-to-pdf oft-to-word" >}}


{{% blocks/products/pf/feature-page-section  h2="Перетворення Excel в Word" %}}
Android API також обробляє перетворення Excel.  Процес такий: завантажте файл EXCEL XLSX за допомогою класу [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) і конвертуйте EXCEL у PDF, спочатку встановивши для SaveFormat значення AUTO.  Потім завантажте збережений PDF-файл за допомогою класу [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) і викликайте метод [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-), щоб зберегти документ у форматі Word DOC / DOCX.

{{% blocks/products/pf/feature-page-code h3="Android - Перетворення Excel в Word" %}}

{{< gist "aspose-com-gists" "10fdb88fb4d39618cdc2dfd0d0bd86c1" "excel-to-word-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mhtml-to-docm pdf-to-rtf svg-to-docm xps-to-dotx pdf-to-powerpoint tex-to-ppsx xps-to-potx csv-to-doc excel-to-word xls-to-word xlsx-to-powerpoint xltx-to-word word-to-excel" >}}

{{% blocks/products/pf/feature-page-section  h2="Перетворення POWERPOINT на HTML і MHTML" %}}
Android Total API працює з різними форматами, включаючи файли PowerPoint, тому може конвертувати презентації у HTML і MHTML.  Процес полягає в завантаженні файлу POWERPOINT PPT/PPTX за допомогою класу [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) і виклику методу [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) для перетворення POWERPOINT на HTML.  Крім того, тепер завантажте перетворений документ HTML за допомогою класу [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) і викличте метод [save](https://reference.aspose.com/cells/java/com.aspose.cells/) для перетворення MHTML.  
{{% blocks/products/pf/feature-page-code h3="Android – перетворення презентацій PowerPoint на HTML і MHTML" %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="rtf-to-excel docx-to-csv json-to-word json-to-powerpoint word-to-json powerpoint-to-json potm-to-excel pptx-to-excel ppsx-to-mhtml" >}}