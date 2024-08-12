---
title: Конвертація документів через C++  

description: Перетворюйте різноманітні формати документів, такі як Word, Excel, PowerPoint, PDF, JSON, зображення тощо за допомогою C++ API.  
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Перетворення документів за допомогою C++" h2="Конвертуйте Microsoft Office Word, Excel, PowerPoint, PDF, зображення та різні інші формати за допомогою бібліотеки C++." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Android API](https://products.aspose.com/total/android-java/) вирішує проблему перетворення документів, і розробники можуть легко автоматизувати рішення для керування документами та маніпуляції, інтегруючи API у нові розроблені програми або в існуючі програми.  Програмісти C++ можуть додавати такі функції, як створення, редагування або конвертація документів різного формату в рамках свого рішення, не покладаючись на будь-яке програмне забезпечення.  Кілька загальних випадків, як-от txt у PDF, SVG у PNG, XLSX у CSV, JSON у CSV, Word у PDF, HTML у PDF, можна легко конвертувати.  Крім того, кілька випадків, які API розглядає, перелічені нижче, і кілька посилань, наданих для відповідних випадків перетворення.  

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Перетворення Microsoft Word на Excel" %}}
Total C++ API підтримує перетворення Microsoft Word DOC/DOCX у Excel.    Процес полягає в завантаженні файлу Word DOC / DOCX за допомогою посилання на клас [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/) і виклику функції-члена [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) для спочатку перетворення в HTML.  Потім завантажте HTML-документ за допомогою посилання на клас [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) і викличте функцію-член [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-), щоб зберегти документ у форматі Excel.  

{{% blocks/products/pf/feature-page-code h3="C++ - перетворення Word в Excel" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc  doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="Конвертація PDF у Word" %}}
Бібліотека перетворення C++ також підтримує перетворення PDF у Word DOC, DOCX та інші формати.  Розглядаючи випадок візуалізації PDF у формат RTF, це двоетапний процес: спочатку конвертуйте PDF у формат Word DOC/DOCX, а потім відтворюйте його у формат RTF.  Для цього включено кроки, завантаження файлу PDF за допомогою посилання на клас [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) і виклик функції-члена [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) для перетворення PDF у Word.  Тепер знову завантажте файл Word DOC / DOCX за допомогою посилання на клас [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) API Aspose.Words і збережіть його у форматі RTF за допомогою функції-члена [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).

{{% blocks/products/pf/feature-page-code h3="C++ - Конвертація PDF у Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Перетворення JSON на Word" %}}
Для перетворення JSON C++ API підтримує різні комбінації, такі як JSON у Word, Json у PowerPoint, Word у JSON тощо.  Розглядаючи випадок перетворення Word, процес полягає в тому, щоб зчитувати дійсні дані JSON із файлу за допомогою нового об’єкта [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-), а потім викликати метод [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation), щоб зберегти JSON як файл PDF.  Тепер завантажте збережений файл за допомогою класу [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) і збережіть його у форматі документа Word за допомогою методу [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
{{% blocks/products/pf/feature-page-code h3="C++ - перетворення JSON у Word" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}