---
title: Перетворення документів через Python  

description: Перетворюйте формати Microsoft Word DOC, DOCX у PDF, зображення тощо, а також слайди презентацій, повідомлення електронної пошти та 3D-зображення лише кількома рядками коду Python.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Перетворення документів за допомогою API Python" h2="Перетворюйте Microsoft Office Word, PDF, зображення та різні інші формати за допомогою Aspose.Words для Python через .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Python API](https://products.aspose.com/total/python-net/) прискорює розробку рішень автоматизації документообігу з нуля або вдосконалення існуючих програм для створення, редагування або конвертації документів, презентацій, електронних листів і 3D-файлів.  Python API не тільки обробляє Microsoft Office Word і слайди презентацій, але також обробляє PDF, HTML, зображення та файли електронної пошти та багато іншого.  API не залежить від будь-якого програмного забезпечення і являє собою повний набір рішень для управління та маніпулювання документами.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Перетворення Microsoft Word на PDF" %}}
Total Python API підтримує багаторазове перетворення таких форматів, як Microsoft Word у PDF, Images, Markdown і HTML.  API робить процес перетворення документа Word у PDF простим із якісним виходом, наближеним до документа, як у файлі DOC, DOCX.  Процес завантажує файл DOC або DOCX в об’єкт [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) і просто викликає метод [save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) із цільовим форматом PDF разом із шляхом до його каталогу.  Це так просто. Якщо потрібно вказати стандарти PDF, такі як PDF 1.7 або 1.5, API забезпечує перерахування [PdfComplaince](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfcompliance/) для встановлення [PdfSaveOptions()](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfsaveoptions/).  

{{% blocks/products/pf/feature-page-code h3="Python - перетворення Word у PDF" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-document-to-pdf-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="pdf-to-images pdf-to-mhtml" >}}

{{% blocks/products/pf/feature-page-section  h2="Перетворення Microsoft Word на зображення" %}}
Перетворення Word to Images є основною функцією API Python. Крім простого перетворення, можна легко встановити різні параметри збереження, такі як яскравість, контраст, горизонтальна та вертикальна роздільна здатність тощо.  Процес полягає в тому, щоб завантажити документ через об’єкт Document, а потім викликати метод збереження з потрібним розширенням файлу зображення з указаним шляхом.  Щоб указати різні параметри збереження, API надає класи [ImageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/imagesaveoptions/), [FixedPageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/fixedpagesaveoptions/) або [SaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/saveoptions/), які можна використовувати відповідно до необхідного сценарію.  Наведений нижче приклад коду демонструє створення попереднього перегляду першої сторінки документа із застосуванням деяких додаткових параметрів.

{{% blocks/products/pf/feature-page-code h3="Python - перетворення слова в зображення" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-to-images-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="docx-to-images rtf-to-images mhtml-to-images mhtml-to-rtf mhtml-to-doc" >}}

{{% blocks/products/pf/feature-page-section  h2="Перетворення Microsoft PowerPoint на Word" %}}
Python API підтримує перетворення файлів Microsoft PowerPoint PPT/PPTX у Word DOC/DOCX. Для виконання цього перетворення використовуються два API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) і [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/).  Завантажте файл PPT / PPTX за допомогою [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/). Отримайте об’єкт класу Word Document.  Переглядайте кожен слайд, створюйте та вставляйте зображення слайда, а потім вставляйте текст слайда, перебираючи фігури слайдів.

{{% blocks/products/pf/feature-page-code h3="Python – перетворення слайдів PowerPoint у Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-presentation-to-word-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-word ppsx-to-doc pptx-to-docx ppt-to-docm pot-to-dotx potx-to-dotm potm-to-rtf pptm-to-word pps-to-docx odp-to-doc word-to-powerpoint doc-to-odp dot-to-pps docx-to-ppsm docm-to-pptm dotx-to-potm dotm-to-potx rtf-to-pot wordml-to-pptx odt-to-ppsx ott-to-pps txt-to-powerpoint md-to-ppsm" >}}

{{% blocks/products/pf/feature-page-section  h2="Перетворення електронної пошти в Word, PDF, HTML і зображення" %}}
Для перетворення файлів електронної пошти у PDF, Word, зображення та HTML, API електронної пошти Python [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) виконує перетворення.  API завантажує вихідний файл у його об’єктну модель і викликає метод збереження з відповідними параметрами.  

{{% blocks/products/pf/feature-page-code h3="Python - Перетворення файлів електронною поштою в Word" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="email-to-doc ics-to-docx mbox-to-pdf ost-to-image msg-to-tiff pst-to-jpeg oft-to-gif vcf-to-docm emlx-to-png eml-to-text" >}}